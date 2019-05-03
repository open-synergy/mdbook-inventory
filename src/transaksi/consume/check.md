# Mengecek Ketersediaan Consume

## A. INPUT

* Data consume yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/consume/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek consume.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Consume**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data consume yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/consume/tombol-check.png)

## C. OUTPUT

* Status dari Consume akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/consume/status-ready-to-transfer.png)

* Status dari Consume akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/consume/status-partial.png)

* Status dari Consume tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/consume/status-waiting.png)
