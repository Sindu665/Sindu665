
#include <iostream>
using namespace std;

int main() {
    double nilai1, nilai2, hasil;
    char operasi;

    cout << "Masukkan nilai pertama: ";
    cin >> nilai1;

    cout << "Masukkan operator (+, -, *, /): ";
    cin >> operasi;

    cout << "Masukkan nilai kedua: ";
    cin >> nilai2;

    switch(operasi) {
        case '+':
            hasil = nilai1 + nilai2;
            break;

        case '-':
            hasil = nilai1 - nilai2;
            break;

        case '*':
            hasil = nilai1 * nilai2;
            break;

        case '/':
            hasil = nilai1 / nilai2;
            break;

        default:
            cout << "Operator yang dimasukkan tidak valid";
            return 0;
    }

    cout << "Hasil: " << hasil;
    return 0;
}
