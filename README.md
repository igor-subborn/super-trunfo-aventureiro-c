# Desafio Super Trunfo - Países (Nível Aventureiro)

Olá! Eu passei por este desafio de **Super Trunfo - Países**. Aqui mostro a minha implementação do **nível Aventureiro**, criando um sistema completo de cadastro e análise de cartas.

Este repositório contém um programa em C onde faço o **cadastro de cartas** usando `scanf` para ler os valores e `printf` para exibir os resultados. Também implemento **cálculos automáticos** de propriedades derivadas para uma análise mais profunda dos dados. O objetivo é familiarizar-me com entrada/saída de dados, estruturas simples e operações matemáticas.

## 🧩 O que eu construí

- Um sistema robusto para cadastrar cartas de cidades de um país fictício.
- Cada carta representa uma cidade e possui propriedades básicas:
  - **População**
  - **Área**
  - **PIB**
  - **Número de pontos turísticos**
- As cartas são codificadas com uma letra (A–H) para o estado e um número (1–4) para a cidade (por exemplo, `A01`, `B03`).

### 📈 Propriedades Calculadas

Além das propriedades básicas, meu programa calcula automaticamente:
- **Densidade Populacional:** Resultado da divisão entre população e área
- **PIB per Capita:** Resultado da divisão entre PIB total e população

Essas propriedades são calculadas em tempo real e exibidas junto com os dados básicos, oferecendo uma análise mais completa de cada cidade.


## 🛠️ Como usar

```bash
gcc SuperTrunfoAventureiro.c -o SuperTrunfoAventureiro
./SuperTrunfoAventureiro
```

Boa programação!

*— Igor-Subborn*