# menampilkan-bilangan-genap

        #include <iostream>
        #include <Conio.h>
        using namespace std ;

          int main ( )
        {
        cout << " \t|============================================|" << endl ;
        cout << " \t|=== PROGRAM MENAMPILKAN BILANGAN GENAP =====|" << endl ;
        cout << " \t|============= ALIF MUSTAFANAH ==============|" << endl ;
        cout << " \t|============================================|\n" << endl ;


        for ( int gnp = 1 ; gnp <= 100 ; gnp ++ )
        if ( gnp % 2 == 0 ) {
        cout << gnp << " " ;
        } else {
        //tidak ada aksi
        }

        cout << " \n\t" << endl ;
        cout << " \n\t|===============================================|" << endl ;
        cout << " \t|== TERIMAKASIH SUDAH MENGGUNAKAN PROGRAM INI ==|" << endl ;
        cout << " \t|============== ALIF MUSTAFANAH ================|" << endl ;
        cout << " \t|===============================================|\n" << endl ;

        return 0;
        }
