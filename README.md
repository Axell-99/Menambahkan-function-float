#Menambahkan-function-float

## Penjelasan program
Saya menggunakan int dan float sebagai functionnya,saya menggunakan float untuk mencari rata rata dari codingan yang saya gunakan, karena sebelumnya di UUK saya disuruh mencari jarak terjauh dan saya memodifikasinya untuk mencari rata rata dari program tersebut

[image](https://github.com/user-attachments/assets/d15ee01c-3e57-443c-8683-1e4cd4cf6739)
itu menjadi parameeter dan mengembalikan nilai ke float

[image](https://github.com/user-attachments/assets/7979fd6a-a7fa-4739-a537-d1c0536f984c)
float hasil[4]; (untuk mendeklarasikan array hasil dengan 4 elemen tipe float untuk menyimpan jarak yang dimasukkan pengguna)
cout << "Silahkan Masukkan Jarak Yang Ingin Di Cek: " << endl; (menampilkan pesan untuk meminta pengguna memasukkan jarak)
for(int i = 0; i < 4; ++i) { cin >> hasil[i]; } (permintaan pengguna untuk memasukkan 4 jarak dan menyimpannya dalam array)
float rataRata = cariRataRata(hasil, 4); (untuk memanggil fungsi cariRataRata untuk menghitung rata-rata jarak dan menyimpannya dalam variabel rataRata)
cout << "Rata-Rata Jarak adalah: " << rataRata << " KM" << endl; ( untuk menampilkan rata-rata jarak)
return 0; (menandakan bahwa program sukses dijalankan)

[image](https://github.com/user-attachments/assets/a3ba0703-7c48-49fe-8405-6e6e0476e2f0)
float cariRataRata(float jarak[], int ukuran) (ini untuk mendefinisikan fungsi cariRataRata)
float total = 0; (untuk mendeklarasikan variabel total dengan nilai awal 0 untuk menyimpan jumlah total jarak)
for(int i = 0; i < ukuran; ++i) { total += jarak[i]; } (ini adalah loop yang menjumlahkan semua elemen dalam array jarak)
return total / ukuran; (mengembalikan nilai rata-rata dengan membagi total dengan ukuran (yaa sebenernya ngide aja ini tp bener))
##Tampilan Akhir
Menampilkan rata rata dari angka yang sudah di masukkan
