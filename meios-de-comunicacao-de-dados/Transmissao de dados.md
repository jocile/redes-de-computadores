# Transmissão

Para que haja comunicação são necessários os seguintes elementos:

- Transmissor: é o dispositivo (computador, telefone, câmera) que envia a informação.
- Receptor: é o dispositivo a quem foi endereçada a informação. O receptor vai receber a mensagem enviada pelo transmissor.
- Mensagem: são os dados e as informações que precisam ser enviados.
- Meio: é o meio físico, ou seja, o caminho pelo qual a mensagem trafegará do transmissor até chegar ao receptor.
- Protocolo: controla o envio e recepção da mensagem e define alguns aspectos como formato da mensagem e ordem de chegada. Tanto o transmissor quanto o receptor devem estar seguindo o mesmo protocolo.

Para que a comunicação de dados obtenha sucesso ela necessita de três atributos:

- Entrega: os dados devem estar endereçados corretamente. Deve-se ter a certeza de que a informação será entregue ao destinatário correto.
- Confiabilidade: os dados devem chegar ao destino, e mais do que simplesmente chegar, os dados devem estar intactos, sem nenhum tipo de alteração e sem faltar nenhuma parte da informação.
- Controle do Atraso: o tempo que a informação possui para chegar ao destino não pode ser indeterminado. Deve haver um tempo limite para que o destinatário a receba, principalmente no caso de aplicações multimídia em tempo real como áudio e vídeo. Não seria interessante, por exemplo, ao receber um vídeo, ver primeiro as imagens e só depois ouvir o áudio.

## Taxa de transmissão

Ao se transmitir um arquivo, seja ele de que tipo for, pela rede, na realidade estão sendo transmitidos vários bits que, em conjunto, comporão o arquivo depois de processados. A taxa de transmissão de uma rede é a velocidade com a qual esses bits trafegam pelos meios de comunicação e é medida em bps (bits por segundo), ou seja, a quantidade de bits que são enviados em um segundo, portanto quanto maior a taxa de transmissão de uma rede, mais rápido o arquivo consegue ser transmitido do emissor para o receptor.

## Modos de operação

![Image](https://user-images.githubusercontent.com/45495068/182736472-99d96cd9-8f26-49c5-b69b-5a51b931767e.png)

Existem três tipos de operação na transmissão de dados: simplex, half-duplex e full-duplex. Vejamos como funciona cada uma delas:

- Simplex: a transmissão é unidirecional. Só existe um transmissor e um canal de transmissão. Quaisquer outros componentes que apareçam na comunicação serão receptores. Exemplos: televisão e radiodifusão.
- Half-duplex: a transmissão é bidirecional, ou seja, as duas partes transmitem e também são receptoras, mas, assim como no modo simplex, existe somente um canal de transmissão, portanto só é possível transmitir um por vez. Exemplo: walkie-talkie.
- Full-duplex: é o modo de transmissão mais completo, já que ambas as partes podem transmitir e receber dados simultaneamente, pois existem dois canais de transmissão. Exemplo: telefone.