# 📑 Sistema de Folha de Pagamento (Python)

Este projeto é um **sistema de folha de pagamento** feito em Python, que permite cadastrar funcionários, calcular seus descontos obrigatórios (INSS, IR e sindicato) e exibir o salário líquido final.  

Foi desenvolvido com base nas **tabelas de desconto de 2025** para INSS e IR.  

---

## ⚙️ Funcionalidades

✔️ Cadastrar funcionários informando:
- Nome
- Valor da hora trabalhada
- Quantidade de horas no mês  

✔️ Calcular automaticamente:
- Salário bruto (valor da hora × quantidade de horas)  
- INSS (de acordo com a faixa salarial de 2025)  
- IR (Imposto de Renda, considerando desconto do INSS antes)  
- Sindicato (5% fixo do salário bruto)  
- Salário líquido (quanto realmente sobra depois dos descontos)  

✔️ Listar todos os funcionários cadastrados com seus respectivos cálculos  

✔️ Excluir funcionário da lista pelo nome  

✔️ Menu interativo com as opções:
1. Cadastrar Funcionário  
2. Listar Funcionários  
3. Excluir Funcionário  
4. Sair do sistema  

---

## 🧮 Fórmulas utilizadas

- **Salário Bruto** = valor_hora × quantidade_horas  
- **INSS** = cálculo progressivo (dependendo da faixa salarial de 2025)  
- **IR** = cálculo em cima do salário já com desconto do INSS  
- **Sindicato** = 5% do salário bruto  
- **Salário Líquido** = salário bruto - (INSS + IR + sindicato)  

---

## ▶️ Como usar

1. Abra o código em qualquer editor Python (ex: VS Code, PyCharm ou IDLE).  
2. Execute o programa.  
3. Use o menu para:  
   - Cadastrar funcionários  
   - Listar funcionários  
   - Excluir funcionários  
   - Encerrar o programa  

---

## 📌 Observações

- O cálculo do INSS e IR está baseado nas **tabelas de 2025**.  
- Caso o usuário não preencha algum campo no cadastro, o programa avisa que todos os campos são obrigatórios.  
- O sistema roda em **loop** até o usuário escolher a opção de sair.  

---
