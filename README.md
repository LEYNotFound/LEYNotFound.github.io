# LEYNotFound
### LEYNotFound.github.io

#### P2
```c++
#include <bits/stdc++.h>
using namespace std;
int dp[501][501],n,m,a[501],b[501];
int q[501];
void print(int x){
	if(x==0){
		return;
	}
	print(q[x]);
	cout<<b[x]<<" ";
}
int main(){
	cin>>n;
	for(int i=1;i<=n;i++){
		cin>>a[i];
	}
	cin>>m;
	for(int i=1;i<=m;i++){
		cin>>b[i];
	}
	for(int i=1;i<=n;i++){
		for(int j=1;j<=m;j++){
			int maxs=1,last=0;
			
			if(a[i]==b[j]){
				for(int k=1;k<j;k++){
					if(b[k]<b[j] && dp[i-1][k]+1>maxs){
						maxs=dp[i-1][k]+1;
						last=k;
					}
				}
				q[j]=last;
				dp[i][j]=max(dp[i][j],maxs);
			}else{
				dp[i][j]=dp[i-1][j];
			}
		}
	}
	int maxm=1,start;
	for(int i=1;i<=m;i++){
		if(dp[n][i]>=maxm){
			maxm=dp[n][i];
			start=i;
		}
	}
	cout<<maxm<<endl;
	print(start);
	return 0;
}
```
