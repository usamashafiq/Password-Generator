#include<iostream>
#include<conio.h>
#include<string>
#include<cstdlib>
#include<ctime>
using namespace std;
void main() {
	srand(time(0));
	int  x, z;
	char y;
	char paw[5];
	for (int i = 0; i < 5; i++) {
		//srand(time(0));
		x =65+rand() % 26;
		z = rand() % 5;
		if (i == z) {
			x = x + 32;
		}
	
		y = char(x);
		
		paw[i] = y;
		
	}cout << "pasword is " << endl;
	for (int j = 0; j < 5; j++){
		cout << paw[j];

}
	_getch();
}
