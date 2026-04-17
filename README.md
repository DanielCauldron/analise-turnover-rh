# HR Turnover Analysis

Análise de rotatividade de funcionários desenvolvida em Power BI com foco em identificar padrões de desligamento e apoiar decisões de retenção de talentos.

---

## 📊 Dashboard

<img width="1232" height="699" alt="dashboard_preview png" src="https://github.com/user-attachments/assets/988236b7-0ff9-4956-9ec6-3993563ef12a" />


---

## 🎯 Objetivo

Identificar onde e por que a empresa está perdendo funcionários, cruzando dados de departamento, motivo de saída e faixa salarial.

---

## 💡 Principais Insights

- Taxa de turnover de **52%** — índice elevado
- Funcionários saem em média com **2,3 anos** de casa
- **54% das saídas** foram por pedido próprio
- Média salarial dos desligados (**R$ 3.380**) é **R$ 1.220 menor** que a dos ativos
- Comercial, Operações e TI concentram o maior volume de desligamentos
- TI perdeu 2 funcionários para concorrência — sinal de defasagem salarial

---

## 🛠️ Ferramentas

- Power BI (DAX, Power Query)
- CSV como fonte de dados

---

## 📁 Estrutura do Projeto

```
hr-turnover-analysis/
├── data/        → base de dados
├── pbix/        → arquivo Power BI
├── assets/      → imagens do dashboard
└── README.md    → documentação
```

---

## 🔄 Etapas do Projeto

1. Recebimento e exploração da base de dados
2. Tratamento e limpeza no Power Query (padronização de categorias, tratamento de nulos)
3. Criação de coluna de Status (Ativo / Desligado)
4. Modelagem e criação de medidas DAX
5. Construção do dashboard com foco em decisão

---

## 📐 Medidas DAX Criadas

| Medida | Descrição |
|---|---|
| Total Funcionarios | Contagem total de registros |
| Total Ativos | Funcionários sem data de saída |
| Total Desligados | Funcionários com saída registrada |
| Taxa Turnover | % de desligados sobre o total |
| Tempo Medio Casa | Média de anos até o desligamento |
| Media Salarial Ativos | Média salarial de quem ainda está na empresa |
| Media Salarial Desligados | Média salarial de quem saiu |

---

## 👤 Autor

Daniel Cauldron
[LinkedIn](https://www.linkedin.com/in/daniel-caldeirao/) | [GitHub](https://github.com/DanielCauldron)
