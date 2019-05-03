# Mengecek Ketersediaan Delivery Order

## A. INPUT

* Data delivery order yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/delivery-order/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek delivery order.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Delivery Order**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data delivery order yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/delivery-order/tombol-check.png)

## C. OUTPUT

* Status dari delivery order akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/delivery-order/status-ready-to-transfer.png)

* Status dari delivery order akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/delivery-order/status-partial.png)

* Status dari delivery order tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/delivery-order/status-waiting.png)
