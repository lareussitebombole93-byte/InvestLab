# 💰 InvestLab

Projeto prático de simulação e comparação de investimentos de longo prazo.

## 🎯 Sobre o projeto
O InvestLab permite que o usuário simule quanto seu dinheiro pode render ao longo do tempo, aplicando juros compostos com aportes mensais. O projeto foi construído para mostrar como a tecnologia pode ajudar nas decisões financeiras.

## 🛠️ Tecnologias Utilizadas
- **HTML5**: Estrutura da página.
- **CSS3**: Estilização personalizada (tema escuro focado em UX).
- **JavaScript**: Lógica de negócio e cálculos matemáticos.
- **Chart.js**: Biblioteca para renderização do gráfico de evolução patrimonial.

## 🧮 Fórmulas e Premissas Financeiras
- **Taxa de Juros**: Utilizamos uma taxa hipotética de 10% ao ano, convertida para mensal através da fórmula de juros compostos: `taxaMensal = Math.pow(1 + taxaAnual, 1/12) - 1`.
- **Aportes**: Consideramos que os aportes mensais são feitos no **final** de cada mês.
- **Cálculo**: A fórmula utilizada foi `M = P * (1+r)^n + A * [((1+r)^n - 1) / r]`, onde `P` é o valor inicial, `A` é o aporte, `r` é a taxa mensal e `n` é o número de meses.
- **Aviso**: Todos os resultados são estimativas baseadas nas premissas informadas e não representam garantia de rentabilidade.

## ⚙️ Como executar
Basta abrir o arquivo `index.html` em qualquer navegador moderno. Não é necessário instalar nenhum servidor.