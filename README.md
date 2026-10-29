# Şoför Bul VIP Sözleşmeleri

Uygulamanın yasal metinleri (HTML). Uygulama bu metinlerin adreslerini backend'in `GET /config` servisinden alır.

| Metin | Dosya |
|---|---|
| Kullanıcı Sözleşmesi | [kullanici-sozlesmesi.html](kullanici-sozlesmesi.html) |
| KVKK Aydınlatma Metni | [kvkk-aydinlatma-metni.html](kvkk-aydinlatma-metni.html) |
| Gizlilik Politikası | [gizlilik-politikasi.html](gizlilik-politikasi.html) |
| Açık Rıza Metni | [acik-riza-metni.html](acik-riza-metni.html) |

## Yayın
Sayfalar GitHub Pages ile yayınlanır (Settings → Pages → Branch: `main`, klasör `/`). Adresler: `https://iscetech.github.io/find-driver-agreements/<dosya>.html`

## Sürümleme
Her dosyanın başında sürüm ve yürürlük tarihi bulunur. Metin değiştiğinde sürümü artırın, backend'de `APP_LEGAL_VERSION` değerini güncelleyin ve değişikliği commit mesajında belirtin.
