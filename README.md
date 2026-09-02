# Consumo e Energia Python

Calculadora de Consumo de Energia

* Sobre o projeto

A Calculadora de Consumo de Energia é um programa desenvolvido em Python que permite estimar quanto um aparelho elétrico consome de energia durante um mês.

O usuário informa o nome do aparelho, sua potência em watts e o tempo médio de utilização por dia. O programa calcula o consumo mensal estimado em kWh e também apresenta uma estimativa de custo.

* Objetivo

O objetivo do projeto é facilitar a compreensão do consumo de energia elétrica dos aparelhos utilizados no dia a dia.

🛠️ Tecnologias utilizadas
🐍 Python
💻 Visual Studio Code
🐙 Git e GitHub
🧮 Fórmula utilizada

O consumo mensal é calculado utilizando a seguinte fórmula:

consumoMensal = (potencia × horasDia × 30) / 1000

Onde:

potencia = potência do aparelho em watts (W)
horasDia = tempo médio de uso diário
30 = quantidade aproximada de dias no mês
1000 = conversão de Wh para kWh

*  Cálculo do custo

Também é utilizado um valor fixo de R$ 0,75 por kWh para estimar o custo mensal:

custoMensal = consumoMensal × 0,75

O valor de R$ 0,75 é apenas uma estimativa e pode ser alterado no código de acordo com o preço do kWh.

*  Como executar
1. Clone o repositório
git clone URL_DO_SEU_REPOSITORIO
2. Entre na pasta do projeto
cd consumo-energia
3. Execute o programa
python app.py

* Exemplo de uso
=== Calculadora de Consumo de Energia ===

Digite o nome do aparelho: Geladeira
Digite a potência do aparelho (W): 150
Digite o tempo médio de uso diário (horas): 10

=== Resultado ===
Aparelho: Geladeira
Consumo estimado: 45.00 kWh/mês
Custo estimado: R$ 33.75 por mês
* Estrutura do projeto

consumo-energia/
├── app.py
└── README.md
👨‍💻 Autor

Projeto desenvolvido como atividade de iniciação em tecnologia.
