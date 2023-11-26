isim = input ("adınız: ") 
vize = int(input("Vize notunuzu girin: "))
final = int(input("Final notunuzu girin: "))

skor = round(((vize*0.6)+(final*0.4)))
print("Toplam ders notunuz", skor)

if skor > 88:
    print("Harf Notu = AA")
elif skor > 78 and skor <= 88:
    print("Harf Notu BA")
elif skor > 68 and skor <= 78:
    print("Harf Notu BB")
elif skor > 59 and skor <= 68:
    print("Harf Notu CB")
elif skor > 49 and skor <= 59:
    print("Harf Notu CC")
elif skor > 39 and skor <= 49:
    print("Harf Notu DC")
elif skor > 30 and skor <= 39:
    print("Harf Notu DD")
elif skor > 24 and skor <= 30:
    print("Harf Notu FD")
else:	
    print("Harf Notu FF")
