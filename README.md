# USB_PD_Sink

USB C todas as coisas!.
Com essa quebra do STUSB4500, você pode alimentar todos os seus dispositivos e projetos eletrônicos. De Arduinos a laptops, o USB-C Power Delivery pode fornecer até 100W (20V @ 5A).

Agora você pode comprar isso no meu Tindie!

Este dispositivo pode armazenar 3 PDOs (Power Delivery Outputs) e, após a conexão, tentará negociar a mais alta dessas 3. Isso significa que ele pode operar como um dispositivo autônomo, sem a necessidade de um microcontrolador externo. A DOP negociada é mostrada pelas seguintes cores. Por padrão, o dispositivo tem os seguintes PDOs:

PDO1	DOP2	DOP3
5V @ 1.5A	15V @ 1.5A	20V @ 1A
Azul	Verde	Vermelho
Os PDOs também podem ser personalizados programando os registros de memória não volátil (NVM) via I2C. O dispositivo também pode ser conectado a um microcontrolador, para permitir a negociação em tempo real do contrato de PD. Para fazer isso, o dispositivo só precisa ser conectado via I2C de acordo com a pinagem abaixo. As bibliotecas para Arduino existem e são rápidas e fáceis de usar.

Especificações técnicas
Controlador: STUSB4500
Tensão de saída: 5-20V *
Corrente de saída: 0-5A*
LED: LED embutido para exibir qual DOP é negociado (veja acima os detalhes)
Proteção: ESD e proteção transitória nos pinos de alimentação e USB-C, descarga do caminho VBUS na mudança de tensão ou desconexão capaz
Projetado e fabricado no Canadá

*A potência de saída é limitada pela capacidade do seu carregador

<a href="https://www.tindie.com/stores/ketszim/?ref=offsite_badges&utm_source=sellers_ketszim&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" width="200" height="104"></a>

![Pinout](https://github.com/ketszim97/USB_PD_Sink/blob/master/Renders/Fusion_Render_17_800px.png)

![Fusion Render 1](https://github.com/ketszim97/USB_PD_Sink/blob/master/Renders/Fusion_Render_18.png)
