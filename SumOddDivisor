
// Sum of odd divisors 
// find the sum between the given range


#include <iostream>
using namespace std;

int main() {
	int t;
	long long int l,r;
	cin>>t;
	while(t--)
	{
	    cin>>l;
	    cin>>r;
	    int sum=0;
	    for(int i=l;i<=r;i++)
	    {
	        
	        for(int j=1;j<=i;j++)
	        {
	            int m=i%j;
	            if(m==0)
	            {
	                if(j%2==1)
	                sum=sum+j;
	            }
	            
	        }
	    }
	    cout<<sum<<endl;
	}
	return 0;
}
