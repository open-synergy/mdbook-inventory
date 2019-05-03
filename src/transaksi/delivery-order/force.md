# Memaksa Ketersediaan Delivery Order

## A. INPUT

* Data delivery order yang akan dipaksa ketersediannya harus memiliki status **Waiting Availability** atau **Partially Available**

![](../../img/delivery-order/status-waiting.png)

![](../../img/delivery-order/status-partial.png)

* User yang akan memaksa ketersediaan harus memiliki akses untuk mengecek delivery order.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Delivery Order**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data delivery order yang akan dipaksa ketersediaanya. Abaikan jika data sudah dibuka.
3. Klik tombol **Force Availability** pada bagian atas-kiri form.

![](../../img/delivery-order/tombol-force.png)

## C. OUTPUT

* Status dari Delivery Order akan berubah menjadi **Ready To Transfer**.

![](../../img/delivery-order/status-ready-to-transfer.png)
