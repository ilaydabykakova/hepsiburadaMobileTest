# Hepsiburada Sepet Otomasyonu – Maestro

Hepsiburada Android uygulamasının **sepet sayfası** için yazılmış Maestro test senaryoları.

## Yapı

- `common/` → Tekrar eden adımlar (sepet_checkbox,ürün doğrulama,kargo_bedava_doğrulama)
- Kök dizin → Her biri bağımsız çalışan test senaryoları

## Senaryolar

| Dosya | Ne Test Eder |
|-------|-------------|
| `sepet_urun_dogrulama` | Ürün adı, fiyat, bilgi kontrolü |
| `sepet_adet_artirma` | (+) ile adet artırma |
| `sepet_adet_azaltma` | (-) ile adet azaltma |
| `sepet_checkbox_secim` | Ürün seçim/kaldırma |
| `sepet_kargo_bedava_dogrulama` | Kargo bedava etiketi |
| `sepet_urun_silme` | Sepetten ürün kaldırma |
| `sepet_urun_detaya_geri_donus` | Sepetten ürün detaya dönüş |
| `sepet_odeme_login_yonlendirme` | Ödeme → login yönlendirme |

## Çalıştırma

```bash
maestro test .
```