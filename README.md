bulan = int(input("Masukkan bulan (1-12): "))
tahun = int(input("Masukkan tahun: "))

while bulan < 1 or bulan > 12:
    print("Bulan tidak valid. Silakan masukkan bulan antara 1 dan 12.")
    bulan = int(input("Masukkan bulan (1-12): "))

hari = jumlah_hari(bulan, tahun)

if hari is not None:
    print(f"Bulan {bulan} tahun {tahun} memiliki {hari} hari.")
else:
    print("Input tidak valid.")





for i in range(7, 0, -1):  
  print(str(i)*i)
