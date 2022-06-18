#define _USE_MATH_DEFINES
#include<iostream>
#include<cmath>
using namespace std;

int main() {
	cout << M_PI << endl;
	cout << M_E << endl;
	// tính góc
	double angle = 45 * M_PI / 180;
	cout << "sin(45) =" << sin(angle) << endl;
	cout << "cos(45) =" << cos(angle) << endl;
	cout << "asin(0.866) =" << asin(0.866) * 180 / M_PI << endl;
	// tính e^5
	cout << "e^5" << exp(5) << endl;
	// tach phan nguyen thap phan
	double fracPart, intPart;
	fracPart = modf(M_PI, &intPart);
	cout << "PI=" << intPart << "+" << fracPart << endl;
	// tính a^b;
	int a = 5;
	int b = 6;
	cout << "a^b=" << pow(a, b) << endl;
	// lam tron;
	double x = 12.55;
	double y = -5.88;
	cout << "round(x)=" << round(x) << endl;
	cout << "round(y)=" << round(y) << endl;
	// tim phan du
	cout << "phan du cua x/y" << remainder(x, y) << endl;
	return 0;
}
