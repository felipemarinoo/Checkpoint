# 🪙 Projeto: Crypto Monitor

## 👨‍💻 Desenvolvido por:
**Felipe Marino**  
**RM: 98805**

---

## 📱 Descrição do Projeto

O **Crypto Monitor** é um aplicativo Android desenvolvido em **Kotlin** que consome a API REST do site Mercado Bitcoin para exibir a **cotação atual do Bitcoin (BTC)**. 

Este projeto tem como objetivo aplicar conceitos de:
- Consumo de API externa com Retrofit
- Tratamento de dados JSON
- Arquitetura RESTful
- Atualização em tempo real de valores via GET

---

## 🌐 API Utilizada

- **URL base:** `https://www.mercadobitcoin.net/api/BTC/ticker/`

### 🔁 Exemplo de retorno (JSON)
```json
{
  "ticker": {
    "high": "14481.47000000",
    "low": "13706.00002000",
    "vol": "443.73564488",
    "last": "14447.01000000",
    "buy": "14447.00100000",
    "sell": "14447.01000000",
    "date": 1502977646
  }
}
```

- O valor exibido no app é o **"last"**, que representa o preço da **última negociação** de Bitcoin.

---

## 🔧 Funcionalidades

- Consulta automática da cotação do Bitcoin via requisição GET
- Exibição em tempo real do valor do BTC
- Interface simples e funcional

---

## 🛠 Tecnologias Utilizadas

- Android Studio (Kotlin)
- Retrofit (HTTP Client)
- JSON Parsing
- RESTful API
- Material Design

---

## 🖼️ Prints das Telas

> 🔎 Imagens ilustrativas com a exibição da cotação do BTC (adaptadas do repositório original)

<p align="center">
  <img src="https://raw.githubusercontent.com/carreiras/kotlin-android-crypto-monitor/master/images/img1.png" width="250"/>
  <img src="https://raw.githubusercontent.com/carreiras/kotlin-android-crypto-monitor/master/images/img2.png" width="250"/>
</p>

---

## 🧪 Como Rodar o Projeto

> ⚠️ **Observação**: este projeto requer o Android Studio para ser executado.

1. Clone o repositório:
```bash
git clone https://github.com/carreiras/kotlin-android-crypto-monitor.git
```

2. Abra o projeto no Android Studio.
3. Rode em um emulador Android ou dispositivo físico conectado.

---

## 📚 Conceitos Abordados

- **REST**: arquitetura de serviços baseada em HTTP (GET, POST, PUT, DELETE)
- **JSON**: estrutura leve para transporte de dados
- **HTTP Status Codes**: códigos de resposta como `200 OK`, `404 Not Found`, etc.
- **Retrofit**: biblioteca para requisições HTTP em apps Android

---

## ✅ Conclusão

Este projeto demonstra, de forma prática, como integrar um app Android com uma API pública da web para obter dados em tempo real e exibi-los ao usuário de forma clara e objetiva.

---

📁 [Repositório Base no GitHub](https://github.com/carreiras/kotlin-android-crypto-monitor)
