# Gün Projesi: Workintech Revizeleri

## Güncel Sürüm

Bu repodaki kod, Workintech NextGen üzerinde **%100 başarıyla tamamlanan güncel sürümdür.**

> **Not:** Logo görselinin URL'si, NextGen testlerinde kullanılan güncel bağlantıya göre düzenlenmiştir. Bu nedenle proje içerisindeki logo bağlantısı, bazı eski test dosyalarında bulunan URL'den farklı olabilir.


## Proje Tanımı

Workintech firması ile yapılan toplantıda dün yaptığın layout gösterildi.
Öncelikle, beğendiklerini söylediler ama hayalini kurdukları biraz daha farklı idi.
Bu yüzden hazırladığın layout için bazı geri-bildirimler verdiler:

1. Tasarımda ufak bir değişiklik istiyorlar. Yeni [masaüstü tasarımına](https://materials.cdn.workintech.com.tr/projects/fullstack/workintech-landing/tasarim_desktop.jpg) bakabilirsin.
2. Sayfanın responsive olmasını ve en azından bir cep telefonunda **(max-width: 500px)** [mobil tasarımdaki](https://materials.cdn.workintech.com.tr/projects/fullstack/workintech-landing/tasarim_mobil.jpg) gibi görünmesini istiyorlar.

Bu 2 isteği hızlıca hazırlamalısın. Bunun için `index.html` ve `index.css` dosyalarını kullanabilirsin.

**Not:** Geniş ekranlarda veya yüksek çözünürlüklerde mobil tasarım görünmeyebilir. Mobil görünümü test etmek için tarayıcı penceresini daraltabilir ya da geliştirici araçlarını (F12) kullanabilirsin.

## Önemli Notlar

- Proje dizinindeki `user.json` dosyasını bulun ve `user_id` alanını NextGen proje ekranında görünen kendi `user_id` değeriniz ile güncelleyin.
- Geliştirme sırasında testleri izlemek için `npm test` komutunu kullanın.
- Testleri çalıştırıp skoru NextGen'e kaydetmek için `npm run sendresults` komutunu kullanın.
