<p align="justify"><b>Python</b> merupakan bahasa pemrograman yag diciptakan pada tahun 1991 oleh Guido van Russom, seorang matematikawan.</br>Python mulai beranjak naik dan populer. Pada beberapa survey terkait bahasa pemrograman yang sering dicari di google, Python berhasil melonjak tajam bahkan mengungguli Java. Bahkan dari insight developer survey dari stackoverflow pada tahun 2018, Python berhasil naik pada TOP 10 programming language yang paling dicari menggungguli seniornya, C, PHP, dan C#. Python merupakan programming language yang memiliki peningkatan pencarian yang sangat tajam dalam setahun terakhir. Python mengklaim dirinya adalah programming language dengan perkembangan tercepat. Selain dari perkembangan library yang semakin kuat, kontributor dari python juga sangat banyak yang akhirnya membuat python menjadi salah satu programming language yang solid dan berkembang pesat.</p>
Python sendiri berguna dalam berbagai aspek :
<ol align="justify"><li>Web Development (Server – Side)</li>
<li>Software Development</li>
<li>Mathematics</li>
<li>Scripting</li>
<li>Data Science</li>
<li>Bisa mengelola Big Data dan Rumus matematika yang complex</li>
<li>Cocok untuk riset dan rapid prototype suatu product dan launch hingga produksi</li>
<li>CRUD sebuah file dan database</li></ol>
<p align="justify"><b>Mengapa Python Populer</b></br>
Selain aspek dari meningkatnya minat masyarakat dunia terhadap data science, ada banyak hal yang membuat Python populer. Python merupakan salah satu programming language yang cocok untuk scripting dan bisa bergerak dalam berbagai platform OS dan IoT. Python sangat mirip English language. Meskipun tergolong sebagai high level programming language, python sangat mudah dimengerti karena syntaxnya yang sederhana. Python bisa bergerak dalam dalam berbagai fungsional programming dan OOP.  Python berjalan pada intepreter system, artinya code yang sudah ditulis bisa dijalankan sesegera mungkin.</p>
Beberapa hal yang mungkin kelebihan dari python:<ol align="justify"><li>Python dirancang untuk mudah dibaca, dan memiliki beberapa kesamaan dengan bahasa Inggris dengan pengaruh dari matematika.</li>
<li>Python menggunakan baris baru untuk mengakhiri perintah, dibandingkan dengan bahasa pemrograman lain yang sering menggunakan titik koma atau tanda kurung.</li>
<li>Python bergantung pada indentasi, menggunakan spasi, untuk mendefinisikan ruang lingkup; seperti lingkup loop, fungsi, dan kelas. Bahasa pemrograman lainnya sering menggunakan kurung kurawal untuk tujuan ini</li>
<li>Jika kalian mencari di internet tentang programming python, biasanya akan ada 2 jenis python, python 2 dan python 3. versi utama Python yang paling baru adalah Python 3, yang akan kami gunakan dalam platform ini. Meskipun begitu, Python 2. Python 2 masih banyak digunakan karena versi python2 ini dianggap sudah stable dan masih bisa digunakan untuk production level. Berbeda dengan python3 yang masih berkembang terus menerus.</li></ol>

<details> <summary><b>Contoh Source coding </b></br>print (10*2+5)</br>
print ("Academy DQLab")
  </summary><table align="justify"><i>Output : </br>25</br>
Academy DQLab</i></table></details>

<details> <summary><b>Melakukan Comment Pada Python</b></br>print(10*2+5) #fungsi matematika</br>
print("Academy DQLab") #fungsi mencetak kalimat
</summary><table align="justify"><i>Output : </br>25</br>
Academy DQLab</i></table></details>

<p align="justify"><b>Variable, Basic Data Type and Print</b></br>Pada sesi kali ini kita akan belajar bagaimana cara inisialisasi variable dalam beberapa data type dan menampilkannya (print)</br><table><tr align="center">
  <td><b>Tipe Data</b></td><td><b>Contoh</b></td><td><b>Penjelasan</b></td></tr>
<tr><td>Boolean</td><td>True atau False</td><td>Menyatakan benar True yang bernilai 1, atau salah False yang bernilai 0</td></tr>
<tr><td>String</td><td>	"Ayo belajar Python"</td><td>Menyatakan karakter/kalimat bisa berupa huruf angka, dll (diapit tanda " atau ')</td></tr>
<tr><td>Integer</td><td>25 atau 1209</td><td>Menyatakan bilangan bulat</td></tr>
<tr><td>Float</td><td>3.14 atau 0.99</td><td>Menyatakan bilangan yang mempunyai koma</td></tr>
<tr><td>List</td><td>		['xyz', 786, 2.23]</td><td>Data untaian yang menyimpan berbagai tipe data dan isinya bisa diubah-ubah</td></tr>
<tr><td>Tuple</td><td>('xyz', 768, 2.23)</td><td>Data untaian yang menyimpan berbagai tipe data tapi isinya tidak bisa diubah</td></tr>
<tr><td>Dictionary</td><td>{'nama': 'adi','id':2}</td><td>Data untaian yang menyimpan berbagai tipe data berupa pasangan penunjuk dan nilai</td></tr>
</table>
<details> <summary><b>Printing Data Type</b></br>var_string="Belajar Python DQLAB"</br>
var_int=10</br>
var_float=3.14</br>
var_list=[1,2,3,4]</br>
var_tuple=("satu","dua","tiga")</br>
var_dict={"nama":"Ali", 'umur':20}</br>
print(var_string)</br>
print(var_int)</br>
print(var_float)</br>
print(var_list)</br>
print(var_tuple)</br>
print(var_dict)	</br>
print(type(var_string))</br>
print(type(var_int))</br>
print(type(var_float))</br>
print(type(var_list))</br>
print(type(var_tuple))</br>
print(type(var_dict))
</summary><table><img src="https://github.com/yenysyafitry/Python-Fundamental-for-Data-Science/blob/main/Screenshot_1.jpg"></table></details>
Pada praktek kali ini akan dibagi menjadi 3 bagian :<ol align="justify"><li>Menggunakan IF yang jika direpresentasikan dengan kata – kata, (Jika, sesuatu memenuhi suatu kondisi, maka lakukan A, jika tidak, tidak terjadi apa-apa)</li>
<li>Menggunakan IF dan ELSE yang jika direpresentasikan dengan kata – kata, (Jika, sesuatu memenuhi suatu kondisi, maka lakukan A, jika tidak, lakukan B </li>
<li>Menggunakan IF, ELIF dan ELSE. ELIF sendiri sebenarnya sama persis dengan ELSE IF. Namun, pada python disingkat menjadi ELSE IF. (Jika, sesuatu memenuhi suatu kondisi, maka lakukan A, jika tidak, lakukan pengecekan pada kondisi berikutnya, jika memenuhi lakukan B, jika tidak maka lakukan C)</li></ol>

<details> <summary><b>IF Statement</b></br><i>i = 7 #inisialisasi variable i yang memiliki nilai 10</br>
if(i==10): #pengecekan nilai i apakah sama dengan 10</br>
    print("ini adalah angka 10") #jika TRUE maka akan mencetak kalimat ini	</i>
</summary><table><i></br>Karena nilai 7 tidak memenuhi syarat kondisi dalam IF. Karena tidak ada kelanjutan perintah maka program dihentikan dan tidak mengeluarkan hasil apapun.</i></table></details>

<details> <summary><b>IF … ELSE …</b></br>i = 5 #inisialisasi variable i yang memiliki nilai 10</br>
if(i==10): #pengecekan nilai i apakah sama dengan 10</br>
    print("ini adalah angka 10") #jika TRUE maka akan mencetak kalimat ini</br>
else:</br>
    print("bukan angka 10") #jika FALSE akan mencetak kalimat ini
</summary><table align="justify"><i>Output : </br>bukan angka 10 </i> </br>Penjelasan: Nilai variable adalah 5. Pada kondisi pertama variable i tidak memenuhi. Maka dari output yang diberikan adalah perintah pada else yang merupakan hasil apabila pengecekan pertama tidak sesuai.</table></details>

<details> <summary><b>IF … ELIF … ELSE ….</b></br>i=5 </br>
if(i==5):</br>
     print("ini adalah angka 5")</br>
elif(i>5):</br>
     print("lebih besar dari 5")</br>
else:</br>
     print("lebih kecil dari 5")
</summary><table align="justify"><i>Output : </br>ini adalah angka 5</i></br>Penjelasan : Nilai variable i tidak memenuhi dari kondisi pertama dimana ditanyakan apakah nilai i sama dengan 5. Lalu masuk pada pengecekan kedua variable i juga tidak memenuhi. Maka dari itu langsung masuk pada perintah ketiga karena kedua pengecekan awal tidak memenuhi.</table></details>

<details> <summary><b>NESTED IF</b></br>i=2
if (i<7):</br>
print("nilai i kurang dari 7")</br>
if (i<3):</br>
print("nilai i kurang dari 7 dan kurang dari 3")</br>
else:</br>
print("nilai i kurang dari 7 tapi lebih dari 3")
</summary><table>Pengecekan bertingkat ini kerap disebut sebagai nested IF.</table></details>

<details> <summary><b>Praktek Operasi Matematika</b></br>a=10
b=5</br>
selisih = a-b</br>
jumlah = a+b</br>
kali = a*b</br>
bagi = a/b</br>
print("Hasil penjumlahan a dan b adalah", jumlah)</br>
print("Selisih a dan b adalah :",selisih)</br>
print("Hasil perkalian a dan b adalah :",kali)</br>
print("Hasil pembagian a dan b adalah:",bagi)				
</summary><table><i>Output : </br>Hasil penjumlahan a dan b adalah 15</br>
Selisih a dan b adalah : 5</br>
Hasil perkalian a dan b adalah : 50</br>
Hasil pembagian a dan b adalah: 2.0</i></table></details>

<details> <summary><b>Operasi modulus</b></br>c=10</br>
d=3</br>
modulus=c%d</br>
print("Hasil modulus",modulus)
</summary><table align="justify"><i>Output : </br>Hasil modulus 1</i></br>Kenapa bisa seperti itu? Prinsip modulus adalah dasarnya sebuah pembagian. Jika pembagi tidak bisa membagi habis angka yang dibagi maka. Fungsi modulus akan membagi hingga mendekati nilai yang dibagi namun tidak melebihi. Selisih dari angka yang mendekati dan angka yang dibagi nanti merupakan hasil modulus. Jika bisa dibagi habis seperti kasus pertama 10/5 maka modulus akan mengembalikan nilai 0.</table></details>

<details> <summary align="justify"><b>Tugas Mid Praktek</b></br>Buatlah sebuah program yang bisa menentukan suatu nilai pada variable itu genap atau ganjil! Lakukan percobaan dengan langkah berikut:</br>
Buat variabel dengan nama “angka” isi dengan nilai 10</br>
Ganti bagian … dengan perhitungan untuk menentukan angka modulus 2 bernilai 0.</br>
Cek apakah benar dia bernilai genap maka keluarkan "angka termasuk bilangan genap", jika sudah ganti nilai variable angka dengan nilai 5 cek lagi apakah dia bernilai ganjil dan keluarkan "angka termasuk bilangan ganjil".
</summary><table align="justify"><i>Output : </br>angka=5</br>
if(angka%2==0):</br>
print("angka termasuk bilangan genap")</br>
else:</br>
print("angka termasuk bilangan ganjil")</i></table></details>

<details> <summary><b>while</b></br>j = 0 #nilai awal j =0</br>
while j<6: #ketika j kurang dari 6 lakukan perulangan, jika tidak stop perulangan</br>
    print("Ini adalah perulangan ke -",j) #lakukan perintah ini ketika perulangan</br>
    j=j+1 #setiap kali diakhir perulangan update nilai dengan ditambah 1.
</summary><table><i>Output :</br>Ini adalah perulangan ke - 0</br>
Ini adalah perulangan ke - 1</br>
Ini adalah perulangan ke - 2</br>
Ini adalah perulangan ke - 3</br>
Ini adalah perulangan ke - 4</br>
Ini adalah perulangan ke - 5></i></table></details>
<details> <summary><b>for (1)</b></br>Maksud dari fungsi ini for i in range (1,6): jika kita konversi pada JAVA atau C sama dengan for(i=1;i<6i++). Jika dikonversi menjadi kalimat adalah “perulangan dimulai dari nilai i = 1 hingga nilai i kurang dari 6 dimana setiap kali perulangan nilai i akan selalu ditambah 1”. Jika nilai i sudah mencapai 6 perulangan akan dihentikan. </br><i>&nbspfor i in range (1,6): #perulangan for sebagai inisialisasi dari angka 1 hingga angka yang lebih kecil daripada 6.</br>
&nbsp &nbsp &nbsp print("Ini adalah perulangan ke -", i) #perintah jika looping akan tetap berjalan</br></i>
</summary><table><i>Output : </br>Ini adalah perulangan ke - 1</br>
Ini adalah perulangan ke - 2</br>
Ini adalah perulangan ke - 3</br>
Ini adalah perulangan ke - 4</br>
Ini adalah perulangan ke - 5</i></table></details>

<details> <summary align="justify"><b>for (2) with access element</b></br>for i in range (1,11):</br>
    if(i%2==0):</br>
        print("Angka genap",i)</br>
    else:</br>
         print("Angka ganjil",i)
</summary><table><i>Output : </br>Angka ganjil 1</br>
Angka genap 2</br>
Angka ganjil 3</br>
Angka genap 4</br>
Angka ganjil 5</br>
Angka genap 6</br>
Angka ganjil 7</br>
Angka genap 8</br>
Angka ganjil 9</br>
Angka genap 10</i></table></details>

<details> <summary align="justify"><b>Membuat fungsi sendiri</b></br>#Membuat Fungsi</br>
def salam():</br>
    print("Hello, Selamat Pagi")</br>
##Pemanggilan Fungsi</br>
salam()	
</summary><table><i>Output :</br>Hello, Selamat Pagi </i></table></details>
<details> <summary align="justify"><b>Parameter pada fungsi</b></br>def luas_segitiga(alas, tinggi): #alas dan tinggi merupakan parameter yang masuk</br>
    luas = (alas * tinggi) / 2</br>
    print("Luas segitiga: %f" % luas);</br>
#Pemanggilan fungsi</br>
##4 dan 6 merupakan parameter yang diinputkan kedalam fungsi luas segitiga</br>
luas_segitiga(4, 6) 	
</summary><table><i>Output :</br>Luas segitiga: 12.000000</i></table></details>

<details> <summary align="justify"><b>Fungsi dengan Return Value</b></br>Fungsi yang tidak mengembalikan nilai biasanya disebut dengan prosedur. Namun, kadang kita butuh hasil proses dari fungsi untuk digunakan pada proses berikutnya. Maka fungsi harus mengembalikan nilai dari hasil pemrosesannya. Cara mengembalikan nilai adalah menggunakan kata kunci return lalu diikuti dengan nilai atau variabel yang akan dikembalikan.</br></br><i>
# Buat fungsi untuk menghitung luas segitiga</br>
#alas dan tinggi merupakan parameter yang masuk</br>
def luas_segitiga(alas, tinggi):</br>
    luas = (alas * tinggi) / 2</br>
    return luas</br>
#pemanggilan fungsi</br>
print("Luas segitiga: %d" % luas_segitiga(4, 6))</i>
</summary><table><i>Output :</br>Luas segitiga: 12</i></table></details>

<details> <summary align="justify"><b>Import Package dan Menggunakan modul</b></br>import math</br>
print("Nilai pi adalah:", math.pi)# math.pi merupakan sintak untuk memanggil fungsi	
</summary><table><i>Output :</br>Nilai pi adalah: 3.141592653589793 </i></table></details>

<details> <summary align="justify"><b>Import dengan Module Rename atau Alias</b></br>import math as m #menggunakan m sebagai module rename atau alias</br>
print("Nilai pi adalah:", m.pi) #m.pi merupakan sintak untuk memanggil fungsi​
</summary><table><i>Output :</br>Nilai pi adalah: 3.141592653589793</i></table></details>

<details> <summary align="justify"><b>Import Sebagian Fungsi</b></br>from math import pi</br>
print("Nilai pi adalah", pi)
</summary><table><i>Output :</br>Nilai pi adalah 3.141592653589793</i></table></details>

<details> <summary align="justify"><b>Import Sebagian Fungsi</b></br>Pada suatu module tidak bisa dipungkiri terdiri dari puluhan bahkan ribuan fungsi. Namun, yang kita butuhkan hanya 1 atau 2 fungsi saja. Untuk meminimalisir ketidakefisienan suatu program dalam load suatu module bisa dilakukan import module namun hanya beberapa fungsi saja yang kita import kedalam code. Format (from module_name import function_name)</br></br>from math import pi</br>
print("Nilai pi adalah", pi)
  </summary><table><i>Output :</br>Nilai pi adalah 3.141592653589793</i></table></details>

<details> <summary align="justify"><b>Import Semua isi Moduls</b></br>Namun, jika memang yang dibutuhkan banyak, semisal lebih dari 10 atau bahkan ratusan fungsi, bisa dilakukan import semuanya dengan menggunakan format from module_name import *. Tanda * disini menunjukan semua fungsi diimport kedalam code.</br></br>from math import *</br>
print("Nilai e adalah:", e)	
</summary><table><i>Output :</br>Nilai e adalah: 2.718281828459045</i></table></details>

<p align="justify"><b>CSV atau comma separated value</b> adalah salah satu tipe file yang digunakan secara luas di dunia programming. Tidak hanya itu CSV pun sering digunakan dalam pengolahan informasi yang dihasilkan spreadsheet untuk diproses lebih lanjut melalui mesin analitik. CSV pun dianggap sebagai file yang agnostik karena dapat digunakan oleh berbagai database untuk proses backup data. CSV dianggap sebagai salah satu tipe data yang sering dipakai untuk mengelola data pada proses lanjutan.</p>

<p align="justify"><b>Membaca Teks File (CSV)</b></br>Sekarang kita akan mencoba membaca sebuah file CSV yang telah dihasilkan aplikasi atau program lain. Di Python, hasil pembacaan setiap baris pada file CSV akan dikonversi menjadi list Python.</br></br>import csv</br>
#tentukan lokasi file, nama file, dan inisialisasi csv</br>
f = open('https://storage.googleapis.com/dqlab-dataset/penduduk_gender_head.csv', 'r')</br>
reader = csv.reader(f)</br>
#membaca baris per baris</br>
for row in reader:</br>
     print (row)</br>
#menutup file csv</br>
f.close()
  </p>

<details> <summary align="justify"><b>Membaca file CSV dengan menggunakan PANDAS</b></br>Bagi yang belum familiar, PANDAS merupakan salah satu library yang sangat sering digunakan untuk aplikasi dan implementasi data science. Baik untuk data manipulation, data pre-processing, atau data wrangling. Pada sesi kali ini, kita akan menggunakan PANDAS untuk membaca file dari csv.</br></br>import pandas as pd</br>
table = pd.read_csv("https://storage.googleapis.com/dqlab-dataset/penduduk_gender_head.csv")</br>
table.head()</br>
print(table)				
  </summary><table><tr><td>No</td><td>TAHUN</td><td>NAMA PROVINSI</td><td>NAMA KABUPATEN</td><td>NAMA KECAMATAN</td></tr>
  <tr><td>0</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>GAMBIR</td></tr>
 <tr><td>1</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>GAMBIR</td></tr>
 <tr><td>2</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>GAMBIR</td></tr>
<tr><td>3</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>GAMBIR</td></tr>
 <tr><td>4</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>GAMBIR</td></tr>
  <tr><td>5</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>GAMBIR</td></tr>
  <tr><td>6</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>SAWAH BESAR</td></tr>
   <tr><td>7</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>SAWAH BESAR</td></tr>
    <tr><td>8</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>SAWAH BESAR</td></tr>
     <tr><td>9</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>SAWAH BESAR</td></tr>
      <tr><td>10</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>SAWAH BESAR</td></tr>
       <tr><td>11</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>KEMAYORAN</td></tr>
       <tr><td>12</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>KEMAYORAN</td></tr>
       <tr><td>13</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>KEMAYORAN</td></tr>
       <tr><td>14</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>KEMAYORAN</td></tr>
       <tr><td>15</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>KEMAYORAN</td></tr>
<tr><td>16</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>KEMAYORAN</td></tr>
<tr><td>17</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>KEMAYORAN</td></tr>
<tr><td>18</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>KEMAYORAN</td></tr>
<tr><td>19</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>SENEN</td></tr>
<tr><td>20</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>SENEN</td></tr>
<tr><td>21</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>SENEN</td></tr>
<tr><td>22</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>SENEN</td></tr>
<tr><td>23</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>SENEN</td></tr>
<tr><td>24</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>SENEN</td></tr>
<tr><td>25</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>CEMPAKA PUTIH</td></tr>
<tr><td>26</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>CEMPAKA PUTIH</td></tr>
<tr><td>27</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>CEMPAKA PUTIH</td></tr>
<tr><td>28</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>MENTENG</td></tr>
<tr><td>29</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>MENTENG</td></tr>
<tr><td>30</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>MENTENG</td></tr>
<tr><td>31</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>MENTENG</td></tr>
<tr><td>32</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>MENTENG</td></tr>
<tr><td>33</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>TANAH ABANG</td></tr>
<tr><td>34</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>TANAH ABANG</td></tr>
<tr><td>35</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>TANAH ABANG</td></tr>
<tr><td>36</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>TANAH ABANG</td></tr>
<tr><td>37</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>TANAH ABANG</td></tr>
<tr><td>38</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>TANAH ABANG</td></tr>
<tr><td>39</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>TANAH ABANG</td></tr>
<tr><td>40</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>JOHAR BARU</td></tr>
<tr><td>41</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>JOHAR BARU</td></tr>
<tr><td>42</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>JOHAR BARU</td></tr>
<tr><td>43</td> <td>2013</td><td>PROVINSI DKI JAKARTA</td><td>JAKARTA PUSAT</td><td>JOHAR BARU</td></tr>
  </table></details>
  
  <p align="justify"><b>Grafik</b> merupakan salah satu perangkat visualisasi. Visualisasi sendiri sudah menjadi salah satu challenge atau poin penting dalam data science. Selain bisa mempermudah seseorang untuk memahami data, bagi para data scientist visualisasi bisa meningkatkan analisa atau memunculkan knowledge yang tidak sempat terekspose ketika tidak menggunakan visualisasi. Pada sesi kali ini, kita akan menggunakan matplotlib untuk melakukan visualisasi data yang sudah ada.</p>
  
  <details> <summary align="justify"><b> Bar Chart</b></br>import pandas as pd</br>
import numpy as np</br>
import matplotlib.pyplot as plt</br>
table = pd.read_csv("https://academy.dqlab.id/dataset/penduduk_gender_head.csv")</br>
table.head()</br>
x_label = table['NAMA KELURAHAN']</br>
plt.bar(x=np.arange(len(x_label)),height=table['LAKI-LAKI WNI'])</br>
plt.show()			</br>
  </summary><table><i>Output :</br> </i><img src="https://github.com/yenysyafitry/Python-Fundamental-for-Data-Science/blob/main/download.png"></table></details></br>

  
  <details> <summary align="justify"><b>Parameter dalam Grafik (Memberikan Nilai Axis dari data CSV)</b></br><i>import pandas as pd</br>
import numpy as np</br>
import matplotlib.pyplot as plt</br>
table = pd.read_csv("https://academy.dqlab.id/dataset/penduduk_gender_head.csv")</br>
table.head()</br>
x_label = table['NAMA KELURAHAN']</br>
plt.bar(x=np.arange(len(x_label)),height=table['LAKI-LAKI WNI'])</br>
plt.xticks(np.arange(len(x_label)), table['NAMA KELURAHAN'], rotation=30)</br>
plt.show()				</i>
  </summary><table><i>Output :</br> </i> <img src="https://github.com/yenysyafitry/Python-Fundamental-for-Data-Science/blob/main/download (1).png"></table></details>

<details> <summary align="justify"><b>Menambah Title dan Label pada Grafik</b></br>import pandas as pd</br>
import numpy as np</br>
import matplotlib.pyplot as plt</br>
table = pd.read_csv("https://academy.dqlab.id/dataset/penduduk_gender_head.csv")</br>
table.head()</br>
x_label = table['NAMA KELURAHAN']</br>
plt.bar(x=np.arange(len(x_label)),height=table['LAKI-LAKI WNI'])</br>
plt.xticks(np.arange(len(x_label)), table['NAMA KELURAHAN'], rotation=90)</br>
plt.xlabel('Keluarahan di Jakarta pusat')</br>
plt.ylabel('Jumlah Penduduk Laki - Laki')</br>
plt.title('Persebaran Jumlah Penduduk Laki- Laki di Jakarta Pusat')</br>
plt.show()	
  </summary><table><i>Output :</br> </i><img src="https://github.com/yenysyafitry/Python-Fundamental-for-Data-Science/blob/main/download (2).png"></table></details>
  
  </br>
  </br>
  <p align="center"><b>E-Sertifikat </b></br><img src="https://github.com/yenysyafitry/Python-Fundamental-for-Data-Science/blob/main/e-sertifikat.jpg"></p>



