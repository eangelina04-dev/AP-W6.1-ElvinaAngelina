3. Distinguish overridden and inherited methods
What is the output? Why does one method use the subclass version, but the other uses the superclass version?

Outputnya pada line 1 adalah Programmer writes code
Outputnya pada line 2 adalah Employee attend meeting.

<img src="/src/question3/Screenshot 2026-03-09 141920.png">
Variabel e melakukan inisialisasi objek Programmer yang memiliki sifat Programmer, kemudian melakukan 2 metode, metode work() dan metode attendMeeting()

<img src="/src/question3/Screenshot 2026-03-09 143934.png">
Metode work() ada di Employee, tetapi didefinisikan ulang di Programmer dengan override. Variabel e merujuk ke programmer sehingga outputnya yang sudah di override yaitu Programmer Writes Code. Jadi metode disini menggunakan subclass version.

Metode attendMeeting() hanya ada di superclass Employee dan tidak di override sehingga outputnya tetap Employee attends meeting. Jadi metode disini menggunakan superclass version.