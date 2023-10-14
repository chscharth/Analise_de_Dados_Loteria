# Dasboards Loterias

## Contexto
Fomos abordados por um cliente que precisava de um painel com os dados que ssuas loterias geravam. Por mais que a loteria ja possuísse um sistema de controle, a massa de dados diária e a falta de cruzamento de dados interna não facilitava as análises relevantes por parte do gestor.

## Objetivos
O Objetivo principal era identificar junto ao cliente, os principais indicadores que seriam acompanhados e construír um painel estruturado que facilitasse na tomada de decisão.

## Público alvo
Gestor (Dono) das Loterias

## Fontes de Dados
Foram Extraídas informações do sistema atual de gestão em 3 Dimensões distintas que são:
* Venda por Produto.
* Venda por Funcionário
* Visão de Receitas e Despesas

## Processos de Integração e Carga (ETL)
Houve uma integração das datas entre as 5 bases utilziadas, através da criação de um calendário padronizado. No momento não houve a necessidade de uma estruturação mais complexa, porem, para podermos contextualizar os dados inseridos, assim como realizar a criação dos 16 Indicadores Obrigatórios e a criação do Censo do setor, onde medimos quantidade de procedimentos por cirurgão, divisão por faixa etária e porte de cirurgia, foram criadas mais de 30 interaçãoes através de Fórmulas DAX.

## O Dashboard
https://app.powerbi.com/view?r=eyJrIjoiZTk3ZGZlNGQtZGQwMS00NWNiLTg2ODgtZWRiOTVkY2FhOGI2IiwidCI6ImVlODdkOWJlLTRiZDMtNDYzOC04MWIzLTE1OGU0ZjIxNDczYSJ9
https://app.powerbi.com/view?r=eyJrIjoiMDhhY2YzYzktYjIzNS00ZWUyLTllOWMtNTA5NGM3ZjJjN2Q2IiwidCI6ImVlODdkOWJlLTRiZDMtNDYzOC04MWIzLTE1OGU0ZjIxNDczYSJ9


## Conclusões
Com a visualização estruturada dos dados conseguimos determinar que o nosso perfil majoritário é feminino e está entre os 40 e 79 anos, sendo o perfil mais proeminete o perfil de 50-59, verifcamos também que nosso foco são cirugias de pequeno porte e eletivas, além disso percebemos que para um centro cirúgico aberto 24h por dia e 7 dias por semana, o perfil médio de 300 cirurgias é pouco e por sí só e em termos de capacidade instalada, ele pode dobrar de tamanho, porem isso depende da quantidade de leitos hospitalares para absorver o paciente pós cirúrgico, assim como a agenda dos cirurgiões para horários diferenciados (noite, madrugada), verificamos também que a taxa de cancelamento vem aumentando e precisa ser adereçada, quanto ao número de atrasos vemos uma pequena variação na casa dos 40%, o que é valor consideravelmente alto e que deve ser sanado o quanto antes, além disso de fato relevante temos a quantidade de preenchimentos incompletos do formulário de cirurgia segura, o que se trata de um indicador que deve ser zero, de resto temos ótimos números quanto a cirurgias em pacientes errados, local de cirurgia errada e queda, onde temos zero eventos. 
Como proposta de melhorias, foi sugerida a instalação de um comitê multidiscipliar para o acompanhamento e construção/execução de planos de ação para mitigação dos indicadores negativos, assim como para entender o porque da baixa adesão cirúrgica de pacientes masculinos e planos de aumento estruturado de cirurgias realizadas no hospital. 

**DISCLAIMER - PARA PROTEGER A SEGURANÇA DAS INFORMAÇÕES, TODOS OS DADOS APRESENTADOS FORAM RANDOMIZADOS**
