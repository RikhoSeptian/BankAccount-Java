Membuatlah program Java yang mensimulasikan sistem ATM sederhana dengan mengimplementasikan Materi yang telah Anda pelajari. Program terdiri dari dua class:
  BankAccount dan ATMSimulator.
  Class BankAccount memiliki atribut:
    • accountNumber (String)
    • accountHolder (String)
    • balance (double)
    • transactionCount (static int) untuk menghitung total transaksi di semua akun
  Implementasikan:
    1. Constructor dengan parameter accountNumber dan accountHolder yang menginisialisasi balance dengan 0.
    2. Constructor dengan parameter accountNumber, accountHolder, dan initialBalance yang memanggil constructor pertama menggunakan keyword this dan kemudian menetapkan balance dengan nilai initialBalance jika nilainya positif.
    3. Method deposit(double amount) yang menambahkan jumlah ke balance jika positif dan menambah transactionCount.
    4. Method withdraw(double amount) yang mengurangi jumlah dari balance jika dana mencukupi dan menambah transactionCount. Method ini harus mengembalikan true jika berhasil dan false jika gagal.
    5. Static method getTransactionCount() yang mengembalikan jumlah total transaksi.
    6. Method getBalance() yang mengembalikan saldo akun saat ini.
    7. Method printStatement() yang mencetak informasi akun.
  Class ATMSimulator harus memiliki method main yang:
    1. Meminta input dari pengguna untuk nomor akun, nama pemilik, dan saldo awal menggunakan class Scanner
    2. Membuat objek BankAccount dengan data yang dimasukkan
    3. Menampilkan menu untuk:
      1. Deposit
      2. Tarik Tunai
      3. Cek Saldo
      4. Lihat Total Transaksi
      5. Keluar dari program
    4. Mengimplementasikan logika untuk setiap opsi menu dengan input dari pengguna
