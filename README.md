# tugas-MKU-coding

# PENJELASAN NOMOR 1

        String name = "Muhammad Farhan Dzakki";
        String NPM = "G1A023041";
        System.out.println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
        System.out.println("NAMA :" + name);
        System.out.println("NPM :" + NPM);
        System.out.println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");

code diatas berfungsi untuk membuat nama dan NPM kita

pada soal nomor 1 ini kita menggunakan fungsi perulangan for

        for (int i = 1 ; i <= 100; i++){

for merupakan salah satu bentuk fungsi perulangan yang digunakan untuk melaksanakan pernyataan atau statment berulang kali terhadap sejumlah nilai yang telah ditetapkan seperti integer yang ada pada code for diatas menetapkan i = 1; i <= 100; i++

penjelasan if dan else

        if (i<=9){
              System.out.println(i);
        }
        else {
              System.out.println(name);
        }

if disini digunakan untuk i lebih kecil dari pada 9 yang artinya 0 - 9 akan memprint i dan else yang artinya sisanya mengeprint nama kita

# PENJALANAN PROGRAM NOMOR 1

![Screenshot (316)](https://github.com/dzakki08/tugas-MKU-coding/assets/147239806/e5b452ae-c5a8-4de9-a5eb-2b139525c41c)


# PENJELASAN NOMOR 2

        String name = "Muhammad Farhan Dzakki";
        String NPM = "G1A023041";
        System.out.println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
        System.out.println("NAMA :" + name);
        System.out.println("NPM :" + NPM);
        System.out.println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");

sama seperti nomor satu code diatas digunakan sebagai nama dan npm kita
while,if dan else

        int a = 1;

        while (a <= 20) {
            if (a % 2 == 0) {
                System.out.println(a + " Bilangan Genap");
            }else {
                System.out.println(a + " Bilangan Ganjil");
            }

            a++;

masukanlah integer a = 1 (bisa dengan angka apa saja) di sini saya memulai dengan angka 1,kemudian masukkan perulangan while dan atur atau masukkan data batasan,masukkan angka batasan yang kalian inginkan seperti saya menggunkan atau memasukkan angka 20,lalu masukkan if (a % 2 == 0) { lalu enter dan ketik   System.out.println(a + " Bilangan Genap"); kemudian masukkan else dan ketik yang sama dengan if tetapi gantilah "bilangan genap" menjadi "bilangan ganjil" seperti code diatas 

# PENJALANAN PROGRAM NOMOR 2

![Screenshot (317)](https://github.com/dzakki08/tugas-MKU-coding/assets/147239806/de4d278e-87f4-4951-89eb-4900514646ee)


# PENJELASAN NOMOR 3

        String name = "Muhammad Farhan Dzakki";
        String NPM = "G1A023041";
        System.out.println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
        System.out.println("NAMA :" + name);
        System.out.println("NPM :" + NPM);
        System.out.println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");

sama seperti nomor-nomor sebelumnya code diatas digunakan untuk membuat nama dan NPM kita

Scanner untuk melakukan input data

        Scanner zodiak = new Scanner(System.in);
        int tahun ;

        System.out.println("Masukkan tanggal lahir (1-31) :  ");
        int tanggal = zodiak.nextInt();

        System.out.print("masukkan nama bulan (1-12) :  ");
        int bulan = zodiak.nextInt();

code Scanner digunakan untuk menginput data yang nanti akan kita masukkan misalnya seperti diatas, kita dapat memasukkan data tanggal dan bulan,jika kita ingin memasukkan data 2 ke dalam terminal dan nanti akan dibaca oleh program

menambahkan data tanggal,bulan dan zodiak

        System.out.println();
        if ((tanggal >= 21 && bulan == 3) || (tanggal <= 19 && bulan == 4)){
            System.out.println("zodiak anda : Aries");
        }else if((tanggal >= 20 && bulan == 4) || (tanggal <= 20 && bulan == 5)){
            System.out.println("zodiak anda : Taurus");
        }else if((tanggal >= 21 && bulan == 5) || (tanggal<= 20 && bulan == 6)){
            System.out.println("zodiak anda : Gemini");
        }else if((tanggal >= 21 && bulan == 6) || (tanggal <= 22 && bulan == 7)){
            System.out.println("zodiak anda : Cancer");
        }else if((tanggal >= 23 && bulan == 7) || (tanggal <= 22 && bulan == 8)){
            System.out.println("zodiak anda : Leo");
        }else if((tanggal >= 23 && bulan == 8) || (tanggal <= 22 && bulan == 9)){
            System.out.println("zodiak anda : Virgo");
        }else if((tanggal >= 23 && bulan == 9) || (tanggal <= 22 && bulan == 10)){
            System.out.println("zodiak anda : Libra");
        }else if((tanggal >= 23 && bulan == 10) || (tanggal <= 21 && bulan == 11)){
            System.out.println("zodiak anda : Scorpio");
        }else if((tanggal >= 22 && bulan == 11) || (tanggal <= 21 && bulan == 12)){
            System.out.println("zodiak anda : Sagitarius");
        }else if((tanggal >= 22 && bulan == 12) || (tanggal <= 19 && bulan == 1)){
            System.out.println("zodiak anda : Capricorn");
        }else if((tanggal >= 20 && bulan == 1) || (tanggal <= 20 && bulan == 2)){
            System.out.println("zodiak anda : Aquarius");
        }else if((tanggal >= 21 && bulan == 2) || (tanggal <= 20 && bulan == 3)){
            System.out.println("zodiak anda : Pisces");
        }

untuk memasukkan data kita menggunakan perulangan if dan else if,kegunaan if sama seperti code sebelumnya yaitu membuat perbandingan logis antara nilai dan apa yang diharapkan dengan menguji kondisi dan mengembalikan hasil jika true atau fale ,lalu else if memiliki fungsi yang sama seperti pernyataan if dan diletakan setelah pernyataan if. else adalah pilihan terakhir yang akan dijalankan jika semua pilihan tidak memiliki nilai benar (true) pada kondisi yang ada.

# PENJALANAN PROGRAM 3

![image](https://github.com/dzakki08/tugas-MKU-coding/assets/147239806/de07af3e-54d4-4fc5-b790-03b7e8e9fba9)

# PENJELASAN NOMOR 4



