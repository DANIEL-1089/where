#include <iostream>
#include <ctime>
#include <wchar.h>
#include <Windows.h>
#include <algorithm>
#include <vector>
#include <string>
#include <string.h>
#include <stdlib.h>
#include <cstring>
#include <conio.h>
#include <iomanip>
#include <process.h>
#include <ctime>
#include <cstdlib>



using namespace std;
class where {
private:
    char charray[10];
public:
    void reveal() {
        cout << "\nMy address is not a house and not a street - my address - " << this;
    }
};


int main()
{
    where w1, w2, w3;
    w1.reveal();
    w2.reveal();
    w3.reveal();
    cout << endl;

    return 0;
}
