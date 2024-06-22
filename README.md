# Lecture-7


In theis lecture i learned that how to drclare an array and hoe to take input and print then an array and also add then here is the sample program 
#include <iostream>

int main() {
    const int SIZE = 5;  // Define the size of the array
    int numbers[SIZE];   // Declare an array of integers

    // Prompt the user for input
    std::cout << "Enter 5 numbers:" << std::endl;

    // Input elements into the array
    for (int i = 0; i < SIZE; ++i) {
        std::cout << "Enter number " << (i + 1) << ": ";
        std::cin >> numbers[i];
    }

    // Print the elements of the array
    std::cout << "You entered the following numbers:" << std::endl;
    for (int i = 0; i < SIZE; ++i) {
        std::cout << "Number " << (i + 1) << ": " << numbers[i] << std::endl;
    }

    return 0;
}
