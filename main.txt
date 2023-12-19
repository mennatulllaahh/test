#include <iostream>

// Function to add two numbers
int add(int a, int b) {
    return a + b;
}

int main() {
    int num1 = 5;
    int num2 = 7;

    // Calling the add function and printing the result
    int sum = add(num1, num2);
    std::cout << "The sum is: " << sum << std::endl;

    return 0;
}
