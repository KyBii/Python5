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
def Player(nama , age):
    print(f"Welcome {nama} - {age}")



Player("Abigail",19)
Player("Bocil",19)

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
![Z4](https://user-images.githubusercontent.com/93004722/141120040-f3604d0f-83e2-4bf8-bf90-b5bc61fa6af1.PNG)

## 5. Keyword Argument
### Source Code

```py
def hello(nama, age):
    print(f"Status {nama} - {age}")
    print("Welcome to new game")


print("Link Start")
hello(age = 19, nama = "Abigail") #digunakan pada saat tertentu agar mudah dipahami
print("Game Over")

# output sesuai urutan
```
### VS Code & Output
![Z5](https://user-images.githubusercontent.com/93004722/141122314-58c380da-7839-4941-a2a7-00edd4523648.PNG)

## 6. Return Value
### Source Code

```py
def pembagian(a, b):
  return  a / b

hasil = pembagian (70, 7)
print(hasil)
```
### VS Code & Output
![Z6](https://user-images.githubusercontent.com/93004722/141122776-185685d8-e73e-48ac-ad87-4ec065c63dd5.PNG)
