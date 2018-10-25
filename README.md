# Praktikum3

## latihan1.cpp program menghitung bilangan terbesar dari 3 bilangan

**Alur Algoritma**
1. Mendeklarasikan Variable int A,B,C sebagai varible input
. membaca input dari key board  cin >> A >> B >> C
4. membandingkan nilain variable **A** dengan Variable **B** & **C**
5. Jika kondisi **true** Atau Sama Maka cetaklah variable **SAMA SISI**
6. Membandingkanlah nilai **B** dengan **C** & **A**
7. jika kondisi **or** Atau Salah satu nilai tidak sama Maka cetaklah variable **SAMA KAKI**
7. jika kondisi **false** Atau tidak sama semua nilainya **cout** **SEMBARANG** 

**CODE PROGRAM**

```c++
#include <iostream>

using namespace std;

int main()
{
    int A,B,C;
    cout<<"MASUKAN BILANGAN 1: ";
    cin>> A;
    cout<<"MASUKAN BILANGAN 2: ";
    cin>> B;
    cout<<"MASUKAN BILANGAN 3: ";
    cin>> C;

    if (A==B && A==C && B==C) cout << "SAMA SISI " << endl;    {
        if (A==B && A!=C) cout << "SAMA KAKI  " << endl;}
         {             if (A==C && B!=C) cout << "SAMA KAKI " << endl;}
        {if (B==C && A!=B) cout << "SAMA KAKI  " << endl;}
        { if (A!=B && A!=C && B!=C) cout << "SEMABARANG " << endl;}


    return 0;
}
}

```

hasilnya :
![Gmbr2](https://raw.githubusercontent.com/Khunaify/Praktikum3/master/Gmbr2.png)```

hasilnya :
![Gmbr3](https://raw.githubusercontent.com/Khunaify/Praktikum3/master/Gmbr3.png) ```

hasilnya :
![Gmbr4](https://raw.githubusercontent.com/Khunaify/Praktikum3/master/Gmbr4.png)


## 