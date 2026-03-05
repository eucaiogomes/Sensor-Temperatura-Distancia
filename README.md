# 📏 Sensor de Distância - HC-SR04

Projeto de monitoramento utilizando ESP8266 para leitura de distância e integração com sistema web em tempo real.

---

## 🔎 Sensor Utilizado

**Modelo:** HC-SR04  
**Tipo:** Sensor Ultrassônico de Distância  

O sensor HC-SR04 funciona emitindo um pulso ultrassônico e medindo o tempo que o eco leva para retornar, permitindo calcular a distância até o objeto.

📚 Fonte de estudo:  
Sensor Ultrassônico HC-SR04 | MakerHero

---

## ⚡ Alimentação

- VCC: 5V  
- GND: GND  
- Trigger: 3.3V (compatível com ESP8266)  
- Echo: 5V ⚠️ (necessário divisor de tensão para usar no ESP8266)

> O pino ECHO envia sinal em 5V.  
> O ESP8266 trabalha com 3.3V.  
> É obrigatório utilizar divisor de tensão para evitar danos ao microcontrolador.



## 📚 Bibliotecas Utilizadas

- Ultrasonic  
- OneWire  
- DallasTemperature  
- ESP8266WiFi  
- ESP8266WebServer  


## 👨‍💻 Desenvolvido por

Projeto acadêmico Senai 2026, materia de IOT.
