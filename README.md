# EFI OPENCORE IDESK7 BKP 0.8.7 intel 6700k SkyLake SSDTs FULL 01122022
EFI Compatible with Gigabyte Z170 XP SLI 100 series. Opencore boot loader to run Hackintosh macOS Ventura 13.0.1

Esta pasta EFi está em perfeito funcionamento para placa mãe Gigabyte Z170 XP Sli v.1

Bootloader Opencore versão 25-11-2022 0.8.7

EFI Opencore Z170 Xp SLI 



Link do fabricante da placa:

https://www.gigabyte.com/br/Motherboard/GA-Z170XP-SLI-rev-10#ov


Nela contém inclusive um mapeamento de portas USB elaborado com SSDT-USBPORTS.aml que compilei passo a passo, e usando também as demais ferramentas comuns (Hackintool e UsbMap). Está pronta, inclusive funciona o sleep no macOs. 

Pode ser utilizada com macOs Ventura 13.0.1 
 

O Processador que me utilizo é intel i7 conforme descrição abaixo. Mas creio que qualquer dos processadores intel compatíveis com este chipset Z170 será possível utilizar. 

IMPORTANTE

Contém um SMBIOS gerada com GenSMBIOS, modelo  MacPro 1,1  deste guia:

https://github.com/corpnewt/GenSMBIOS 

1. Aconselho gerar o seu próprio pois deixei nesta pasta apenas para o caso de desejar testar. 

2. Não está programada para dar boot com a placa onboard intel (igfx), e sim com as placas Amd Radeon, como por exemplo, a RX 64 Vega. 

3. Mas, para isso, é preciso usar as ferramentas como Hackintool para escolher seu device corretamente. Por isso deixei sem device Properties para sua placa de vídeo. 

Boa sorte. 


Att Christian Max Picelli Corrêa
