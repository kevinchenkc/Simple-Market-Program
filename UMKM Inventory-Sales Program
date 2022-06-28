import math as m
stok={
        "susucair":{"nama":"Susu Cair","kemasan":"Kotak 1L","kategori":"Minuman","unit":10,"harga":20000},
        "margarin":{"nama":"Margarin","kemasan":"Kotak 200gr","kategori":"Bahan Masak","unit":5,"harga":15000},
        "gula":{"nama":"Gula","kemasan":"Pouch 500gr","kategori":"Bahan Masak","unit":30,"harga":12000},
        "minyakgrg":{"nama":"Minyak Grg","kemasan":"Pouch 2L","kategori":"Bahan Masak","unit":90,"harga":48000},
        "susububuk":{"nama":"Susu Bubuk","kemasan":"Kaleng 1kg","kategori":"Minuman","unit":23,"harga":100000},
        "kopi":{"nama":"Kopi","kemasan":"Bks 5 Sachet","kategori":"Minuman","unit":20,"harga":5000},
        "rotitawar":{"nama":"Roti Tawar","kemasan":"1 Sisir","kategori":"Makanan","unit":12,"harga":17000},
        "beras":{"nama":"Beras","kemasan":"Sak 10kg","kategori":"Makanan","unit":7,"harga":140000},
    }
kode_pegawai="13579"
cart=[]

def tampil_stok_semua():
    if len(stok)==0:
        print("Tidak ada stok yang tersedia")
    else:
        print("Daftar Barang \n\t  |Nama Barang \t| Kemasan \t| Kategori \t| Stok \t| Harga/unit")
        for key in stok.keys():
            print("\t  |{} \t| {} \t| {} \t| {} \t| {}".format(stok[key]["nama"],stok[key]["kemasan"],stok[key]["kategori"],stok[key]["unit"],stok[key]["harga"]))

def list_stok():    
    while len(stok)==0:
        print("Tidak ada stok yang tersedia")
        break

    else:
        while True:
            pilih_tampilan=int(input("-----TAMPILAN STOK----- \n1. Tampilkan Per Kategori  \n2. Tampilkan Semua \n3. Cari Dengan Keyword \n4. Kembali ke Menu Utama \n\nTampilan Stok Yang Ingin Dipilih (1-4): "))
            if pilih_tampilan==1:
                pilih_kategori=int(input("-----PILIHAN KATEGORI----- \n1. Bahan Masak  \n2. Minuman  \n3. Makanan \n4. Kembali ke Menu Utama \n\nKategori Yang Ingin Ditampilkan (1-4): "))
                if pilih_kategori==1:
                    print("Daftar Barang \n\t  |Nama Barang \t| Kemasan \t| Kategori \t| Qty \t| Harga/unit")
                    for key in stok.keys():
                        if stok[key]["kategori"]=="Bahan Masak":
                            print("\t  |{} \t| {} \t| {} \t| {} \t| {}".format(stok[key]["nama"],stok[key]["kemasan"],stok[key]["kategori"],stok[key]["unit"],stok[key]["harga"]))
                        else:
                            continue
        
                elif pilih_kategori==2:
                    print("Daftar Barang \n\t  |Nama Barang \t| Kemasan \t| Kategori \t| Qty \t| Harga/unit")
                    for key in stok.keys():
                        if stok[key]["kategori"]=="Minuman":
                            print("\t  |{} \t| {} \t| {} \t| {} \t| {}".format(stok[key]["nama"],stok[key]["kemasan"],stok[key]["kategori"],stok[key]["unit"],stok[key]["harga"]))
                        else:
                            continue

                elif pilih_kategori==3:
                    print("Daftar Barang \n\t  |Nama Barang \t| Kemasan \t| Kategori \t| Qty \t| Harga/unit")
                    for key in stok.keys():
                        if stok[key]["kategori"]=="Makanan":
                            print("\t  |{} \t| {} \t| {} \t| {} \t| {}".format(stok[key]["nama"],stok[key]["kemasan"],stok[key]["kategori"],stok[key]["unit"],stok[key]["harga"]))
                        else:
                            continue

                elif pilih_kategori!=1 and pilih_kategori!=2 and pilih_kategori!=3:
                    break

            elif pilih_tampilan==2:
                tampil_stok_semua()

            elif pilih_tampilan==3:
                item_cari=input("Masukkan kata kunci barang yang ingin ditampilkan: ")
                print("Daftar Barang \n\t  |Nama Barang \t| Kemasan \t| Kategori \t| Qty \t| Harga/unit")
                for key in stok.keys():
                    if item_cari.lower() in stok[key]["nama"].lower():
                        print("\t  |{} \t| {} \t| {} \t| {} \t| {}".format(stok[key]["nama"],stok[key]["kemasan"],stok[key]["kategori"],stok[key]["unit"],stok[key]["harga"]))
                    else:
                        continue

            elif pilih_tampilan==4:
                break
        
            else:
                print("Menu yang anda pilih tidak tersedia. Silahkan dicoba lagi.")

def tambah_stok():
    while True:
        input_nama=input("Masukkan Nama Produk yang Ingin Ditambahkan: ")
        item_baru=input_nama.replace(" ","")
        while len(input_nama)>10:
            print("Maks. Karakter 10, mohon input ulang.")
            input_nama=input("Masukkan Nama Produk yang Ingin Ditambahkan: ")
            item_baru=input_nama.replace(" ","")
        if item_baru.lower() not in stok.keys():
            input_kemasan=input("Masukkan Kemasan dari Produk Baru: ")
            while len(input_kemasan)>10:
                print("Maks. Karakter 10, mohon input ulang.")
                input_kemasan=input("Masukkan Kemasan dari Produk Baru: ")
            input_kategori=input("Masukkan Kategori dari Produk Baru: ")
            while len(input_kategori)>10:
                print("Maks. Karakter 10, mohon input ulang.")
                input_kategori=input("Masukkan Kategori dari Produk Baru: ")
            input_qty=float(input("Masukkan Jumlah Stok dari Produk Baru: "))
            input_harga=int(input("Masukkan Harga per Unit dari Produk Baru: "))
            checker2=input(f"Apakah anda yakin ingin menambahkan produk {input_nama} {input_kategori} dengan jumlah {m.ceil(input_qty)} dan harga {input_harga}? (Y/N): ")
            if checker2!="Y".lower():
                break
            else:
                stok[item_baru.lower()]={"nama":input_nama.capitalize(),"kemasan":input_kemasan.capitalize(),"kategori":input_kategori.capitalize(),"unit":m.ceil(input_qty),"harga":input_harga}
                tampil_stok_semua()
                break
        else:
            print("Kami sudah mempunyai item yang sama dengan input anda, tidak dapat menambahkan item")
            break

def update_stok():
    update_stok=int(input("-----UPDATE STOK----- \n1. Update Produk \n2. Delete Produk \n3. Kembali ke Menu Utama \n\nUpdate yang Ingin Dipilih (1-3): "))
    if update_stok==1:
        tampil_stok_semua()
        item_updatestok=input("Masukkan nama item yang mau diupdate: ")
        item_update=item_updatestok.replace(" ","")
        while item_update.lower() in stok.keys():
            jenis_update=int(input("-----UPDATE FIELD----- \n1. Nama Barang \n2. Kemasan \n3. Kategori \n4. Unit \n5. Harga/unit \n6. Kembali ke Menu Utama \nField yang ingin diupdate(1-6): "))
            if jenis_update==1:
                item_baru=input("Masukkan nama item baru: ")
                nama_baru=item_baru.replace(" ","")
                while len(item_baru)>10:
                    print("Maks. Karakter 10, mohon input ulang.")
                    item_baru=input("Masukkan nama item baru: ")
                    nama_baru=item_baru.replace(" ","")
                while nama_baru.lower() in stok.keys():
                    print("Nama Produk Sudah Ada, Masukkan Nama Baru")
                    item_baru=input("Masukkan nama item baru: ")
                    nama_baru=item_baru.replace(" ","")
                checker3=input(f"Apakah anda yakin ingin menambahkan update nama {item_updatestok} menjadi {item_baru}? (Y/N): ")
                if checker3!="Y".lower():
                    break
                else:
                    stok[nama_baru.lower()]=stok[item_update.lower()]
                    del stok[item_update.lower()]
                    stok[nama_baru.lower()]["nama"]=item_baru.capitalize()
                    tampil_stok_semua()
                    break
            elif jenis_update==2:
                kemasan_baru=input("Masukkan detail kemasan baru: ")
                while len(kemasan_baru)>10:
                   print("Maks. Karakter 10, mohon input ulang.") 
                   kemasan_baru=input("Masukkan detail kemasan baru: ")
                checker4=input(f"Apakah anda yakin ingin menambahkan update kemasan {item_updatestok} menjadi {kemasan_baru}? (Y/N): ")
                if checker4!="Y".lower():
                    break
                else:
                    stok[item_update.lower()]["kemasan"]=kemasan_baru.capitalize()
                    tampil_stok_semua()
                    break
            elif jenis_update==3:
                kategori_baru=input("Masukkan detail kategori baru: ")
                while len(kategori_baru)>10:
                   print("Maks. Karakter 10, mohon input ulang.") 
                   kategori_baru=input("Masukkan detail kategori baru: ")
                checker5=input(f"Apakah anda yakin ingin menambahkan update kategori {item_updatestok} menjadi {kategori_baru}? (Y/N): ")
                if checker5!="Y".lower():
                    break
                else:
                    stok[item_update.lower()]["kategori"]=kategori_baru.capitalize()
                    tampil_stok_semua()
                    break
            elif jenis_update==4:
                unit_baru=int(input("Masukkan jumlah stok baru: "))
                checker6=input(f"Apakah anda yakin ingin menambahkan update jumlah stok {item_updatestok} menjadi {m.ceil(unit_baru)}? (Y/N): ")
                if checker6!="Y".lower():
                    break
                else:
                    stok[item_update.lower()]["unit"]=unit_baru
                    tampil_stok_semua()
                    break
            elif jenis_update==5:
                harga_baru=int(input("Masukkan harga produk baru: "))
                checker7=input(f"Apakah anda yakin ingin menambahkan update harga {item_updatestok} menjadi {m.ceil(harga_baru)}? (Y/N): ")
                if checker7!="Y".lower():
                    break
                else:
                    stok[item_update.lower()]["harga"]=harga_baru
                    tampil_stok_semua()
                    break
            else:
                break
        else:
            print("Item yang anda masukkan tidak ada di list, update tidak bisa dilakukan.")
    elif update_stok==2:
        tampil_stok_semua()
        input_delete=input("Masukkan nama produk yang ingin dibuang: ")
        checker8=input(f"Apakah anda yakin ingin membuang seluruh informasi untuk produk {input_delete}? (Y/N): ")
        while checker8!="Y".lower():
            break
        else:
            nama_delete=input_delete.replace(" ","")
            del stok[nama_delete.lower()]
            tampil_stok_semua()
    
    while update_stok==3:
        break

    if update_stok==1 and update_stok==2 and update_stok==3:
        print("Menu yang anda pilih tidak tersedia. Silahkan dicoba lagi.")

def belanja():
    tampil_stok_semua()
    while True:
        input_beli=input("Masukkan Nama Barang Yang Ingin Dibeli: ")
        nama_beli=input_beli.replace(" ","")
        if nama_beli.lower() not in stok.keys():
            print("Barang yang ingin dibeli tidak ditemukan")
        else:
            qty_beli=float(input("Masukkan Jumlah Yang Ingin Dibeli: "))
            if qty_beli>stok[nama_beli.lower()]["unit"]:
                print("Stok tidak cukup. Stok {} sisa {}".format(stok[nama_beli.lower()]["nama"],stok[nama_beli.lower()]["unit"]))
            elif qty_beli<=0:
                print("Jumlah pembelian tidak boleh kurang dari 1")
            else:
                cart.append([stok[nama_beli.lower()]["nama"],stok[nama_beli.lower()]["kemasan"],qty_beli,stok[nama_beli.lower()]["harga"],stok[nama_beli.lower()]["nama"].replace(" ","")])
            print("Keranjang Belanja \n\t  |Nama Barang \t| Kemasan \t| Qty \t| Harga \t| Total Harga")
            for item in cart:
                print("\t  |{} \t| {} \t| {} \t| {}    \t| {}".format(item[0], item[1], m.ceil(item[2]), item [3], m.ceil(item[2] * item[3])))
            checker=input("Apakah Ingin Membeli Item Lain? (Y/N): ")
            if checker.upper()!="Y":
                break
    while len(cart)==0:
        break    
    
    else:
        print("Keranjang Belanja \n\t  |Nama Barang \t| Kemasan \t| Qty \t| Harga \t| Total Harga")
        total=0
        for item in cart:
            print("\t  |{} \t| {} \t| {} \t| {}    \t| {}".format(item[0], item[1], m.ceil(item[2]), item[3], m.ceil(item[2] * item[3])))
            total+=item[2]*item[3]
        while True:
            print('Total Yang Harus Dibayar = {}'.format(m.ceil(total)))
            input_uang = int(input('Masukkan jumlah uang : '))
            if input_uang>total:
                kembali = input_uang - total
                print('Terima kasih sudah berbelanja di Toko Kelontong JSDC \n\nUang kembalian anda : {}'.format(m.ceil(kembali)))
                for item in cart :
                    stok[item[4].lower()]["unit"] -= m.ceil(item[2])
                cart.clear()
                break
            elif input_uang==total:
                print('Terima kasih sudah berbelanja di Toko Kelontong JSDC')
                for item in cart :
                    stok[(item[4].lower())]["unit"] -= m.ceil(item[2])
                cart.clear()
                break
            else :
                kekurangan = total - input_uang
                print('Uang anda kurang sebesar {}'.format(m.ceil(kekurangan)))
        
while True:
    user_input=int(input("--------------------------------------\nSELAMAT DATANG DI TOKO KELONTONG JCDS\n-------------------------------------- \n\nMasuk Sebagai: \n1. Karyawan Toko Kelontong JCDS \n2. Customer \n3. Exit Program \n\nMasukkan Menu Login(1-3): "))
    while user_input==1:
        login_staff=input("Masukkan Kode Pegawai: ")
        if login_staff==kode_pegawai:
            pilih_menu_staff=int(input("------------\nPEGAWAI TOKO\n------------ \n\n-----MAIN MENU----- \n1. Tampilkan Stok Barang \n2. Tambah Barang \n3. Update Stok \n4. Kembali ke Menu Utama \n\nInput Menu Yang Ingin Dipilih (1-4): "))
            if pilih_menu_staff==1:
                list_stok()
            elif pilih_menu_staff==2:
                tambah_stok()
            elif pilih_menu_staff==3:
                update_stok()
            elif pilih_menu_staff!=1 and  pilih_menu_staff!=2 and  pilih_menu_staff!=3 and  pilih_menu_staff!=4:
                print("Menu yang anda pilih tidak tersedia. Silahkan dicoba lagi.")
            else:
                user_input=int(input("--------------------------------------\nSELAMAT DATANG DI TOKO KELONTONG JCDS\n-------------------------------------- \n\nMasuk Sebagai: \n1. Karyawan Toko Kelontong JCDS \n2. Customer \n3. Exit Program \n\nMasukkan Menu Login(1-3): "))
            
        else:
            print("Kode Pegawai yang Dimasukkan Salah. Login Tidak Bisa Dilakukan")
            user_input=int(input("--------------------------------------\nSELAMAT DATANG DI TOKO KELONTONG JCDS\n-------------------------------------- \n\nMasuk Sebagai: \n1. Karyawan Toko Kelontong JCDS \n2. Customer \n3. Exit Program \n\nMasukkan Menu Login(1-3): "))

    while user_input==2:
        pilih_menu_cust=int(input("---------\nPELANGGAN\n---------\n\n-----MAIN MENU----- \n1. Tampilkan Daftar Barang \n2. Belanja \n3. Kembali ke Menu Utama \n\nInput Menu Yang Ingin Dipilih (1-3): "))
        if pilih_menu_cust==1:
            list_stok()
        elif pilih_menu_cust==2:
            belanja()
        elif pilih_menu_cust!=1 and pilih_menu_cust!=2 and pilih_menu_cust!=3:
            print("Menu yang anda pilih tidak tersedia. Silahkan dicoba lagi.")
        else:
            user_input=int(input("--------------------------------------\nSELAMAT DATANG DI TOKO KELONTONG JCDS\n-------------------------------------- \n\nMasuk Sebagai: \n1. Karyawan Toko Kelontong JCDS \n2. Customer \n3. Exit Program \n\nMasukkan Menu Login(1-3): "))    
        
    if user_input!=1 and user_input!=2 and user_input!=3:
        print("Menu yang anda pilih tidak tersedia. Silahkan dicoba lagi.")

    else:
        break
