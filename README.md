# LEYNotFound
### LEYNotFound.github.io

```c++
#include <bits/stdc++.h>
using namespace std;
string s;
int dp[101][101];
int main(){
	cin>>s;
	int lens=s.size();
	for(int i=0;i<lens;i++){
		for(int j=i;j<lens;j++){
			dp[i][j]=INT_MAX;
		}
	}
	for(int i=0;i<lens;i++){
		dp[i][i]=1;
	}
	for(int len=2;len<=lens;len++){
		for(int l=0;l<=lens-len;l++){
			int r=l+len-1;
			for(int k=l;k<r;k++){
				dp[l][r]=min(dp[l][r],dp[l][k]+dp[k+1][r]);
			}
			if(s[l]=='(' && s[r]==')' || s[l]=='[' && s[r]==']' ){
				dp[l][r]=min(dp[l][r],dp[l+1][r-1]);
			}
		}
	}
	cout<<dp[0][lens-1];
	return 0;
}
```
