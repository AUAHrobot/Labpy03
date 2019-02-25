# Labpy03
#labpy03

Latihan1.py

Menampilkan ‘n’ bilangan acak yang lebih kecil dari 0.5 dengan perulangan for

1.Buatlah program python baru, dan beri judul “latihan1” pada pychram

2.masukan program di bawah ini

![latihan 3 bagian a 
atas](https://user-images.githubusercontent.com/46749882/53343111-256c7380-3942-11e9-83a9-86914696dbd0.JPG)


sc program

3.lalu Run program tsb

4.berikut hasilnya

![latihan 3 bagian a 
bawah](https://user-images.githubusercontent.com/46749882/53343173-4fbe3100-3942-11e9-8502-ed78d755d0d4.JPG)


sc all

5.Berikut penjelasan program diatas

•	Import random fungsi ini akan mengembalikan bilangan float random n,dimana 0<n<1.fungsi Random() tidak memiliki parameter masukan

•	n = int(input(“Masukan nilai n: “)) fungsi ini untuk menginput data dalam bentuk bilangan bulat

•	x=0 ,X disini sebagai variabel untuk menampilkan “data ke- “

•	for i in range(n) : , sebagai perintah perulangan data dari variabel (n)

•	x = x+1,suatu perintah untuk memberikan nilai pada variabel x dimana nilai x akan bertambah 1

•	i = random.uniform(0.0,0.5), maksud dari perintah ini i sebagai variabel untuk menampilkan data acak dengan batas awal sebesar 0.0 dan batas akhir 0.5

•	print(“data ke: “,x,”=>”,i) untuk menampilkan “data ke :” dengan nila x & “=>” dengan nilai i

Latihan2.py

Program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan

1.Masukan program di bawah ini

![latihan 3 bagian b 
atas](https://user-images.githubusercontent.com/46749882/53343237-767c6780-3942-11e9-8924-fd3cefdf6c20.JPG)


sc program

2.Run program tersebut

3.Berikut hasilnya

![latihan 3 bagian b 
bawah](https://user-images.githubusercontent.com/46749882/53343280-9a3fad80-3942-11e9-952f-8ba9dc5b6924.JPG)


sc all

4.Berikut penjelasan program tersebut

•	print(“menentukan bilangan terbesar dari n data”),,untuk menampilkan kalimat “menentukan bilangan terbesar dari n data”

•	a = 0,,program untuk memberikan variabel a

•	while true : ,,,adalah salah satu jenis pengulangan,anda dapat membuat kondisi tertentu dengan while. Biasanya digunakan untuk pengulangan tidak pasti

•	n = int(input(“masukan bilangan = “)),,program untuk menginput bilangan pada variabel n

•	if a < n :,,,program yang artinya kondisi a lebih kecil dari n

•	a = n,,,artinya a sama dengan n

•	if a == 0 : break,,artinya,,jika nilai a sama dengan 0 maka program akan berhenti

•	print(“bilangan terbesar= “,a),,untuk menampilkan “bilangan terbesar = “ nilai a

•	print(“selesai”),,untuk menampilkan kalimat penutup “selesai”

Program1.py

Membuat program sederhana dengan perulangan: "program1".py

Diketahui seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan modal awal 100jt,pada bulan pertama belum mendapatkan laba. Pada bulan ke 3 baru mendapat laba sebesar 1% dan pada bulan ke 5 pendapatan meningkat 5%, Selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%, sehingga laba menjadi 3%.

1.Masukan program dibawah ini

![latihan 3 bagian c 
atas](https://user-images.githubusercontent.com/46749882/53343321-b4798b80-3942-11e9-8309-9df078e3637c.JPG)

sc program

2.Run program tersebut

3.dan berikut hasilnya

![latihan 3 bagian c 
bawah](https://user-images.githubusercontent.com/46749882/53343322-b6dbe580-3942-11e9-821d-143a101059a6.JPG)


sc all

4.Berikut penjelasan program tersebut

•	a=100000000,,untuk memberikan variabel pada a,,disini a sebagai modal awal

•	jml_laba=0,,untuk memberikan variabel pada jml_laba,,disini sebagai total laba

•	b=0,,untuk memberikan variabel b,,disini sebagai nilai dar bulan ke –

•	c=(int(0),int(0),int(a) * .1,int(a) * .1,int(a) * .5,int(a) * .5,int(a) * .5,int(a) * .2 ),,program untuk menentukan nilai dari persentase laba dikali modal awal

•	print(“modal pengusaha : “,a),,program untuk menampilkan “modal pengusaha : “ a,,a sebagai modal awal

•	for i in c :,,program perulangan untuk memasukan nilai c kedalam i

•	jml_laba : jml_laba+I,,program untuk menentukan nilai dari total laba

•	b=b+1,,program untuk menentukan nilai dari “bulan ke-“

•	print("laba bulan ke- ",b,"sebesar : ",i),,program untuk menampilkan “laba bulan ke-“ sebesar b

•	print("Total Laba Adalah : ",jml_laba),,program untuk menampilkan “Total Laba Adalah :” sebesar jml_laba
