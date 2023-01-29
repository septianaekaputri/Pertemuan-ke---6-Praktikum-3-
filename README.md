# Nama    : Septiana Eka Putri
# NIM     : 312210705
# Kelas   : TI.22.C.9

# Cara Installasi Pycharm
Anda harus install Pycharm di https://www.jetbrains.com/pycharm/download/#section=windows  , Dan anda pilih yang Community

![2022-10-31 (2)](https://user-images.githubusercontent.com/115775237/198932831-83182560-3117-4469-8e45-924b8cd7887d.png)

next saja semua perintahnya 
<img width="369" alt="2" src="https://user-images.githubusercontent.com/123891182/215353971-3bcbed55-b358-4b80-b453-b386ab9424d6.png">


tunggu hingga selesai

<img width="369" alt="3" src="https://user-images.githubusercontent.com/123891182/215353976-ac34860d-a2dd-4b59-b5c3-32d4791ff376.png">


Jika sudah selesai maka program siap di gunakan

# Cara Menjalankan Pycharm 
# Latihan 1

Pertama-tama anda harus Klik New project lalu kasih nama project anda(sesuai yang anda mau), Dan anda harus pilih yang Previously Configurred interperter lalu klik yang add interperter dan pilih yang System interperter dan anda klik yang versi Python anda seperti gambar di bawah ini


<img width="589" alt="4" src="https://user-images.githubusercontent.com/123891182/215353989-a0fa9b22-5ff7-4cf2-a98f-5ea3c5dc0745.png">

<img width="589" alt="5" src="https://user-images.githubusercontent.com/123891182/215353996-917d170a-e786-427b-a3e9-cf3ba6f35b65.png">

Selanjutnya anda membuat file Python baru di project anda tadi dan anda kasih nama file sesuai yang anda inginkan

<img width="927" alt="6" src="https://user-images.githubusercontent.com/123891182/215354002-9d4845f7-be98-4b7d-8915-7b39d08272e0.png">

masukan code dari latihan1 anda lalu Run

	# penggunaan end

	print('A', end='')
	print('B', end='')
	print('C', end='')
	print()
	print('X')
	print('Y')
	print('Z')

	# penggunaan separator
	w, x, y, z = 10, 15, 20, 25
	print(w, x, y, z)
	print(w, x, y, z, sep=',')
	print(w, x, y, z, sep='')
	print(w, x, y, z, sep=':')
	print(w, x, y, z, sep='-----')

	# string format
	print(0, 10 ** 0)
	print(1, 10 ** 1)
	print(2, 10 ** 2)
	print(3, 10 ** 3)
	print(4, 10 ** 4)
	print(5, 10 ** 5)
	print(6, 10 ** 6)
	print(7, 10 ** 7)
	print(8, 10 ** 8)
	print(9, 10 ** 9)
	print(10, 10 ** 10)

	# string format
	print('{0:>3} {1:>16}'.format(0, 10 ** 0))
	print('{0:>3} {1:>16}'.format(1, 10 ** 1))
	print('{0:>3} {1:>16}'.format(2, 10 ** 2))
	print('{0:>3} {1:>16}'.format(3, 10 ** 3))
	print('{0:>3} {1:>16}'.format(4, 10 ** 4))
	print('{0:>3} {1:>16}'.format(5, 10 ** 5))
	print('{0:>3} {1:>16}'.format(6, 10 ** 6))
	print('{0:>3} {1:>16}'.format(7, 10 ** 7))
	print('{0:>3} {1:>16}'.format(8, 10 ** 8))
	print('{0:>3} {1:>16}'.format(9, 10 ** 9))
	print('{0:>3} {1:>16}'.format(10, 10 ** 10))

<img width="960" alt="1" src="https://user-images.githubusercontent.com/123891182/215354024-66f161ae-d519-4b62-8df6-533240b442a6.png">
<img width="960" alt="2" src="https://user-images.githubusercontent.com/123891182/215354031-8b21d059-8aa4-449c-b6c2-5c5a0b9430bb.png">

lalu hasil run nya


<img width="924" alt="4" src="https://user-images.githubusercontent.com/123891182/215354036-036d8410-e781-4411-972f-380462d640ee.png">
<img width="924" alt="5" src="https://user-images.githubusercontent.com/123891182/215354040-c8286bcf-560e-465c-a43d-212cf51d6e9b.png">

# Latihan 2 
buat latihan baru "latihan2"

lalu masukkan code program

	a=input("masukkan nilai a:")
	b=input("masukkan nilai b:")
	print("variabel a=",a)
	print("variabel b=",b)
	print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))

	#konversi nilai variabel
	a=int(a)
	b=int(b)
	print("hasil penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
	print("hasil penjumlahan {1}/{0}=%s".format(a,b) %(a/b))

<img width="933" alt="1" src="https://user-images.githubusercontent.com/123891182/215354077-3ee9ccb3-62b0-47f7-8bb1-2c559bddfc51.png">

lalu hasil run nya menjadi
<img width="933" alt="3" src="https://user-images.githubusercontent.com/123891182/215354093-ba070d2a-923a-4c06-9d69-d42c3999f264.png">



# Latihan 3
buat file baru "latihan3"
masukkan code programnya

	string = ""

	x = int(input("Masukkan angka :"))
	bar = x
	# Looping Baris
	while bar >= 0:
	# Looping Kolom Spasi Kosong
	kol = bar
	while kol > 0:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri
	kiri = 1
	while kiri < (x - (bar-1)):
		string = string + " * "
		kiri = kiri + 1
	# Looping Kolom Bintang Sisi Kanan
	kanan = 1
	while kanan < kiri -1:
		string = string + " * "
		kanan = kanan + 1

	string = string + "\n\n"
	bar = bar - 1

	bar = 1
	# Looping Baris
	while bar <= x:
	kol = bar+1
	# Looping Kolom Spasi Kosong
	while kol > 1:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri
	kiri = 0
	while kiri < (x - bar):
		string = string + " * "
		kiri = kiri + 1
	# Looping Kolom Bintang Sisi Kanan
	kanan = kiri
	while kanan > 1:
		string = string + " * "
		kanan = kanan - 1

	string = string + "\n\n"
	bar = bar + 1
	print (string)
<img width="946" alt="1" src="https://user-images.githubusercontent.com/123891182/215354227-a4794631-4412-429b-9eb1-d52e30fd0ef4.png">

<img width="946" alt="2" src="https://user-images.githubusercontent.com/123891182/215354235-0f84b9a7-b5f7-459f-a80e-f97101862570.png">

<img width="684" alt="3" src="https://user-images.githubusercontent.com/123891182/215354240-acd9c2d2-9bdc-4997-8cba-aaa5216fe2ad.png">

*Hasil Run*


<img width="926" alt="12" src="https://user-images.githubusercontent.com/123891182/215354249-ff29822a-a709-414c-982d-ffb091e73a19.png">

# Menghitung Luas Dan Keliling Lingkaran
buat file baru "praktikum3"

	print('menghitung luas dan keliling lingkarang')
	print('________________________________________')

	r=float(input('masukkan nilai jari - jari :'))

	phi=3.14
	diameter=2*r

	print('\nluasnya =', str("%.2f" % luas))
	print('kelilingnya =', str("%.2f" % keliling))

![2022-10-31 (20)](https://user-images.githubusercontent.com/115775237/198937031-381eab4c-c619-48e3-b6b1-2b26d58ea5d9.png)

*Hasil Run*

![2022-10-31 (21)](https://user-images.githubusercontent.com/115775237/198937108-6674b88a-4277-4f76-8802-52dbf5a07503.png)

# Flowchart Menghitung luas dan keliling lingkaran

![2022-10-31 (22)](https://user-images.githubusercontent.com/115775237/199132888-b964fb68-df4c-4b40-a824-8365a2337d9c.png)

