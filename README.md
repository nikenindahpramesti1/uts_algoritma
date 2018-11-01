# uts_algoritma


## Soal 1

**Alur algoritma**
1. Mendeklarasikan variabel `int A,B,X,Y` sebagai variabel input
2. Membaca input dari keyboard `cin >> A >> B >> X >> Y `
3. Membandingkan variabel **X** dengan **Y** jika sama
4. Karena statement **false** tidak akan terjadi karena `{X != Y}`
5. Dan jika statement **True** maka **X < Y** berlaku rumus statement **True** dengan syntax `X = X + A`
6. Dan jika statement **False** `Y = Y + B`


**Kode lengkap program**
**soal A**

```
#include<iostream>

using namespace std;

int main ()
{
    int A,B,X,Y;

    cout << "masukan bilangan X: ";
    cin >> A;
    cout << "masukan bilangan Y: ";
    cin >> B;

    X = A;
    Y = B;
    if(X != Y )
          {if ( X < Y  )
                { X = X + A;}
           else
                { Y = Y + B;}
          }

    cout << X;


}
```

**Kode lengkap program**
**soal B**

```
#include<iostream>

using namespace std;

int main ()
{
    int A,B,X,Y;

    cout << "masukan bilangan X: ";
    cin >> A;
    cout << "masukan bilangan Y: ";
    cin >> B;

    X = A;
    Y = B;
    if(X != Y )
          {if ( X < Y  )
                { X = X + A;}
           else
                { Y = Y + B;}
          }

    cout << Y;


}
```


## Soal 2

**Alur algoritma**
1. Mendeklarasikan variabel `int N,X,T,Batas` sebagai variabel input
2. Membaca input dari keyboard `cin >> N `
3. Masukan nilai **N** yaitu 2 angka terakhir Nim saya, dan batasnya adalah hasil jumlah N+100 
4. Dimana **T** lebih kecil dari atau sama dengan **Batas**
5. Kemudian cetak variabel **T**


**Kode lengkap program**
```
#include<iostream>

using namespace std;

int main ()
{
    int N,X,T,Batas;

    cout << "masukan nilai N: ";
    cin >> N;


    Batas = N + 100;
    X = 20;
    T = N;

    while ( T <= Batas)
        { T = T + X;
          X = X + 10;
        }


    cout << T;


}
```





