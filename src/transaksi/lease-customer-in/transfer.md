# Merealisasi Lease Customer In

## A. INPUT

* Data lease customer in yang akan direalisasi harus memiliki status **Ready To Transfer**.

![](../../img/lease-customer-in/status-ready-to-transfer.png)

* User yang akan merealisasi harus memiliki akses untuk merealisasi lease customer in.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operations -> (Nama Gudang) -> Lease Customer In**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data lease customer in yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.

![](../../img/lease-customer-in/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/lease-customer-in/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. <a name="l5">Untuk</a> setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Merealisasi Produk Pada Lease Customer In](./transfer-produk.md).
6. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/lease-customer-in/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari lease customer in akan berubah menjadi **Transfered**

![](../../img/lease-customer-in/status-transfered.png)
