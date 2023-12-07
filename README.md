# pert-12
<p>Buat program sederhana dengan mengaplikasikan penggunaan class. Buatlah
class untuk menampilkan daftar nilai mahasiswa, dengan ketentuan:</p>
<p>Method tambah() untuk menambah data</p>
<p>Method tampilkan() untuk menampilkan data</p>
<p>Method hapus(nama) untuk menghapus data berdasarkan nama</p>
<p>Method ubah(nama) untuk mengubah data berdasarkan nama</p>
<p>Buat diagram class, flowchart dan penjelasan programnya pada
README.md.</p>
<p>Commit dan push repository ke github.</p>

# <p>masukan kode program</p>

    def tampilkan():
        print(f"{'Daftar Data Mahasiswa':^82}")
        print('='*84)
        print(f"|{'NO':^4}|{'NIM':^20}|{'NAMA':^20}|{'TUGAS':^10}|{'UTS':^6}|{'UAS':^6}|{'AKHIR':^10}|")
        print('='*84)
        n = 0
        for a in data.items():
            n += 1
            print("|{no:^4}|{0:^20}|{1:^20}|{2:^10}|{3:^6}|{4:^6}|{5:^10}|"
            .format(a[1][0], a[0][:13], a[1][1], a[1][2], a[1][3], a[1][4], no = n))
        print('='*84)

    def hapus(nama):
        print(f"{'Data Berhasil di Hapus':^17}")
        print('='*17)
        del data[nama]

    def ubah(nama):
        print(f"{'Ubah Data':^17}")
        print('='*17)
        nim = str(input('NIM\t\t: ')) 
        uts = int(input('Nilai UTS\t: '))
        uas = int(input('Nilai UAS\t: '))
        tugas = int(input('Nilai Tugas\t: '))
        akhir = round(float((tugas*0.3)+(uts*0.35)+(uas*0.35)),2)
        data[nama] = nim, uts, uas, tugas, akhir

    def salah():
        print(f"{'Daftar Data Mahasiswa':^82}")
        print('='*84)
        print(f"|{'NO':^4}|{'NIM':^20}|{'NAMA':^20}|{'TUGAS':^10}|{'UTS':^6}|{'UAS':^6}|{'AKHIR':^10}|")
        print('='*84)
        print(F"|{'Tidak ada data':^82}|")
        print('='*84)

       

# <p>program tambah data</p>

![image](https://github.com/Theresianababan/pert-12/assets/148035194/f2cdaf50-2ecf-4c19-ad1e-03ab5f765416)
![image](https://github.com/Theresianababan/pert-12/assets/148035194/430c8312-cc61-4449-96e0-3e683e7377be)

# <p>menampilkan data</p>

![image](https://github.com/Theresianababan/pert-12/assets/148035194/aa1c4da4-0f51-482a-85ee-2a57527486b7)

# <p>menghapus data</p>

![image](https://github.com/Theresianababan/pert-12/assets/148035194/d9d93048-4ce2-4ae9-ac52-a4ff14e85016)

# <p>mengubah data</p>

![image](https://github.com/Theresianababan/pert-12/assets/148035194/aadfae59-85e8-4a83-adba-6a7bef7841f5)

# <p>keluar aplikasi</p>

![image](https://github.com/Theresianababan/pert-12/assets/148035194/07381708-d8ee-4e34-bb74-1ea3015d4844)

# <p>diagram class</p>

![image](https://github.com/Theresianababan/pert-12/assets/148035194/aa4d6316-4dc7-41c1-941f-674707c054ea)

# <p>flowchart</p>

![image](https://github.com/Theresianababan/pert-12/assets/148035194/3b6d1402-29fb-4b72-9054-14ba11c6e70e)






