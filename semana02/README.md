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

### OctoStudio

![Image](https://github.com/user-attachments/assets/8598db0e-9d1d-401e-bee8-18d9c80fcc4d)

### Little Man Computer

![Image](https://github.com/user-attachments/assets/da239db2-4833-4dfc-9320-d8ea306504ab)
