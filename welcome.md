## 1A-program pertamaku

```cpp
#include <iostream>

int main() {
    std::cout << "Halo, dunia!" << std::endl;
}

```

## 1B-program pertamaku
```cpp
#include <iostream>

int main() {
    std::cout << "Halo, dunia!" << std::endl;
    
std::cout << "Aku semangat belajar C++!" << std::endl;
    
}
```







## 1C-MENCETAK BILANGAN

```cpp
#include <iostream>

int main() {
    std::cout << "Pak Dengklek memiliki " << ... << " ekor bebek." << std::endl;
}

```


## 1D-menjumlahkan bilangan
```cpp
#include <iostream>

int main() {
    std::cout << "Pak Dengklek memiliki " << 738 + 519 << " ekor bebek." << std::endl;
}

```


## 1F-MENGUKUR KANDANG
```cpp
#include <iostream>

int main() {
    // cetak luas kandang
    std::cout << 364 * 79 << std::endl;

    // cetak keliling kandang
    std::cout << 2*(364+79) << std::endl;
}

```

## 2b-perkenalan variabel
```cpp
#include <iostream>
using namespace std;

int main() {
    int panjang = 364;
    int lebar = 79;

    // cetak luas kandang
    cout << panjang * lebar << endl;

    // cetak keliling kandang
    cout << 2*(panjang+lebar) << endl;
}

```


## 2C-Memperbarui Nilai Variable
```cpp
#include <iostream>
using namespace std;

int main() {
    // kata sandi bulan pertama
    int sandi = 174;
    cout << sandi << endl;

    // kata sandi bulan kedua
    sandi = 174*23;
    cout << sandi << endl;

    // kata sandi bulan ketiga
    sandi = 174*23*23;
    cout << sandi << endl;
}

```


## 2D-kuis
```cpp
Pada soal no. 1, berikut adalah "perjalanan" perubahan nilai dari variabel `x`:

|Perintah|Nilai x setelah  <br>perintah dijalankan|
|---|---|
|```<br>int x = 3;<br>```|3|
|```<br>x = x + 1;<br>```|4|

---

Pada soal no. 2, berikut adalah "perjalanan" perubahan nilai dari variabel `x`:

|Perintah|Nilai x setelah  <br>perintah dijalankan|
|---|---|
|```<br>int x = 3;<br>```|3|
|```<br>x = x + x;<br>```|6|

---

Pada soal no. 3, berikut adalah "perjalanan" perubahan nilai dari variabel `x` dan `y`:

|Perintah|Nilai x setelah  <br>perintah dijalankan|Nilai y setelah  <br>perintah dijalankan|
|---|---|---|
|```<br>int x = 3;<br>```|3|(tidak ada)|
|```<br>int y = 4;<br>```|3|4|
|```<br>x = y;<br>```|4|4|
|```<br>y = x;<br>```|4|4|

Perhatikan bahwa program tersebut TIDAK menukar isi dari variabel `x` dan `y`
```

## 2E-perkenalan tipe data string
```cpp
#include <iostream> // untuk menggunakan cout dan endl
#include <string>   // untuk menggunakan string
using namespace std;

int main() {
    int tanggal = 15;
    int tahun = 2023;

    // jangan lupa bahwa string perlu diapit dengan kutip dua
    string bulan = "Februari"; 

    // cetak kata sandi
    cout << tahun +10 << "-" << bulan << "-" << tanggal +7 << endl;
}


```

## 3A-variasi operasi assignment

```cpp
Pada soal no. 1, berikut adalah "perjalanan" perubahan nilai dari variabel `x` dan `y`:

|Perintah|Nilai x setelah  <br>perintah dijalankan|Nilai y setelah  <br>perintah dijalankan|
|---|---|---|
|```<br>int x = 3, y = 4;<br>```|3|4|
|```<br>x -= 1;<br>```|2|4|
|```<br>y += x * 5;<br>```|2|14|

---

Pada soal no. 2, semua operasi (kecuali no. c) melipatgandakan nilai variabel `x`.
```


## 3b-