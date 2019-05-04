# Mengecek Ketersediaan Interwarehouse Out

## A. INPUT

* Data inter-warehouse out yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/interwarehouse-out/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek inter-warehouse out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Inter-Warehouse Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data inter-warehouse out yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/interwarehouse-out/tombol-check.png)

## C. OUTPUT

* Status dari inter-warehouse out akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/interwarehouse-out/status-ready-to-transfer.png)

* Status dari inter-warehouse out akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/interwarehouse-out/status-partial.png)

* Status dari inter-warehouse out tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/interwarehouse-out/status-waiting.png)
