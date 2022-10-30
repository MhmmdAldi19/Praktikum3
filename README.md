# Menghitung luas dan keliling lingkaran menggunakan `Python`

1. Buat File bernama luasKelilingLingkaran.py
2. Berikut Flowchart untuk menghitung luas dan keliling lingkaran

   <img width="625" alt="flow" src="https://user-images.githubusercontent.com/115919203/198866932-1b16aa3d-0a77-4970-8ec8-693977aaa112.png">

4. Lalu Masukan CODE berikut :

    ```python
      # import module math
    import math

    # Variable jariJari menampung nilai input yang dimasukan yaitu berupa string
    jariJari = input('Masukan jari-jari lingkaran :')

    """

    rumus luas & keliling lingkaran
    _____________________________________

    luas     = phi * r^2

    keliling = 2 * phi * r

    _____________________________________

    """

    # convert string to integer
    jariJari = int(jariJari)

    # hitung luas lingkaran
    luas = math.pi * (jariJari * jariJari)

    # hitung luas keliling
    keliling = 2 * math.pi * jariJari

    # output luas & keliling lingkaran
    # .2f => mengambil 2 angka setelah (,)
    print("Berikut Luas lingkaran =  ", format(luas, '.2f'))
    print("Berikut Keliling lingkaran = ", format(keliling, '.2f'))

    ```

4. Ketika dijalankan Inputkan Jari jari dan Berikut Hasil nya

   ![hasil](https://user-images.githubusercontent.com/115919203/198866964-fde45693-f544-46d3-98b7-d62a24deced2.png)

5. Selesai Begitulah cara menghitung luas dan keliling Lingkaran
