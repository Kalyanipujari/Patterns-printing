# Patterns-printing
>>> Input:5
>>> Output:
                 *
                *1*
               *2*1*
              *1*2*3*
             *4*3*2*1*
            *1*2*3*4*5*

---- C++ Pattern Code: ----
#include<iostream>
using namespace std;
int main()
{
    int row,totalRow,symbol,space;
    cin>>totalRow;
    totalRow=totalRow+1;
    //rows
    for(row=1;row<=totalRow;row++)
    {
        int i=1,j=(row-1);
        for(space=1;space<=(totalRow-row);space++)
            cout<<" ";
        for(symbol=1;symbol<=((2*row)-1);symbol++)
        {
           if((symbol%2)==1)
                cout<<"*";
           else
                if((row%2)==0)
                {
                    cout<<i;
                    i++;
                }
                else
                {
                    cout<<j;
                    j--;
                }
        }
        cout<<endl;
    }
    
    return 0;
}
