
## Projeto de Teste MQTT com Python

###  Descrição

Projeto de teste de comunicação MQTT utilizando Python e a biblioteca paho-mqtt, realizando publicação e leitura de mensagens em um broker público (HiveMQ).

---

### Preparação do Ambiente

1. Instalar Python 3
2. Instalar a biblioteca MQTT:

```
pip install paho-mqtt
```

---

###  Arquivos do Projeto

* publisher.py → Responsável por publicar mensagens.
* subscriber.py → Responsável por receber mensagens.

---

### Como Executar

1. Abrir dois terminais na pasta do projeto.

2. No primeiro terminal executar:

```
python subscriber.py
```

3. No segundo terminal executar:

```
python publisher.py
```

4. Digitar uma mensagem no publisher e verificar o recebimento no subscriber.

---

###  Broker Utilizado

broker.hivemq.com
Porta: 1883
Tópico: senai/dev


