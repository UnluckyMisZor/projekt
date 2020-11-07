## Witam na mojej stronie



### Markdown

Ukończyłem tehcnikum informatyczne gdzie przez 2 lata miałem zajęcia z programowania w C++. Uważam że szło mi w miarę dobrze, nie uważam się za jakiegoś super progrimistę ale na programy na lekcjach pisałem bez większych trudności. Poznałem strukturę if, pętli, tablice, odczytywanie i zapisywanie plików tekstowych oraz funkcje.

Przykładowy program mojego autorstwa na obliczanie czy pierwsza podana prosta jest prostopadła/równoległa do drugiej prostej
```markdown

#include <iostream>

using namespace std;

int main() {
	float a1,b1,c1,a2,b2,c2,z,x;
	cout<<"Podaj a1: ";
	cin>>a1;
	cout<<"Podaj b1: ";
	cin>>b1;
	cout<<"Podaj c1: ";
	cin>>c1;
	cout<<"Podaj a2: ";
	cin>>a2;
	cout<<"Podaj b2: ";
	cin>>b2;
	cout<<"Podaj c2: ";
	cin>>c2;
	z=b1*(-1);
	x=b2*(-1);
	if(z!=1)
	{
		a1=a1/z;
		c1=c1/z;
		z=1;
	}
	if(x!=1)
	{
		a2=a2/x;
		c2=c2/x;
		x=1;
	}
	if(a1==a2)
	{
		cout<<"Proste sa rownolegle";
	}
	if(a1*a2==-1)
	{
		cout<<"Proste sa prostopadle";
	}
	if(a1!=a2 && a1*a2!=-1)
	cout<<"Proste nie sa ani rownolegle ani prostopadle";
	return 0;
}
```

Mam nadzieję że programowanie na studiach będzie równie przyjemne i będzie mi dobrze szło.
