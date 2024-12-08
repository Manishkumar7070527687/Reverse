// Reverse

#include <iostream>
#include <cmath>

using namespace std;

int main()
{
    int input[]={1,3,4,3,33,52,6,5,4,4};
     
        for (int i =sizeof(input)/sizeof(int )-1; i >= 0; i--)
        {
            cout << input[i] << " ";
        }
    

    return 0;
}
