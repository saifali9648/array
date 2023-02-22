#include<iostream>
using namespace std;
bool search(int arr[],int size,int element)
{
	for(int i=0;i<size;i++)
	{
		if(arr[i]==element)
		{
			return 1;
		}
	}
	return 0;
}
int main()
{
	int arr[10]={10,5,9,-2,7,8,30,20,1,2};
	cout<<"enter the element"<<endl;
	int element;
	cin>>element;
	bool found=search(arr,10,element);
	if(found)
	{
		cout<<element<<" is present"<<endl;
	}
	else
	{
		cout<<element<<" is absent"<<endl;
	}
return 0;
}
