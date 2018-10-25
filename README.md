# Praktikum2

## latihann1.cpp program menghitung bilangan terbesar dari 3 bilangan

**Alur Algoritma**
1. Mendeklarasikan Variable int A,B,C sebagai varible input
2. membaca input dari key board  cin >> A >> B >> C
4. membandingkan nilain variable **A** dengan Variable **B** & **C**
5. Jika kondisi **true** Maka cetaklah variable **A**
6. Membandingkanlah nilai **B** dengan **C** & **A**
7. jika kondisi **true** Maka cetaklah variable **B**
7. jika kondisi **false** **cout** **C** 

**flowchart program**
![flowchart](https://raw.githubusercontent.com/Amirul29/Praktikum2/master/FLOWCHART1.jpg)

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

    if (A>B && A>C) cout << "bilangan terbesar =" << A << endl;
    else
    {
        if (B>A && B>C) cout << "bilangan terbesar = " << B << endl;
        else
            cout << "bilangan terbesar = " << C;
    }
}

```

hasilnya :
![pic1](https://raw.githubusercontent.com/Amirul29/Praktikum2/master/pic1.png)


## latihan2.cpp menghitung bilangan terbesar dari 4 bilangan

**Alur Algoritma**
1. Mendeklarasikan Variable int A,B,C,D sebagai varible input
2. membaca input dari key board  cin >> A >> B >> C >>D
3. membandingkan nilain variable **A** dengan Variable **B** & **C** & **D**
4. Jika kondisi **true** Maka cetaklah variable **A**
5. dan bandingkan nilai  **B** dengan **A**,**C** & **D**
6. jika kondisi **true** maka cetaklah  **B**
7. dan variable **C** dibandingkan lagi **B**,**A** & **D**
8. jika kondisi **true** maka cetaklah **C** 
9. dan jika kondisi **false** maka cetaklah **D**

**flowchart program**
![FLOWCHARTLT2](https://raw.githubusercontent.com/Amirul29/Praktikum2/master/FLOWCHARTLT2.jpg)
  
**CODE PROGRAM**
```c++
#include <iostream>

using namespace std;

int main()
{
    int A,B,C,D;
    cout<<"MASUKAN BILANGAN 1: ";
    cin>> A;
    cout<<"MASUKAN BILANGAN 2: ";
    cin>> B;
    cout<<"MASUKAN BILANGAN 3: ";
    cin>> C;
    cout<<"MASUKAN BIANGAN 4: ";
    cin>> D;

    if (A>B && A>C && A>D) cout << "bilangan terbesar = " << A << endl;
    else

    if (B>A && B>C && B>D) cout << "bilangan terbesar = " << B << endl;

    else {
        if (C>A && C>B && C>D) cout << "bilangan terbesar = " << C << endl;
        else
            cout << "bilangan terbesar = " << D;
    }
}
```

hasilnya :
![pic2](https://raw.githubusercontent.com/Amirul29/Praktikum2/master/pic2.png)

