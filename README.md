#include <iostream>
#include <string>
using namespace std;

int main() {
    string username, password;
    string inputUser, inputPass;

    cout << "===== SIGN UP =====" << endl;
    cout << "Create username: ";
    cin >> username;
    cout << "Create password: ";
    cin >> password;
    cout << "\nSign Up Successful!" << endl;

    cout << "\n===== LOG IN =====" << endl;
    cout << "Enter username: ";
    cin >> inputUser;
    cout << "Enter password: ";
    cin >> inputPass;

    if (inputUser == username && inputPass == password) {
        cout << "\nLogin Successful! Welcome, " << inputUser << "!" << endl;
    } 
    else {
        cout << "\nLogin Failed. Incorrect username or password." << endl;
    }

    return 0;
}
