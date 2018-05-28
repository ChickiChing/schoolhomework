# schoolhomework
Program nr 1:
#include <iostream>
#include <cstdio>
using namespace std;
int main()
{
int i = 13, j = 16;
int *wsk;
wsk = &i; // wskaźnik wskazuje na zmienną i
cout << "Wskaznik 'wsk' wskazuje na 'i', ktora ma wartosc: " << wsk << endl;
cout << "Wartosc wskaznika: " << wsk << endl;
cout << "Za chwile przekierujemy wskaznik na adres zmiennej 'j'" << endl;
wsk = &j; // wskaźnik wskazuje na zmienną j
cout << "Teraz wskaznik wskazuje na 'j', ktora ma wartosc: " << wsk << endl;
cout << "Wartosc wskaznika: " << wsk;
getchar();
return 0;
}
