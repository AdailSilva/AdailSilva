<div align="center">

<img src="./assets/header.svg" width="100%" alt="Adail Silva — LoRaWAN, IoT e Kubernetes"/>

<br/>

<a href="https://k8s.adailsilva.com.br"><img src="https://img.shields.io/badge/k8s.adailsilva.com.br-00E5A0?style=for-the-badge&logo=kubernetes&logoColor=041018" alt="Site"/></a>
<a href="https://linkedin.com/in/adailsilva"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<img src="https://img.shields.io/badge/Tianguá%20·%20CE%20·%20BR-071624?style=for-the-badge&logo=googlemaps&logoColor=00C6FF" alt="Localização"/>
<img src="https://komarev.com/ghpvc/?username=AdailSilva&style=for-the-badge&color=00c6ff&label=PACOTES+RECEBIDOS" alt="Visitas"/>

</div>

<img src="./assets/wave.svg" width="100%" alt=""/>

## 📡 Sobre mim

```c
// Uplink #1 — perfil do operador
struct Operador {
    const char *nome     = "Adail Silva";
    const char *base     = "Tianguá, Ceará — Brasil";
    const char *regiao   = "AU915 · sub-banda 1";
    const char *missao   = "Da Sua Ideia ao Kubernetes";
    const char *foco[]   = { "LoRaWAN", "Firmware ESP32/STM32", "Gateways multicanal",
                             "ChirpStack", "Kubernetes ARM64", "Full Stack" };
};
```

- 🛰️ Projeto e opero **redes LoRaWAN** de ponta a ponta: do nó com sensor ao Network Server rodando em Kubernetes.
- 🔧 Escrevo **firmware em C/C++** para ESP32 e STM32 — nós ABP/OTAA e gateways de 8 canais com SX1301 e SX1302 sem Raspberry Pi.
- ☁️ Mantenho um **cluster Kubernetes ARM64 na OCI Always Free** que hospeda o ChirpStack e meus sistemas.
- 💻 Desenvolvo sistemas **Java/Spring, Angular e Flutter** que consomem a telemetria e viram produto.
- 📶 Na área de TI desde 2007 — suporte, redes, NOC e, hoje, IoT e desenvolvimento.

<img src="./assets/network.svg" width="100%" alt="Fluxo bidirecional: sensores/atuadores ↔ nós LoRa ↔ gateway ESP32+SX1302 ↔ ChirpStack ↔ Kubernetes OCI ↔ aplicações (uplink e downlink)"/>

<img src="./assets/frame.svg" width="100%" alt="Join OTAA (JoinRequest/JoinAccept) e anatomia de um quadro LoRaWAN"/>

## 🔭 Projetos em destaque

### 📶 Gateways multicanal (sem Raspberry Pi)

| Projeto | O que faz |
|---|---|
| [**Gateway_ESP32_SX1302_LR1302_HAT_Elecrow**](https://github.com/AdailSilva/Gateway_ESP32_SX1302_LR1302_HAT_Elecrow) | Gateway LoRaWAN de 8 canais e baixo custo, com o SX1302_HAL v2.1.0 rodando nativo em um único ESP32. |
| [**Gateway_ESP32_SX1301_RD43HATGPS_Radioenge**](https://github.com/AdailSilva/Gateway_ESP32_SX1301_RD43HATGPS_Radioenge) | Gateway LoRaWAN de 8 canais com o HAL do SX1301 (lora_gateway v5.0.1) portado para um único ESP32. |

### 📟 Nós LoRaWAN (end devices)

| Projeto | O que faz |
|---|---|
| [**Node_STM32_SX1272_RD49C_Radioenge_ABP_e_OTAA**](https://github.com/AdailSilva/Node_STM32_SX1272_RD49C_Radioenge_ABP_e_OTAA) | Firmware para o módulo Radioenge EndDevice (STM32L071CZ + SX1272): ABP e OTAA num só firmware, classes A/B/C, LoRaMac-node v4.7.1 e o conjunto completo de comandos AT. |
| [**Node_ESP32_SX1276_RFM95W_HOPERF_OTAA**](https://github.com/AdailSilva/Node_ESP32_SX1276_RFM95W_HOPERF_OTAA) | Nó OTAA ESP32 + RFM95W em AU915 com ChirpStack v4, página web e app Android — ESP-IDF e MCCI LMiC 6.0.1. |
| [**Node_ESP32_SX1276_RFM95W_HOPERF_ABP**](https://github.com/AdailSilva/Node_ESP32_SX1276_RFM95W_HOPERF_ABP) | Nó ABP ESP32 + RFM95W em AU915 com ChirpStack v4, página web e app Android — ESP-IDF e MCCI LMiC 3.3.0. |
| [**esp32-lorawan-otaa-au915-chirpstack**](https://github.com/AdailSilva/esp32-lorawan-otaa-au915-chirpstack) | Versão Arduino do nó OTAA (LMiC 6.0.1, sub-banda 1), com chave de sessão pós-JOIN, diagnóstico de MIC e depuração completa. |
| [**esp32-lorawan-abp-au915-chirpstack**](https://github.com/AdailSilva/esp32-lorawan-abp-au915-chirpstack) | Versão Arduino do nó ABP (LMiC 3.3.0, sub-banda 1), com contador de frames persistido em NVS e diagnóstico de MIC. |

### ☁️ Network Server na nuvem

| Projeto | O que faz |
|---|---|
| [**k8s-arm-oci-chirpstack**](https://github.com/AdailSilva/k8s-arm-oci-chirpstack) | ChirpStack LoRaWAN (v3 e v4) implantado em cluster Kubernetes ARM na OCI Always Free. |

### 📚 Documentação

| Projeto | O que faz |
|---|---|
| [**DocsEverynet_pt-BR**](https://github.com/AdailSilva/DocsEverynet_pt-BR) | Documentação da Everynet traduzida para o português brasileiro. |

<img src="./assets/coverage.svg" width="100%" alt="Radar de cobertura do gateway e comparação de spreading factors SF7–SF12"/>

## 🧰 Stack

<div align="center">

**Rádio & Embarcados**

<img src="https://img.shields.io/badge/LoRaWAN-00E5A0?style=flat-square&logo=lora&logoColor=041018"/>
<img src="https://img.shields.io/badge/ChirpStack-0B1F2E?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTIgMTggTDggNiBMMTQgMTggTDIwIDYiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzAwRTVBMCIgc3Ryb2tlLXdpZHRoPSIyLjUiLz48L3N2Zz4=&logoColor=00E5A0"/>
<img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white"/>
<img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white"/>
<img src="https://img.shields.io/badge/Semtech%20SX130x-1A1A1A?style=flat-square"/>
<img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white"/>
<img src="https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white"/>

<br/><br/>

<img src="https://skillicons.dev/icons?i=c,cpp,arduino,raspberrypi,linux&theme=dark" alt="Embarcados"/>

<br/><br/>

**Backend, Frontend & Mobile**

<img src="https://skillicons.dev/icons?i=java,spring,ts,angular,dart,flutter,postgres&theme=dark" alt="Desenvolvimento"/>

<br/><br/>

**Cloud & DevOps**

<img src="https://skillicons.dev/icons?i=kubernetes,docker,terraform,nginx,githubactions,git&theme=dark" alt="DevOps"/>
<img src="https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat-square&logo=oracle&logoColor=white"/>

</div>

<img src="./assets/wave.svg" width="100%" alt=""/>

<div align="center">

```
>>> downlink: obrigado pela visita!  ACK ✓   73 de AdailSilva
```

</div>
