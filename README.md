<table>
  <tr>
    <th colspan="2">DATA MAHASISWA</th>
  </tr>
  <tr>
    <td>Nama</td>
    <td>Muhammad Arifin</td>
  </tr>
  <tr>
    <td>NIM</td>
    <td>312210330</td>
  </tr>
  <tr>
    <td>Kelas</td>
    <td>TI.22.A3</td>
  </tr>
</table>

# <p align="center">Praktikum5 : Javascript</p>

### Langkah-langkah praktikum

- Persiapan membuat dokumen HTML dengan nama file <b>lab5_javascript.html</b> seperti berikut.

      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>mengenal javascript</title>
      </head>
      <body>
          <h1>Pengenalan javascript</h1>
          <h3>Contoh javascript document.write</h3>
          <script>
              document.write("Hello World");
              console.log("Hello world");
          </script>
      </body>
      </html>

- Contoh ```document.write``` dan ```console.log```

```document.write``` adalah sintak javascript yang berfungsi untuk menampilkan teks pada browser. Kemudian ```console.log``` adalah untuk menampilkan teks pada console web browser. Untuk melihat console harus melalui inspect element.
- Kemudian hasilnya adalah
<img width="960" alt="Screenshot 2023-10-28 213053" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/d8b11bac-ff14-472d-bf10-aa28c762cec0">

## Melakukan validasi dokumen html ```lab5_javascript.html``` dengan mengakses https://validator.w3.org

<img width="960" alt="Screenshot 2023-10-28 213441" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/0370cf9d-ac68-4afb-9bcc-7570defda59e">

## Javascript Dasar

- Pemakaian Alert sebagai property window.

Membuat alert box dengan menggunakan ```window.alert```. ```window.alert``` akan memunculkan popup alert pada web browser ketika halaman tersebut di akses.

    <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>alert box</title>
      </head>
      <body>
          <script language = "JavaScript">
              window.alert(
                  "ini merupakan pesan untuk anda"
              );
          </script>
      </body>
      </html>
      
- Kemudian hasilnya adalah
<img width="960" alt="Screenshot 2023-10-28 214130" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/e9754512-4ec6-4d6c-811c-5865e34ea769">

- Pemakaian method dalam objek

```document.write``` akan menampilkan teks pada browser.

      <html>
          <head>
              <title>skrip javascript</title>
          </head>
          <body>
              percobaan pemakaian javascript
              <script language = "javascript">
                  <!--
                  document.write("selamat mencoba java<br>");
                  document.write("semoga sukses!")
                  -->
              </script>
          </body>
      </html>

  - Kemudian hasilnya adalah
<img width="960" alt="Screenshot 2023-10-28 214802" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/ff1bf859-0b61-4f6a-a9af-d812a1a90371">

- Pemakaian Prompt

      <html>
          <head>
              <title>pemasukan data</title>
          </head>
          <body>
              <script language = "javascript">
                  <!--
                  var nama = prompt("siapa nama anda?","masukan nama anda");
                  document.write("hai, " + nama);
                  -->
              </script>
          </body>
      </html>

- Kemudian hasilnya adalah
<img width="960" alt="Screenshot 2023-10-28 215053" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/9f3b339a-7fee-4a13-b457-e11ec26315b8">
<img width="960" alt="Screenshot 2023-10-28 215106" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/a784241b-ac74-4514-a9ba-e652c425c398">

## Dasar Pemograman di Javascript

- Operasi dasar aritmatika

Operasi dasar aritmatika menggunakan javascript seperti perkalian, penjumlahan, pengurangan, pembagian dan modulus.

  - Kemudian hasilnya adalah

![image](https://github.com/roswanda11/lab5web/assets/115516632/dda2026d-f123-4cb3-88b9-02e90746d7c3)

![image](https://github.com/roswanda11/lab5web/assets/115516632/d68baff3-4709-4d1c-90e1-fd943bbff61a)

- Seleksi kondisi (if.else)

Dengan menggunakan perintah prompt akan muncul pop up form yang harus di isi nilai 1-100. Kemudian jika di Ok akan menjalankan perintah if else. if jika nilai lebih dari sama dengan 60 maka hasi sama dengan lulus. Else berarti hasil tidak lulus.

    <html>
      	<head>
      		<title>contoh if else</title>
      	</head>
      	<body>
      		<script language = "javascript">
      			<!--
      			var nilai = prompt("nilai (0-100): ",0);
      			var hasil = "";
      			if (nilai >= 60)
      			hasil = "lulus";
      			else
      			hasil = "tidak lulus";
      			document.write("hasil: " + hasil);    
      			//-->
      		</script>
      	</body>
      </html>

  - Kemudian hasilnya adalah
<img width="960" alt="Screenshot 2023-10-28 220218" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/38017cb3-2879-480c-9619-52ca33454397">
<img width="960" alt="Screenshot 2023-10-28 220236" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/bbd7939d-b977-4b6b-b029-7d991329db58">

- Penggunaan operator switch untuk seleksi kondisi

Switch atau beralih. Dengan perintah window.promt akan muncul popup form yang harus di isi nilai 1-5. Kemudian jika di Ok pada halaman website akan memunculkan ejaan dari nilai yang sudah di pilih.

    <html>
      	<head>
      		<title>contoh operator switch</title>
      		<script language = "javascript">
      			function test ()
      			{
      			    val1=window.prompt("input nilai (1-5):")
      			    switch (val1)
      			    {
      			        case "1" :
      			            document.write("bilangan satu")
      			            break
      			        case "2" :
      			            document.write("bilangan dua")
      			            break
      			        case "3" :
      			            document.write("bilangan tiga")
      			            break
      			        case "4" :
      			            document.write("bilangan empat")
      			            break
      			            case "5" :
      			            document.write("bilangan lima")
      			            break
      			        default :
      			            document.write("bilangan lainnya")
      			            break
      			    }
      			}
      			
      		</script>
      	</head>
      	<body>
      		<input type="button" name="button1" value="switch" onclick=test()>
      	</body>
      </html>

  - Kemudian hasilnya adalah
<img width="960" alt="Screenshot 2023-10-28 221320" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/27b9862e-ce9c-4327-99f0-e09d0c16ed86">
<img width="960" alt="Screenshot 2023-10-28 221327" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/3a695294-5417-409f-9463-1835724a41bd">

## Pembuatan Form

- Form Input

Form input BIL di isi dengan angka bebas, kemudian pada form MERUPAKAN BIL akan muncul angka tersebut ganjil atau genap setelah di klik tombol TEBAK. Form tersebut bisa menebak ganjil atau genap menggunakan fungsi if else.

    <html>
      	<body>
      		<script language = "javascript">
      			function test() {
      			    var val1=document.kirim.T1.value
      			    if (val1%2==0)
      			    document.kirim.T2.value="bilangan genap"
      			    else
      			    document.kirim.T2.value="bilangan ganjil"
      			}
      			
      		</script>
      	</body>
      	<form method="POST" name="kirim">
      		<p>BIL <input type="text" name="T1" size="20">
      			MERUPAKAN BIL <input type="text" name="T2" size="20">
      		</p>
      		<p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
      	</form>
      </html>

  - Kemudian hasilnya adalah
<img width="960" alt="Screenshot 2023-10-28 221827" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/2629d186-38c4-4d6b-a2d3-a763438d4872">

- Form Button

Dengan perintah untuk merubah background dan warna teks. Jika tombol tersebut diklik maka akan merubah background atau warna teks sesuai dengan yang sudah di setting pada javascript.

      <html>
      	<head>
      		<title>objek document</title>
      	</head>
      	<body>
      		<script language= "javascript">
      			<!--
      			    function ubahWarnaLB(warna) {
      			        document.bgColor = warna;
      			    }
      			    function ubahWarnaLD(warna) {
      			        document.fgColor = warna;
      			    }
      			-->
      		</script>
      	</body>
      	<h1>Test</h1>
      	<form>
      		<input type="button" value="Latar belakang oren" onclick="ubahWarnaLB('ORANGE')">
      		<input type="button" value="Latar belakang putih" onclick="ubahWarnaLB('WHITE')">
      		<input type="button" value="Teks kuning" onclick="ubahWarnaLD('YELLOW')">
      		<input type="button" value="Teks hijau" onclick="ubahWarnaLD('GREEN')">
      	</form>
      	<script language = 'javascript'>
      		<!--
      		document.write("Dimodifikasi terakhir pada " +
      		document.lastModified);
      		//-->

  - Kemudian hasilnya adalah
<img width="960" alt="Screenshot 2023-10-28 222438" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/54926fcc-ae68-4416-bd44-27ec965b6868">

## HTML DOM

- Pemilihan menggunakan CheckBox dengan perhitungan otomatis

Membuat form checkbox dan pada saat chechbox tersebut di centang maka nilai yang ada di checkbox tersebut akan langsung terhitung otomatis pada kolom total bayar.

      <html>
      	<head>
      		<title>Daftar Menu</title>
      		<script language = "javascript">
      			function hitung(ele) {
      			    var total = document.getElementById('total').value;
      			    total = (total ? parseInt(total) : 0);
      			    var harga = 0;
      			
      			if (ele.checked) {
      			    harga = ele.value;
      			    total += parseInt(harga);
      			} else {
      			    harga = ele.value;
      			    if (total > 0)
      			    total -= parseInt(harga);
      			}
      			document.getElementById('total').value = total;
      			}
      		</script>
      	</head>
      	<body>
      		<h1>Daftar Menu Makanan</h1>
      		<label><input type="checkbox" value="25000" id="menu1" onclick="hitung(this);"> Ayam Sambal Matah Rp. 25.000</label><br />
      		<label><input type="checkbox" value="3000" id="menu2" onclick="hitung(this);"> Tempe Mendoan Rp. 3.000</label><br />
      		<label><input type="checkbox" value="2000" id="menu3" onclick="hitung(this);"> Tahu Goreng Rp. 2.000</label><br />
              <label><input type="checkbox" value="20000" id="menu3" onclick="hitung(this);"> Ikan Gurame Bakar Rp. 20.000</label><br />
              <label><input type="checkbox" value="7000" id="menu3" onclick="hitung(this);"> Tongseng Kangkung Rp. 7.000</label><br />
              <h2>Daftar Menu Minuman</h2>
              <label><input type="checkbox" value="3000" id="menu1" onclick="hitung(this);"> Es Teh Manis Rp. 3.000</label><br />
      		<label><input type="checkbox" value="5000" id="menu2" onclick="hitung(this);"> Es Jeruk Rp. 5.000</label><br />
      		<label><input type="checkbox" value="10000" id="menu3" onclick="hitung(this);"> Jus Alpukat Rp. 10.000</label><br />
              <label><input type="checkbox" value="12000" id="menu3" onclick="hitung(this);"> Es Campur Rp. 12.000</label><br />
              <label><input type="checkbox" value="1000" id="menu3" onclick="hitung(this);"> Teh Tawar Rp. 1.000</label><br />
      		<strong>Total Bayar: Rp. <input id="total" type="text"></strong>       
      	</body>

  - Kemudian hasilnya adalah
<img width="960" alt="Screenshot 2023-10-28 223202" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/063fc080-caff-4749-bac3-97c6d69929eb">

# Pertanyaan dan Tugas

1. Buat script untuk melakukan validasi pada isian form.

Jika form tidak di isi dengan lengkap maka akan muncul pop up warning. untuk memunculkan popup tersebut menggunakan fungsi if else. if jika semua form sudah ada nilainya atau di isi maka bernilai true atau bisa di lanjutkan.

      <!DOCTYPE html>
      <html>
      	<head>
      		<title>Form Validasi JavaScript</title>
              <script type="text/javascript">
                  function validasi() {
                      var nama = document.getElementById("nama").value;
                      var email = document.getElementById("email").value;
                      var alamat = document.getElementById("alamat").value;
                      if (nama != "" && email!="" && alamat !="") {
                          return true;
                      }else{
                          alert('isi form pendaftaran dengan lengkap!');
                      }
                  }
              </script>
      	</head>
      	<body>
              <h1>Form Pendaftaran</h1>
      			<form action="#" method="POST" onSubmit="validasi()">
      				<div>
      					<label>Nama Lengkap:</label>
      					<input type="text" name="nama" id="nama" />
      				</div>
      				<div>
      					<label>Email:</label>
      					<input type="email" name="email" id="email" />
      				</div>
      				<div>
      					<label>Alamat:</label>
      					<textarea cols="40" rows="5" name="alamat" id="alamat"></textarea>
      				</div>
      				<div>
      					<input type="submit" value="Daftar" class="tombol">
      				</div>
      			</form>
      	</body>
      </html>

  - Kemudian hasilnya adalah
<img width="960" alt="Screenshot 2023-10-28 223635" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/6957dbb5-3046-4f77-8220-eae670309f1e">
<img width="960" alt="Screenshot 2023-10-28 223907" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/2ceea313-f69d-4d7c-918a-64ebb4cc9d5b">

Sedangkan else jika form nya belum di isi semua maka akan memunculkan alert.

  - Kemudian hasilnya adalah
<img width="960" alt="Screenshot 2023-10-28 223918" src="https://github.com/marifinnnnn/Lab5Web/assets/115518274/682cbf38-2791-43e3-a095-fbfe90149fe3">
