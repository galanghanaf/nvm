<a href="https://github.com/nvm-sh/logos"><img alt="nvm project logo" src="https://raw.githubusercontent.com/nvm-sh/logos/HEAD/nvm-logo-color.svg" height="50" /></a>

# Apa itu NVM?

NVM merupakan singkatan dari Node Version Manager. Menurut Petani Kode, NVM adalah sebuah program yang akan membantu kita menggunakan lebih dari satu versi Nodejs di dalam satu komputer.

# Cara Menginstal NVM

### Install & Update Script
## Linux
Berikut ini merupakan script yang digunakan untuk menginstall nvm dan juga dapat digunakan untuk mengupdate versi nvm.

Sumber: https://github.com/nvm-sh/nvm

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
```

```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
```

Setelah proses instalasi atau update selesai, silahkan reboot komputer anda.

## Windows

https://github.com/coreybutler/nvm-windows

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

## Cara Cepat

nvm juga mengijinkan kita menginstal secara instan, hanya dengan beberapa baris code.

```
$ nvm use 16
Now using node v16.9.1 (npm v7.21.1)

$ node -v
v16.9.1

$ nvm use 14
Now using node v14.18.0 (npm v6.14.15)

$ node -v
v14.18.0

$ nvm install 12
Now using node v12.22.6 (npm v6.14.5)

$ node -v
v12.22.6
```
