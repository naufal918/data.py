# data.py
tugas ap2b M13 (python) [def data]

def data():
    nama    = input("masukan nama anda  : ")
    kelas   = input("masukan kelas anda : ")
    npm     = int(input("masukan npm anda   : "))
    uts     = int(input("Masukkan Nilai UTS: "))
    uas     = int(input("Masukkan Nilai UAS: "))
    tempat  = input("masukan tempat kuliah anda : ")
    hobi    = input("masukan hobi anda : ")
    tinggal = input("masukan tinggal anda : ")
    jurusan = input("masukan jurusan anda : ")
    ganjil =  list(input("masukan bilangan ganjil  : "))
    Data = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15]
    print("++++++++++++++++++++++++++++++++++")
    
    print("nama anda",  nama)
    print("npm anda",   kelas)
    print("kelas anda", npm)
    jml = (uts * 0.7) + (uas * 0.3)
    print("Rata-rata anda", jml)
    print("tempat kuliah anda", tempat)
    print("hobi anda", hobi)
    print("tinggal anda", tinggal)
    print("jurusan anda", jurusan)
    print("bilangan ganjil adalah", ganjil)
    if jml >= 90.0:
        print("grade nilai anda : A")
        print("SELAMAT ANDA LULUS")
    elif jml >= 80.0:
        print("grade nilai anda : B")
        print("SELAMAT ANDA LULUS")
    elif jml >= 70.0:
        print("grade nilai anda : C")
        print("SELAMAT ANDA LULUS")
    elif jml >= 60.0:
        print("grade nilai anda : D")
        print("MAAF ANDA TIDAK LULUS")
    else:
        print("grade nilai anda : E")
        ("MAAF ANDA TIDAK LULUS")

data()
