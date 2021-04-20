# Praktikum-Alpro-9
List
#NAMA: Tri Hadiono
#NIM: 71200536
#UNIVERSITAS KRISTEN DUTA WACANA
REFERENSI : MODUL

def pemetaanList(na, no, um):
    cetak='===============Daftar Siswa===============\n'    
    for data in range(len(na)):
        cetak+='Nama: '+na[data]+' | NIS: '+no[data]+' | Umur: '+str(um[data])+'\n'
    print(cetak)

nama=['Angel','Riani','Vista','Fani']
nis=['17305','17306','17307','17308']
umur=[19,22,20,21]
pemetaanList(nama, nis, umur)
