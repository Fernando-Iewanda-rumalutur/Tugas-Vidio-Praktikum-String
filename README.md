# Tugas-Vidio-Praktikum-String
#menghitung jumlah subyek pada kalimat 
#mengubah subyek menjadi huruf kapital #mengubah subyek menjadi huruf non kapital 
#mengubah huruf pertama pada suatu kalimat menjadi huruf kapital  
nama=input("masukkan nama anda:") 
nim= int(input("masukkan nim anda:")) 
kalimat1 = input("masukkan kalimat pertama:") 
kalimat2 = input("masukkan kalimat kedua:") 
jumlah = len(kalimat1)+len(kalimat2) 
kapital = kalimat1.upper() 
nonkapital = kalimat2.lower() 
subyek_benar1= kalimat1.capitalize() 
subyek_benar2= kalimat2.capitalize() 
if jumlah>20:     
  print(kapital)     
  print(nonkapital)     
  print(subyek_benar1)     
  print(subyek_benar2) 
elif jumlah<20:     
  print("jumlah subyek anda adalah",jumlah)     
  print("jumlah harus lebih dari 20 jika ingin mengeluarkan kalimar1 dan kalimat2")
