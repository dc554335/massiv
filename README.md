# massiv
#include&lt;iostream>  using namespace std;  int main()      int ** creat(int &amp;n, int &amp;m)      {     cout &lt;&lt; "n = ";     cin >> n;     cout &lt;&lt; "m = ";     cin >> m;     int **mas = new int * [n];     for (int i = 0; i &lt; n; ++i)     mas [i] = new int *[n];     mas [i] = new int [2 * m]; }
