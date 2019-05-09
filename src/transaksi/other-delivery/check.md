# Mengecek Ketersediaan Other Delivery

## A. INPUT

* Data other delivery yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/other-delivery/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek other delivery.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Other Delivery**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data other delivery yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/other-delivery/tombol-check.png)

## C. OUTPUT

* Status dari other delivery akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/other-delivery/status-ready-to-transfer.png)

* Status dari other delivery akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/other-delivery/status-partial.png)

* Status dari other delivery tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/other-delivery/status-waiting.png)
