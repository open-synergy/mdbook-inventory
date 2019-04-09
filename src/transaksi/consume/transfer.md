# Merealisasi Consume

## A. INPUT

* Data consume yang akan direalisasi harus memiliki status **Ready To Transfer**.
* User yang akan merealisasi harus memiliki akses untuk merealisasi consume.

## B. LANGKAH KERJA

1. Buka menu **Warehouse -> Operation -> (Nama Gudang) -> Consume**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data consume yang akan direalisasikan. Abaikan jika data sudah dibuka.
3. Klik tombol **Transfer** pada bagian atas-kiri form.


![](../../img/consume/tombol-transfer.png)

Pop-up **Enter Transfer Detail** akan muncul

![](../../img/consume/pop-up-enter-transfer-detail.png)

4. Isi **Actual Movement Date**.
5. Untuk setiap produk yang terdapat pada tabel **Product To Move** lakukan prosedur [Realisasi Produk](./transfer-product.md).
6. Apabila serial number ingin dibuat secara otomatis klik tombol **Generate Lot**

![](../../img/consume/tombol-generate-lot.png)

7. Klik tombol **Apply** pada bagian bawah-kiri form

![](../../img/consume/tombol-apply-transfer-detail.png)

## C. OUTPUT

* Status dari consume akan berubah menjadi **Transfered**

![](../../img/consume/status-transfered.png)
