# Merealisasi Rental Supplier Out

## A. INPUT

* Data rental supplier out yang akan direalisasi harus memiliki status **Ready To Transfer**.

![](../../img/rental-supplier-out/status-ready-to-transfer.png)

* User yang akan merealisasi harus memiliki akses untuk merealisasi rental supplier out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operations -> (Nama Gudang) -> Rental Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data rental supplier out yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.

![](../../img/rental-supplier-out/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/rental-supplier-out/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. <a name="l5">Untuk</a> setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Merealisasi Produk Pada Rental Supplier Out](./transfer-produk.md).
6. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/rental-supplier-out/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari rental supplier out akan berubah menjadi **Transfered**

![](../../img/rental-supplier-out/status-transfered.png)
