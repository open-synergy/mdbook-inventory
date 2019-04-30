# Mengecek Ketersediaan Supplier Promotion

## A. INPUT

* Data supplier promotion yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/supplier-promotion/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek supplier promotion.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Supplier Promotion**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data supplier promotion yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form apabila user ingin melakukan pengecekan.

![](../../img/supplier-promotion/tombol-check.png)

## C. OUTPUT

* Status dari supplier promotion akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/supplier-promotion/status-ready-to-transfer.png)

* Status dari supplier promotion akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/supplier-promotion/status-partial.png)

* Status dari supplier promotion tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/supplier-promotion/status-waiting.png)
