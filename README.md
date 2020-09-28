<h1 align="center">

  <br>
  KryPtoN WhatsApp Bot
  <br>
</h1>

<h3 align=center>A multipurpose whatsapp bot built with <a href="https://github.com/pedroslopez/whatsapp-web.js">whatsapp-web.js</a></h3>

For English on here : <a href="https://github.com/Kry9toN/KryPtoN-WhatsApp-Bot/blob/master/README_EN.MD"> English </a>
<div align=center>


  <a href="https://github.com/pedroslopez/whatsapp-web.js">
    <img src="https://img.shields.io/badge/whatsapp--web.js-V.1.7%205-green?style=flat&logo=npm" alt="shield.png">

  <a href="https://github.com/Kry9toN">
    <img src="https://img.shields.io/badge/license-GNU%20GPL%20v3-green" alt="shield.png">
  </a>

</div>

<p align="center">
  <a href="#features">Features</a>
  •
  <a href="#installation">Installation</a>
  •
  <a href="#set-up">Set Up</a>
  •
  <a href="#colors">Colors</a>
  •
  <a href="#license">License</a>
  •
  <a href="#credits">Credits</a>
</p>

### Install

Clone project ini

```bash
> git clone https://github.com/Kry9toN/KryPtoN-WhatsApp-Bot
> cd KryPtoN-WhatsApp-Bot

```

Install dependencies:

```bash
> npm i
```
jangan lupa install ffmpeg sama wget 

kalo kelen pake rdp windows , jan lupa download binary penunjang
dibawah ini
<a href="https://drive.google.com/file/d/1SugE8vjfOyyW3VTRqsxlW_GJh6EKQ19X/view?usp=drivesdk"> Download </a>

pindahin folder ffmpeg ke `C:\`
dan file wget.exe ke `system32`

add juga path ffmpeg di environtment variable nya
agar bisa dipanggil di cmd 
path ffmpeg nya yaitu
```batch
C:\ffmpeg\bin

```

kalo kelen pengguna linux , jangan lupa ganti path ffmpeg pada fitur youtube mp3 
jadi `/usr/bin/ffmpeg`

dan jangan lupa ubah path chrome nya
jadi 
`/usr/bin/google-chrome-stable`

### Usage
1. menjalankan bot

```bash
> node index.js
```

kalo status bot nya udah berjalan , silahkan scan qr nya 
di aplikasi whatsapp

### Fitur 
ketik !menu untuk menampilkan fitur

 Feature  | Status |
| ------------- | ------------- |
| Facebook Download | Oke|
| Tiktok Downlod | Soon |
| WhatsAnime | Oke |
| Youtube Mp3|  Oke|
| Wiki|  Oke|
| Text To Voice|  Oke|
| Youtube MP4|  Oke|
| Horoscope menu|  Oke|

dan masih banyak lagi

### Bot Whatsapp Command 

## Admin Command
( Hanya admin )

- `!promote`: Buat ngejadiin member sebagai admin
- `!kick`: Kick member
- `!demote`: Hapus status admin
- `!desc`: Ubah deskripsi grup
- `!judul`: Ubah judul grup

## Download Command

  - `!ytmp3 [URL] `: Download Youtube and Convert to mp3
  - `!yt [URL]`: Download Youtube Mp4
  - `!fb [URL]`: Download Facebook Videos
  - `!tiktok [URL]`: Download Tiktok Videos
  - `!ig [URL]`: Download Instagram Videos

## Fun Mode Command
  - `!play nama lagu` : memutar musik dari youtube berdasarkan kata kunci
  - `!nama text`: Arti nama
  - `!pasangan text & text `: Cek kecocokan pasangan
  - `!tts text`: Convert text to voice
  - `ptl1` : Random gambar gambar cewe cantik
  - `ptl2` : Random gambar gambar cowo gans 
  - `randomanime` : Random gambar gambar anime
  - `!searchimage` : Pencarian gambar

## Educational Command
  - `!fakta` : random fakta
  - `!brainly`: Convert text to voice
  - `!wiki`: cari apapun di wiki
  - `!tts`: Convert text to voice

Jika ingin menambah fitur silakan pull req atau chat di telegram :

On : <a href="https://t.me/Kry9toN"> Telegram</a>

## Support Me :)

Mohon jangan di jual lagi ya source ini :)

ngopi kuy :P
<a href="https://saweria.co/donate/Kry9toN"><img width ="100" height="100" src="https://www.pngmart.com/files/7/Donation-Transparent-PNG.png" widht ="350" align="center" height="350"></a>
