#include <iostream>
#include <string>
using namespace std;

int main() {
    // Variables to store applicant's data
    string name, education, experience, hobby, birthDate, favoriteAnimal;
    int age, wifeAge, answer, correctAnswers = 0;

    // Request applicant data
    cout << "-----------------------------" << endl;
    cout << "    Job Application Form     " << endl;
    cout << "-----------------------------" << endl;

    cout << "Enter your full name: ";
    getline(cin, name); // Read full name

    cout << "Enter your age: ";
    cin >> age; // Read age

    cin.ignore(); // To clear the newline left by cin

    cout << "Enter your educational qualification: ";
    getline(cin, education); // Read educational qualification

    cout << "Enter your previous experience: ";
    getline(cin, experience); // Read previous experience

    // Additional questions
    cout << "Enter your favorite hobby: ";
    getline(cin, hobby); // Read favorite hobby

    cout << "Enter your wife's age: ";
    cin >> wifeAge; // Read wife's age

    // Display the entered data
    cout << "\n-----------------------------" << endl;
    cout << "      Applicant Details      " << endl;
    cout << "-----------------------------" << endl;
    cout << "Name: " << name << endl;
    cout << "Age: " << age << endl;
    cout << "Educational Qualification: " << education << endl;
    cout << "Previous Experience: " << experience << endl;
    cout << "Favorite Hobby: " << hobby << endl;
    cout << "Wife's Age: " << wifeAge << endl;
    cout << "-----------------------------" << endl;

    // Acceptance condition based on age
    if (age >= 22) {
        cout << "Congratulations, " << name << "! You are accepted for the job." << endl;

        // Ask additional questions in case of acceptance
        cout << "Enter your birth date (DD/MM/YYYY): ";
        cin.ignore();  // To make sure the line is read correctly
        getline(cin, birthDate); // Read birth date

        cout << "Enter your favorite animal: ";
        getline(cin, favoriteAnimal); // Read favorite animal

        // Display additional details
        cout << "\n-----------------------------" << endl;
        cout << "      Additional Details      " << endl;
        cout << "-----------------------------" << endl;
        cout << "Birth Date: " << birthDate << endl;
        cout << "Favorite Animal: " << favoriteAnimal << endl;
        cout << "-----------------------------" << endl;

        // Ask math questions
        cout << "\n-----------------------------" << endl;
        cout << "    Answer the following math questions    " << endl;
        cout << "-----------------------------" << endl;

        // Question 1
        cout << "1. What is 5 + 3? ";
        cin >> answer;
        if (answer == 8) correctAnswers++;

        // Question 2
        cout << "2. What is 10 - 4? ";
        cin >> answer;
        if (answer == 6) correctAnswers++;

        // Question 3
        cout << "3. What is 15 + 7? ";
        cin >> answer;
        if (answer == 22) correctAnswers++;

        // Question 4
        cout << "4. What is 9 - 2? ";
        cin >> answer;
        if (answer == 7) correctAnswers++;

        // Question 5
        cout << "5. What is 20 + 10? ";
        cin >> answer;
        if (answer == 30) correctAnswers++;

        // Check the answers
        if (correctAnswers == 5) {
            cout << "\nCongratulations! You answered all the questions correctly. You will receive a salary increase within the year!" << endl;
        } else {
            cout << "\nSorry, " << name << ". You did not answer all the questions correctly." << endl;
        }
    } else {
        cout << "Sorry, " << name << ". You are not eligible for the job." << endl;
    }

    return 0;
}
