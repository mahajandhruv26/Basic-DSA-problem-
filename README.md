# Basic-DSA-problem-#include<iostream>
using namespace std;
int main(){
    int i,j,n;
    cin>>n;
    i=1;
    while(i<=n){
        int j=1;
        int k=n-i+1;
        while(j<=k){
            cout<<j;
            j++;
        }
        int l=i;
        l=(i-1)*2;
        while(l){
            cout<<"*";
            l--;
        }
        
        j--;
        while(j){
            cout<<j;
            j--;
        }
    i++;
    cout<<endl;
    }
}
    
    
/*output:
5
1234554321
1234**4321
123****321
12******21
1********1*/
