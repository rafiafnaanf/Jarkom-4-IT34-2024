# Jarkom-Modul-4-IT34-2024
| Nama | NRP |
|---|---|
|Raditya Hardian Santoso|5027231033|
|Rafi Afnaan Fathurrahman|5027231040|

# GNS - CIDR

## Topologi GNS CIDR
<img width="715" alt="layer 0" src="https://github.com/user-attachments/assets/8985db22-ee97-46d6-8515-3688c07da833">

## Prefix IP
`10.80.X.X`

## Rute CIDR
| Subnet | Rute | JumlahIP | Netmask |
|---|---|---|---|
|A1|GAMERS-Fubuki-Korone, Okayu, Mio|120|/25|
|A2|GEN:1-GAMERS|2|/30|
|A3|GEN:1-Member-FBKMatsuri, AkiHachama|470|/23|
|A4|GEN:0-Switch3-MiComet, SoreRoboAZKi, GEN:1|2045|/21|
|A5|Holo-JP-Switch1-DEVIS, GEN:0|3|/29|
|A6|DEVIS-RE:GLOSS1-RirikaRaden, Ao, HajimeKanade|14|/28|
|A7|Hololive-Holo-JP|2|/30|
|A8|ProjectHope-Irys|3|/29|
|A9|Holo-Council-Switch4-KroniiMumei, BaeFauna|62|/26|
|A10|Holo-Myth-HoloPromise-ProjectHope, Holo-Council|3|/29|
|A11|Holo-Myth-Switch2-GuraAmeIna, KiaraCalli|503|/23|
|A12|Holo-EN-Holo-Myth|2|/30|
|A13|Holo-EN-Holo-Advent|2|/30|
|A14|Holo-Advent-Switch12-FuwaMoco, ShioriNerissa, Biboo|28|/27|
|A15|Hololive-Holo-EN|2|/30|
|A16|holoh3ro-Switch8-Zeta, Kaela, Kobo|299|/23|
|A17|Holo-ID-holoh3ro|2|/30|
|A18|holoro-Switch7-Ollie, Anya, Reine|34|/26|
|A19|Holo-ID-holoro|2|/30|
|A20|AREA15-Switch6-lofi, Moona, Risu|661|/22|
|A21|Holo-ID-AREA15|2|/30|
|A22|Hololive-Holo-ID|2|/30|
||Total|4263||

## Penggabungan IP CIDR
### Kondisi awal topologi CIDR (A)
<img width="715" alt="layer A" src="https://github.com/user-attachments/assets/943cf8eb-8039-4f2c-80c1-6e59ae69375b">

### Penggabungan node pertama (B)
<img width="715" alt="layer B" src="https://github.com/user-attachments/assets/04d2b49d-fc91-445c-bc72-3628d4e38b39">

|Subnet Akhir|Gabungan|Gabungan|Gabungan|Gabungan|Netmask Akhir|
|---|---|---|---|---|---|
|Subnet Akhir|1|1|2|2|Netmask Akhir|
|Subnet Akhir|Subnet|Netmask|Subnet|Netmask|Netmask Akhir|
|B1|A1|/25|A2|/30|/24|
