# Apa itu NVM?

NVM merupakan singkatan dari Node Version Manager. Menurut website Petani Kode, NVM adalah sebuah program yang akan membantu kita menggunakan lebih dari satu versi Nodejs di dalam satu komputer.

# Cara Menginstal NVM
### Install & Update Script
Berikut ini merupakan script yang digunakan untuk menginstall nvm dan juga dapat digunakan untuk mengupdate versi nvm.

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
Setelah proses instalasi atau update selesai, silahkan reboot komputer anda.
### Mengecek versi NVM
```
nvm -v
```

# Cara Menggunakan NVM
### Melihat seluruh versi Nodejs
```
nvm ls-remote
```
### Melihat versi Nodejs yang terinstal
```
nvm ls
```
### Cara menginstall Nodejs versi terakhir (Latest Version)
```
nvm install node
```
### Cara menginstall Nodejs berdasarkan versi
```
nvm install 16.17.0
```
### Cara mengubah versi Nodejs yang ingin digunakan
```
nvm use 16.17.0
```
### Cara Mengecek versi Nodejs yang digunakan saat ini
```
node -v
```