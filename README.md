#include <iostream>

int main() {
    int rows = 5;

    for (int i = 1; i <= rows; ++i) {
        for (int space = 1; space <= rows - i; ++space) {
            std::cout << " ";
        }
        for (int j = 1; j <= i; ++j) {
            std::cout << "*";
        }
        std::cout << std::ends;
    }

    return 0;
}
