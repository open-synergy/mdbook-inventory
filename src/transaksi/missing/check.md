# Mengecek Ketersediaan Missing

## A. INPUT

* Data missing yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/missing/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek missing.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Missing**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data missing yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form apabila user ingin melakukan pengecekan.

![](../../img/missing/tombol-check.png)


## C. OUTPUT

* Status dari Missing akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/missing/status-ready-to-transfer.png)

* Status dari Missing akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/missing/status-partial.png)

* Status dari Missing tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/missing/status-waiting.png)
