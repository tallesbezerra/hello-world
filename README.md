# em c++
#include <iostream>
using namespace std;

int main()
{
	int i = 0;
	
	for(i=0;i<12;i+=3)
	{
		/*
		 *Verifica se o valor é 5 
		 */
		if(i>5)
		{
			cout<< "Maior que 5"<<endl;
		}
		else
		{
			cout<< "Menor que 5"<<endl;
		}
	cout << i << endl;	
	}
	
	return 0;
}
