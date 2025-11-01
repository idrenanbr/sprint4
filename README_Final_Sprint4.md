# 🌞 SolarFlowAI – Solução Final Integrada e Inovadora GoodWe

**Sprint 4 – FIAP 2025 – Ciência da Computação**

---

## 🎯 Objetivo

Entregar uma **solução integrada, funcional e inovadora**, totalmente alinhada ao desafio proposto pela **GoodWe** e às **competências do curso de Ciência da Computação da FIAP**.

---

## 📹 Vídeo da Solução Final

🎥 **Assista à demonstração completa no YouTube:**  
[https://youtu.be/LX5uhUGmkdU](https://youtu.be/LX5uhUGmkdU)

---

## 🧩 Descrição Geral

**SolarFlowAI** é um sistema inteligente de gerenciamento de energia solar que integra:
- Inversor híbrido **GoodWe GW5000‑EH**
- Bateria **LiFePO₄ 10 kWh 48 V**
- Sensores **IoT (ACS712, DS18B20)** controlados por **ESP32**
- Backend em **Node.js + MQTT (Mosquitto)**
- Dashboard em **React + Tailwind CSS**
- Controle por voz via **Amazon Alexa** e **Google Assistant**

A solução permite **monitorar geração, consumo e armazenamento de energia em tempo real**, além de **otimizar o uso** por meio de três modos automáticos: **Economia, Conforto e Inteligente**.

---

## 🏗️ Arquitetura Final Integrada

```
Painéis Solares → Inversor GoodWe → Bateria LiFePO₄
                         │
                      ESP32 + Sensores
                         │ MQTT
                   Backend Node.js (API)
                         │ REST/WS
      Dashboard React  ←→ Alexa / Google Assistant
```

---

## 📊 Resultados e Métricas

| Indicador | Valor | Observação |
|------------|--------|------------|
| Eficiência do sistema | **96,2 %** | conversão solar → utilizável |
| Aproveitamento solar | **73 %** | energia solar vs. total consumida |
| Economia semanal | **R$ 98,50** | com tarifa média R$ 0,65/kWh |
| CO₂ evitado | **≈ 86 kg/semana** | equivalente a 6 árvores |
| Payback | **7 anos e 2 meses** | investimento ≈ R$ 40 mil |
| ROI em 25 anos | **256 %** | economia ≈ R$ 142 mil |

---

## 🌱 Sustentabilidade e Inovação

- Redução direta de emissões e dependência da rede elétrica.  
- Uso de **inteligência de modos** para otimizar o autoconsumo.  
- Interface inclusiva e acessível.  
- Integração **voz + dados + automação** inédita em projeto acadêmico.  

---

## 🔍 Análise Crítica

**Limitações atuais**
- Dados simulados; integração Modbus real planejada para 2026.  
- Falta de persistência em MongoDB e histórico de uso.  
- Calibração física dos sensores em andamento.  

**Próximos passos**
- Implementar telemetria real GoodWe.  
- Adicionar ML para predição de geração/consumo.  
- Publicar Alexa Skill e Google Action oficial.  

---

## 📚 Aderência PCAP / SERS

| Requisito GoodWe / Disciplina | Implementação SolarFlowAI |
|--------------------------------|---------------------------|
| Inversor híbrido | GoodWe GW5000‑EH (Modbus/HTTP) |
| Armazenamento HV | Bateria LiFePO₄ 10 kWh 48 V |
| Monitoramento IoT | ESP32 + MQTT (Mosquitto) |
| Controle inteligente | Modos Economia / Conforto / Inteligente |
| Visualização de dados | Dashboard React + Tailwind |
| Automação por voz | Alexa / Google Assistant |
| Sustentabilidade | Redução CO₂ + ROI positivo |

---

## 👥 Equipe

- **Auro Vanetti — RM 563761**  
- **Enzo H. K. Nishida — RM 565052**  
- **Francisco B. N. Neto — RM 565868**  
- **Kaio Correa — RM 563443**  
- **Renan Mano Otero — RM 554911**  

**Curso:** Ciência da Computação — FIAP 2025  

---

## 📄 Licença

Projeto sob **Licença MIT**.  
Documento elaborado para a **Sprint 4 – Solução Final Integrada e Inovadora GoodWe (Outubro 2025)**.

---
