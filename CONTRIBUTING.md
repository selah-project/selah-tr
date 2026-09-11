# Selah'ın Türkçe çeviriyazımına katkıda bulunmak

Bu çeviriyazımın daha doğru, daha açık ve Türkçe'ye daha uygun
olmasına yardım ettiğiniz için teşekkürler. Bilgin olmak gerekmez:
gördüğünüzü söyleyin, elinizdeki kanıtı sunun ve kesin olanı öneri
olandan ayırın.

## Hata bildirmek ya da düzeltme önermek

- Metin tartışma gerektiriyorsa, birden fazla okunuş varsa ya da
  düzeltmenin sözcük hizalamasını nasıl etkileyeceğinden emin
  değilseniz **Issue** açın.
- Hem hata hem düzeltme açıksa **Pull request** açın.
- Yazılım sorunları ya da güvenlik/hesap/gizlilik konuları için
  [Selah Support](https://selahproject.com/support) kullanın.

## Neler eklemeli

Kitap, bölüm, ayet, ilgili İbranice metin; mevcut metin; önerdiğiniz
metin; değişikliğin gerekçesi; ve sözlük, dilbilgisi, bağlam ya da
yayımlanmış kaynaklardan kanıt. Ayrıca Türkçe'yi ana diliniz olarak
konuşup konuşmadığınızı ve İbranice'yi doğrudan okuyup okuyamadığınızı
belirtin.

## Dosya düzenleme kuralları

Dosyalar `<book>/<chapter>/<verse>.json` biçimindedir.

- İkisi de etkileniyorsa, ilgili bölümün `translation` ve `gloss`
  alanlarını birlikte düzeltin.
- `book`, `chapter`, `verse`, `ref` alanlarına, İbranice `surface`
  değerlerine ya da token'ların sırasına ve sayısına **asla**
  dokunmayın — hizalama hatası en pahalı hatadır.
- **İsim tablosuna uyun**: יהוה → **Yahve**; אלהים → **Elohim**;
  אדני → **Adonay**; שדי → **Şadday**; שאול → **Şeol**; חסד →
  **Khesed**. İsmin yerinde **Yehova**, **RAB/Rab** ve **Tanrı**
  kabul edilmez. (Sıradan *elohim* için **Tanrı** doğru olabilir —
  token'a göre karar verin, toptan reddetmeyin.)
- **⟨את⟩** işaretlerini ve ⟨ayraç⟩ içindeki eklemeleri koruyun;
  sessizce silmeyin.
- Ayraçların dışında yalnızca Türk alfabesi — CJK yok, Kiril yok,
  Arap harfleri yok, Devanagari yok.

## Ölçüt

Önce İbranice. İki okunuş da ayakta duruyorsa, farkı sunun — seçimi
kesinlik gibi sunmayın. Telif hakkı korumalı modern çevirilerden
kopyalamayın.

## Yapay zekâ ile çalışmak

Büyük dil modelleri ya da makine çevirisi kullanımını açıkça
belirtin — kendi denetiminizle birlikte. Denetlenmemiş büyük metin
yığınları göndermeyin. Önerilen her sözcük katkıda bulunanın
sorumluluğudur.

## Lisans, kayıt ve değerlendirme

Katkıda bulunarak buna hakkınız olduğunu doğrulamış ve eklenen her
şeyin [CC BY-SA 4.0](LICENSE.md) ile dağıtılacağını kabul etmiş
olursunuz. Git geçmişi açık kaydı ve tanıklığı tutar. Bakım ekibi
önerileri İbranice ile, kurallarla, kaynaklarla ve hizalamayla
karşılaştırır — kabul edebilir, sizinle birlikte çözebilir, daha
fazla kanıt bekleyebilir ya da gerekçeli reddedebilir. Metin
değerlendirilir, insan değil.

## Conduct

Be honest, be kind, show your evidence. Distinguish certainty from
suggestion. The maintainers weigh and decide.
