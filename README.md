harjoitus-08
============

Palautus viikolla 40

Tee ohjelma, joka tulostaa annetut kolme lukua suuruus-
järjestyksessä (pienimmästä suurimpaan) näytölle
(katso harj. 1 suunnitelma)
a) käytä kokonaislukuja
b) käytä liukulukuja (=reaalilukuja)

#include <iostream>
using namespace std;
int main()
{
	float luku1;
	float luku2;
	float luku3;
	cout << "Anna luku 1 "<<endl;
	cin >> luku1;
	cout << "Anna luku 2 "<<endl;
	cin >> luku2;
	cout << "Anna luku 3 "<<endl;
	cin >> luku3;
	if (luku1 > luku2)
	{
		if (luku1 > luku3)
		{
			if (luku2 > luku3)
				cout << luku1 <<" > "<< luku2 << " > "<< luku3<<endl;
			else 
			cout << luku1 <<" > "<< luku3 << " > "<< luku2<<endl;
		}
		else
			cout << luku3 <<" > "<< luku1 << " > "<< luku2<<endl;
	}
	else
	{
		if (luku1 > luku3)
			cout << luku2 <<" > "<< luku1 << " > "<< luku3<<endl;
		else
		{
			if (luku2 > luku3)
				cout << luku2 <<" > "<< luku3 << " > "<< luku1<<endl;
			else
				cout << luku3 <<" > "<< luku2 << " > "<< luku1<<endl;
		}
	}
return (0);
}
/*#include <iostream>
using namespace std;
int main()
{
	int luku1;
	int luku2;
	int luku3;
	cout << "Anna luku 1 "<<endl;
	cin >> luku1;
	cout << "Anna luku 2 "<<endl;
	cin >> luku2;
	cout << "Anna luku 3 "<<endl;
	cin >> luku3;
	if (luku1 > luku2)
	{
		if (luku1 > luku3)
		{
			if (luku2 > luku3)
				cout << luku1 <<" > "<< luku2 << " > "<< luku3<<endl;
			else 
			cout << luku1 <<" > "<< luku3 << " > "<< luku2<<endl;
		}
		else
			cout << luku3 <<" > "<< luku1 << " > "<< luku2<<endl;
	}
	else
	{
		if (luku1 > luku3)
			cout << luku2 <<" > "<< luku1 << " > "<< luku3<<endl;
		else
		{
			if (luku2 > luku3)
				cout << luku2 <<" > "<< luku3 << " > "<< luku1<<endl;
			else
				cout << luku3 <<" > "<< luku2 << " > "<< luku1<<endl;
		}
	}
return (0);
}*/