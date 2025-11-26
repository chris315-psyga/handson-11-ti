Nama : Chris Maruli Siagian
NIM : 2481004
Mata Kuliah: Pemrograman Berorientasi Objek

[Tulis 3-5 poin pembelajaran penting yang Anda dapatkan dari handson ini]
1. Jangan memaksakan sebuah class untuk mengimplementasikan method yang tidak ia butuhkan. Interface yang terlalu besar atau bisa dibilang fat interface akan menyebabkan class tersebut memiliki method kosong yang hanya melempar UnsupportedOperationException.
2. Alangkah lebih baik kalau memecah interface besar menjadi beberapa interface kecil yang lebih spesifik. Setiap class kemudian dapat mengimplementasikan interface-interface kecil yang sesuai dengan kemampuan yang benar-benar dimilikinya.
3. Modul tingkat tinggi tidak boleh bergantung pada detail implementasi dari modul tingkat rendah. Seharusnya kedua modul tersebut harus bergantung pada sebuah abstraksi, contohnya seperti interface.
4. Kemudian dependensi tidak boleh dibuat di dalam kelas yang membutuhkannya, melainkan harus diberikan dari luar. Proses ini disebut sebagai dependency injection yang akan membuat kelas menjadi lebih fleksibel dan mudah untuk diuji.