# Tutorial: Usando o DHT22 com ESP32

## 1. Preparar o Mecanismo

Conecte a placa **ESP32** na **Protoboard**:  

<img src="https://github.com/GustavoLoghan/Sensor_DHT22/blob/main/2/WhatsApp%20Image%202025-08-27%20at%2013.58.46.jpeg" width="400"/>

Em seguida, conecte os fios nos seus respectivos lugares:

- O **cabo preto** no **GND**
- O **cabo vermelho** no **5V/VIN**
- O **cabo laranja** no **Pino Digital**

<img src="https://github.com/GustavoLoghan/Sensor_DHT22/blob/main/2/WhatsApp%20Image%202025-08-27%20at%2013.37.24.jpeg" width="400"/>

---

## 2. Baixe a Biblioteca `Bonezegei_DHT11`

É necessário baixar esta biblioteca, pois ela contém funcionalidades que serão implementadas no código.  

<img src="https://github.com/GustavoLoghan/Sensor_DHT22/blob/main/2/Captura%20de%20tela%202025-08-27%20142821.png" width="400"/>

---

## 3. Código 🧑‍💻

Escreva o seguinte código para fazer o **DHT22** funcionar corretamente:  

<img src="https://github.com/GustavoLoghan/Sensor_DHT22/blob/main/2/WhatsApp%20Image%202025-08-27%20at%2013.37.10.jpeg" width="400"/>

### Explicação do Código:

- Primeiramente, importe a biblioteca baixada anteriormente com `#include`
- Defina o **pino digital** em que seu DHT22 está conectado
- No `void setup()`, inicialize o sensor com `dht.begin();`
- No `void loop()`, coloque o código de coleta de informações:
  - Ele irá capturar os dados usando as variáveis `tempDeg` (temperatura) e `hum` (umidade)
  - Os dados serão exibidos no monitor serial utilizando concatenação de strings

---

## 4. Conecte a Placa no Computador

O cabo Utilizado foi um **"Micro USB"**.  

<img src="https://github.com/GustavoLoghan/Sensor_DHT22/blob/main/2/WhatsApp%20Image%202025-08-27%20at%2013.58.14.jpeg" width="400"/>

---

Aviso: A imagem apresentada apresenta somente a conexão com o cabo, nenhum outro componente se encontra em uso.

---

## 4.1 Gravando no ESP32

Clique na **seta no canto superior esquerdo** da IDE (normalmente o Arduino IDE) para carregar o código para a placa.

<img src="https://github.com/GustavoLoghan/Sensor_DHT22/blob/main/2/Captura%20de%20tela%202025-08-27%20143351.png" width="400"/>

---

## 4.5 Caso de Erro "BOOT"

Se sua placa for um modelo mais simples, pode ser necessário:

1. Pressionar o botão **BOOT** enquanto o código está sendo enviado
2. Soltar o botão assim que a conexão for estabelecida

---

## 5. Seja Feliz 🎉

Se você seguiu todos os passos corretamente, tudo deve estar funcionando perfeitamente! 😁👍

---
