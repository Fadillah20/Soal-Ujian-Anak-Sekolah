#include <iostream>
using namespace std;

int main(int argc, char *argv[])
{
//variabel
int skor = 0;
int input;

//soal pertama
cout << "Hewan Pemakan Rumput?" << endl;
cout << "[1] Kambing" << endl;
cout << "[2] Singa" << endl;
cout << "[3] Burung" << endl;
cout << "[4] Badak" << endl;
cout << "[5] Jerapah" << endl;
cout << "Masukan Jawaban Mu: ";
cin >> input;

if(input==1){
  skor = skor + 100;
  }

//soal Kedua
cout << "Hewan Pemakan Daging?" << endl;
cout << "[1] Sapi" << endl;
cout << "[2] Kerbau" << endl;
cout << "[3] Kuda" << endl;
cout << "[4] Gajah" << endl;
cout << "[5] Singa" << endl;
cout << "Masukan Jawaban Mu: ";
cin >> input;

if(input==5){
  skor = skor + 100;
  }

//Soal Ketiga
cout << "Hewan Pemakan Serangga?" << endl;
cout << "[1] Kodok" << endl;
cout << "[2] Cicak" << endl;
cout << "[3] Lalat" << endl;
cout << "[4] Burung" << endl;
cout << "[5] Jangkrik" << endl;
cout << "Masukan Jawaban Mu: ";
cin >> input;

if(input==1){
  skor = skor + 100;
  }

//soal Keempat
cout << "Hewan Yang Hidup Di Air?" << endl;
cout << "[1] Ikan" << endl;
cout << "[2] Rusa" << endl;
cout << "[3] Macan" << endl;
cout << "[4] Kangguru" << endl;
cout << "[5] Tringgiling" << endl;
cout << "Masukan Jawaban Mu: ";
cin >> input;

if(input==1){
  skor = skor + 100;
  }

//soal Kelima
cout << "Hewan Yang Mempunyai Tempurung?" << endl;
cout << "[1] Ikan Hiu" << endl;
cout << "[2] Ikan Salmon" << endl;
cout << "[3] Gurita" << endl;
cout << "[4] Penyu" << endl;
cout << "[5] Kepiting" << endl;
cout << "Masukan Jawaban Mu: ";
cin >> input;

if(input==4){
  skor = skor + 100;
  }

system("cls");

cout << "Skor Anda: ";
cout << skor;
}
