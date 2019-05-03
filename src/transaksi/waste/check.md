# Mengecek Ketersediaan Waste

## A. INPUT

* Data waste yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/waste/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek waste.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Waste**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data waste yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form apabila user ingin melakukan pengecekan.

![](../../img/waste/tombol-check.png)


## C. OUTPUT

* Status dari Waste akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/waste/status-ready-to-transfer.png)

* Status dari Waste akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/waste/status-partial.png)

* Status dari Waste tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/waste/status-waiting.png)
