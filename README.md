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
  </summary><table><i>25</br>
Academy DQLab</i></table></details>

<details> <summary><b>Melakukan Comment Pada Python</b></br>print(10*2+5) #fungsi matematika</br>
print("Academy DQLab") #fungsi mencetak kalimat
</summary><table><i>25</br>
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
</summary><table><img src="https://github.com/yenysyafitry/Python-Fundamental-for-Data-Science//blob/main/Screenshot_1.jpg"></table></details>
Pada praktek kali ini akan dibagi menjadi 3 bagian :<ol align="justify"><li>Menggunakan IF yang jika direpresentasikan dengan kata – kata, (Jika, sesuatu memenuhi suatu kondisi, maka lakukan A, jika tidak, tidak terjadi apa-apa)</li>
<li>Menggunakan IF dan ELSE yang jika direpresentasikan dengan kata – kata, (Jika, sesuatu memenuhi suatu kondisi, maka lakukan A, jika tidak, lakukan B </li>
<li>Menggunakan IF, ELIF dan ELSE. ELIF sendiri sebenarnya sama persis dengan ELSE IF. Namun, pada python disingkat menjadi ELSE IF. (Jika, sesuatu memenuhi suatu kondisi, maka lakukan A, jika tidak, lakukan pengecekan pada kondisi berikutnya, jika memenuhi lakukan B, jika tidak maka lakukan C)</li></ol>

<details> <summary><b>IF Statement</b></br>i = 7 #inisialisasi variable i yang memiliki nilai 10</br>
if(i==10): #pengecekan nilai i apakah sama dengan 10</br>
    print("ini adalah angka 10") #jika TRUE maka akan mencetak kalimat ini	
</summary><table><i>Karena nilai 7 tidak memenuhi syarat kondisi dalam IF. Karena tidak ada kelanjutan perintah maka program dihentikan dan tidak mengeluarkan hasil apapun.</i></table></details>

<details> <summary><b>IF … ELSE …</b></br>i = 5 #inisialisasi variable i yang memiliki nilai 10</br>
if(i==10): #pengecekan nilai i apakah sama dengan 10</br>
    print("ini adalah angka 10") #jika TRUE maka akan mencetak kalimat ini</br>
else:</br>
    print("bukan angka 10") #jika FALSE akan mencetak kalimat ini
</summary><table align="justify"><i>bukan angka 10 </i> </br>Penjelasan: Nilai variable adalah 5. Pada kondisi pertama variable i tidak memenuhi. Maka dari output yang diberikan adalah perintah pada else yang merupakan hasil apabila pengecekan pertama tidak sesuai.</table></details>

<details> <summary><b></br>
</summary><table><img src="https://github.com/yenysyafitry/Advanced-Data-Visualization-with-ggplot2-using-R/blob/main/Screenshot_1.jpg"></table></details>
<details> <summary><b></br>
</summary><table><img src="https://github.com/yenysyafitry/Advanced-Data-Visualization-with-ggplot2-using-R/blob/main/Screenshot_1.jpg"></table></details>
<details> <summary><b></br>
</summary><table><img src="https://github.com/yenysyafitry/Advanced-Data-Visualization-with-ggplot2-using-R/blob/main/Screenshot_1.jpg"></table></details>
<details> <summary><b></br>
</summary><table><img src="https://github.com/yenysyafitry/Advanced-Data-Visualization-with-ggplot2-using-R/blob/main/Screenshot_1.jpg"></table></details>
<details> <summary><b></br>
</summary><table><img src="https://github.com/yenysyafitry/Advanced-Data-Visualization-with-ggplot2-using-R/blob/main/Screenshot_1.jpg"></table></details>
<details> <summary><b></br>
</summary><table><img src="https://github.com/yenysyafitry/Advanced-Data-Visualization-with-ggplot2-using-R/blob/main/Screenshot_1.jpg"></table></details>
<details> <summary><b></br>
</summary><table><img src="https://github.com/yenysyafitry/Advanced-Data-Visualization-with-ggplot2-using-R/blob/main/Screenshot_1.jpg"></table></details>

