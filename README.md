# 📘 Lista de Exercícios em C

Projeto desenvolvido em linguagem C contendo a resolução de múltiplos exercícios acadêmicos envolvendo conceitos fundamentais de programação e matemática.

## 🚀 Sobre o Projeto

Este programa apresenta um **menu interativo no terminal**, permitindo ao usuário escolher entre diferentes exercícios:

- 📊 Cálculo de Média e Desvio Padrão  
- ➗ Inequação Quociente  
- 📈 Tipos de Média (Aritmética, Ponderada e Harmônica)  
- 💰 Cálculo de Bônus de Natal  

O objetivo é reforçar conceitos como:
- Estruturas condicionais (`if`, `switch`)
- Entrada e saída de dados (`scanf`, `printf`)
- Operações matemáticas
- Organização de código em funções

---

## 🧠 Funcionalidades

### 1️⃣ Média e Desvio Padrão
- Calcula a média de três números
- Calcula o desvio padrão usando a fórmula matemática

### 2️⃣ Inequação Quociente
- Verifica se um número satisfaz a inequação:
  
  (x - 3) / (2x - 4) <= 0

- Trata divisão por zero (quando `x = 2`)

### 3️⃣ Tipos de Média
Permite escolher entre:

- 📌 Média Aritmética  
- 📌 Média Ponderada (pesos: 3, 3 e 4)  
- 📌 Média Harmônica (com validação para evitar divisão por zero)

### 4️⃣ Bônus de Natal 🎄
Calcula o bônus baseado em:
- Sexo do funcionário
- Tempo de trabalho
- Salário

#### Regras:
- 👨 Masculino:
  - ≥ 15 anos → 20% de bônus
  - < 15 anos → R$100 fixo
- 👩 Feminino:
  - ≥ 10 anos → 25% de bônus
  - < 10 anos → R$100 fixo

---

## 🛠️ Tecnologias Utilizadas

- Linguagem C
- Bibliotecas:
  - `stdio.h`
  - `stdlib.h`
  - `math.h`
  - `locale.h`

---

## ⚠️ Tratamento de Erros

O programa inclui validações importantes:

- ❌ Evita divisão por zero
- ❌ Verifica entradas inválidas no menu
- ❌ Impede cálculo da média harmônica com valores zero
- ❌ Valida opções de tipo de média e sexo

---

## 📂 Estrutura do Código

- `menu()` → Exibe o menu principal  
- `main()` → Controla o fluxo do programa e executa os exercícios  

---

## 🎯 Objetivo Acadêmico

Este projeto foi desenvolvido com foco em:

- Prática de lógica de programação
- Aplicação de conceitos matemáticos
- Desenvolvimento de soluções estruturadas em C

---

## 📌 Melhorias Futuras

- [ ] Implementar interface gráfica (GUI)
- [ ] Permitir repetição automática do menu
- [ ] Modularizar cada exercício em funções separadas
- [ ] Validação mais robusta de entrada de dados

---

## 👨‍💻 Autor

**Vinicius Souza Vazquez**  
🎓 Estudante de Engenharia da Computação  

---

## ⭐ Contribuição

Sinta-se à vontade para:
- Dar uma ⭐ no repositório
- Sugerir melhorias
- Fazer um fork do projeto