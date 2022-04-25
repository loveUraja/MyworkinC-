# MyworkinC-
Bcoz my luck is often to change my laptop monthly so that's why i am making the github to save my work.
// simple counting program by recursion..
// 
#include <iostream>
using namespace std;
void Counting(int n)
{ 
    if (n == 0)
        return;
    Counting(n - 1);
    cout << endl;
    cout << n << " ";  
}

int main()
{
    int a;
    cin >> a;
    Counting(a);
    return 0;
}
