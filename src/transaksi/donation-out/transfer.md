# Merealisasi Donation Out

## A. INPUT

* Data donation out yang akan direalisasi harus memiliki status **Ready To Transfer**.

![](../../img/donation-out/status-ready-to-transfer.png)

* User yang akan merealisasi harus memiliki akses untuk merealisasi donation out.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operations -> (Nama Gudang) -> Donation Out**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data donation out yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.

![](../../img/donation-out/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/donation-out/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. <a name="l5">Untuk</a> setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Merealisasi Produk Pada Donation Out](./transfer-produk.md).
6. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/donation-out/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari donation out akan berubah menjadi **Transfered**

![](../../img/donation-out/status-transfered.png)
