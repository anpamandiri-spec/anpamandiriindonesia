<!-- frontend/transaksi.html -->
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Transaksi Keuangan | PT ANPA MANDIRI INDONESIA</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <h1>📑 Pencatatan Transaksi</h1>

  <form id="formTransaksi">
    <input type="date" id="tanggal" required>
    <select id="jenis">
      <option value="pemasukan">Pemasukan</option>
      <option value="pengeluaran">Pengeluaran</option>
    </select>
    <input type="text" id="kategori_id" placeholder="ID Kategori" required>
    <input type="number" id="jumlah" placeholder="Jumlah" required>
    <textarea id="deskripsi" placeholder="Deskripsi"></textarea>
    <button type="submit">Simpan</button>
  </form>

  <table id="tabelTransaksi">
    <thead>
      <tr>
        <th>Tanggal</th><th>Jenis</th><th>Kategori</th><th>Jumlah</th><th>Deskripsi</th>
      </tr>
    </thead>
    <tbody></tbody>
  </table>

  <script src="js/main.js"></script>
</body>
</html>

