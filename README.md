#include "teste.h"
#include <iostream>
#include <string>
#include <windows.h>
#include <limits>


int main()
{
	int a, b, c, d, e, f;


	std::cout << "o aluno tirou quanto no teste? ";
	std::cin >> a;

	std::cout << "o aluno tirou quanto na prova? ";
	std::cin >> b;

	std::cout << "o aluno tirou quanto no dever de casa? ";
	std::cin >> c;

	std::cout << "o aluno tirou quanto no teste segundo bimestre? ";
	std::cin >> d;

	std::cout << "o aluno tirou quanto no prova segundo bimestre? ";
	std::cin >> e;

	std::cout << "o aluno tirou quanto no dever de casa segundo bimestre? ";
	std::cin >> f;


	double media1 = (a + b + c * 2) / 4.0;
	double media2 = (a + b + c) / 4.0;

	std::cout << "Média do 1º bimestre: " << media1 << std::endl;
	std::cout << "Média do 2º bimestre: " << media2 << std::endl;





}
