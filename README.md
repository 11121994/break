
#include <iostream>
#include <cstdlib>
using namespace std;

 

int main (void)

{

    int i;
    for (i=1; i<=1000; i++) //i vai de 1 a 1000

    {
    cout <<i<<"\n";
    }
    cout <<"1a Sequencia - nao tem break - vai de 1 a 1000\n";

    system ("pause");
    for (i=1; i<=1000; i++) //i vai de 1 a 1000

    {

    cout <<i<<"\n";
    if (i==200) //se i for 200

    break; //sair da iteração

    }
    cout <<"\n2a Sequencia - tem break - vai de 1 a 200, ";

    cout <<"mesmo que tenha que acabar em mil\n";

    system ("pause");

    return EXIT_SUCCESS;

    }
