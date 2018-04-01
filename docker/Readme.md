# Docker

![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Docker_%28container_engine%29_logo.svg/500px-Docker_%28container_engine%29_logo.svg.png)


### Persyaratan Mengikuti Praktikum
		1. Sudah menginstall Ubuntu 16.04/Unix yang lainnya.
		2. Sudah menginstall Docker CE
		3. Sudah menginstall Docker Compose
		4. Pastikan komputer dapat connect ke Internet

## A. Dasar Teori
### 1. Perbedaan _Virtual Machine_ dengan Docker
![](https://i.imgur.com/MJHfm1c.jpg)


### 2. Docker
Docker adalah virtualisasi berbentuk kontainer. Kontainer bekerja lebih efisien daripada virtual mesin, karena yang divirtualisasikan hanya aplikasi dan library yang dibutuhkan saja. Kontainer lebih hemat memory daripada virtual mesin. Untuk memulai menggunakan docker terlebih dahulu mesin docker harus terinstall harus terinstall pada komputer host.



## B. Instalasi

### 1. Instalasi Docker
- Instalasi pada [Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-docker-ce-1)


### C. Getting Started
Untuk mengecek apakah docker sudah terinstall dengan benar silahkan jalankan perintah

    docker run hello-world