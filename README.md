# code-2

#include<bits/stdc++.h>
using namespace std;

 string compareNM(int n, int m){
        if(n < m){
            return "lesser";
        }
        if(n==m){
            return "equal";
        }
        else{
            return "greater";
        }
    }

int main(){
int t;
cin>>t;
while(t--){
    int n,m; cin>>n>>m;
    Solution obj;
    cout<<obj.compareNM(n,m)<<"\n";
  }
return 0;
}
