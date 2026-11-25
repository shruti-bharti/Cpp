
#include <iostream>
using namespace std;

class Swap
{
    int a, b, temp;

public:
    void getData()
    {
        cout << "Enter two numbers: ";
        cin >> a >> b;
    }

    void swapNumbers()
    {
        temp = a;
        a = b;
        b = temp;
    }

    void display()
    {
        cout << "After swapping:" << endl;
        cout << "A = " << a << endl;
        cout << "B = " << b << endl;
    }
};

int main()
{
    Swap s;

    s.getData();
    s.swapNumbers();
    s.display();

    return 0;
}
