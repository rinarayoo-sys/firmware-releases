# NEXTU ONE-R AX1800 — Firmware (Full / 32MB)

**Full (32MB NOR)** 변종의 OTA 펌웨어 릴리스. 단말 web-UI(ntfwupdate)가
`releases/latest/download/manifest.json` 으로 자동 수신합니다.

> Slim(16MB) 변종 → https://github.com/rinarayoo-sys/firmware-releases-16m

## 라인업 비교 (Full vs Slim)

| 항목 | **Full** (ONE-R AX1800) | Slim (ONE-R AX1800 16M) |
|---|:---:|:---:|
| Flash (SPI NOR) | 32 MB | 16 MB |
| 이미지 크기 | ~16.1 MiB | ~12.9 MiB |
| firmware 파티션 | 31.4 MiB | 15.4 MiB |
| OTA repo | firmware-releases | firmware-releases-16m |
| WiFi · 방화벽 · 자녀보호 · QoS · 게스트 · 백업/복원 · 재부팅예약 · 장치모드 · 진단 | ✓ | ✓ |
| WireGuard 클라이언트 | ✓ | ✓ |
| VPN 서버 (OpenVPN·IPSec·PPTP·L2TP) | ✓ | ✗ |
| 광고 차단 (adblock) | ✓ | ✗ |
| 이메일 알림 (SMTP) | ✓ | ✗ |
| DDNS | ✓ | ✗ |
| URL 필터 | ✓ | ✗ |
| IPTV | ✓ | ✗ |
| GeoIP 국가 차단 | ✓ | ✗ |
| WOL (원격 켜기) | ✓ | ✗ |
| IoT 전용 네트워크 | ✓ | ✗ |
| DMZ | ✓ | ✗ |

✗ = slim 원가절감 BOM(16MB)에서 미탑재. 코어 기능(WiFi·보안·자녀보호·QoS 등)은 양쪽 동일.
