#include <iostream>
#include <string>

int main() {
    std::string input;

    std::cout << "Welcome to Eternal Echoes! Type 'exit' to end the program.\n";

    while (true) {
        std::cout << "> ";
        std::getline(std::cin, input);

        if (input == "exit") {
            break;
        }

        std::cout << "Echo: " << input << "\n";
    }

    std::cout << "Goodbye!\n";
    return 0;
}
