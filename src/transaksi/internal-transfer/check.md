# Mengecek Ketersediaan Internal Transfer

## A. INPUT

* Data internal transfer yang akan dicek harus memiliki status **Waiting Availability**.

![](../../img/internal-transfer/status-waiting.png)

* User yang akan mengecek harus memiliki akses untuk mengecek internal transfer.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Internal Transfer**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data internal transfer yang akan dicek. Abaikan jika data sudah dibuka.
3. Klik tombol **Check Availability** pada bagian atas-kiri form.

![](../../img/internal-transfer/tombol-check.png)

## C. OUTPUT

* Status dari Internal Transfer akan berubah menjadi **Ready To Transfer** apabila semua produk tersedia.

![](../../img/internal-transfer/status-ready-to-transfer.png)

* Status dari Internal Transfer akan berubah menjadi **Partially Available** apabila hanya sebagian produk yang tersedia.

![](../../img/internal-transfer/status-partial.png)

* Status dari Internal Transfer tetap **Waiting Availability** apabila produk tidak tersedia.

![](../../img/internal-transfer/status-waiting.png)
