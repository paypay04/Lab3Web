# 🌸 Praktikum 3: Membuat List, Table, dan Form

**Nama:** Vivi Alydia  
**NIM:** 312410224  
**Kelas:** TI.24.A2  
**Mata Kuliah:** Pemrograman Web 1  

---


##  Langkah-Langkah Praktikum

###  Membuat List
Buat file bernama **`lab3_list.html`** dan tambahkan kode HTML berikut:

```html
<section id="order-list">
  <h2>Ordered List</h2>
  <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
  </ol>
</section>

<section id="unorder-list">
  <h2>Unordered List</h2>
  <ul type="square">
    <li>Jaringan Komputer</li>
    <li>Struktur Data</li>
    <li>Algoritma & Pemrograman</li>
  </ul>
</section>

<section id="desc-list">
  <h2>Description List</h2>
  <dl>
    <dt>Fakultas Teknik</dt>
    <dd>Teknik Informatika</dd>
    <dd>Teknik Industri</dd>
    <dd>Teknik Lingkungan</dd>
    <dt>Fakultas Ekonomi dan Bisnis</dt>
    <dd>Akuntansi</dd>
    <dd>Manajemen</dd>
    <dd>Bisnis Digital</dd>
  </dl>
</section>
```

📸 **Hasil Tampilan List:**
![List]<img width="397" height="759" alt="Screenshot 2025-10-06 130348" src="https://github.com/user-attachments/assets/4a208356-4255-4856-b19a-f364dda586f7" />


---

###  Membuat Form Dasar
Buat file **`lab3_form.html`** lalu tambahkan form sederhana seperti berikut:

```html
<form action="proses.php" method="post">
  <fieldset>
    <legend>Data Pelanggan</legend>
    <p>
      <label for="nama">Nama</label>
      <input type="text" id="nama" name="nama">
    </p>
    <p>
      <label for="alamat">Alamat</label>
      <textarea id="alamat" name="alamat" rows="3"></textarea>
    </p>
    <p>
      <label>Jenis Kelamin</label>
      <input type="radio" name="kelamin" value="L">Laki-laki
      <input type="radio" name="kelamin" value="P">Perempuan
    </p>
    <p><input type="submit" value="Login"></p>
  </fieldset>
</form>
```

📸 **Hasil Tampilan Form:**
![Form]<img width="673" height="530" alt="Screenshot 2025-10-06 132452" src="https://github.com/user-attachments/assets/d4e7f086-cd31-418e-857d-348a536c8062" />


---

##  Membuat Tabel

### Langkah-langkah:
1. Buat file `praktik3_table.html`.
2. Tambahkan struktur HTML dasar.
3. Buat tabel pertama menggunakan tag `<table>`, `<tr>`, `<th>`, dan `<td>`.
4. Tambahkan tabel kedua menggunakan `rowspan` untuk menggabungkan sel vertikal.
5. Tambahkan CSS agar tampilan rapi.

### Kode:
```html
<h1>Membuat Table</h1>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th>No.</th>
    <th>Fakultas</th>
    <th>Program Studi</th>
  </tr>
  <tr>
    <td>1.</td>
    <td>Teknik</td>
    <td>Teknik Informatika</td>
  </tr>
  <tr>
    <td>2.</td>
    <td>Teknik</td>
    <td>Teknik Industri</td>
  </tr>
  <tr>
    <td>3.</td>
    <td>Teknik</td>
    <td>Teknik Lingkungan</td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th>No.</th>
    <th>Fakultas</th>
    <th>Program Studi</th>
  </tr>
  <tr>
    <td>1.</td>
    <td rowspan="3">Teknik</td>
    <td>Teknik Informatika</td>
  </tr>
  <tr>
    <td>2.</td>
    <td>Teknik Industri</td>
  </tr>
  <tr>
    <td>3.</td>
    <td>Teknik Lingkungan</td>
  </tr>
</table>

📸 **Hasil Akhir Tampilan:**<img width="755" height="512" alt="Screenshot 2025-10-06 132751" src="https://github.com/user-attachments/assets/76ad6cdf-137e-4179-be62-788fc34082d3" />


---

###  Membuat Pengisian From 
Sebagai pengembangan dari praktikum, dibuat form versi **Pixel** dengan tema ungu pastel dan font pixel.

📸 **Hasil Akhir Tampilan:**
![Pixel Lavender Form]<img width="1918" height="965" alt="Screenshot 2025-10-06 222113" src="https://github.com/user-attachments/assets/9c4b39de-5df7-493f-97f2-e8d0ae821df6" />


---

