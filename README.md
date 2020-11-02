## Pertemuan 5 - Latihan
Buatlah program untuk menginputkan biodata terdiri dari nama lengkap, nama panggilan, NPM, tempat lahir, tanggal lahir, telepon, alamat.
![soal 5](assets/img/pertemuan-5/1.png)

berikut [source code](assets/tugas-5.py) nya:

``` python
namalengkap = input("Please enter your full name : ") 
namapanggilan = input("Please enter nickname : ")  
npm = int(input("Please enter your NPM : "))
tempatlahir = input("Please enter place of birth : ") 
umur = int(input("Please enter year of birth : "))
alamat = input("Please enter your address : ") 
telepon = int(input("Please enter your phone number : "))

print("\n\n Assalamu'alaikum. ")
print("\n Let me introduce my self, my name is", namalengkap , "but you can call me", namapanggilan , "my NPM", npm , "I was born in", tempatlahir , "and iam", umur , "years old, I am very glad if you want to invite my house in", alamat , "So, don't forget to call me before with the number", telepon , "\n\n Thank you ")
```


