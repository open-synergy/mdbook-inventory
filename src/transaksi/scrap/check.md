# Mengecek Ketersediaan Scrap

## A. INPUT

* Data scrap yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/scrap/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek scrap.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Scrap**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data scrap yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form apabila user ingin melakukan pengecekan.

![](../../img/scrap/tombol-check.png)

## C. OUTPUT

* Status dari Scrap akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/scrap/status-ready-to-transfer.png)

* Status dari Scrap akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/scrap/status-partial.png)

* Status dari Scrap tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/scrap/status-waiting.png)
