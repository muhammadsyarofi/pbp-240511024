# Refleksi Diri

Sebagai mahasiswa dengan konsentrasi Data Science, platform yang paling menarik bagi saya untuk dipelajari adalah Web. Alasannya, platform Web (terutama melalui framework seperti Streamlit, Dash, atau Shiny) saat ini menjadi jembatan utama untuk men-deploy model machine learning atau memvisualisasikan hasil analisis data agar dapat diakses dengan mudah oleh pengguna awam melalui browser. Karakteristik web yang cross-platform dan tidak memerlukan instalasi memudahkan kolaborasi antar stakeholder dalam melihat dashboard data secara real-time.

Meskipun begitu, platform Desktop juga memiliki peran krusial di bidang Data Science. Komputasi berat, pemrosesan dataset berukuran raksasa (Big Data), dan pelatihan model deep learning biasanya lebih optimal dilakukan menggunakan aplikasi Desktop (seperti Jupyter Notebook lokal, RStudio, atau software pengolah data lainnya) karena akses penuh ke hardware (RAM dan GPU).

Tantangan terbesar saat menyiapkan environment tugas ini adalah konfigurasi variabel lingkungan (Environment Variables) untuk Java JDK dan error kebijakan eksekusi script pada PowerShell. Saat menjalankan java -version, CMD tidak mengenalinya karena JAVA_HOME belum diatur. Selain itu, muncul SecurityError saat menjalankan npm karena Windows membatasi eksekusi file .ps1.

Rencana saya ke depannya adalah membiasakan diri membaca pesan error dengan teliti dan mencari solusinya di dokumentasi resmi. Saya belajar bahwa masalah tersebut dapat diatasi dengan menambahkan %JAVA_HOME%\bin ke Path dan mengubah Execution Policy PowerShell. Ke depannya, saya akan mendokumentasikan setiap langkah setup environment dan menggunakan virtual environment agar proses pengembangan Data Science saya berjalan lebih lancar dan bebas konflik.
