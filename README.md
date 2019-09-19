# Install Flutter
Nama : Leo Bimo Aryaputranto <br>
NIM  : 20175520010 <br>
Prodi: Teknik Informatika 2017<br>

# Langkah mudah menginstall Flutter pada Komputer spesifikasi ringan
- Download SDK Flutter.<br>
  Silahkan kunjungi laman download Flutter. Sesuaikan dengan sistem operasi teman-teman. Untuk Windows silahkan download <a href="https://flutter.dev/docs/get-started/install/windows"> disini </a> dan untuk MacOs <a href="https://flutter.dev/docs/get-started/install/macos"> disini </a>, karena saya menggunakan sistem operasi Windows maka saya akan memberikan tutorial menggunakan windows.<br>
  Akan keluar laman seperti ini:<br>
  <img src = "image.png">
  
-Download Command Tools Only:
 Silahkan kunjungi laman download <a href=" https://developer.android.com/studio/#command-tools ">disini</a>.
 Akan keluar laman seperti ini:<br>
    <img src = "Capture2.PNG">
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
 Akan muncul laman seperti ini:<br>
 <img src = "Capture3.PNG">
 
-Buka terminal (Command Prompt) di C:/Android/tools/bin lalu ketikan beberapa perintah berikut. Diperlukan akses internet untuk melakukan ini. <br> 
 <code> sdkmanager “system-images;android-28;default;x86_64” </code> <br> 
 <code> sdkmanager “platform-tools” </code><br>
 <code> sdkmanager “build-tools;28.0.3” .</code><br>
 <code> sdkmanager “platforms;android-28” </code><br>
 Setelah semua code diatas selesai, akan muncul seperti ini.<br>
 <img src = "Capture4.PNG"> <br>
 <img src = "Capture5.PNG"> <br>
 
 Selanjutnya install Visual Studio Code dan ekstension flutter serta dart nya.<br>
 <img src = "Capture6.PNG"><br>

 Step terakhir adalah buat project di VsCode dengan klik F1 dan mengetikan Flutter: New Project setelah project selesai di load, klik F5   untuk mendeploy ke android device teman-teman.
                                                    

