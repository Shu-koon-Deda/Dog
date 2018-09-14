# Dog
Defining a Dog

#include <iostream>

void Dog()
{
	std::cout << "Do you see that Dog?" << std::endl;
}
int main()
{
	int legs(4);
	int eyes(2);
	int ears(2);
	int tail(1);
	int scars(0);


	Dog();

	std::cout << "Define the Dog." << std::endl;
	std::cout << "How many legs does this Dog have?" << std::endl;

	std::cin >> legs;
	std::cin.clear();
	std::cin.ignore(1000, '\n');

	if (legs == 4)
	{
		std::cout << "Straight edge Dog ;)" << std::endl;
	}
	if (legs < 4)
	{
		std::cout << "Poor Dog. Was he in a fight?" << std::endl;
	}
	if (legs > 4)
	{
		std::cout << "Thats one wierd looking Dog..." << std::endl;
	}

	system("pause");

}
