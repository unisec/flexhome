![Banner Logo](https://imgs.unisec.com.br/unicontrol/Banner.svg)

<p style="width: 100%; display: flex;">
    <img width="170"  src="https://esphome.io/_images/made-for-esphome-black-on-white.svg" />&nbsp;
    <img width="170" src="https://partner.home-assistant.io/images/works-locally-with-home-assistant.png" />
</p>

# **`FLEXHOME`** Exemplos

O produto **FLEXHOME** é baseado no projeto Open-source [**`Esphome`**](https://github.com/esphome/esphome) que é muito utilizado mundialmente mundo a fora pelas pessoas de IOT - Internet das coisas. Essa solução permite agilidade no processo de concepção de pequenos e grandes projetos de [**Sistemas Embarcados**](https://pt.wikipedia.org/wiki/Sistema_embarcado) que funcionam nas plataformas **[ESP32](https://www.espressif.com/en/products/modules/esp32)**/**[ESP8266](https://www.espressif.com/en/products/modules/esp8266)**

## Dispositivos

### Modulo Inteligente - **FLEXIP**

![FLEXIP.PNG](https://imgs.unisec.com.br/unicontrol/FlexIP.png)

A **FLEX IP** atua como controlador central de uma pré-automação com ele é possível comandar as placas da linha **FLEXHOME** que são a `IDC`,`IODC` e `OAC` facilmente via barramento I2c, não apenas isso, A **FLEX IP** tem incluso nela os seguintes componentes como `WI-FI`,`Ethernet`,`I2C Bus` e o `Bluetooth` graças ao modulo [ESP32](https://www.espressif.com/en/products/modules/esp32) que os suporta nativamente, esses recursos podem ser ativados e usados em diferente contextos. E ah claro, não vamos esquecer que o Home Assistant possui integração nativa com os módulos **FLEXHOME**. Disponilizamos abaixo um firmware de modelo inicial para guiar seus primeiros passos com esse produto.

[Baixar esse Firmware](./flexip.yaml)
[Veja o datasheet dessa placa](.)

### Entrada de Corrente Contínua - **IDC**

![FLEXIP.PNG](https://imgs.unisec.com.br/unicontrol/idc.png)

A placa IDC tem como característica de atuar como entrada, sendo, portanto, um dispositivo responsável por receber os comandos efetuados ao longo de suas 32 conexões. Cada uma dessas entradas têm a capacidade de receber pulsos de 12-24VDC para as mais diversas aplicações como por exemplo a de `Teclas Pulsadores` e `Sensores de Presença`.

[Baixar esse Firmware](./idc.yaml)
[Veja o datasheet dessa placa](.)

### Entrada/Saída de Corrente Contínua - **IODC**

![FLEXIP.PNG](https://imgs.unisec.com.br/unicontrol/iodc.png)

O módulo IODC Flexhome é flexível e de alta capacidade, possui um total de 32 conexões que podem atuar como entrada ou como saída, dependendo de como foi configurado. Quando configurado no modo de entrada, pode exercer a função de ler `Sensores de Presença` e `Teclas de Pulso`. Quando configurado no modo de saída, pode acionar, por exemplo, `Relés de Impulso`, `Contatores`, `Solenóides` e dentro outros, fornecendo até 2 A em 12 V DC ou 24 V DC

[Baixar esse Firmware](./iodc.yaml)
[Veja o datasheet dessa placa](.)

### Saída de Corrente Alternada - **OAC**

![FLEXIP.PNG](https://imgs.unisec.com.br/unicontrol/oac.png)

O módulo OAC Flexhome tem como característica atuar como saída, sendo, portanto, responsável pelo acionamento de cargas de corrente alternada de 110V/220V AC ao longo de 16 conexões que serão exploradas mais adiante. Cada uma dessas saídas têm a capacidade de acionar até 1 A (220V = 220W ou 110V = 110W), com as mais diversas aplicações, como por exemplo, acioanemtos de `Iluminação`, `Led`,`Incandescente`, `Persianas`,`Cortinas` ou também `Contatores`.

[Baixar esse Firmware](./oac.yaml)
[Veja o datasheet dessa placa](.)
