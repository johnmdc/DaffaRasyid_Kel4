#include <bits/stdc++.h>
using namespace std;


int batasNilai() {
    return 75;
}

double hitungRataRata(double tugas, double uts, double uas) {
    return (tugas + uts + uas) / 3;
}

void cekKelulusan(double rata) {
    if (rata >= batasNilai()) {
        cout << "Status : LULUS SELEKSI" << endl;
    } else {
        cout << "Status : TIDAK LULUS SELEKSI" << endl;
    }
}

class Beasiswa {
public:
    void tampilkanJudul() {
        cout << "================================" << endl;
        cout << "     SELEKSI BEASISWA" << endl;
        cout << "         KELOMPOK XX" << endl;
        cout << "================================" << endl;
    }
};

int main() {

    Beasiswa program;
    program.tampilkanJudul();

    int jumlah;

    cout << "Masukkan jumlah mahasiswa: ";
    cin >> jumlah;

    for (int i = 1; i <= jumlah; i++) {
        double tugas, uts, uas;
        cout << "\nMahasiswa ke-" << i << endl;
        cout << "Nilai Tugas : ";
        cin >> tugas;
        cout << "Nilai UTS   : ";
        cin >> uts;
        cout << "Nilai UAS   : ";
        cin >> uas;
        double rata = hitungRataRata(tugas, uts, uas);
        cout << "Rata-rata   : " << rata << endl;
        cekKelulusan(rata);
    }
    cout << "\nProgram selesai." << endl;
}
