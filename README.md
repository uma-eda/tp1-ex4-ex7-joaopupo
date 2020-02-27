/* 4.	Escreva um programa que apresenta no ecrã as seguintes operações aritméticas e calcula os respetivos resultados:
7+3 = 10
7-3 = 4
7*3 = 21
7/3 = 2
7.0/3.0 = 2.3
7%3 = 1
7+3*5 = 22
(7+3)*5 = 50
*/

#include <iostream>
#include <iomanip>    // para fixar casas decimais no output
using namespace std;

int main()
{
    int n1 = 7, n2 = 3, n3 = 5;

    cout << "7+3 = " << n1 + n2 << endl;
    cout << "7-3 = " << n1 - n2 << endl;
    cout << "7*3 = " << n1 * n2 << endl;
    cout << "7/3 = " << n1 / n2 << endl;
    cout << fixed;
    cout << setprecision(1) << "7.0/3.0 = " << (float)n1 / n2 << endl;
    cout << "7%3 = " << n1 % n2 << endl;
    cout << "7+3*5 = " << n1 + n2 * n3 << endl;
    cout << "(7+3)*5 = " << (n1 + n2) * n3 << endl;

    return 0;
}
