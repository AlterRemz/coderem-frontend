# CSS Nowrap vs Wrap Experiment

⚠️ Disarankan menggunakan handphone atau layar kecil untuk melihat perbedaannya dengan lebih jelas.

Eksperimen sederhana untuk memahami perbedaan antara:
```
flex-wrap: nowrap;
```
dan
```
flex-wrap: wrap;
```
## Nowrap
### Container 1
Contoh container tanpa menggunakan:
```
flex-wrap: wrap;
```
Karena default flexbox adalah:
```
flex-wrap: nowrap;
```
maka semua box dipaksa tetap berada dalam satu baris.

Akibatnya:
- box menyempit
- ukuran berubah
- terlihat gepeng
- layout bisa terasa sesak

## Wrap
### Container 2
Contoh container menggunakan:
```
flex-wrap: wrap;
```
Jika ruang sudah tidak cukup, box akan otomatis turun ke baris berikutnya.

Hasilnya:
- layout lebih rapi
- ukuran box tetap terjaga
- item lebih nyaman dilihat
- lebih cocok untuk responsive layout

## Tujuan Eksperimen

Eksperimen ini dibuat untuk memahami bagaimana perilaku flexbox saat ruang container mulai mengecil, terutama pada layar kecil seperti handphone 📱
