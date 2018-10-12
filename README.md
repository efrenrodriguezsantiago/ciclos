//crear una serie de numeros la cual debera iniciar en 1 y debera terminar en el que el usuario determine

#include<iostream>
using namespace std;
int main()
{
	
	int i,numero;
	
	cout<<"\nintroduce el numero que deseas que corra:";cin>>numero;
	
	
	i =1;
	
while(i<=numero){
	cout<<i<<endl;
	i++;
}
	
	
	
	return 0;
}
