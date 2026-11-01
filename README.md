# ESP5-WarBox

ESP32 tabanlı RF güvenlik araştırma aracı. WiFi deauth, BLE flood, 2.4GHz spektrum analizi ve SD kart kayıt özellikleri ile donatılmış, Marauder tarzı menü yapısına sahip portable RF tool.

![ESP32](https://img.shields.io/badge/ESP32-WROOM--32U-blue)
![Display](https://img.shields.io/badge/Display-ILI9341%20320x240-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Özellikler

### WiFi Attacks
- **Network Scan**: Çevredeki WiFi ağlarını tara (SSID, BSSID, Channel, RSSI)
- **Deauth Attack**: Seçili hedefe deauthentication paketleri gönder
- **Beacon Spam**: Sahte WiFi AP'leri oluştur (Free WiFi, Starbucks, Airport_Free vb.)
- **Packet Sniff**: WiFi trafiğini dinle

### Bluetooth Attacks
- **BLE Flood**: Çevredeki BLE cihazlarını flood et (AirPods, Galaxy Buds, JBL vb. isimlerle)
- **BLE Sniff**: Bluetooth cihazlarını tara
- **Wardriving**: BLE cihazlarını SD'ye kaydet

### Spectrum Analyzer
- 2.4GHz bandının 13 kanalını gerçek zamanlı tara
- RSSI enerji seviyelerini görselleştir (Yeşil/Sarı/Kırmızı)
- SD karta CSV formatında kaydet

### Hardware
- ILI9341 320x240 TFT ekran
- 4 buton navigasyon (L/R/UP/DN)
- SD kart slotu (kayıt ve oyun yükleme)
- Marauder tarzı gradient UI

## Donanım

| Komponent | Model |
|-----------|-------|
| MCU | ESP32 WROOM-32U |
| Display | ILI9341 2.4" TFT (320x240) |
| SD Card | MicroSD module (SPI) |
| Buttons | 4x tactile push button |
| Power | 5V USB or 3.7V LiPo |

## Bağlantılar

### ILI9341 TFT (SPI)
