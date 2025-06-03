#include <iostream>
#include <iomanip>
#include <sstream>
#include<string>

int main () {
    std::string input;
    int choice = 0;
    int quantity = 0;
    double total = 0.0;

    while (true) {
        std::cout << "=== Welcome to Nick Vending Machine ===\n";
        std::cout << "1. Coca-Cola           £1.50\n";
        std::cout << "2. Pepsi               £1.45\n";
        std::cout << "3. Sprite              £1.75\n";
        std::cout << "4. Mountain Dew        £1.85\n";
        std::cout << "5. Water               £1.00\n";
        std::cout << "6. Exit \n\n";

        std::cout << "Please select an iteam (1-6): ";
        std::getline(std::cin, input);
        std::stringstream(input) >>choice;

        if (choice == 6) {
            std::cout << "Thank you for using Nick Vending Machine!\n";
            break;
        }

        switch (choice) {
            case 1:
                std::cout << "Enter quantity of Coca-Cola: ";
                break;

            case 2:
                std::cout << "Enter quantity of Pepsi: ";
                break;

            case 3:
                std::cout << "Enter quantity of Sprite: ";
                break;

            case 4:
                std::cout << "Enter quantity of Mountain Dew: ";
                break;

            case 5:
                std::cout << "Enter quantity of Water: ";
                break;
            default:
                std::cout << "Invalid selection. Please try again.\n";
            
            }

            std::getline(std::cin, input);
            std::stringstream(input) >>quantity;

            switch (choice) {
                case 1: total = quantity * 1.50; break;
                case 2: total = quantity * 1.45; break;
                case 3: total = quantity * 1.75; break;
                case 4: total = quantity * 1.85; break;
                case 5: total = quantity * 1.00; break;
            }

            std::cout << std::fixed << std::setprecision(2);
            std::cout << "Total to pay: £" << total << "\n";
            std::cout << "Thank you for your purchase!\n\n";
        }

        return 0;
}

