# 🌸 Praktikum 3: Membuat List, Table, dan Form

**Nama:** Vivi Alydia  
**NIM:** 312410224  
**Kelas:** TI.24.A2  
**Mata Kuliah:** Pemrograman Web 1  

---


## 🧩 Langkah-Langkah Praktikum

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
![List](./Screenshot%202025-10-06%20130348.png)

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
![Form](./Screenshot%202025-10-06%20132751.png)

---

###  Membuat Dropdown dan Listbox Multiple
Buat file **`lab3_dropdown_listbox.html`** berisi form dengan dropdown dan listbox multiple selection:

```html
<form action="proses.php" method="post">
  <fieldset>
    <legend>Data Pemilihan</legend>

    <p>
      <label for="jurusan">Pilih Jurusan:</label>
      <select id="jurusan" name="jurusan">
        <option value="">-- Pilih Jurusan --</option>
        <option value="ti">Teknik Informatika</option>
        <option value="industri">Teknik Industri</option>
        <option value="ars">Teknik Arsitektur</option>
        <option value="sipil">Teknik Sipil</option>
      </select>
    </p>

    <p>
      <label for="minat">Bidang Minat:</label>
      <select id="minat" name="minat[]" multiple size="5">
        <option value="web">Pemrograman Web</option>
        <option value="ai">Kecerdasan Buatan</option>
        <option value="data">Data Mining</option>
        <option value="iot">Internet of Things</option>
        <option value="cyber">Cyber Security</option>
      </select>
    </p>

    <p><input type="submit" value="Kirim"></p>
  </fieldset>
</form>
```

📸 **Hasil Tampilan Form Dropdown & Listbox:**
![Dropdown](./Screenshot%202025-10-06%20134341.png)

---

###  Membuat Pengisian From *(Kreativitas Tambahan)*
Sebagai pengembangan dari praktikum, dibuat form versi **Pixel Lavender** dengan tema ungu pastel dan font pixel.

📸 **Hasil Akhir Tampilan:**
![Pixel Lavender Form](./314b0eec-8887-4894-842e-409ac5229aa7.png) 

---

