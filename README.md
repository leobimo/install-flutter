# Install Flutter
Nama : Leo Bimo Aryaputranto <br>
NIM  : 20175520010 <br>
Prodi: Teknik Informatika 2017<br>

# Langkah mudah menginstall Flutter pada Komputer spesifikasi ringan
- Download SDK Flutter.<br>
  Silahkan kunjungi laman download Flutter. Sesuaikan dengan sistem operasi teman-teman. Untuk Windows silahkan download <a href="https://flutter.dev/docs/get-started/install/windows"> disini </a> dan untuk MacOs <a href="https://flutter.dev/docs/get-started/install/macos"> disini </a>, karena saya menggunakan sistem operasi Windows maka saya akan memberikan tutorial menggunakan windows.<br>
  Akan keluar laman seperti ini:<br>
  
-Download Command Tools Only:
 Silahkan kunjungi laman download <a href=" https://developer.android.com/studio/#command-tools ">disini</a>.
 Akan keluar laman seperti ini:
    
-Ekstrak file tersebut.
 Sebelum di ekstrak buat file di C: dengan nama "Android". Kemudian letakan hasil download Flutter dan Command Line Tools pada folder tersebut. Ekstrak file tersebut dan akan menghasilkan 2 folder yaitu flutter dan tools.
 
-Selanjutnya silahkan download OpenJDK di halaman ini, dan pilih yang berekstensi zip. sesuaikan dengan sistem operasi yang digunakan, saya menggunakan versi jdk8u212-b03 . setelah di download jangan lupa untuk mengekstrak ke folder Android yang sudah kita punya sebelumnya dan rename nama folder dari jdk8u212-b03 menjadi openjdk. totalnya sekarang kita punya 3 folder yaitu flutter, tools dan openjdk.

-Set Enviroment Variable dan Path.
 Buka Command Prompt pada windows dan ketikan Command perbaris.<br>
 <code> setx JAVA_HOME “C:\Android\openjdk” </code><br>
 <code> setx ANDROID_HOME “C:\Android” </code><br>
 <code> setx ANDROID_SDK_ROOT “C:\Android\tools” </code><br>
 <code> setx path “%path%;”C:\Android\sdk;C:\Android\tools\bin;C:\Android\flutter\bin” </code><br>
 Setelah dimasukan command diatas, anda bisa mengecek di Enviroment Variable.<br>
 Akan muncul laman seperti ini:
 
- 



