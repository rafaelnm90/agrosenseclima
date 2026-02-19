# 🚜 Painel AgroSense

> **Inteligência Climática & Mercado Agrícola**

O **Painel AgroSense** é um dashboard web focado na tomada de decisão rural. Diferente de previsões comuns, ele utiliza um motor de decisão exclusivo (V16) que cruza dados de 6 fontes diferentes (Juízes) para determinar o risco real de tempestades, volume de chuva e janelas de plantio/colheita.

## 🚀 Funcionalidades Principais

### 🌦️ Inteligência Climática (Motor V16)
O sistema analisa dados horários da API Open-Meteo e aplica regras agronômicas rigorosas:
* **Os 6 Juízes:** Algoritmo que pondera Chuva (mm), CAPE (Energia), Código WMO, Vento (Gate), Saturação e Nuvens.
* **Alerta Inteligente:** O sistema só emite **ALERTA VERMELHO 🚨** se houver volume significativo de chuva (>5mm) ou risco severo, evitando alarmes falsos para ventos secos ou garoa.
* **Monitoramento Local:** Focado nas estações de Uberlândia, Tupaciguara, Lavras e Fazenda.

### 📈 Mercado & Commodities
Acompanhamento em tempo real e histórico de variação (1 dia a 1 ano) para:
* 🐮 Pecuária (Boi Gordo, Vaca, Novilha)
* 🌽 Grãos (Milho, Soja, Café)
* 💵 Financeiro (Dólar, Bitcoin)

## 🛠️ Tecnologias Utilizadas
* **Frontend:** HTML5, JavaScript (ES6+), TailwindCSS (Estilização), Chart.js (Sparklines).
* **Backend / Proxy:** Google Apps Script (Processamento de JSON e Cache).
* **Fonte de Dados:** Open-Meteo API e Google Sheets.
* **Hospedagem:** Vercel.

---

### 👨‍💻 Desenvolvedor
**Rafael Novais de Miranda**
* 📧 rafaelnovaismiranda@gmail.com

© 2026 Painel AgroSense. Todos os direitos reservados.
