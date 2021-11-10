# Tugas Python5
## 1. Aplikasi Terbilang
### Source Code

```py
numbers = input("Masukkan angka : ")

number_mapping = {
    "1":"Satu",
    "2":"Dua",
    "3":"Tiga",
    "4":"Empat",
    "5":"Lima",
    "6":"Enam",
    "7":"Tujuh",
    "8":"Delapan",
    "9":"Sembilan",
}
output = ""
for n in numbers:
    terbilang = number_mapping.get(n, "Tidak Terdefinisi")
    output = output + terbilang + " "
print(output)
```
### VS Code & Output
![Z1](https://user-images.githubusercontent.com/93004722/141076447-73de71b4-169d-4ee6-9f56-9d9e58985f7b.PNG)

## 2. Emoji Converter
### Source Code

```py
kalimat = input(">>>  : ")

emoji_mapping = {
    ":-|": "😶",
    ":A": "😡",
    "XD": "🤣"

}
output = ""
words = kalimat.split(" ")
for w in words:
    output = output+emoji_mapping.get(w , w)+ " "
print(output)
```
### VS Code & Output
![Z2](https://user-images.githubusercontent.com/93004722/141080489-e4fa8eac-4b7d-4da3-8313-df642d4b8b59.PNG)

## 3. Fungsi
### Source Code

```py
def name():
    print("Abigail Perkasa")

print("Hallo")
name() 
print("Orang")    

# output sesuai urutan
```
### VS Code & Output
![Z3](https://user-images.githubusercontent.com/93004722/141086922-743d6fa4-a7b2-44d4-99d4-785937075e7f.PNG)

## 4. Parameter Fungsi
### Source Code

```py
nomor2 = [4, 6, 3, 5, 2]

nomor3 = 0

for nomor in nomor2:
    nomor3 = nomor3 + nomor

print(nomor3)
```
### VS Code & Output
![A4](https://user-images.githubusercontent.com/93004722/140851493-31cf1c3f-e89b-4356-8742-0555e56d4d33.PNG)

## 5. Keyword Argument
### Source Code

```py
nomor_nomor = [5,4,7,3,1]

nomormaks = max(nomor_nomor)
print(nomormaks)

#2
nomor_nomor.sort()
nomormaks = nomor_nomor[-1]
print(nomormaks)

#3
nomormaks = nomor_nomor[0]
for nomor in nomor_nomor:
    if nomor > nomormaks:
        nomormaks = nomor
print(nomormaks)
```
### VS Code & Output
![A5](https://user-images.githubusercontent.com/93004722/140852227-71727321-85ff-4220-a84e-9e97fa0d565c.PNG)

## 6. Return Value
### Source Code

```py
# Perbedaan dengan list, isi tuple tidak bisa diubah

angka = (6, 3, 7, 4, 5)
print(angka[2])
```
### VS Code & Output
![A6](https://user-images.githubusercontent.com/93004722/140853358-2e1289bc-e077-4d21-a96e-100aa17af743.PNG)

