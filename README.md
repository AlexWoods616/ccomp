# ccomp

#include <iostream>

using namespace std;

int main()
{
    int x;
    int y;
    int z;
    cout << "Ingrese variable x: ";
    cin >> x;
    cout << "Ingrese variable y: ";
    cin >> y;
    cout << "Ingrese variable z: ";
    cin >> z;
    if ((x>y) && (x>z))
    {
        cout << x << " es el mayor";
    }
    else if (y>z)
    {
        cout << y << " es el mayor";
    }
    else
    {
        cout << z << " es el mayor";
    }
    return 0;
}
