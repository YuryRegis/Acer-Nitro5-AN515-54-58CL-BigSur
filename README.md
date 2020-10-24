# Acer-Nitro5-AN515-54-58CL-BigSur-OPENCORE

EFI files to boot Big Sur 11.0 (20A5395g) Hackintosh on Acer Nitro 5


<p align="center">
  <img src="https://i.ibb.co/gr4MSzR/Captura-de-Tela-2020-10-23-a-s-12-02-42.png">
</p>


# Atualizando o Catalina para a ultima versão BigSur

1. Faça download e Instalação do [DeveloperBeta Acces Utility](https://drive.google.com/file/d/1OY8CQ2r-45TpDzOc90lAMaonHjY5OOH4/view?usp=sharing);
2. Faça [download do repositório](https://github.com/YuryRegis/Acer-Nitro5-AN515-54-58CL-BigSur/archive/main.zip) e descompacte o arquivo ZIP;
3. Procure por atualização do seu OSX e faça download do instalador do BigSur (`Preferências do Sistema>atualização de Software`);
4. Abra a partição EFI do HD/SSD (use algum [gerenciador EFI](https://hackintoshbrasil.com/forum/topic/8-diferentes-formas-de-montar-a-efi/)) onde seu OSX Catalina está instalado;
5. Substitua a pasta EFI do seu HD/SSD pela pasta EFI do repositório;
6. Inicie o processo de atualização do OSX BigSur, clique no botão reiniciar quando for solicitado (evite reiniciar pelo icone da maçã);
7. Aguarde o processo de Instalação, demora um pouco e seu Hackintosh irá reiniciar algumas vezes


## Observações

Kext para Airport `Itlw` para placa wireless Intel AX200 adicionado. Usar aplicação Heliport para reconhecer as redes disponíveis (créditos: [Alexandre Lima](https://github.com/aclima01)). Para inicia-lo automaticamente ao abrir o Catalina, adicione-o na lista de aplicativos em `itens de início` (Preferências do Sistema > Usuários e Grupos > Itens de Início).

<p align="center">
  <img src="https://i.ibb.co/ngft7VN/Captura-de-Tela-2020-10-23-a-s-00-54-39.png">
</p>

- [Heliport App](https://github.com/OpenIntelWireless/HeliPort/releases/tag/v1.0.1) download.

### Especificações do Hardware
INFO           | ESPECIFICAÇÃO
:------------- | :---------------------------------
Fabricante     | ACER BRASIL
Modelo         | NITRO 5 AN515-54-58CL
OS Fabrica     | Endless OS
BIOS           | v1.31
CPU            | Intel Core i5-9300H
iGPU           | Intel UHD Graphics 630
GPU            | GeForce GTX 1650 4 GB GDDR5 
HDD            | 1 TB 5400 RPM SATA III
SSD            | SSD de 128 GB M.2 SATA III (x2)
RAM            | 16 GB 2667 MHz DDR4 (2x8GB)
Wifi+Bluetooth | Intel AX200 (INT9560)
Ethernet       | Realtek RTL8168/8111 PCI-E Gbit
Audio          | Realtek ALC255 
Trackpad       | ELAN 0504

## Roda ou não roda ?

- Placa de vídeo dedicada Nvidea ❌;
- Intel UHD Graphics 630  ✔️;
- Trackpad (Apple gestures) ✔️;
- WebCam ✔️;
- Teclado ✔️;
- Audio (OTIMIZADO) ✔️;
- Rede Ethernet (limitado a 100Mbps) ✔️;
- Rede Wifi ✔️;
- Bluetooth ❌
