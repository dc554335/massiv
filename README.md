# massiv
#include<iostream>

using namespace std;

int main()

    int ** creat(int &n, int &m)
    
{
    cout << "n = ";
    cin >> n;
    cout << "m = ";
    cin >> m;
    int **mas = new int * [n];
    for (int i = 0; i < n; ++i)
    mas [i] = new int *[n];
    mas [i] = new int [2 * m];
}
