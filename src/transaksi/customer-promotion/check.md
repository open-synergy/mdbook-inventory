# Mengecek Ketersediaan Customer Promotion

## A. INPUT

* Data customer promotion yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/customer-promotion/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek customer promotion.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Customer Promotion**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data customer promotion yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/customer-promotion/tombol-check.png)

## C. OUTPUT

* Status dari customer promotion akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/customer-promotion/status-ready-to-transfer.png)

* Status dari customer promotion akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/customer-promotion/status-partial.png)

* Status dari customer promotion tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/customer-promotion/status-waiting.png)
