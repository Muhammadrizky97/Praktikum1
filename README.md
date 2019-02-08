# praktikum1
praktikum1
A. latihan1 Membuat perhitungan Luas persegi panjang -mendeklarasikan variabel int p,l sebagai variabel input dan variabel L sebagai variabel hasil -menghitung luas dengan rumus L = pl -menampilkan hasilnya kelayar << cout" hasilnya adalah : " << L << endl; Beriut code lengkapnya. int main() { int p, l, L; p= 10; l= 8; L= pl; cout<< "Luasnya adalah :" << L << endl; }

B. latihan2 menentukan nilai terbesar dan terkecil dari nilai yang di input -mendeklarasikan variabel int i untuk pembatasan inputan, variabel n,nilai untuk inputan -variabel max,min untuk pembatasan nilai -membuat perintah for i untuk menentukan banyak nilai yang akan dibandingkan -for (i=2;i<=n;i++) penjelasannya *dimana i akan membaca pada inputan kedua dan i kurang dari sama dengan inputan n dan nilai i akan menambah satu. -menggunakan perintah if untuk menentukan nilai terbesar dan terkecil -if (nilai>max) max=nilai; -if (nilai<min) min=nilai; penjelasanya *jika inputan nilai lebih dari max maka terbesar lah hasilnya. *jika inputan nilai kurang dari min maka terkecil lah hasilnya -menampilkan hasilnya kelayar dengan kode cout << "Nilai Terbesar adalah:" <<max<< "\nNilai Terkecil adalah:"<<min<< endl; -Berikut kode lengkapnya int main() { int i,n,max,min,nilai;

	   cout<<"=====Mencari Bilangan Terbesar & Terkecil==== \n";
	   cout<<"Masukan Banyak data :";
	   cin>> n;
	   cout<< "Masukan Nilai :";
	   cin>> nilai;

	   max=nilai;
	   min=nilai;

	   for(i=2;i<=n;i++){
	   cout<<"Masukan Nilai :";
	   cin>>nilai;
		   if (nilai>max) max=nilai;
		   if (nilai<min) min=nilai;
	}
		  cout << "Nilai Terbesar adalah:" <<max<< "\nNilai Terkecil adalah:"<<min<< endl;
	 return 0;
C. latihan3 Membuat perulangan penjumlahan -mendeklarasikan variabel int x sebagai batasan inputan nilai -mendeklarasikan variabel nilai,bil sebagai inputan -mendeklarasikan total sebagai variabel hasil -membuat pembatasan perulangan untuk inputan nilai yang akan dijumlahkan dengan rumus for for (x=1;x<=nilai;x++) penjelasanya x akan membaca saat inputan ke 1 dimana x kurang dari sama dengan inputan nilai dan x akan bertambah 1 -menjumlahkan nilai yang diinput pada nilai bil dengan rumus total=total+bil; -menampilkan hasilnya kelayar cout<<"\ntotal="<<total; Berikut kode lengkapnya. int main() { int x,nilai, bil, total=0; cout<< "Masukan Jumlah Nilai Yang Akan Di input ="; cin>> nilai; for (x=1;x<=nilai;x++) { cout<<"Masukan Nilai ke " <<x<<"="; cin>>bil; total=total+bil; cout<<"\ntotal="<<total; } return 0; }
