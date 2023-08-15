# LEYNotFound.github.io

## P1
```c++
#include<bits/stdc++.h>
using namespace std;  
int n,a[100002],dp[100002],dp2[100002];
int main()
{
    int n=1;
    while(cin>>a[n]){
        dp[n]=1;
        dp2[n]=1;
        n++;
    }
    for(int i=2;i<=n;i++){
        for(int j=1;j<i;j++){
            if(a[i]<=a[j]){
                dp[i]=max(dp[j]+1,dp[i]);
            }else{
                dp2[i]=max(dp2[j]+1,dp2[i]);
            }
        }
    }
    int maxx=INT_MIN,cnt=0;
    for(int i=1;i<=n;i++){
        maxx=max(maxx,dp[i]);
        cnt=max(cnt,dp2[i]);
    }
    cout<<maxx-1<<endl<<cnt;
    return 0;
}
```
