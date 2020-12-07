# Merealisasi Lease Customer Out

## A. INPUT

* Data lease customer out yang akan direalisasi harus memiliki status **Ready To Transfer**.

![](../../img/lease-customer-out/status-ready-to-transfer.png)

* User yang akan merealisasi harus memiliki akses untuk merealisasi lease customer out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operations -> (Nama Gudang) -> Lease Customer Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data lease customer out yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.

![](../../img/lease-customer-out/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/lease-customer-out/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. <a name="l5">Untuk</a> setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Merealisasi Produk Pada Lease Customer Out](./transfer-produk.md).
6. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/lease-customer-out/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari lease customer out akan berubah menjadi **Transfered**

![](../../img/lease-customer-out/status-transfered.png)
