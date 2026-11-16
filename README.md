# 💰 InvestLab - Simulador de Investimentos

Este projeto foi desenvolvido como requisito para a disciplina de Desenvolvimento Web. O InvestLab é uma plataforma que permite simular o crescimento de um patrimônio ao longo do tempo, utilizando juros compostos com aportes mensais.

## 🔗 Link do Projeto Publicado
O site está disponível em: https://lareussitebombole93-byte.github.io/InvestLab/

## 🛠️ Tecnologias Utilizadas
- **HTML5**: Estruturação da página.
- **CSS3**: Estilização com design moderno (tema claro, inspirado em fintechs).
- **JavaScript**: Lógica de negócio e cálculos matemáticos.
- **Chart.js**: Biblioteca utilizada para gerar os dois gráficos dinâmicos (Linha e Rosca).

## 🧮 Fórmulas e Premissas Financeiras
- **Taxa de Juros**: Utilizamos uma taxa hipotética de 10% ao ano, convertida para mensal através da fórmula de juros compostos: `taxaMensal = Math.pow(1 + taxaAnual, 1/12) - 1`.
- **Aportes**: Consideramos que os aportes mensais são feitos no **final** de cada mês.
- **Cálculo**: A fórmula utilizada foi `M = P * (1+r)^n + A * [((1+r)^n - 1) / r]`, onde `P` é o valor inicial, `A` é o aporte, `r` é a taxa mensal e `n` é o número de meses.
- **Gráficos**: O gráfico de linha mostra a evolução mês a mês. O gráfico de rosca mostra a proporção entre o valor investido (aporte + inicial) e os juros ganhos.
- **Aviso**: Todos os resultados são estimativas baseadas nas premissas informadas e não representam garantia de rentabilidade.

## ⚙️ Como executar
Basta abrir o arquivo `index.html` em qualquer navegador moderno.
