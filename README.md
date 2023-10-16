Membuat file nama dengan nama lab3_list.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Membuat List</title>
</head>
<body>
    <header>
        <h1> Membuat List </h1>
    </header>
    
</body>
</html>
```
<h3>Membuat Order List </h3>

Tambahkan kode ordered list
```html
<section id="order-list">
      <h2>Ordered List</h2>
      <ol>
        <li>Pemograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data</li>
      </ol>
</section> 
```
<section id="order-list">
      <h2>Ordered List</h2>
      <ol>
        <li>Pemograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data</li>
      </ol>
</section> 

![image](https://github.com/twn304/Lab3Web./assets/115573041/aa4b6557-9df4-4bb2-89ad-e7098bea2ce8)


<h3>Membuat Unoreder List</h3>

Lalu menambahkan kode unorder list 
```html
<section id="unorder-list">
      <h2>Unordered List</h2>
      <ul type="circle">
        <li>Struktur Data</li>
        <li>Algoritma &amp; Pemograman</li>
        <li>Jaringan Komputer</li>
      </ul>
</section>

<section id="unorder-list">
      <h2>Unordered List</h2>
      <ul type="circle">
        <li>Struktur Data</li>
        <li>Algoritma &amp; Pemograman</li>
        <li>Jaringan Komputer</li>
      </ul>
</section>

```

![image-1](https://github.com/twn304/Lab3Web./assets/115573041/fefdc806-205d-4c96-8709-244b645a8a76)

<h2> Membuat Desription List</h2>

Tambah kode Description List 
```html
<section id="desc-list">
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
<section id="desc-list">
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

![image-2](https://github.com/twn304/Lab3Web./assets/115573041/12e86fe8-399b-45da-bd4f-d3d81d981a47)


<h2>Membuat Table</h2>

Membuat file baru dengan nama lab3_table.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Praktikum 3</title>
</head>
<body>
  <header>
    <h1>Membuat Tabel</h1>
  </header>
</body>
</html>
```

Tambah kode untuk membuat table

```html 
<table border="1">
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
<table border="1">
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

![image-3](https://github.com/twn304/Lab3Web./assets/115573041/d41b2974-3e1f-4c76-a253-ea7c66dffbf6)


<h3> Membuat Margin dan Padding </h3>
Menambahkan Margin dan Padding, tambahkan atribut Margin dan Padding pada tag table

```html
<table border="1" cellpadding="4" cellspacing="0">
```

![image-4](https://github.com/twn304/Lab3Web./assets/115573041/de6ad885-4ebc-47cd-baf4-3538320cc828)

<h3> Menggabungkan Cell </h3>

```html
<table border="1" cellpadding="4" cellspacing="0">
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
</table
```

<table border="1" cellpadding="4" cellspacing="0">
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
</table

![image-5](https://github.com/twn304/Lab3Web./assets/115573041/c364d867-429b-4ad5-a12d-0c7feac2e8d8)

<h3> Membuat Form </h3>
Membuat file baru dengan nama lab3_form.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <header>
         <h1> Membuat Form </h1>
    </header>
</body>
</html>
```
<h3> Tambahkan kode untuk membuat form </h3> 

```html
<form action="proses.php" method="post">
    <fieldset>
      <legend>Data Pelanggan</legend>
      <p>
        <label for="nama">Nama</label>
        <input type="text" name="nama" id="nama" />
      </p>
      <p>
        <label for="alamat">Alamat</label>
        <textarea name="alamat" id="alamat" cols="20" rows="3"></textarea>
      </p>
      <p>
        <label>Jeniss Kelamin</label>
        <input type="radio" name="kelamin" id="jk_l" value="L" /><label for="jk_l">Laki-Laki</label>
        <input type="radio" name="kelamin" id="jk_p" value="P" /><label for="jk_p">Perempuan</label>
      </p>
      <p>
        <input type="submit" value="Login" />
      </p>
    </fieldset>
  </form>
</body>
```
<h1> Membuat Form </h1>


<style>
    form p>label {
      display: inline-block;
      width: 100px;
    }

    form input[type="text"],
    form textarea {
      border: 2px solid #197a43;
    }

    form input[type="submit"] {
      border: 1px solid #197a43;
      background-color: #197a43;
      color: #fff;
      font-weight: bold;
      padding: 5px 15px;
    }
</style>
<form action="proses.php" method="post">
    <fieldset>
      <legend>Data Pelanggan</legend>
      <p>
        <label for="nama">Nama</label>
        <input type="text" name="nama" id="nama" />
      </p>
      <p>
        <label for="alamat">Alamat</label>
        <textarea name="alamat" id="alamat" cols="20" rows="3"></textarea>
      </p>
      <p>
        <label>Jeniss Kelamin</label>
        <input type="radio" name="kelamin" id="jk_l" value="L" /><label for="jk_l">Laki-Laki</label>
        <input type="radio" name="kelamin" id="jk_p" value="P" /><label for="jk_p">Perempuan</label>
      </p>
      <p>
        <input type="submit" value="Login" />
      </p>
    </fieldset>
  </form>
</body>


![image-6](https://github.com/twn304/Lab3Web./assets/115573041/275047af-16cb-4215-b6c1-6bde62f0da80)

