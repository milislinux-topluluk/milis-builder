# milis-builder
Milis Linux tabanlı dağıtım hazırlama işlemlerini hızlandırma için hazırladığımız uygulama.

Mevcut sürüm Milis Linux dağıtımı altında çalışmaktadır. İleriki sürümlerde diğer dağıtımlarda da çalışacak şekilde gerekli geliştirmeler planlanmaktadır.

Desteklenen masaüstleri:
- xfce4

Login yöneticisi:
- slim


```
Milis Builder 2017.07

Genel Parametreler
	-t | --temizle
	Tüm çalışmaları siler ve çalışmaya sıfırdan başlamanızı sağlar. Silme işlemi geri alınamaz.

	-o | --onhazirlik
	Gerekli klasör yapısını oluşturur, temel paketlerin indirilmesi ve kurulması işlemleri yapar.

	-i | --iso
	Son aşamadır, dağıtımı iso formatına çevirir. Öncesinde --onhazirlik ile gerekli temel paketlerin
	kurulmuş olması gerekmektedir.

	-y | --yardim
	Bu yardım metnini görüntüler.

Yerel Paket Sistemi:
	--yps-olustur
	Yerel paket sunucusu oluşturmak için kullanılır. Dağıtım hazırlama sırasında tekrar tekrar
	tüm paketlerin indirilmesi istenmiyorsa bu seçenek kullanılabilir. Fakat unutulmamalıdır ki
	kullanmasanız da sunucuda bulunan tüm paketler indirilecektir.

	--yps-baslat
	Oluşturulmuş olan Yerel Paket Sistemi (--yps-olustur) başlatılacaktır.

	--yps-durdur
	Başlatılan Yerel Paket Sistemi (--yps-baslat) durdurulacaktır.

	--yps-kontrol
	Yerel Paket Sunucusu yolu, veritabanı kontrolü, çalışıp çalışmadığı gibi kontrolleri sağlar.
```
