# Loki

Loki, Tor ağı üzerinden alınan çıkış IP adresini belirli aralıklarla yenilemeyi deneyen bir Python betiğidir.

## Ne Yapar

- Tor servisini başlatır
- SOCKS5 proxy üzerinden mevcut dış IP'yi kontrol eder
- belirlenen aralıklarla Tor devresini yeniler

## Teknolojiler

- Python
- Tor
- `requests`

## Notlar

- Linux ortamı ve Tor servisi varsayımıyla yazılmıştır
- Eğitim ve deney amaçlı bir betiktir

