# CSS Border-Box Experiment
⚠️ Disarankan menggunakan handphone / layar kecil untuk melihat perbedaan perilaku layout secara lebih jelas.

## Project ini adalah eksperimen sederhana tentang:
```
box-sizing: border-box;
```
dan bagaimana properti tersebut mempengaruhi ukuran element di CSS.

Penjelasan

.box-1

Contoh element tanpa menggunakan:
```
box-sizing: border-box;
```
Karena masih menggunakan default:
```
box-sizing: content-box;
```
maka:
```
width + padding
```
akan dihitung terpisah.

Akibatnya ukuran total element menjadi lebih besar dan bisa menyebabkan:
- layout melebar
- overflow
- keluar layar (terutama di handphone)

.box-2

Contoh element yang menggunakan:
```
box-sizing: border-box;
```
Pada mode ini:

width sudah termasuk padding dan border

sehingga ukuran element tetap rapi, pas, dan tidak meleber keluar container.

## Kesimpulan

border-box membuat perhitungan ukuran element menjadi lebih mudah diprediksi dan lebih aman untuk responsive layout.
