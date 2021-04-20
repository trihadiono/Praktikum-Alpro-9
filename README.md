# Praktikum-Alpro-9
List
#NAMA: Tri Hadiono
#NIM: 71200536
#UNIVERSITAS KRISTEN DUTA WACANA
REFERENSI : MODUL

def daftarnilai(na,nip,nik):
    cetak='===============DAFTAR NILAI PENJAS ORKES===============\n'
    for data in range(len(na)):
        cetak+='Nama: '+na[data]+' | Nilai Pengetahuan: '+str(nip[data])+' | Nilai Praktek: '+str(nik[data])+'\n'
    print(cetak)
    
nama=['Andre','Beni','Budi','Bayu','Cahyo','Dani','Edward','Faisal',]
peng=['80','85','75','77','78','78','87','82']
prak=[87,85,80,80,78,77,88,84]
daftarnilai(nama, peng, prak)
