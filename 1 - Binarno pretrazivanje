#include <iostream>

using namespace std;

int BinarySearch(int array[],int size, int searchValue)
{
    int low=0;
    int high=size-1;
    int mid;
    mid=(high-low)/2;
    if(searchValue==array[mid])
    {
                               return mid;
                               }
                               else if (searchValue>array[mid])
                               {
                                    low=mid+1;
                                }
                                else
                                {
                                    high=mid-1;
                                }
}
int main()
{
    int a[]={12,22,34,56,69,71,82,99};
    int userValue;
    cout<<"Unesite svoj broj:"<<endl;
    cin>>userValue;
    int result=BinarySearch(a, 8 , userValue);
    if(result>= 0)
    {
                cout<<"Broj"<<a[result]<<"pronadjen na indeksu:"<<result<<endl;
                }
                else
                {
                    cout<<"Broj nije pronadjen"<<endl;
                }
    
    system("PAUSE");
    return 0;
}
