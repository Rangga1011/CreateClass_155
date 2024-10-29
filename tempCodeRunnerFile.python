class PersegiPanjang:
    # Konstruktor untuk menginisialisasi objek PersegiPanjang dengan atribut panjang dan lebar
    def __init__(self, panjang, lebar):
        self.panjang = panjang
        self.lebar = lebar

    # Metode untuk menghitung keliling persegi panjang
    def keliling(self):
        return 2 * (self.panjang + self.lebar)

    # Metode untuk menghitung luas persegi panjang
    def luas(self):
        return self.panjang * self.lebar

    # Metode khusus untuk mengembalikan representasi string dari objek PersegiPanjang
    def __str__(self):
        return f"Persegi Panjang, panjang {self.panjang} cm, dan lebar {self.lebar} cm"

def main():
    try:
        # Meminta pengguna memasukkan panjang dan lebar persegi panjang
        panjang = float(input("Masukkan panjang persegi panjang (cm): "))
        lebar = float(input("Masukkan lebar persegi panjang (cm): "))

        # Validasi: memastikan panjang dan lebar lebih dari nol
        if panjang <= 0 or lebar <= 0:
            raise ValueError("Panjang dan lebar harus lebih besar dari nol.")

        # Membuat objek PersegiPanjang dengan nilai panjang dan lebar yang valid
        persegi_panjang = PersegiPanjang(panjang, lebar)

        # Menampilkan informasi objek PersegiPanjang dan hasil perhitungan keliling dan luas
        print(persegi_panjang)  # Menggunakan metode __str__ untuk menampilkan deskripsi objek
        print("Keliling:", persegi_panjang.keliling(), "cm")  # Menampilkan keliling
        print("Luas:", persegi_panjang.luas(), "cm²")  # Menampilkan luas

    # Menangkap dan menampilkan pesan kesalahan jika input tidak valid
    except ValueError as e:
        print("Error:", e)

# Menjalankan fungsi main() hanya jika file ini dijalankan sebagai program utama
if __name__ == "__main__":
    main()
