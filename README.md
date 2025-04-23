# Toplu IMEI Sorgulama Uygulaması

Bu program, Excel dosyanızda bulunan IMEI numaralarını kullanarak, bu IMEI'lerin hangi markaya ait telefonlara kayıtlı olduğunu **toplu bir şekilde sorgulayan** bir uygulamadır.

Program, sorgulama işlemlerini otomatik olarak yapar ve sonuçları tekrar Excel dosyası olarak kaydeder. Böylece her bir IMEI için manuel olarak siteye girmenize gerek kalmadan hızlıca toplu sonuçlara ulaşabilirsiniz.

## Özellikleri:
- Excel dosyasındaki "IMEI" sütununu otomatik olarak okur.
- Her bir IMEI numarasını internet üzerinden sorgular.
- Elde edilen marka/model bilgisini yeni bir Excel dosyasına kaydeder.
- Hata oluşursa masaüstüne `IMEI_error_log.txt` dosyasına kaydeder.

## Kurulum

Uygulamanın kurulum dosyasını aşağıdaki bağlantıdan indirebilirsiniz:

🔗 **[Kurulum dosyasını indir](https://drive.google.com/drive/folders/1RN2sZIMmMRpMFaEPxHV6JAF-GrbVQmsz?usp=sharing)**


## Önemli Uyarı ⚠️

Bu program **kesinlikle `C:\Program Files`, `C:\Program Files (x86)` gibi Windows'un korumalı sistem klasörlerine kurulmamalıdır.**  
Bu dizinlerde yazma izinleri kısıtlı olduğu için program düzgün çalışmaz, sonuç dosyası ve hata kayıtları kaydedilemez.

✅ **Programı aşağıdaki gibi bir dizine kaydedin:**
- Masaüstü (Önerilen)
- Belgeler
- `C:\Users\KULLANICI_ADINIZ\` altındaki herhangi bir klasör

## Kullanım Adımları:

1. Programı başlatın.
2. IMEI numaralarının bulunduğu Excel dosyasını seçin.
3. "Sorgulamayı Başlat" butonuna basın.
4. Sorgulama işlemi sırasında ekranın ortasında ilerleme çubuğu ve anlık olarak sorgulanan IMEI görüntülenir.
5. İşlem tamamlandığında sonuçlar Excel dosyasına kaydedilir.

### Başlangıç Ekranı:

![IMEI Sorgulama Aracı Başlangıç Ekranı](1.png)

### Sorgulama Esnasında:

![IMEI Sorgulama Aracı Sorgulama Ekranı](2.png)

---

Hazırlayan: **Mehmet Esen**  
📧 Sorularınız için iletişim: mehmetesen@example.com
