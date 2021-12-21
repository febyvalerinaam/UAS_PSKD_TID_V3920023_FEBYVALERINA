# UAS_PSKD_TID_V3920023_FEBYVALERINA

1. PROGRAM KEY.py
   Pada program ini terdapat pendeklarasian fungsi generator yang akan kemudian akan melakukuan export kunci private dan public dalam bentul PEM. Kemudian kunci tersebut akan  diprint.
2. PROGRAM ENKRIPSI & DEKRIPSI
   Pada program enkripsi gambar ini menggunakan fungsi blob. Kemudian file kunci publik diambil untuk membuat rsa kunci dan blob akan dikompres. Perulangan pada program ini menyatakan jika nilai chunk menjadi blob panjanganya dibagi dengan ukuran tidak sama dengan maka chunk akan bernilai byte dari ukuran chuck dikurangani panjangnya, kemudian enkripsi dideklarasikan dengan kunci rsa dan enkripsi chunk, kemudian jika masih tidak diakhiri maka akan mengulang encode enkripsinya.
