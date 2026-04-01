# 📖 Semana 02 - Simulador de CPU (Little Man Computer)

## 🎯 Objetivo

Compreender como um processador executa instruções através do simulador **Little Man Computer (LMC)**.

---

## 📚 Conceitos Abordados

### O que é Little Man Computer?

O LMC é um simulador educacional que representa uma CPU simplificada. É composto por:

- **Memória**: 100 posições (00-99) para armazenar instruções e dados
- **Accumulator (ACC)**: Registro que armazena o resultado de operações
- **Program Counter (PC)**: Rastreia qual instrução está sendo executada
- **ALU (Arithmetic Logic Unit)**: Realiza operações matemáticas e lógicas

### Instruções Básicas

| Código | Mnemônico | Descrição |
|--------|-----------|-----------|
| 1xx | LDA | Load - Carregar valor da memória no ACC |
| 2xx | STA | Store - Armazenar ACC na memória |
| 3xx | ADD | Adicionar valor ao ACC |
| 4xx | SUB | Subtrair valor do ACC |
| 5xx | OUT | Output - Exibir ACC |
| 6xx | IN | Input - Ler valor para ACC |
| 7xx | BRA | Branch - Pular para instrução |
| 8xx | BRZ | Branch if Zero - Pular se ACC = 0 |
| 9xx | BRP | Branch if Positive - Pular se ACC ≥ 0 |
| 0xx | HLT | Halt - Parar execução |

---

## 🖼️ Arquivos da Semana

- **[octostudio.txt](./octostudio.txt)** - Arquivo do OctoStudio
- **[lmc_screenshot.png](./lmc_screenshot.png)** - Print da execução do simulador

---

## 💡 Aprendizados Principais

1. ✅ Como instruções são armazenadas em memória
2. ✅ O ciclo Fetch-Decode-Execute (FDE)
3. ✅ Como dados fluem através de um processador
4. ✅ Conceitos de registadores e memória
5. ✅ Lógica de controle de fluxo (loops, branches)

---

## 🔗 Recursos

- **Simulador Online**: [101computing.net/LMC](https://www.101computing.net/LMC/)

---

## 📝 Reflexões

Este simulador foi essencial para solidificar meu entendimento sobre como processadores funcionam no nível mais fundamental. Ver o ciclo FDE em tempo real ajudou a desmistificar a "magia" por trás da execução de programas.

---

**Semana completada**: ✅ 2026-04-01