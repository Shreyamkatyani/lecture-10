# lecture-10
#include<iostream>
using namespace std;

int main()
{
    int i,j,k;
    i=0;
    j=0;
    k=0;
    cout<<"i = "<<i<<" j = "<<j<<" k = "<<k<<endl;
    j = i++;
    cout<<"i = "<<i<<" j = "<<j<<" k = "<<k<<endl;
    k = ++i;
    cout<<"i = "<<i<<" j = "<<j<<" k = "<<k<<endl;
}

//2. Print numbers 1 to 100 using for loop

#include<iostream>
using namespace std;
int main()
{
    int i;
    for(i=1;i<101;i++)  //called the update which happens after the interaction(part of a loop is completed)
    {
        cout<<i<<" ";
    }
    return 0;
}
