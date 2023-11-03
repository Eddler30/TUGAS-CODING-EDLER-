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

# TUGAS 3
1

      // Membuat kamus zodiak
        String[] zodiacSigns = {
                "Aries", "Taurus", "Gemini", "Cancer", "Leo", "Virgo",
                "Libra", "Scorpio", "Sagittarius", "Capricorn", "Aquarius", "Pisc
Array zodiacSigns adalah cara yang baik untuk menyimpan daftar data yang memiliki hubungan atau sifat yang sama. Dalam hal ini, array ini digunakan untuk menyimpan daftar nama-nama zodiak. Setiap elemen dalam array adalah string yang mewakili nama zodiak.

2

      int[] startDates = { 21, 20, 21, 21, 23, 23, 23, 23, 22, 22, 20, 19 };
        int[] endDates = { 19, 20, 20, 22, 22, 22, 22, 21, 21, 19, 18, 20 };
Array startDates dan endDates yang Anda berikan mungkin digunakan untuk merepresentasikan rentang tanggal yang berkaitan dengan periode zodiak atau mungkin juga digunakan untuk tujuan lain yang melibatkan tanggal. startDates adalah array yang berisi tanggal awal (atau tanggal mulai) dari masing-masing periode.endDates adalah array yang berisi tanggal akhir (atau tanggal selesai) dari masing-masing periode.

3

      // Meminta pengguna memasukkan bulan dan tanggal lahir
        Scanner scanner = new Scanner(System.in);
        System.out.print("Masukkan bulan kelahiran (dalam angka): ");
        int month = scanner.nextInt();
        System.out.print("Masukkan hari kelahiran: ");
        int day = scanner.nextInt();
Scanner scanner = new Scanner(System.in);: Ini adalah baris yang digunakan untuk membuat objek Scanner yang akan digunakan untuk mengambil masukan dari pengguna melalui konsol.System.out.print("Masukkan bulan kelahiran (dalam angka): ");: Ini adalah perintah yang mencetak pesan ke layar untuk meminta pengguna memasukkan bulan kelahiran dalam bentuk angka.int month = scanner.nextInt();: Ini adalah baris kode yang digunakan untuk membaca masukan bulan yang dimasukkan oleh pengguna dan menyimpannya dalam variabel month sebagai integer.System.out.print("Masukkan hari kelahiran: ");: Ini adalah perintah yang mencetak pesan ke layar untuk meminta pengguna memasukkan tanggal kelahiran.int day = scanner.nextInt();: Ini adalah baris kode yang digunakan untuk membaca masukan tanggal yang dimasukkan oleh pengguna dan menyimpannya dalam variabel day sebagai integer.

4

            // Mencari zodiak yang sesuai dengan tanggal lahir
        String zodiacSign = null;
        for (int i = 0; i < zodiacSigns.length; i++) {
            if ((month == i + 1 && day >= startDates[i]) || (month == i + 2 && day <= endDates[i])) {
                zodiacSign = zodiacSigns[i];
                break;
String zodiacSign = null;: Pada awalnya, Anda mendeklarasikan variabel zodiacSign sebagai null. Variabel ini akan digunakan untuk menyimpan zodiak yang sesuai setelah pencarian.
for (int i = 0; i < zodiacSigns.length; i++) {: Ini adalah perulangan for yang digunakan untuk mengiterasi melalui array zodiacSigns yang berisi nama-nama zodiak.
if ((month == i + 1 && day >= startDates[i]) || (month == i + 2 && day <= endDates[i])) {: Ini adalah pernyataan if yang memeriksa apakah bulan dan tanggal kelahiran yang dimasukkan oleh pengguna cocok dengan rentang tanggal yang sesuai dengan zodiak dalam array. Dalam pernyataan ini:
zodiacSign = zodiacSigns[i];: Jika kondisi dalam pernyataan if adalah benar, maka variabel zodiacSign akan diisi dengan nama zodiak yang sesuai dengan rentang tanggal kelahiran tersebut.
break;: Setelah menemukan zodiak yang sesuai, perulangan dihentikan menggunakan break. Ini berarti kita hanya mencari zodiak yang sesuai dengan tanggal lahir pengguna dan tidak perlu melanjutkan iterasi melalui array zodiak.

5

      // Menampilkan zodiak
        if (zodiacSign != null) {
            System.out.println("Zodiak Anda adalah " + zodiacSign + ".");
        } else {
            System.out.println("Tanggal lahir tidak valid.");
        }
if (zodiacSign != null) {: Ini adalah pernyataan if yang memeriksa apakah variabel zodiacSign tidak sama dengan null
System.out.println("Zodiak Anda adalah " + zodiacSign + ".");: Jika kondisi dalam pernyataan if adalah benar, maka program akan mencetak pesan yang menginformasikan kepada pengguna zodiak yang sesuai dengan tanggal lahir mereka. else {: Jika variabel zodiacSign masih null, maka pernyataan dalam blok else akan dijalankan.System.out.println("Tanggal lahir tidak valid.");: Jika kondisi dalam pernyataan else adalah benar, maka program akan mencetak pesan kesalahan yang menginformasikan kepada pengguna bahwa tanggal lahir yang dimasukkan tidak valid.
CONTOHNYA 
![Screenshot (28)](https://github.com/Eddler30/TUGAS-CODING-EDLER-/assets/149713403/f86f53fb-9a08-4b43-904e-456a943c3581)

# TUGAS 4
1

        // Membuat sebuah array integer
        int[] angka = {1, 2, 3, 4, 5};
int[] angka: Ini adalah deklarasi variabel yang membuat sebuah array integer dengan nama angka. Tanda [] menunjukkan bahwa ini adalah tipe data array yang akan berisi bilangan bulat.
{1, 2, 3, 4, 5}: Ini adalah inisialisasi array. Dalam kurung kurawal ini, Anda menyediakan nilai-nilai yang akan disimpan dalam array. Dalam contoh ini, array angka diisi dengan lima nilai, yaitu 1, 2, 3, 4, dan 5.

2

    // Menampilkan semua nilai dalam array menggunakan perulangan for
        for (int i = 0; i < angka.length; i++) {
            System.out.println("Nilai ke-" + (i + 1) + ": " + angka[i]);
for (int i = 0; i < angka.length; i++) {: Ini adalah perulangan for yang digunakan untuk mengiterasi melalui semua elemen dalam array angka. Perulangan ini dimulai dengan inisialisasi variabel i ke 0. Kondisi i < angka.length menentukan bahwa perulangan akan berlanjut selama i kurang dari panjang (jumlah elemen) array angka. Pada setiap iterasi, i akan ditambahkan dengan 1 menggunakan i++.
System.out.println("Nilai ke-" + (i + 1) + ": " + angka[i]);: Ini adalah pernyataan yang digunakan untuk mencetak nilai dalam array.
CONTOHNYA
![Screenshot (29)](https://github.com/Eddler30/TUGAS-CODING-EDLER-/assets/149713403/ad9d10c3-cac9-45a3-81a6-c7f6bbc68b9a)




    

  
