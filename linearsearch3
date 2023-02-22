#include<iostream>
using namespace std;
bool search(int arr[],int size,int element)
{
	for(int i=0;i<size;i++)
	{
		if(arr[i]==element)
		{
			return 1;
			break;
		}
	}
	return 0;
}
int main()
{
	int arr[100];
	cout<<"entr the size of array:-"<<endl;
	int size;
	cin>>size;
	cout<<"enter the value:-"<<endl;
	for(int i=0;i<size;i++)
	{
		cin>>arr[i];
	}
	cout<<"enter the element"<<endl;
	int element;
	cin>>element;
	bool found=search(arr,size,element);
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
