
# Setup Mint Bot di Termux

## 1. Update & Upgrade Termux
```bash
pkg update && pkg upgrade
```

## 2. Install Dependencies
```bash
pkg install nodejs-lts git unzip nano
```

## 3. Pindahkan File `mint-bot.zip` ke HP
Pastikan file `mint-bot.zip` sudah ada di HP.

## 4. Ekstrak File
Masuk ke folder tempat file berada, misalnya di folder **Downloads**:
```bash
cd ~/storage/downloads
unzip mint-bot.zip
```

## 5. Masuk ke Folder `mint-bot`
```bash
cd mint-bot
```

## 6. Install Package
```bash
npm install
```

## 7. Salin File `.env`
```bash
cp .env.example .env
```

## 8. Edit File `.env`
Gunakan `nano` untuk mengedit:
```bash
nano .env
```
Lalu ubah dan isi satu per satu sesuai kebutuhan.

### Contoh:
```env
RPC_URL=https://rpc.ankr.com/eth
```
Ganti nilai variabel sesuai pengaturan yang diperlukan.
