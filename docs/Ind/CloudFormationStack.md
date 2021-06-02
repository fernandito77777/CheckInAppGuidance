## Menjalankan template CloudFormation Stack untuk infrastruktur

1. pergi ke [AWS Console](https://console.aws.amazon.com/console/home?region=us-east-1#)
2. buka *CloudFormation* dengan mengisi nama service diatas dan tulis `CloudFormation` dan klik bagian tersebut.

    ![](../../images/CloudFormationStack/2.png)

3. Klik `Create stack`

    ![](../../images/CloudFormationStack/3.png)

4. dalam *prepare template*, pilih `Template is ready` dan pilih `Amazon S3 URL`
5. *Copy* dan *paste* S3 URL ini `https://s3.amazonaws.com/solutions-reference/auto-check-in-app/latest/auto-check-in-app.template`
6. klik `Next`

    ![](../../images/CloudFormationStack/6.png)

7. dalam nama stack, isi dengan `AutoCheckInAppStack` dan klik `Next`

    ![](../../images/CloudFormationStack/7.png)

8. dalam halaman *Configure stack options*, klik `Next`
9. dalam halaman *review*, mohon untuk mengecek semua checkbox dalam bagian *capabilities and transforms*
10. klik `Create stack`

    ![](../../images/CloudFormationStack/10.png)

Proses ini akan memakan waktu sementara untuk mempersiapkan *stack* infrastruktur

11. Setelah selesai, maka akan muncul tampilan `CREATE_COMPLETE` dalam bagian kiri dari *stack*
12. Mohon klik bagian tab `Outputs` dan pastikan untuk tidak menutup halam ini, karena halaman ini akan digunakan pada tahap nantinya.

    ![](../../images/CloudFormationStack/12.png)

[KEMBALI KE PETUNJUK WORKSHOP :house:](../../IndonesiaGuide.md)

[LANJUT KE PETUNJUK SELANJUTNYA :arrow_right:](UploadImageS3.md)

[KEMBALI KE PETUNJUK SEBELUMNYA :arrow_left:](Prerequisites.md)