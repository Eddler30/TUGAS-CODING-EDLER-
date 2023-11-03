# TUGAS-CODING-EDLER-
# TUGAS 1
1

    public class LoopExample {
public class LoopExample {: Ini adalah awal deklarasi kelas Java. Kata kunci public digunakan untuk menentukan bahwa kelas ini dapat diakses dari luar paket (public class)   

2

     public static void main(String[] args) {
public static void main(String[] args) {: Ini adalah deklarasi metode main. Metode main adalah metode khusus dalam bahasa Java yang digunakan sebagai titik masuk untuk program Java. 

3

         for (int i = 1; i <= 100; i++) {
            System.out.printf("%4d(Edler)%n", i);
for (int i = 1; i <= 100; i++) {: Ini adalah perulangan for yang digunakan untuk mengiterasi dari 1 hingga 100. Variabel i diinisialisasi dengan 1, dan perulangan akan berlanjut selama nilai i kurang dari atau sama dengan 100. Setiap kali perulangan selesai dijalankan, nilai i akan ditambahkan dengan 1 menggunakan i++.
System.out.printf("%4d(Edler)%n", i);: Dalam setiap iterasi perulangan, perintah printf digunakan untuk mencetak nilai i ke layar dengan format tertentu. 

4 Contohnya
![Screenshot (26)](https://github.com/Eddler30/TUGAS-CODING-EDLER-/assets/149713403/eabf3a52-00a3-439a-adb1-e39dd868a1c6)

# TUGAS 2
1

     Scanner scanner = new Scanner(System.in);
Objek Scanner digunakan untuk mengambil masukan dari pengguna melalui konsol atau berbagai sumber masukan, seperti berkas teks.

2

     System.out.print("Masukkan angka maksimal: ");
System.out.print("Masukkan angka maksimal: "); adalah perintah yang digunakan untuk mencetak pesan kepada pengguna yang meminta pengguna untuk memasukkan angka maksimal.

3  

        int n = scanner.nextInt();
        int totalGenap = 0;
        int i = 1;
int n = scanner.nextInt();: Baris ini digunakan untuk membaca sebuah angka dari pengguna dan menyimpannya dalam variabel n. Angka ini akan digunakan sebagai angka maksimal untuk perhitungan selanjutnya. 
int totalGenap = 0;: Ini adalah inisialisasi variabel totalGenap dengan nilai awal 0. Variabel ini akan digunakan untuk menghitung jumlah bilangan genap yang akan ditemukan dalam perulangan.
int i = 1;: Ini adalah inisialisasi variabel i dengan nilai awal 1. Variabel i ini akan digunakan sebagai penghitung dalam perulangan untuk mengiterasi dari 1 hingga n.

4

            while (i <= n) {
            if (i % 2 == 0) {
                totalGenap += i;
            }
            i++;
while (i <= n) {: Ini adalah deklarasi perulangan while. Perulangan ini akan terus berjalan selama kondisi dalam tanda kurung kurawal ( dan ) bernilai benar. 
if (i % 2 == 0) {: Ini adalah pernyataan if yang digunakan untuk memeriksa apakah i adalah bilangan genap.
totalGenap += i;: Jika i adalah bilangan genap (memenuhi kondisi dalam pernyataan if), maka nilai i akan ditambahkan ke dalam totalGenap. Ini digunakan untuk mengakumulasi jumlah bilangan genap selama perulangan.
i++;: Setiap kali pernyataan dalam perulangan selesai dieksekusi, nilai i akan ditambahkan dengan 1 menggunakan i++. Ini digunakan untuk menginkrementasi (menambahkan 1) nilai i sehingga perulangan dapat berlanjut ke bilangan berikutnya.

5  

    System.out.println("Jumlah bilangan genap dari 1 hingga " + n + " adalah: " + totalGenap);
System.out.println(): Ini adalah perintah yang digunakan untuk mencetak teks atau hasil ke layar. Dalam hal ini, kita akan mencetak pesan yang menginformasikan hasil perhitungan.
"Jumlah bilangan genap dari 1 hingga ": Ini adalah string teks yang akan dicetak ke layar. Pesan ini berisi informasi awal yang menjelaskan apa yang akan dicetak.
+ n + " adalah bagian yang digunakan untuk menambahkan nilai variabel n ke dalam pesan yang akan dicetak. Ini akan menggantikan bagian + n + dalam pesan dengan nilai aktual dari variabel n.
+ " adalah: ": Ini adalah string teks yang akan digunakan sebagai pemisah antara informasi dan hasil perhitungan.
+ + totalGenap: Ini adalah bagian yang digunakan untuk menambahkan nilai variabel totalGenap ke dalam pesan.

Contohny
![Screenshot (27)](https://github.com/Eddler30/TUGAS-CODING-EDLER-/assets/149713403/0980218e-b58e-4a0a-aad7-31ae1c437095)


    

  
