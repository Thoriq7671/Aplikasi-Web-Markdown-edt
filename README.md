# Aplikasi-Web-Markdown-edt

## Sekilas Tentang

Ini adalah online markdown editor yang dapat mempermudah anda dalam men-sunting dokumen dengan teknologi web.

## Instalasi

## Kebutuhan sistem :
- Unix, Linux atau Windows.
- Apache Web server 1.3+.

## Proses Instalasi :
1. Login kedalam server menggunakan SSH.
    ```
    $ ssh student@localhost -p 2200
    ```
2. Lakukan kloning pada github yang menjadi refrensi.
    ```
    $ git clone http://github.com/georegeosddev/markdown-edit.git
    ```
3. Kemudian install bower agar tampilannya lebih bagus.
    ```
    $ bower install
    ```
4. Meluncurkannya ke web server.
    ```
    $ ln -s /home/student/markdown-edit /var/www/html/markdown-edit
    $ ls -la
    ```
5. Setelah proses instalasi selesai hapus direktori install untuk alasan keamanan.    
    ``` 
    $ sudo rm -rf /var/www/html/markdown-edit
    ```
6. Setelah semuanya dilakukan, akses http://localhost:8000 untuk melihat hasilnya.



# Pembahasan

**Markdown Edit** Merupakan Editor text berbasis 'github-flavored-markdown' yang bisa dikonversi menjadi 'HTML' yang didasari oleh 'javascript' dan diperkuat oleh 'CodeMirror', Aplikasi ini mmemberikan kemudahan untuk penggunanya dalam hal :
- Aplikasi ini bisa mengedit atau menambahkan text dan di konversi menjadi html
- Aplikasi ini langsung bisa mengganti dan menambahkan text html secara real-time
- tema text editor ini dapat diganti 'theme' agar tidak membosankan
- bisa membuat tabel dengan 2 cara, 
  menggunakan html menjadi :
  
  <table>
   <tr>
    <th>ID</th><th>Name</th><th>Rank</th>
 </tr>
   <tr>
   <td>1</td><td>Tom Preston-Werner</td><td>Awesome</td>
  </tr>
   <tr>
   <td>2</td><td>Albert Einstein</td><td>Nearly as awesome</td>
  </tr>
  </table>
  
   atau manual berbentuk :
  
    ID  |Name|Rank
    --- |----|----
    1   |Tom Preston-Werner |Awesome
    2   |Albert Einstein |Nearly as awesome
   
Tetapi Apllikasi **MarkDown Edit** juga mempunyai kekurangan, yaitu : 
- hanya bisa digunakan ditempat tertentu (seperti github dll)
- Sedikit rumit untuk editor yang belum terbiasa
