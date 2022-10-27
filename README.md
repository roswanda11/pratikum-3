# Nama: Roswanda Nuraini

# NIM : 312210328

# Kelas : TI.22.A.3

## Latihan 1

# Penggunaan end

![Screenshot (45)](https://user-images.githubusercontent.com/115516632/198201870-0c7c660b-4d28-4940-b8ec-b8dffcf1488c.png)

# Penggunaan separator

![Screenshot (46)](https://user-images.githubusercontent.com/115516632/198202073-77ba80a8-2ad7-4001-ad7d-d4fe993fe697.png)

# String format

![Screenshot (47)](https://user-images.githubusercontent.com/115516632/198202245-a88904b7-d8d0-4c64-bac2-bc5d99cbb4f2.png)

# String format 2

![Screenshot (48)](https://user-images.githubusercontent.com/115516632/198202423-3f94a865-f5e7-4d8e-bb3d-835a60bb50fe.png)

# Hasil Latihan 1

![Screenshot (57)](https://user-images.githubusercontent.com/115516632/198212891-43bc0c54-26a8-4aa8-b1cf-1223d00a60ad.png)

![Screenshot (58)](https://user-images.githubusercontent.com/115516632/198213412-8314452c-50c0-417f-a8d3-489425381c53.png)

## Latihan 2

# Masukkan Variable

1. Penggunaan python untuk menginput nilai variable dengan cara

![Screenshot (50)](https://user-images.githubusercontent.com/115516632/198215615-e559a602-56aa-42e5-a2fd-194826d7fd66.png)

# Mencetak Variable

2. Cetak nilai kedua nilai variable yang sudah diinput

![Screenshot (59)](https://user-images.githubusercontent.com/115516632/198218042-993b7652-5271-41ed-ac86-9e422fa8b67d.png)

# Penggabungan Variable

3. Gabungkan nilai kedua variable

![Screenshot (60)](https://user-images.githubusercontent.com/115516632/198219037-1180beee-00f6-4fc6-82d2-a3d9c5cf069a.png)

# Masukkan Variable 2

1. Input kedua variable

![Screenshot (61)](https://user-images.githubusercontent.com/115516632/198219835-862dd907-b024-4616-bbb9-fb9339e785a2.png)

# Mengkonversi Nilai Variable

1. Mencetak kembali hasil konversi nilai kedua variable

![Screenshot (63)](https://user-images.githubusercontent.com/115516632/198220784-6551c9a3-a595-4a43-8fd3-eabfa2edde12.png)

# Hasil Latihan 2

![Screenshot (64)](https://user-images.githubusercontent.com/115516632/198221549-15dd6774-6d2e-47a9-980a-2ba86eccd397.png)

## Latihan 3 Menggunakan String Format untuk membuat Belah Ketupat

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

![Screenshot (65)](https://user-images.githubusercontent.com/115516632/198223201-45c224de-9109-473e-ba04-f6fb667d0f2f.png)

## Latihan 4 Luas Lingkaran

# Flowchart untuk mencari Luas Lingkaran

![flowchart-menghitung-luas-lingkaran-2](https://user-images.githubusercontent.com/115516632/198225284-5eb3417a-7bbd-42c1-957f-7e1a21c0b7d2.png)

# Mencari Luas Lingkaran

1. Rumus Luas Lingkaran yaitu phi/r atau phi*r^2

![Screenshot (66)](https://user-images.githubusercontent.com/115516632/198232281-c7a0510d-c632-4ec8-b2cb-ac60a40da965.png)

# Menginput Nilai Jari-Jari

2. Masukkan jari-jari untuk mencari luas lingkaran

![Screenshot (67)](https://user-images.githubusercontent.com/115516632/198233465-0c3a920c-d243-42ee-843e-fe85ecd12921.png)

# Mendeklarasikan Nilai Phi

3. Nilai phi yaitu 22/7 atau 3.14

![Screenshot (68)](https://user-images.githubusercontent.com/115516632/198234227-eed6b617-21ed-4f04-adf2-37b22975c040.png)

# Mencetak Hasil Luas Lingkaran

![Screenshot (69)](https://user-images.githubusercontent.com/115516632/198234709-d6f32294-8cb1-40f0-8aad-3c4f749325f8.png)

# Hasil Latihan 4 Luas Lingkaran

![Screenshot (70)](https://user-images.githubusercontent.com/115516632/198236640-5838f4d0-c032-4ea7-816d-dc95130d5b9b.png)

======= SEKIAN TERIMA KASIH =======



