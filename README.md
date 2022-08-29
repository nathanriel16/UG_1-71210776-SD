# UG_1-71210776-SD
#UG 1
print("Kalkulator")
print("1. Tambah")
print("2. Kurang")
print("3. Kali")
print("4. Bagi")

operasi = input("Pilih operasi perhitungan : ")
bilangan_1 = eval(input('Masukkan bilangan pertama : '))
bilangan_2 = eval(input('Masukkan bilangan kedua : '))

def kalkulator_sederhana():
    if operasi == '1':
        hasil = bilangan_1 + bilangan_2
        print(hasil)

    elif operasi == '2':
        hasil = bilangan_1 - bilangan_2
        print(hasil)

    elif operasi == '3':
        hasil = bilangan_1 * bilangan_2
        print(hasil)

    elif operasi == '4':
        hasil = bilangan_1 / bilangan_2
        print(hasil)
    return

kalkulator_sederhana()
