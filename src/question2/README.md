2. Identify which class method is called What is the output of the program? Why are the two lines different?

<img src="/src/question2/Screenshot 2026-03-09 134414.png">

Variabel v1 merujuk ke objek Vehicle.
Variabel v2 merujuk ke objek Car yang mewarisi sifat Vehicle.

<img src="/src/question2/Screenshot 2026-03-09 134735.png">
Ketika ditulis v1.move berarti memanggil metode move milik v1  dari class super yaitu class Vehicle.
Ketika ditulis v2.move berarti memanggil metode move milik v2  dari class sub yaitu class Car.

<img src="/src/question2/Screenshot 2026-03-09 135759.png">
Makanya outputnya pada line 1 adalah Vehicle is moving karena isi dari metode move class Vehicle.
Makanya outputnya pada line 2 adalah Car is moving karena isi dari metode move milik class Car yang diwarisi dari class Vehicle sudah dioverride isinya.

Dua line nya berbeda karena kedua metode move merujuk ke dua objek berbeda.