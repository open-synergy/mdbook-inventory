# Merealisasi Internal Transfer

## A. INPUT

* Data internal transfer yang akan direalisasi harus memiliki status **Ready To Transfer** atau **Partially Available**.

![](../../img/internal-transfer/status-ready-to-transfer.png)

![](../../img/internal-transfer/status-partial.png)


* User yang akan merealisasi harus memiliki akses untuk merealisasi internal transfer.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Internal Transfer**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data internal transfer yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.

![](../../img/internal-transfer/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/internal-transfer/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. <a name="l5">Untuk</a> setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Realisasi Produk](./transfer-produk.md).
6. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/internal-transfer/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari internal transfer akan berubah menjadi **Transfered**

![](../../img/internal-transfer/status-transfered.png)
