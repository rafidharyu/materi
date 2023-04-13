//YANG MAKE CSTRING

#include <iostream>
#include <cstring>
using namespace std;

class Mahasiswa{
  public:
  char nama[50];
  char npm[15];
  char kelas;
  
  Mahasiswa (const char* nama, const char* npm, char kelas){
    strcpy(Mahasiswa::nama, nama);
    strcpy(Mahasiswa::npm, npm);
    Mahasiswa::kelas = kelas;
    }
    
   void akun_mahasiswa(void){
     cout << nama << endl;
     cout << npm << endl;
     cout << kelas << endl;
     }
  };

int main(){
  Mahasiswa ilkom = Mahasiswa ("Rafid Haryu Novrian", "2217051009", 'C');
  ilkom.akun_mahasiswa();
  return 0;
}


//YANG MAKE STRING

#include <iostream>
#include <string>
using namespace std;

class Mahasiswa{
  public:
  string nama;
  string npm;
  char kelas;
  
  Mahasiswa (string nama, string npm, char kelas){
    Mahasiswa::nama = nama;
    Mahasiswa::npm = npm;
    Mahasiswa::kelas = kelas;
    }
    
   void akun_mahasiswa(void){
     cout << nama << endl;
     cout << npm << endl;
     cout << kelas << endl;
     } 
  };



int main(){
  Mahasiswa ilkom = Mahasiswa ("Rafid Haryu Novrian", "2217051009", 'C');
  ilkom.akun_mahasiswa();
  return 0;
}


//PUNYA ARKAN

#include <iostream>
#include <string>

using namespace std;

class Pekerjaan{
    private :
        string nama_pekerjaan;
        double gaji;
    public :
        Pekerjaan(string nama, double gaji){
            nama_pekerjaan = nama;
            this -> gaji = gaji;
        }

        void setNamaKerjaan(string namaKerja){
            this -> nama_pekerjaan = namaKerja;
        }
        void setGaji(double gaji){
            this -> gaji = gaji;
        }

        string getNamaKerja(){
            return nama_pekerjaan;
        }
        double getGaji(){
            return gaji;
        }
    

};

int main(){
    Pekerjaan job1("Guru", 100000);
    cout << job1.getNamaKerja() << endl;
    cout << job1.getGaji() << endl;

    Pekerjaan job2("PSK", 200);
    cout << job2.getNamaKerja() << endl;
    cout << job2.getGaji() << endl;

    Pekerjaan job3("WIRAUSAHAWAN", 20);
    cout << job3.getNamaKerja() << endl;
    cout << job3.getGaji() << endl;

    return 0;
}



#dari itu

#include <iostream>
#include <cstring>

using namespace std;

// Deklarasi class/struct
struct Mahasiswa {
    char* nama;
    int umur;
};

// Deklarasi function
void printMahasiswa(Mahasiswa* mhs) {
    cout << "Nama: " << mhs->nama << endl;
    cout << "Umur: " << mhs->umur << endl;
}

// Deklarasi pointer dan CString
void setNama(Mahasiswa* mhs, const char* nama) {
    mhs->nama = new char[strlen(nama) + 1];
    strcpy(mhs->nama, nama);
}

int main() {
    // Inisialisasi pointer dan CString
    Mahasiswa* mhs = new Mahasiswa;
    const char* nama = "John Doe";

    // Memanggil function dan mengisi nilai untuk struct
    setNama(mhs, nama);
    mhs->umur = 20;

    // Memanggil function untuk mencetak nilai struct
    printMahasiswa(mhs);

    // Menghapus memori yang dialokasikan
    delete[] mhs->nama;
    delete mhs;

    return 0;
}
