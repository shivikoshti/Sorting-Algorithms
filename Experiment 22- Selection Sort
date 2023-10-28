#include<iostream>
using namespace std;

void swap(int *a,int *b)
{
    int temp;
    temp=*a;
    *a=*b;
    *b=temp;
}
void sort(int *a,int elements)
{
    int n=0;
    int *b;
    
    while(n!=elements)
    {
        b=a+1;
        for(int i=0;i<(elements-1)-n;i++)
        {
            if(*a>*b)
            {
                swap(a,b);
            }
            b++;
        }
        n++;
        a++;
    }
}
int main()
{
    int element;
    cout<<"Number of elements in array:"<<endl;
    cin>>element;
    int arr[element];
    cout<<"Enter "<<element<<" Elements:"<<endl;
    for(int i=0;i<element;i++)
    {
        cin>>arr[i];
    }
    sort(&arr[0],element);
    for(int i=0;i<element;i++)
    {
        cout<<arr[i]<<" ";
    }
    return 0;
}
/*
Output:
Number of elements in array:
4
Enter 4 Elements:
2 3 1 2
1 2 2 3 
*/
