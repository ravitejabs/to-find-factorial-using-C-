#include <iostream>
using namespace std;
int factorial(int n)
{
    if (n == 0)
        return 1;
        int smallerproblem = factorial(n-1);
        int biggerperson = n*smallerproblem;
        return biggerperson;
}

int main() {
    int n;
    n = 8;
    int ans = factorial(n);
    cout<<ans<<endl;
    return 0;
}# to-find-factorial-using-C-
