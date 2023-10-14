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
* Visão de Receitas e Despesas.

## Processos de Integração e Carga (ETL)
Através das 3 bases principais acima e sabendo que o cliente gostaria de ver, realizamos as realações conforme imagem abaixo, assim como criamos 6 fórmulas Dax para acompanhamento de indicadores específicos
![etl](https://github.com/chscharth/Analise_de_Dados_Loteria/assets/85425294/5d9d7f43-c5fb-493d-af25-d5f8f44fa720)

## O Dashboard
O Resultado do Trabalho pode ser acessado nos links abaixo

[Painel Loteria 1](https://app.powerbi.com/view?r=eyJrIjoiZTk3ZGZlNGQtZGQwMS00NWNiLTg2ODgtZWRiOTVkY2FhOGI2IiwidCI6ImVlODdkOWJlLTRiZDMtNDYzOC04MWIzLTE1OGU0ZjIxNDczYSJ9)

[Painel Loteria 2](https://app.powerbi.com/view?r=eyJrIjoiMDhhY2YzYzktYjIzNS00ZWUyLTllOWMtNTA5NGM3ZjJjN2Q2IiwidCI6ImVlODdkOWJlLTRiZDMtNDYzOC04MWIzLTE1OGU0ZjIxNDczYSJ9)

## Conclusões
* Vimos através do Paretto em quais produtos estão alocadas 80% das vendas da loja.
* Conseguimos identificar qual o jogo que tem a maior margem liquida.
* Conseguimos identificar seja por volume de venda ou valor, quem são as operadoras que mais vendem.
* Podemos ver por dia da semana o nosso movimento em termos de valor de venda.
* Conseguimos dividir quais receitas são oriundas de jogos e quais receitas vem de demais atividades como pagamento de contas e etc.
* Temos um Ranking geral de Quantidade, Valor Bruto e Valor Líquido de Vendas.
* Um Gráfico para acompanharmos mensalmente a evolução das receitas e despesas.

### Com as informações acima, o gesto agora pode:
* Premiar e direcionar respectivamente as vendendoras que vendem mais e menos.
* Direcionar esforços de venda nos produtos que deixam mais margem a loja.
* Identificar tendências de receitas e despesas, sabendo assim se algo está fora do padrão.
* Identificar dias com maior e menor vendas para ações de marketing nas lojas.

**DISCLAIMER - PARA PROTEGER A SEGURANÇA DAS INFORMAÇÕES, TODOS OS DADOS APRESENTADOS FORAM RANDOMIZADOS**
