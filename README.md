# day40
my c++ langauge pratices 
#include <iostream>
using namespace std;

class Machine
{
public:
    Machine()
    {
        cout << "Machine Started" << endl;
    }

    ~Machine()
    {
        cout << "Machine Stopped" << endl;
    }
};

int main()
{
    Machine m1;

    return 0;
}
