# Memaksa Ketersediaan Interwarehouse Out

## A. INPUT

* Data interwarehouse out yang akan dipaksa ketersediannya harus memiliki status **Waiting Availability** atau **Partially Available**

![](../../img/interwarehouse-out/status-waiting.png)

![](../../img/interwarehouse-out/status-partial.png)

* User yang akan memaksa ketersediaan harus memiliki akses untuk mengecek interwarehouse out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Interwarehouse Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data interwarehouse out yang akan dipaksa ketersediaanya. Abaikan jika data sudah dibuka.
3. Klik tombol **Force Availability** pada bagian atas-kiri form.

![](../../img/interwarehouse-out/tombol-force.png)

## C. OUTPUT

* Status dari Interwarehouse Out akan berubah menjadi **Ready To Transfer**.

![](../../img/interwarehouse-out/status-ready-to-transfer.png)
