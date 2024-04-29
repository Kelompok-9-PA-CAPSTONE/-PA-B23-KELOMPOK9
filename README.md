Projek Akhir ASD Kelompok 9

PEMKOT

Anggota Kelompok :

  - Mohammed Nueno Hadiyanto (2309116081)
  - Asnan Fadjri Wahyudi (2309116094)
  - Muhammad  Shofwan Fikriyannur (2309116062)
  - Trisna Aprilia (2309116072)

---------------------------------------------------------------------------------------------------
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/4005e259-312f-4340-a22e-6f649de386b6)
“Mysql.connector” digunakan untuk berintraksi dengan databases Mysql, sedangkan “PrettyTable” digunakan untuk membuat tabel yang rapi di konsul.

---------------------------------------------------------------------------------------------------
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/c3457ae2-7fdc-4f3c-9bd3-38831f4ded16)
1. RESET: Mengembalikan warna teks ke default.
2.	BOLD: Mengatur teks menjadi tebal.
3.	RED: Mengatur warna teks menjadi merah.
4.	GREEN: Mengatur warna teks menjadi hijau.
5.	YELLOW: Mengatur warna teks menjadi kuning.
6.	BLUE: Mengatur warna teks menjadi biru.
7.	PURPLE: Mengatur warna teks menjadi ungu.
8.	CYAN: Mengatur warna teks menjadi cyan.

---------------------------------------------------------------------------------------------------
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/aafc2496-ce51-416e-ab26-a73920db5e15)
Kode ini membuat konesksi ke database Mysql. Kita harus mengganti nilai “host”, “user”, “password”, dan “database” sesuai dengan konfigurasi Mysql kita.

---------------------------------------------------------------------------------------------------
- Class Node
  ![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/fd661800-3130-4418-a607-f037ce086e8e)
Kita mendefinisikan kelas “Node”. Setiap node dalam linked list akan memiliki atribut “data” untuk menyimpan nilai dan atribut “next” untuk menunjukkan ke node berikutnya dalam linked list.

---------------------------------------------------------------------------------------------------
- Class LinkedList
  ![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/3c0b9d41-93ae-4cdf-aa5a-9c77bfc96205)
Kita menefinisikan kelas “LinkedList”. Kelas ini memiliki metode “append( )” yang digunakan untuk menambahkan data bar uke linked list.

---------------------------------------------------------------------------------------------------
- Method append
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/34eb5642-6020-4d42-b4e2-392d8eb4dd70)
Method ini berfungsi untuk menambahkan node baru di bagian akhir linked list. Method kemudian akan membuat istance baru dari class Node dan menyimpan data pada node tersebut.

---------------------------------------------------------------------------------------------------
- Method display_admin
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/7403a7ff-0271-4264-8d22-0228db3387c4)
Metode “display_admin( )” digunakan untuk menampilkan data dari tabel “admin” dalam format tabel yang rapi di konsol. Itu menggunakan modul “PrettyTable” untuk membentuk tabel.

---------------------------------------------------------------------------------------------------
- Method display_samarinda
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/39105fc4-bb9f-4a4e-bb68-fe67b9efdd63)
Metode “display_samarinda” digunakan untuk menampilkan data dari sebuah daftar yang disusun dalam bentuk tabel rapi.

---------------------------------------------------------------------------------------------------
- Method display_Pemerintah
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/9203d5d8-8dc2-47e1-b23d-9f91d868e02f)
Metode “display_pemerintah” digunkakan untuk menampilkan data dari sebuah daftar yang disusun dalam bentuk tabel rapi.

---------------------------------------------------------------------------------------------------
- Method display_Program
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/efc43a2c-612c-4daf-8cd6-cf0281bf1777)
Metode “display_pemerintah” digunkakan untuk menampilkan data dari sebuah daftar yang disusun dalam bentuk tabel rapi.

---------------------------------------------------------------------------------------------------
- Method quick_sort
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/1e7ecbcd-5bc2-4198-b94c-84029116a82c)
Fungsi “quick_sort( )” digunakan untuk mengurutkan data, terutama digunakan untuk mengurutkan data admin berdasarkan ID.

---------------------------------------------------------------------------------------------------
- Method jum_search
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/37e9c101-c7e2-430f-bc65-65346301af39)
Fungsi “jump_search( )” digunakan untuk mencari data dengan menggunakan algoritma pencarian jump search. Ini digunakakn dalam operasi pencarian data.

---------------------------------------------------------------------------------------------------
- Method read_admin
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/8e2088d1-e212-4d14-86c9-82c79b543449)
Fungsi “read_admin( )” digunakan untuk membaca data admin dari database. Ini menjalankan kueri SQL untuk mengambil semua data admin, kemudian menambahkannya ke linked list dan menampilkan data tersebut menggunakan metode “display_admin( )”.

---------------------------------------------------------------------------------------------------
- Method tambah_data_admin
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/616278a6-0858-4b90-b6a7-8a3135d5c731)
Fungsi “tambah_data_admin( )” digunakan untuk menambahkan data admin baru ke database. Pengguna diminta untuk memasukkan informasi admin, yang kemudian digunakan untuk membuat dan mengeksekusi kueri SQL untuk memasukkan data bar uke tabel admin.

---------------------------------------------------------------------------------------------------
- Method hapus_data_admin
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/bbc04438-b3d1-4f94-b0fc-1f79908f632d)
Fungsi “hapus_data_admin( )” digunakan untuk menghapus data admin dari database. Ini pertama-tama memanggil fungsi “read_admin( )” untuk menampilkan data admin yang ada, kemudian pengguna diminta untuk memasukkan ID orang yang ingin dihapus. Kemudian, kueri SQL dijalankan untuk menghapus data admin denga ID yang sesuai.

---------------------------------------------------------------------------------------------------
- Method Perbarui_data-admin
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/f1196fdc-fe1e-429e-93d5-907285159c5d)
Fungsi “perbarui_data_admin( )” digunakan untuk memoerbarui data admin yang ada di database. Seperti sebelumnya, fungsi ini terlebih dahulu menampilkan data admin yang ada menggunakan fungsi “read_admin( )”, kemudian meminta pengguna untuk memasukkan informasi baru untuk admin yang ingin diperbarui. Setelah itu, kueri SQL dijalankan untuk memperbarui data admin yang sesuai dengan ID yang dimssukkan.

--------------------------------------------------------------------------------------------------
- Method read_samarinda

def read_samarinda():
    mycursor.execute("SELECT * FROM samarinda")
    myresult = mycursor.fetchall()
    data_list = []
    for data in myresult:
        data_list.append(data)

    while True:
        print("============================================================")
        print("|                 TAMPILKAN DATA SAMARINDA                 |")
        print("============================================================")
        print("|   1. Tampilkan Data (urutkan berdasarkan ID - Ascending) |")
        print("|   2. Tampilkan Data (urutkan berdasarkan ID - Descending)|")
        print("|   3. Cari Data (berdasarkan ID)                          |")
        print("|   4. Kembali ke Menu Utama                               |")
        print("============================================================")

        pilihan = input("Masukkan pilihan Anda: ")

        if pilihan == "1":
            sorted_data = quick_sort(data_list, ascending=True)
            ll = LinkedList()
            for data in sorted_data:
                ll.append(data)
            ll.display_samarinda()
        elif pilihan == "2":
            sorted_data = quick_sort(data_list, ascending=False)
            ll = LinkedList()
            for data in sorted_data:
                ll.append(data)
            ll.display_samarinda()
        elif pilihan == "3":
            id_to_search = int(input("Masukkan ID yang ingin dicari: "))
            result_index = jump_search(data_list, id_to_search)
            if result_index != -1:
                print("Data ditemukan:")
                x = PrettyTable()
                x.field_names = ["id_samarinda", "kecamatan", "kelurahan", "kode_pos"]
                x.add_row(data_list[result_index])
                print(x)
            else:
                print("Data tidak ditemukan.")
        elif pilihan == "4":
            break
        else:
            print("Pilihan tidak valid. Silakan pilih kembali.")

fungsi “read_samarinda( )” digunakan untuk membaca data samarinda dari database. Ini menjalankan kueri SQL untuk mengambil semua data samarinda, kemudian menampilkannya ke dalam sebuah list. Selanjutnya, program meminta pengguna untuk memiih opsi untuk menampilkan mencari, atau kemudian ke menu utama. Opsi tersebut kemudian dieksekusi sesuai dengan input pengguna.

--------------------------------------------------------------------------------------------------
- Mrthod tambah_data_samarinda
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/8e46b3b5-91aa-45d3-97f4-e99fc49e4b12)
Fungsi “tambah_data_samarinda( )” digunakan untuk menambhkan data samarinda baru ke database. Pengguna diminta untuk memasukkan informasi samarinda, yang kemudian digunakan untuk membuat dan mengeksekusi kueri SQL untuk memasukkan data baru ke tabel samarinda.

--------------------------------------------------------------------------------------------------
- Method hapus_data_samarinda
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/251a9a19-5d79-406e-b927-080b5b757b1c)
Fungsi “hapus_data_samarinda( )” digunakan untuk menghapus data samarinda dari database. Pertama, fungsi ini menampilkan semua data samarinda yang ada menggunakan PrttTable. Kemudian, pengguna diminta untuk memasukkan ID samarinda yang ingin dihapus. Setelah itu, kueri SQL dijalankan untuk menghapus data samarinda dengan ID yang sesuai.

--------------------------------------------------------------------------------------------------
- Method perbarui_data_samarinda
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/02a802ca-1091-47ba-b34d-b837c6185809)
Fungsi “perbarui_data_samarinda( )” digunakan untuk memperbarui data samarinda yang ada di database. Pertama, fungsi ini menampilkan semua data samrinda yang ada menggunakan PrttyTable. Kemudian, pengguna diminta untuk memasukkan ID samarinda yang ingin diperbarui, serta informasi baru seperti nama kecamatan, nama kelurahan, dan kode pos baru. Setelah mendapatkan input dari pengguna, sebuah kueri SQL dibuat untuk memperbarui data samrinda yang sesuai dengan ID yang dimasukkan.

--------------------------------------------------------------------------------------------------
- Method read_samarinda

def read_pemerintah():
    mycursor.execute("SELECT * FROM pemerintah")
    myresult = mycursor.fetchall()
    data_list = []
    for data in myresult:
        data_list.append(data)

    while True:
        print("============================================================")
        print("|                 TAMPILKAN DATA PEMERINTAH                |")
        print("============================================================")
        print("|   1. Tampilkan Data (urutkan berdasarkan ID - Ascending) |")
        print("|   2. Tampilkan Data (urutkan berdasarkan ID - Descending)|")
        print("|   3. Cari Data (berdasarkan ID)                          |")
        print("|   4. Kembali ke Menu Utama                               |")
        print("============================================================")

        pilihan = input("Masukkan pilihan Anda: ")

        if pilihan == "1":
            sorted_data = quick_sort(data_list, ascending=True)
            ll = LinkedList()
            for data in sorted_data:
                ll.append(data)
            ll.display_pemerintah()
        elif pilihan == "2":
            sorted_data = quick_sort(data_list, ascending=False)
            ll = LinkedList()
            for data in sorted_data:
                ll.append(data)
            ll.display_pemerintah()
        elif pilihan == "3":
            id_to_search = int(input("Masukkan ID yang ingin dicari: "))
            result_index = jump_search(data_list, id_to_search)
            if result_index != -1:
                print("Data ditemukan:")
                x = PrettyTable()
                x.field_names = ["id_pemerintah", "nama_pejabat", "jabatan", "partai",     "hak_akses"]
                x.add_row(data_list[result_index])
                print(x)
            else:
                print("Data tidak ditemukan.")
        elif pilihan == "4":
            break
        else:
            print("Pilihan tidak valid. Silakan pilih kembali.")

Fungsi “read_pemerintah( )” digunakan untuk membaca data pemerintah dari database. Ini juga berfungsi mirip dengan fungsi “read_samarinda( )”, di mana pengguna diminta untuk memilih opsi untuk menampilkan, mencari, atau Kembali ke menu utama. Opsi tersebut kemudian dieksekusi sesuai dengann input pengguna.

--------------------------------------------------------------------------------------------------
- Method tambah_data_pemerintah
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/bd30f645-5320-46a9-b723-a3c6be791c6f)
Fungsi “tambah_data_pemerintah( )” digunakan untuk menambahkan data pemerintah bar uke dalam database. Pengguna di minta untuk memasukkan informasi seperti ID pemerinah, nama pejabat, jabatan, partai, dan hak akses. Setelah mendapatkan input dari pengguna, sebuah kueri SQL dibuat untuk memasukkan data baru ke dalam tabel pemerintah di database.

--------------------------------------------------------------------------------------------------
- Method hapus_data_pemerintah
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/b934d084-20ff-4f7a-ae15-6af1c0070678)
Fungsi “hapus_data_pemerintah( )” digunakan untuk menghapus data pemerintah dari database. Pertama, data pemerintah yang ada ditampilkan menggunakan PrttyTable. Pengguna kemudian diminta untuk memasukkan ID pemerintah yang ingin dihapus. Setelah mendapatkan input tersebut, sebuah kueri SQL dibuat untuk menghapus data pemerintah sesuai dengan ID yang dimasukkan.

--------------------------------------------------------------------------------------------------
- Method perbarui_data_pemerintah
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/d5c0b1d3-755a-4d9e-8a8d-bc7be798eb87)
Fungsi “perbarui_data_pemerintah( )” digunakan untuk memperbarui data pemerintah yang ada di database. Data pemerintah yang ada ditampilkan terlebih dahulu menggunakan PrttyTable. Pengguna kemudian diminta untuk memasukkan ID pemerintah yang ingin diperbarui, serta informasi baru seperti nama pejabat, jabatan, partai, dan hak akses baru. Setelah mendapatkan input tersebut, sebuah kueri SQL dibuat untuk memperbarui data pemerintah sesuai dengan ID yang dimasukkan.

--------------------------------------------------------------------------------------------------
- Method read_program

def read_program():
    mycursor.execute("SELECT * FROM program")
    myresult = mycursor.fetchall()
    data_list = []
    for data in myresult:
        data_list.append(data)

    while True:
        print("============================================================")
        print("|                  TAMPILKAN DATA PROGRAM                  |")
        print("============================================================")
        print("|   1. Tampilkan Data (urutkan berdasarkan ID - Ascending) |")
        print("|   2. Tampilkan Data (urutkan berdasarkan ID - Descending)|")
        print("|   3. Cari Data (berdasarkan ID)                          |")
        print("|   4. Kembali ke Menu Utama                               |")
        print("============================================================")
        pilihan = input("Masukkan pilihan Anda: ")

        if pilihan == "1":
            sorted_data = quick_sort(data_list, ascending=True)
            ll = LinkedList()
            for data in sorted_data:
                ll.append(data)
            ll.display_program()
        elif pilihan == "2":
            sorted_data = quick_sort(data_list, ascending=False)
            ll = LinkedList()
            for data in sorted_data:
                ll.append(data)
            ll.display_program()
        elif pilihan == "3":
            id_to_search = int(input("Masukkan ID yang ingin dicari: "))
            result_index = jump_search(data_list, id_to_search)
            if result_index != -1:
                print("Data ditemukan:")
                x = PrettyTable()
                x.field_names = ["id_program", "nama_program", "bidang_program",      "status_program"]
                x.add_row(data_list[result_index])
                print(x)
            else:
                print("Data tidak ditemukan.")
        elif pilihan == "4":
            break
        else:
            print("Pilihan tidak valid. Silakan pilih kembali.")

Fungsi “read_pemerintah( )” bertugas untuk menampilkan data dari tabel ‘pemerintah’ dan memberika opsi kepada penguna untuk melihat, mengurutkan, atau mencari data berdasarkan ID.

--------------------------------------------------------------------------------------------------
- Method tambah_data_program
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/fdb0f854-98d5-4739-b025-1db6a64d45b9)
Fungsi “tambah_data_program( )” bertujuan untuk menambahkan data program baru  ke dalam database. Ini dilakukan dengan meminta pengguna untuk memasukkan ID program, nama program, bidang program, dan status program melalui input. Setelah itu, fungsi ini membangun sebuah queri SQL untuk memasukkan data tersebut ke dalam tabel program, lalu mengeksekusi queri tersebut dalam melakukan commit untuk menyimpan perubahan ke dalam database.

--------------------------------------------------------------------------------------------------
- Method hapus_data_program
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/7ade537f-e1fb-4065-b59e-342772e790c6)
Fungsi “hapus_data_program( )” bertujuan untuk menghapus data program dari database berdasarkan ID program yang dimasukkan oleh pengguna. Pertama-tama, fungsi ini mengeksekusi queri SQL untuk mengambil semua data dari tabel program dan menyimpan hasilnya dalam variable “myresult”. Kemudian, data tersebut ditamoilkan dalam bentuk tabel menggunakan modul “PrettyTable”. Pengguna diminta untuk memasukkan ID program yang ingin di hapus melalui input.

--------------------------------------------------------------------------------------------------
- Method Perbarui_data_Program
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/42bb3035-d485-408b-84ce-32a28354165e)
Fungsi “perbarui_data_program( )” digunakan untuk memperbarui data program dalam database berdasarkan ID program yang dimasukkan oleh pengguna. Pertama-tama, fungsi ini mengambil semua data program dari tabel program menggunakan queri SQL ‘SELECT * FROM program’ dan menyimpan hasilnya dalam variable ‘myresult’. Data tersebut kemudian ditempatkan dalam bentuk tabel menggunakan modul ‘PrttyTable”.

--------------------------------------------------------------------------------------------------
- Method menu_utama_admin
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/6b722da5-2bd2-4964-8e02-14a26243c8c6)
Fungsi “menu_utama_admin( )” merupakan bagian dari antarmuka pengguna untuk administrasi database. fungsi ini menampilkan menu yang memungkinkan pengguna untuk melakukan operasi pada data admin, seperti menambahkan, menghapuskan, memperbarui, dan menampilkan data admin.
1. Menu tampilan: menampilkan menu utama untuk admin.
2. Input pilihan: meminta pengguna untuk memasukkan pilihan menu.
3. Pengelolaan pilihan: melakukan tindakan sesuai dengan pilihan yang dimasukkan pengguna:
    -  Pilihan 1: memanggil fungsi “tambah_data_admin( )” untuk menambahkan data admin baru.
    -  Pilihan 2: memanggil fungsi “hapus_data_admin( )” untuk menghapuskan data admin baru 
    -  Pilihan 3: memanggil fungsi “perbarui_data_admin( )” untuk memperbarui data admin.
    -  Pilihan 4: memanggil fungsi “read_data_admin( )” untuk menampilkan data admin.
    -  Pilihan 5: mengakhiri program dan mencetak pesan terima kasih.
4. Validasi pilihan: memastikan bahwa pilihan yang dimasukkan valid. Jadi tidak, mencetak         pesan kesalahan dan meminta pengguna untuk memilih Kembali.

--------------------------------------------------------------------------------------------------
- Method menu_utama_samarinda
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/c66875f4-3b92-4b07-b8de-898b34eafbf9)
Fungsi “menu_utama_samarinda( )” adalah bagian dari antaramuka pengguna yang mengelola database samarinda. Fungsi menampilkan menu yang memungkinkan pengguna untuk melakukan barbagai operasi pada data samarinda, seperti menambahkan, menghapus, memperbarui, dan menampilkan data.
1.	Menu tampilan: menampilkan menu untuk pengguna yang mengelola database samarinda.
2.	Input pilihan: meminta pengguna untuk memasukkan pilihan menu.
3.	Pengelolaan pilihan: melakukan tindakan sesuai dengan pilihan yang dimasukkan pengguna:
  -  Pilihan 1: memanggil fungsi “tambah_data_samarinda( )” untuk menambahkan data samarinda        baru.
  - Pilihan 2: memanggil fungsi “hapus_data_samarinda( )” untuk menghapuskan data samarinda.
  - Pilihan 3: memanggil fungsi “perbarui_data_samarinda( )” untuk memperbarui data samarinda.
  - Pilihan 4 : memanggil fungsi “read_samarinda( )” untuk menampilkan data samarinda.
  - Pilihan 5: mengakhiri program dan mencetak pesan terima kasih.
4.	Validasi pilihan: memastikan bahwa pilihan yang dimasukkan valid. Jika tidak, mencetak pesan kesalahan dan meminta pengguna untuk memilih Kembali.

--------------------------------------------------------------------------------------------------
- Method menu_utama_pemerintah
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/3a16f65c-01ad-4579-a0f5-fc79b9f2a85c)
Fungsi “menu_utama_pemerintah( )” adalah bagian antarmuka pengguna yang mengelola database pemerintah. Fungsi ini menampilkanmenu yang memungkinkan pengguna untuk melakukan berbagai operasi pada data pemerintah, seperti menambah, menghapus, memperbarui, dan menampilkan data.
1.	Menu Tampilan: Menampilkan menu utama untuk pengguna yang mengelola database Pemerintah.
2.	Input Pilihan: Meminta pengguna untuk memasukkan pilihan menu.
3.	Pengelolaan Pilihan: Melakukan tindakan sesuai dengan pilihan yang dimasukkan pengguna:
  - Pilihan 1: Memanggil fungsi tambah_data_pemerintah() untuk menambahkan data Pemerintah         baru.
  - Pilihan 2: Memanggil fungsi hapus_data_pemerintah() untuk menghapus data Pemerintah.
  - Pilihan 3: Memanggil fungsi perbarui_data_pemerintah() untuk memperbarui data Pemerintah.
  - Pilihan 4: Memanggil fungsi read_pemerintah() untuk menampilkan data Pemerintah.
  - Pilihan 5: Mengakhiri program dan mencetak pesan terima kasih.
4.	Validasi Pilihan: Memastikan bahwa pilihan yang dimasukkan valid. Jika tidak, mencetak         pesan kesalahan dan meminta pengguna untuk memilih kembali.

--------------------------------------------------------------------------------------------------
- Method menu_utama_program
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/a9119eb4-4caf-4618-819a-f85fa039b289)
Fungsi “menu_utama_program( )” adalah bagian dari antarmuuka pengguna yang mengelola database program. Fungsi ini menampilkan menu yang memungkinkan pengguna untuk melakukan berbagai opersi pada data program, seperti menambahkan, menghapus, memperbarui, dan menampilkan data.
1.	Menu tampilan: menampilkan menu utama untuk pengguna yang mengelolam database program.
2.	Input pilihan: meminta pengguna untuk memasukkan pilihan menu.
3.	Pengelolaan pilihan: melakukukan Tindakan sesuai dengan pilihan yang dimasukkan pengguna:
  - Pilihan 1: memanggil fungsi “tambah_data_program( )” untuk menambahkan data program baru.
  - Pilihan 2: memanggil fungsi “menghapus_data_program( )” untuk menghapus data program.
  - Pilihan 3: memanggil fungsi “perbarui_data_program( )” untuk memperbarui data program.
  - Pilihan 4: memanggil fungsi “read_program( )” untuk menampilkan data program.
  - Pilihan 5: mengakhiri program dan mencetak pesan terima kasih.
4.	Vadilasi pilihan: memastikan bahwa pilihan yang dimasukkan valid. Jika tidak, mencetak         pesan kesalahan dan meminta pengguna untuk memilih Kembali.

--------------------------------------------------------------------------------------------------
- Method menu_utama_superuser
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/5df69174-3ef1-4d29-ab16-6e97e96107f8)
Fungsi “menu_utama_superuser()” bertanggung jawab untuk menampilkan menu utama bagi pengguna superuser. Pengguna superuser dapat mengakses dan mengelola empat database yang berbeda: Admin, Samarinda, Pemerintah, dan Program.
1.	Menu Tampilan: Menampilkan menu utama untuk pengguna superuser, termasuk pesan selamat datang yang mencakup nama pengguna.
2.	Input Pilihan: Meminta pengguna untuk memasukkan pilihan menu.
3.	Pengelolaan Pilihan: Melakukan tindakan sesuai dengan pilihan yang dimasukkan pengguna:
  - Pilihan 1: Memanggil fungsi “menu_utama_admin()” untuk mengelola database Admin.
  - Pilihan 2: Memanggil fungsi “menu_utama_samarinda()” untuk mengelola database Samarinda.
  - Pilihan 3: Memanggil fungsi “menu_utama_pemerintah()” untuk mengelola database Pemerintah.
  - Pilihan 4: Memanggil fungsi “menu_utama_program()” untuk mengelola database Program.
  - Pilihan 5: Mengakhiri program dan mencetak pesan terima kasih.
4.	Validasi Pilihan: Memastikan bahwa pilihan yang dimasukkan valid. Jika tidak, mencetak         pesan kesalahan dan meminta pengguna untuk memilih kembali.

--------------------------------------------------------------------------------------------------
- class LoginSystem
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/d75b1e3c-3092-4cec-87e9-938201062728)
Kelas LoginSystem bertujuan untuk mengelola sistem login.

--------------------------------------------------------------------------------------------------
- Method get_user_info
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/d86b6156-8b6b-4617-abb3-0a0db6f25c98)
Method “get_user_info” dalam kelas “LoginSystem” bertujuan untuk mendapatkan informasi tentang seorang pengguna berdasarkan username yang diberikan.

--------------------------------------------------------------------------------------------------
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/c0408c05-6ba4-4b47-91c6-38bb3bf1ea0d)
1.	‘login_system’ = LoginSystem(mydb): Ini adalah bagian di mana objek LoginSystem dibuat dengan menggunakan database mydb. Diperkirakan LoginSystem adalah kelas yang bertanggung jawab untuk mengelola sistem login, dan mydb adalah objek database yang digunakan dalam sistem.
2.	while True:: Ini adalah loop tak terbatas yang akan menjalankan menu program secara berulang sampai pengguna memilih untuk keluar.
3.	Bagian berikutnya adalah tampilan menu program yang mencakup informasi tentang website, judul, pilihan menu untuk login, masuk sebagai tamu, atau keluar dari program.
4.	choice = input("PILIH MENU : "): Ini adalah bagian di mana pengguna diminta untuk memilih pilihan menu dengan memasukkan nomor yang sesuai.
5.	Kemudian, program akan memeriksa pilihan yang dimasukkan oleh pengguna dan menjalankan tindakan yang sesuai berdasarkan pilihan tersebut. Jika pengguna memilih opsi 1, program akan meminta username dan password, kemudian mencoba untuk melakukan login dengan menggunakan informasi tersebut melalui objek login_system. Jika pengguna memilih opsi 2, program akan memanggil fungsi menu_tamu(). Jika pengguna memilih opsi 3, program akan mencetak pesan terima kasih dan keluar dari loop.
6.	Jika pengguna memasukkan pilihan yang tidak valid, program akan mencetak pesan "SALAH KETIK" dan pengulangan akan terus berlanjut.

--------------------------------------------------------------------------------------------------


Penjelasan output 
--------------------------------------------------------------------------------------------------
- Menu Awal sebelum masuk program
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/7d607f5a-d5f9-4fb5-a945-174b5ac932c7)
Pengguna kemudian diminta untuk memilih salah satu opsi dari menu tersebut dengan memasukkan nomor yang sesuai. Jika pengguna memilih opsi 1, mereka akan diminta untuk memasukkan username dan password. Jika pengguna memilih opsi 2, mungkin akan memanggil fungsi menu_tamu(). Jika pengguna memilih opsi 3, program akan mencetak pesan terima kasih dan keluar dari loop.

--------------------------------------------------------------------------------------------------
- masuk ke menu admin
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/8cf6c06b-d42f-44f5-80eb-1aa8730624a6)
1.	Jika pengguna berhasil login sebagai superuser, program akan menampilkan pesan yang menyatakan bahwa pengguna telah berhasil masuk, dengan menampilkan username pengguna.
2.	Setelah itu, program akan menampilkan menu utama superuser, yang terdiri dari beberapa opsi, termasuk akses ke berbagai database dan opsi untuk keluar dari database pemkot.
3.	Pengguna diminta untuk memasukkan pilihan mereka dengan memasukkan nomor yang sesuai dengan menu yang ditampilkan.
4.	Program akan menanggapi pilihan pengguna dan akan melakukan tindakan yang sesuai berdasarkan pilihan tersebut. Jika pengguna memilih salah satu opsi untuk mengakses database tertentu, program akan memanggil fungsi yang sesuai untuk mengelola database tersebut. Jika pengguna memilih opsi untuk keluar dari database pemkot, program akan mencetak pesan bahwa pengguna telah berhasil keluar dan keluar dari loop.
5.	Jika pengguna memasukkan pilihan yang tidak valid, program akan mencetak pesan "SALAH KETIK" dan kembali menampilkan menu utama untuk pemilihan opsi selanjutnya.

--------------------------------------------------------------------------------------------------
- masuk kemenu database admin
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/b91b23e6-7584-4a0a-b2fe-6ff160e7279e)
1.	Setelah pengguna berhasil login sebagai admin dan memilih opsi untuk mengakses database admin, program akan menampilkan menu utama untuk admin.
2.	Menu ini berisi beberapa opsi untuk melakukan tindakan tertentu terkait dengan pengelolaan data admin dalam sistem.
3.	Pengguna diminta untuk memasukkan pilihan mereka dengan memasukkan nomor yang sesuai dengan menu yang ditampilkan.
4.	Program akan menanggapi pilihan pengguna dan akan melakukan tindakan yang sesuai berdasarkan pilihan tersebut. Misalnya, jika pengguna memilih untuk menambah data admin, program akan memanggil fungsi tambah_data_admin(). Begitu juga dengan opsi lainnya, seperti menghapus data admin, memperbarui data admin, menampilkan data admin, atau keluar dari database admin.
5.	Jika pengguna memasukkan pilihan yang tidak valid, program akan mencetak pesan "COBA LAGI!" dan kembali menampilkan menu utama admin untuk pemilihan opsi selanjutnya.

--------------------------------------------------------------------------------------------------
- masuk ke database samarinda
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/5d48f403-0535-4d52-9147-01e88d5d3d01)
1.	Setelah pengguna memilih opsi untuk mengakses database Samarinda, program akan menampilkan menu utama untuk database Samarinda. Menu ini akan terlihat seperti yang ada diatas:
2.	Pengguna diminta untuk memilih pilihan mereka dengan memasukkan nomor yang sesuai dengan menu yang ditampilkan.
3.	Program akan menanggapi pilihan pengguna dan akan melakukan tindakan yang sesuai berdasarkan pilihan tersebut. Misalnya:
  - Jika pengguna memilih opsi 1, program akan memanggil fungsi tambah_data_samarinda() untuk menambahkan data baru ke dalam database Samarinda.
  - Jika pengguna memilih opsi 2, program akan memanggil fungsi hapus_data_samarinda() untuk menghapus data dari database Samarinda.
  - Jika pengguna memilih opsi 3, program akan memanggil fungsi perbarui_data_samarinda() untuk memperbarui data dalam database Samarinda.
  - Jika pengguna memilih opsi 4, program akan memanggil fungsi read_samarinda() untuk menampilkan data yang tersimpan dalam database Samarinda.
  - Jika pengguna memilih opsi 5, program akan mencetak pesan "BERHASIL KELUAR !" dan keluar dari loop, kembali ke menu utama sebelumnya.
4.	Jika pengguna memasukkan pilihan yang tidak valid, program akan mencetak pesan "COBA LAGI!" dan kembali menampilkan menu utama untuk pemilihan opsi selanjutnya.

--------------------------------------------------------------------------------------------------
- masuk ke database pemerintah
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/e9da67db-6a45-4b72-b159-2c53f63d92be)
1.	Setelah pengguna memilih opsi untuk mengakses database pemerintah, program akan menampilkan menu utama untuk database pemerintah. Menu ini akan terlihat seperti yang ada di atas ini:
2.	Pengguna diminta untuk memilih pilihan mereka dengan memasukkan nomor yang sesuai dengan menu yang ditampilkan.
3.	Program akan menanggapi pilihan pengguna dan akan melakukan tindakan yang sesuai berdasarkan pilihan tersebut. Misalnya:
  -	Jika pengguna memilih opsi 1, program akan memanggil fungsi tambah_data_pemerintah() untuk menambahkan data baru ke dalam database pemerintah.
  -	Jika pengguna memilih opsi 2, program akan memanggil fungsi hapus_data_pemerintah() untuk menghapus data dari database pemerintah.
  -	Jika pengguna memilih opsi 3, program akan memanggil fungsi perbarui_data_pemerintah() untuk memperbarui data dalam database pemerintah.
  -	Jika pengguna memilih opsi 4, program akan memanggil fungsi read_pemerintah() untuk menampilkan data yang tersimpan dalam database pemerintah.
  -	Jika pengguna memilih opsi 5, program akan mencetak pesan "BERHASIL KELUAR !" dan keluar dari loop, kembali ke menu utama sebelumnya.
4.	Jika pengguna memasukkan pilihan yang tidak valid, program akan mencetak pesan "COBA LAGI!" dan kembali menampilkan menu utama untuk pemilihan opsi selanjutnya.

--------------------------------------------------------------------------------------------------
-masuk ke database program 
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/a8c91ad3-6ab8-474d-9e8d-156abe4b8bb9)
1.	Setelah pengguna memilih opsi untuk mengakses database program, program akan menampilkan menu utama untuk database program. Menu ini akan terlihat seperti yang ada diatas ini:
2.	Pengguna diminta untuk memilih pilihan mereka dengan memasukkan nomor yang sesuai dengan menu yang ditampilkan.
3.	Program akan menanggapi pilihan pengguna dan akan melakukan tindakan yang sesuai berdasarkan pilihan tersebut. Misalnya:
  -	Jika pengguna memilih opsi 1, program akan memanggil fungsi tambah_data_program() untuk menambahkan data baru ke dalam database program.
  -	Jika pengguna memilih opsi 2, program akan memanggil fungsi hapus_data_program() untuk menghapus data dari database program.
  -	Jika pengguna memilih opsi 3, program akan memanggil fungsi perbarui_data_program() untuk memperbarui data dalam database program.
  -	Jika pengguna memilih opsi 4, program akan memanggil fungsi read_program() untuk menampilkan data yang tersimpan dalam database program.
  - Jika pengguna memilih opsi 5, program akan mencetak pesan "BERHASIL KELUAR !" dan keluar dari loop, kembali ke menu utama sebelumnya.
4.	Jika pengguna memasukkan pilihan yang tidak valid, program akan mencetak pesan "SALAH PILIH !" dan kembali menampilkan menu utama untuk pemilihan opsi selanjutnya.

--------------------------------------------------------------------------------------------------
- Masuk ke menu Tamu
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/ebe26810-97df-49e4-aee6-fee5a951165b)
1.	Setelah pengguna memilih opsi untuk mengakses database pemerintah, program akan menampilkan menu utama untuk database pemerintah. Menu ini akan terlihat seperti yang ada di atas ini:
2.	Pengguna diminta untuk memilih pilihan mereka dengan memasukkan nomor yang sesuai dengan menu yang ditampilkan.
3.	Program akan menanggapi pilihan pengguna dan akan melakukan tindakan yang sesuai berdasarkan pilihan tersebut. Misalnya:
  -	Jika pengguna memilih opsi 1, program akan memanggil fungsi read_samarinda() untuk menampilkan data dari database Samarinda.
  -	Jika pengguna memilih opsi 2, program akan memanggil fungsi read_pemerintah() untuk menampilkan data dari database pemerintah.
  -	Jika pengguna memilih opsi 3, program akan memanggil fungsi read_program() untuk menampilkan data dari database program.
  -	Jika pengguna memilih opsi 4, program akan mencetak pesan "Terima kasih!" dan keluar dari loop, kembali ke menu utama sebelumnya.
4.	Jika pengguna memasukkan pilihan yang tidak valid, program akan mencetak pesan "Pilihan tidak valid. Silakan pilih kembali." dan kembali menampilkan menu untuk pemilihan opsi selanjutnya.

--------------------------------------------------------------------------------------------------
- Masuk ke tampilkan data samarinda
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/a562d7d3-1ce1-4ae0-8bcd-2dabd6a9beb4)
1.	Jika pengguna memilih opsi 1, data akan diurutkan berdasarkan ID secara ascending (menaik) dan kemudian ditampilkan dalam format yang sesuai.
2.	Jika pengguna memilih opsi 2, data akan diurutkan berdasarkan ID secara descending (menurun) dan kemudian ditampilkan dalam format yang sesuai.
3.	Jika pengguna memilih opsi 3, program akan meminta pengguna untuk memasukkan nama kecamatan yang ingin dicari. Jika ada data yang cocok dengan pencarian tersebut, data tersebut akan ditampilkan dalam format yang sesuai. Jika tidak ada data yang cocok, program akan mencetak pesan "Tidak ada data yang cocok dengan pencarian Anda."
4.	Jika pengguna memilih opsi 4, program akan meminta pengguna untuk memasukkan ID yang ingin dicari. Jika data dengan ID yang cocok ditemukan, detail data tersebut akan ditampilkan dalam format yang sesuai. Jika tidak ditemukan data yang cocok, program akan mencetak pesan "DATA TIDAK DITEMUKAN".
5.	Jika pengguna memilih opsi 5, program akan keluar dari loop dan kembali ke menu utama database Samarinda.
6.	Jika pengguna memasukkan pilihan yang tidak valid, program akan mencetak pesan "PILIHAN TIDAK VALID !" dan kembali menampilkan menu untuk pemilihan opsi selanjutnya.

--------------------------------------------------------------------------------------------------
- Masuk ke tampilkan data Pemerintah
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/d80dd2fb-8285-450b-a313-930feec724d6)
1.	Jika pengguna memilih opsi 1, data akan diurutkan berdasarkan ID secara ascending (menaik) dan kemudian ditampilkan dalam format yang sesuai dengan struktur yang telah ditentukan sebelumnya.
2.	Jika pengguna memilih opsi 2, data akan diurutkan berdasarkan ID secara descending (menurun) dan kemudian ditampilkan dalam format yang sesuai.
3.	Jika pengguna memilih opsi 3, program akan meminta pengguna untuk memasukkan nama pejabat yang ingin dicari. Jika ada data yang cocok dengan pencarian tersebut, data tersebut akan ditampilkan dalam format yang sesuai. Jika tidak ada data yang cocok, program akan mencetak pesan "Tidak ada data yang cocok dengan pencarian Anda."
4.	Jika pengguna memilih opsi 4, program akan meminta pengguna untuk memasukkan ID yang ingin dicari. Jika data dengan ID yang cocok ditemukan, detail data tersebut akan ditampilkan dalam format yang sesuai dengan struktur yang telah ditentukan sebelumnya. Jika tidak ditemukan data yang cocok, program akan mencetak pesan "DATA DATABASE TIDAK DITEMUKAN".
5.	Jika pengguna memilih opsi 5, program akan keluar dari loop dan kembali ke menu utama database Pemerintah.
6.	Jika pengguna memasukkan pilihan yang tidak valid, program akan mencetak pesan "COBA LAGI !" dan kembali menampilkan menu untuk pemilihan opsi selanjutnya.

--------------------------------------------------------------------------------------------------
- Masuk ke tampilkan data Program
![image](https://github.com/Kelompok-9-PA-CAPSTONE/-PA-B23-KELOMPOK9/assets/146003481/2adc316d-cd47-452f-9a42-5820b235fa90)
1.	Jika pengguna memilih opsi 1, data akan diurutkan berdasarkan ID secara ascending (menaik) dan kemudian ditampilkan dalam format yang sesuai dengan struktur yang telah ditentukan sebelumnya.
2.	Jika pengguna memilih opsi 2, data akan diurutkan berdasarkan ID secara descending (menurun) dan kemudian ditampilkan dalam format yang sesuai.
3.	Jika pengguna memilih opsi 3, program akan meminta pengguna untuk memasukkan nama program yang ingin dicari. Jika ada data yang cocok dengan pencarian tersebut, data tersebut akan ditampilkan dalam format yang sesuai. Jika tidak ada data yang cocok, program akan mencetak pesan "Tidak ada data yang cocok dengan pencarian Anda."
4.	Jika pengguna memilih opsi 4, program akan meminta pengguna untuk memasukkan ID yang ingin dicari. Jika data dengan ID yang cocok ditemukan, detail data tersebut akan ditampilkan dalam format yang sesuai dengan struktur yang telah ditentukan sebelumnya. Jika tidak ditemukan data yang cocok, program akan mencetak pesan "DATA DATABASE TIDAK DITEMUKAN".
5.	Jika pengguna memilih opsi 5, program akan keluar dari loop dan kembali ke menu utama database Program.
6.	Jika pengguna memasukkan pilihan yang tidak valid, program akan mencetak pesan "COBA LAGI !" dan kembali menampilkan menu untuk pemilihan opsi selanjutnya.

