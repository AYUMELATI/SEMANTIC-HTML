# SEMANTIC-HTML
Latihan Praktikum Semantic HTML

## Latihan 1: Semantic HTML

### Penjelasan dan Perbedaan dari Code HTML (Code 1: sebelum diperbaiki & Code 2: sesudah diperbaiki)
1. **Tag *html* dan *head***
   - **Code 1** : Tidak memiliki tag *html* dan *head*, sehingga struktur dokumen tidak lengkap. Ini membuat dokumen HTML tidak valid karena tidak sesuai standar HTML.
   - **Code 2** : Menyertakan tag *html* dan *head* yang merupakan bagian penting dari struktur HTML. Ini membuat dokumen lebih terstruktur dan valid.

2. **Tag *body***
   - **Code 1** : Tidak memiliki tag *body*. Konten diletakkan langsung diluar tag *html*.
   - **Code 2** : Menggunakan tag *body* yang merupakan praktik yang benar untuk menempatkan konten utama halaman.
  
3. **Tag *meta* dan *title***
   - **Code 1** : Tidak menyertakan tag *meta* dan *title*, sehingga tidak mendefinisikan metadata seperti charset (pengkodean karakter) atau viewport untuk reponsivitas.
   - **Code 2** : Menyertakan **meta charset="UTF-8"** dan **meta name="viewport"** yang penting untuk kompatibilitas dan tampilan halaman di berbagai perangkat.

4. **Penggunaan CSS Eksternal**
   - **Code 1** : Tidak menyertakan link ke sytlesheet CSS eksternal.
   - **Code 2** : Menyertakan **link rel="stylesheet"href="./assets/styles/styles.css"** untuk menautkan file CSS eksternal yang lebih baik untuk memisahkan gaya dari struktur HTML.
  
5. **Struktur konten**
   - **Code 1** : Menempatkan elemen *header, nav, section,* dan *footer* diluar konteks *html* dan *body*, sehingga tidak sesuai standar.
   - **Code 2** : Menyusun elemen-elemen ini didalam *body*, yang lebih sesuai dengan praktik pengkodean HTML yang benar.
  
### Kesimpulan dari Code HTML
Bahwa Code 1 tidak mengikuti standar HTML seperti tidak adanya tag *html, head,* dan *body*. sedangkan Code 2 lebih terstruktur dengan benar dan sesuai dengan standar HTML.


###  Penjelasan dan Perbedaan dari Code CSS (Code 1: sebelum diperbaiki & Code 2: sesudah diperbaiki)
1. **Urutan dan Struktur Code**
   - **Code 1** : Pada code ini, elemen-elemen seperti nav, header, section, dan footer dideklarasikan terlebih dahulu sebelum aturan untuk body. Ini berarti definisi setiap elemen hadir sebelum pengaturan tata letak (display: grid) diterapkan pada body.
   - **Code 2** : Code ini lebih terstruktur karena bagian body yang mengatur tata letak grid dideklarasikan lebih awal. Setelah itu, elemen seperti header, nav, section, dan footer diatur dengan lebih rapi. Ini dapat membantu dalam pembacaan code dan pemahaman alur.
  
2. **Pencahayaan (Background Color) pada elemen section**
   - **Code 1** : Background untuk section adalah #ABABAB.
   - **Code 2** : Background untuk section adalah #707070 sama dengan elemen header dan footer.
   - **Perbedaan** : Code 1 menggunakan warna yang berbeda untuk elemen section, sedangkan Code 2 menyamakannya dengan elemen lain.
  
3. **Padding**
   - **Code 1** : Deklarasi padding ditempatkan di bagian bawah code.
   - **Code 2** : Deklarasi padding dilakukan lebih awal setelah aturan body.
   - **Keduanya** : Menyediakan padding 5px untuk elemen header, nav, section, dan footer. Namun, deklarasi ini dilakukan ditempat yang berbeda pada kedua code.
  
4. **Konsistensi Deklarasi**
   - **Code 1** : Elemen diatur secara terpisah kemudian pengaturan grid untuk body dilakukan setelah itu.
   - **Code 2** : Memiliki alur yang lebih jelas dimana grid diatur terlebih dahulu di body, lalu elemen-elemen diberi styling berikutnya. Hal ini membuat code lebih mudah dipahami dan diikuti.
  
5. **Penggunaan margin di body**
   - **Code 1** : Menambahkan margin: 10px pada elemen body, yang berarti keseluruhan konten memiliki margin dari tepi halaman.
   - **Code 2** : Tidak menyertakan margin pada elemen body.
  
6. **Kelengkapan dan Kemudahan Pembacaan**
   - **Code 1** : Terlihat lebih berantakan karena tata letak dan styling bercampur, yang bisa membingungkan bagi pengembang lain yang mencoba memahami code.
   - **Code 2** : Lebih mudah dibaca dan di-maintain karena menggunakan pendekatan modular dengan memisahkan tata letak (body) dan styling elemen (nav, header, dll).
  
### Kesimpulan dari Code CSS
Code 1 meskipun fungsional, kurang terorganisir dan bisa membingungkan ketika jumlah elemen bertambah atau jika proyek menjadi lebih kompleks. Sedangkan, Code 2 lebih terstruktur, mudah dibaca, dan menggunakan pendekatan modular yang lebih baik. Menyusun tata letak grid terlebih dahulu sebelum styling elemen memberikan alur logis yang lebih baik.
