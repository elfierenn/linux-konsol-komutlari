# Linux Terminal Komutları
Bu projede 20 tane linux terminal komutları gösterilmiştir.

## Klasör ve Dosya Yönetimi Komutları
#### mkdir Komutu
Yeni bir klasör oluşturur.
```
Örnek:
> mkdir Merve
```
![photo_2024-11-16_03-05-35](https://github.com/user-attachments/assets/c6d0802a-fe0c-463e-ab6a-5374d353718d)

#### rmdir Komutu
Boş bir klasörü siler.
```
Örnek:
> rmdir Çöp
```
![photo_2024-11-16_03-05-40](https://github.com/user-attachments/assets/11500a3d-3094-4d6f-be61-2a681759ad31)

#### cd Komutu
Çalışma dizinini değiştirir.
```
Örnek:
> cd Merve
```
![photo_2024-11-16_03-05-42](https://github.com/user-attachments/assets/f852ff54-b9c7-45e3-b74f-e51a14950ed2)

#### dir Komutu
Mevcut dizindeki dosya ve klasörlerin listesini gösterir.
```
Örnek:
> dir
```
![photo_2024-11-16_03-05-45](https://github.com/user-attachments/assets/a64fa8fe-ab9d-462b-a0da-7b7936de00bd)

#### tree Komutu
Geçerli dizindeki tüm dosya ve klasörleri ağaç şeklinde gösterir.
```
Örnek:
> tree
```
![photo_2024-11-16_03-05-49](https://github.com/user-attachments/assets/e93cac84-63dd-4459-90fe-faec7a448357)

#### rename Komutu
Bir dosyanın veya klasörün adını değiştirir.
```
Örnek:
> rename yazı.txt yazı123.txt
```
![photo_2024-11-16_03-05-51](https://github.com/user-attachments/assets/efc04f3d-624e-4749-8334-81364d1f5976)

## Dosya İçeriği Gösterme ve Arama Komutları
#### echo Komutu
Belirli bir metni ekrana yazdırır.
```
Örnek:
> echo Merve Yılmaz > yazı.txt
```
![photo_2024-11-16_03-05-55](https://github.com/user-attachments/assets/faaf95c4-5ffc-4b38-b2ff-d5836a55454d)

#### type Komutu
Bir dosyanın içeriğini ekrana yazdırır.
```
Örnek:
> type yazı.txt
```
![photo_2024-11-16_03-06-01](https://github.com/user-attachments/assets/6889e0b3-f2bd-4c48-98cc-f5c9c6088150)

#### find Komutu
Bir dosyada belirtilen kelimeyi arar.
```
Örnek:
> find "Merve" yazı.txt
```
![photo_2024-11-16_03-06-05](https://github.com/user-attachments/assets/e26c3187-1fc4-41ee-8ddb-68051df6ed84)

## Dosya Taşıma ve Kopyalama Komutları
#### copy Komutu
Bir dosyayı başka bir yere kopyalar.
```
Örnek:
> copy yazı.txt Yılmaz
```
![photo_2024-11-16_03-06-08](https://github.com/user-attachments/assets/1e2d7553-b259-46b7-9224-45b33a674234)

#### move Komutu
Bir dosyayı veya klasörü başka bir yere taşır.
```
Örnek:
> move Yılmaz Yılmaz123
```
![photo_2024-11-16_03-06-11](https://github.com/user-attachments/assets/5fd77109-572e-4466-9b40-d6fc22c6ae4c)

#### del Komutu
Bir dosyayı siler.
```
Örnek:
> del yazı.txt
```
![photo_2024-11-16_03-06-14](https://github.com/user-attachments/assets/b792df00-2261-4996-a084-c68f51a27338)
> [!NOTE]
> Size "Emin misiniz?" şeklinde bir soru sorulacaktır. Eğer silmek istiyorsanız Y, silmek istemiyorsanız N yazınız.

# Sistem Bilgileri ve Yöneticilik Komutları
#### driverquery Komutu
Sistemde yüklü olan tüm sürücülerin listesini gösterir.
```
Örnek:
> driverquery
```
![photo_2024-11-16_03-06-18](https://github.com/user-attachments/assets/b9ce9ffe-c0a5-4e1e-bc61-2cba3697a2e2)

#### tasklist Komutu
Çalışan tüm işlemleri listeler
```
Örnek:
> tasklist
```
![photo_2024-11-16_03-06-20](https://github.com/user-attachments/assets/80c74412-1ed0-466f-9d45-1a884d18ceaf)

#### getmac Komutu
Bilgisayarınızdaki ağ bağdaştırıcılarının MAC adreslerini gösterir.
```
Örnek:
> getmac
```
![photo_2024-11-16_03-06-23](https://github.com/user-attachments/assets/c84775bb-153e-43df-a5ba-91f0e5412f9f)

#### vol Komutu
Bir sürücünün etiketini ve seri numarasını gösterir.
```
Örnek:
> vol C:
```
![photo_2024-11-16_03-06-25](https://github.com/user-attachments/assets/4d00ff2e-d289-4c46-a8dd-b6a601290039)

#### date /T Komutu
Günün tarihini sadece yazdırır.
```
Örnek:
> date /T
```
![photo_2024-11-16_03-06-28](https://github.com/user-attachments/assets/620ce27f-7c68-4662-acb7-18f37db200fa)

# Görev ve Uygulama Yönetimi Komutları
#### taskmgr.exe Komutu
Görev Yöneticisi'ni açar.
```
Örnek:
> taskmgr.exe
```
![photo_2024-11-16_03-06-30](https://github.com/user-attachments/assets/86c5560e-732c-4d50-8264-51515200c7f7)

#### notepad.exe Komutu
Not Defteri'ni açar.
```
Örnek:
> notepad.exe
```
![photo_2024-11-16_03-06-33](https://github.com/user-attachments/assets/392251f5-d4ab-4ef5-b06a-d42f4e7e0006)

#### pause Komutu
Komutların çalışmasını duraklatır ve bir tuşa basılmasını bekler.
```
Örnek:
> pause
```
![photo_2024-11-16_03-06-35](https://github.com/user-attachments/assets/5a171275-1457-4cc6-99ae-a08b338a6361)
