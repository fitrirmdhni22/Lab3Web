|                |                    |
| -------------- | ------------------ |
|      _Nama_    | Fitri Ramadhani |
|      _NIM_     |      312410085     |
|     _Kelas_    |      TI.24.A.1      |
|  _Mata Kuliah_ | Pemrograman Web 1 |

### 1. Membuat Ordered List

## Input Program
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat List</h1>
</header>
</body>
</html>

<section id="order-list">
<h2>Ordered List</h2>
<ol>
<li>Pemrograman Web</li>
<li>Sistem Informasi</li>
<li>Basis Data 2</li>
</ol>
</section>
```

## Tampilan Ordered List
<img width="1366" height="768" alt="pemweb1" src="https://github.com/user-attachments/assets/4baf5c1a-04be-4679-aa3e-7d2052c8f9a3" />

### 2. Membuat Unorderd List

## Input Program
```HTML
<section id="unorder-list">
<h2>Unordered List</h2>
<ul type="square">
<li>Jaringan Komputer</li>
<li>Struktur Data</li>
<li>Algoritma &amp; Pemrograman</li>
</ul>
</section>
```

## Tampilan Unorderd List
<img width="1366" height="768" alt="pemweb2" src="https://github.com/user-attachments/assets/ebb7fcb9-a1f9-4e6a-8820-30287f1c6914" />

### 3. Membuat Description List

## Input Program
```HTML
<section id="unorder-list">
<h2>Description List</h2>
<dl>
<dt>Fakultas Teknik</dt>
<dd>Teknik Industri</dd>
<dd>Teknik Informatika</dd>
<dd>Teknik Lingkungan</dd>
<dt>Fakultas Ekonomi dan Bisnis</dt>
<dd>Akuntansi</dd>
<dd>Manajemen</dd>
<dd>Bisnis Digital</dd>
</dl>
</section>
```
## Tampilan Description List
<img width="1365" height="219" alt="pemweb3" src="https://github.com/user-attachments/assets/b46f1d72-384b-47c8-a9a3-4b4389abb1a9" />

### 4. Membuat Tabel

## Input Program

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Table</h1>
</header>
</body>
</html>

<table border="1" cellpadding="4" cellspacing="1">
<thead>
<tr>
<th>No.</th>
<th>Fakultas</th>
<th>Program Studi</th>
</tr>
</thead>
<tbody>
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
</tbody>
</table>
```

## Tampilan Membuat Tabel
<img width="1365" height="273" alt="pemweb4" src="https://github.com/user-attachments/assets/682c29a9-6350-45b9-badc-49e76e43854c" />

### Mengatur Margin dan Padding

## Input Program

```HTML
<table border="1" cellpadding="4" cellspacing="0">
```

## Tampilan Penggunaan cellpadding

<img width="1365" height="247" alt="pemweb5" src="https://github.com/user-attachments/assets/dbb0e2f8-bb18-4e43-bae5-38884d1c5974" />

### 5. Menggabungkan Sel Data

## Input Program

```HTML
<table border="1" cellpadding="6" cellspacing="0">
<thead>
<tr>
<th>No.</th>
<th>Fakultas</th>
<th>Program Studi</th>
</tr>
</thead>
<tbody>
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
</tbody>
</table>
```

## Tampilan Penggabungan Sel
<img width="1365" height="266" alt="pemweb6" src="https://github.com/user-attachments/assets/b049a552-c64d-4e39-a84d-0fd50102610e" />

### 6. Membuat Form

## Input Program

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Form</h1>
</header>
</body>
</html>

<form action="proses.php" method="post">
<fieldset>
<legend>Data Pelanggan</legend>
<p>
<label for="nama">Nama</label>
<input type="text" id="nama" name="nama">
</p>
<p>
<label for="alamat">Alamat</label>
<textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
</p>
<p>
<label>Jenis Kelamin</label>
<input id="jk_l" type="radio" name="kelamin" value="L" /><label
for="jk_l">Laki-laki</label>
<input id="jk_p" type="radio" name="kelamin" value="P" /><label
for="jk_p">Perempuan</label>
</p>
<p><input type="submit" value="Login"></p>
</fieldset>
</form>
```

## Tampilan Membuat Form
<img width="1364" height="363" alt="pemweb7" src="https://github.com/user-attachments/assets/6ee59e1c-cf19-49b0-858b-e0a06e2585eb" />

### 7. Menambahkan Style pada Form

## Input Program

```HTML
<style>
form p > label {
display: inline-block;
width: 100px;
}
form input[type="text"], form textarea {
border: 1px solid #197a43;
}
form input[type="submit"] {
border: 1px solid #197a43;
background-color: #197a43;
color: #ffffff;
font-weight: bold;
padding: 5px 15px;
}
</style>
```

## Tampilan Form dengan CSS
<img width="1365" height="399" alt="pemweb8" src="https://github.com/user-attachments/assets/ff929dcb-5311-4975-99d3-f9a0e51e0601" />



Pertanyaan dan Tugas
1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
   
   Jawab:
   ## Input Program
```HTML
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form Dropdown & Listbox Multiple</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fffafc;
      margin: 40px;
    }

    h2 {
      color: #333;
    }

    fieldset {
      width: 350px;
      border: 1px solid #ccc;
      padding: 20px;
      border-radius: 5px;
      background-color: #fff;
    }

    legend {
      font-weight: bold;
      padding: 0 8px;
    }

    label {
      display: block;
      margin-bottom: 6px;
      font-weight: bold;
    }

    select {
      width: 100%;
      padding: 6px;
      margin-bottom: 15px;
      border-radius: 4px;
      border: 1px solid #ccc;
      font-size: 14px;
    }

    button {
      background-color: #2e8b57;
      color: white;
      border: none;
      padding: 8px 15px;
      border-radius: 4px;
      cursor: pointer;
      font-weight: bold;
    }

    button:hover {
      background-color: #256d47;
    }
  </style>
</head>
<body>
  <h1>Form Dropdown & Listbox Multiple</h1>
</header>
</body>
</html>

  <form>
    <fieldset>
      <legend>Formulir Pilihan</legend>

      <label for="jurusan">Pilih Program Studi (Prodi)</label>
      <select id="jurusan" name="jurusan">
        <option value=>Teknik Informatika</option>
        <option value=>Teknik Komputer</option>
        <option value=>Sistem Informasi</option>
        <option value=>Ilmu Komputer</option>
      </select>

      <label for="minat">Fokus Minat</label>
      <select id="minat" name="minat" multiple size="5">
        <option value=>Machine Learning</option>
        <option value=>Kecerdasan Buatan</option>
        <option value=>Data Mining</option>
        <option value=>Internet of Things</option>
        <option value=>Cyber Security</option>
      </select>

      <br>
      <button type="submit">Submit</button>
    </fieldset>
  </form>
</body>
</html>
```

## Output Program
<img width="1365" height="454" alt="image" src="https://github.com/user-attachments/assets/555ff7f7-b65b-46a3-ba79-10b56163fcd7" />
   
