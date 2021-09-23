#include<iostream>
using namespace std;
int main()
{
	int num,i,j,k,l,search=0;
    
    cout<<"assign the order of 2-D array  ";
    cin>>k>>l;
    int arr[k][l];
	cout<<"enter your 2d array of  "<<k<<"*"<<l <<"order"<<endl;
	for(i=0;i<k;i++)
	{
		for(j=0;j<l;j++)
		{
			cin>>arr[i][j];
		}
	}
	cout<<"which element you want to find = ";
	cin>>num;
		for(i=0;i<k;i++)
	{	
		for(j=0;j<l;j++)
		{
			if(num==arr[i][j])
			{
				search=1;
				cout<<"your element is found at "<<i<<","<<j<<" location";
				break;
		}
		}
	}
	if(search==0)
	{
		cout<<"element not their in the array";
	}
	return 0;
}
