# OpenCore Comet Lake 10900k ASRock Z490M-ITX/ac

## Hardware:
- Case: [Cougar QBX Mini Itx](https://cougargaming.com/products/cases2/qbx/)
- Motherboard: ASRock Z490M-ITX/ac
- CPU: Intel i9 10th Gen Comet Lake 10900K
- GPU: Onboard iGPU UHD 630 Desktop
- Memory: 32GB HyperX Fury DDR4 3000MHz (2x16GB)
- SSD: Adata XPG Spectrix S40G 1TB M.2 (Read 3500MB/s, Write 3000MB/s)

## Working:

- Wifi (Original Intel AC3168)
- Bluetooth
- Sleep/awake
- HDMI Port
- DP Port
- Front Panel USB3.0 and Audio

## NOT working

- HDMI - DP Audio
- Motherboard Audio/Mic

## Not Tested

- dGPU as I dont use any.
- USB Type-C port

## Software

- OpenCore 0.6.9
- MacOS Big Sur
- SMBios: IMac20,1 (OpenCore recomendation for Comet Lake)

## Kexts

- Beaware the USBMap.kext that I mapped using the USBMapTool has ports configuration for my Cougar QBX Mini Itx Case. I recommend replacing `USBMap.kext` with `InjectUSBAll.kext` and do the proper mapping using the USBMapTool.
