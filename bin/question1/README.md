1. What is the output of this program? Explain why.
Outputnya adalah Meow karena

<img src="/src/question1/Screenshot 2026-03-09 132344.png">

Dalam potongan kode gambar di atas metode sound dari class Animal dioverride (ditimpa) oleh class cat.  Class animal adalah parent class dan class cat adalah anaknya.

<img src="/src/question1/Screenshot 2026-03-09 132950.png">

Variabel a adalah  referensi yang menunjuk ke object cat yang mewarisi sifat Animal.

Makanya ketika ditulis metode a.sound(); 
<img src="/src/question1/Screenshot 2026-03-09 133411.png">
Metode itu menunjuk ke metode sound milik cat sehingga outputnya adalah "Meow" karena isinya sudah di override dalam kelas turunan Animal yaitu kelas cat.