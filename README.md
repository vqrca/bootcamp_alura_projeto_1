<p align="center">
  <img src="https://github.com/vqrca/bootcamp-alura-2021-modulo-01/blob/main/imagem2.png" />
</p>

---

# **Bootcamp de Data Science Aplicada: Módulo 01: Python e Pandas para Análise de Dados Reais**

Este é o projeto do módulo 01, desenvolvido no Bootcamp Data Science Aplicada 2, da Alura. 
O Módulo 01 foi sobre Python e pandas para análise de dados reais. Neste módulo foi possível aprender como utilizar Python, Pandas e Matplotlib para explorar os dados financeiros do SUS, mais precisamente os gastos por Unidade Federativa ao longo dos anos. Após aprender como realizar essas análises, foi possível desenvolver esse projeto, onde o objetivo era analisar uma outra informação referente a base de dados de produção hospitalar, seja número de internação, óbito, dias de permanência, taxa de mortalidade ou qualquer outra informação disponível no banco de dados do DATASUS. 

# **Projeto desenvolvido**: **Análise dos Gastos Hospitalares do SUS (Sistema Único de Saúde) e Evolução das Taxas de Mortalidade no Brasil**

A aquisição dos dados foi realizada na base de dados governamental de [Produção Hospitalar](https://www2.datasus.gov.br/DATASUS/index.php?area=0202&id=11633&VObj=http://tabnet.datasus.gov.br/cgi/deftohtm.exe?sih/cnv/qi), que disponibliza uma série de informações como número de internação, dias de permanência, procedimentos, exames, atos médicos realizados, diagnóstico,
motivo da alta, número de óbitos, taxa de mortalidade, etc. 

As unidades hospitalares participantes do SUS (públicas ou particulares conveniadas) enviam as informações das internações efetuadas através da AIH - *Autorização de Internação Hospitalar*, para os gestores municipais (se em gestão plena) ou estaduais (para os demais). Estas informações são consolidadas no DATASUS, formando uma valiosa Base de Dados, contendo dados de grande parte das internações hospitalares realizadas no Brasil. 

Os dados são disponibilizados em duas formas diferentes: 

- **Por ano e mês de processamento**

  Período do processamento da informação, sendo igual ao mês anterior ao da
apresentação da AIH para faturamento.

- **Por ano e mês de atendimento**

  Período correspondente à data de internação do paciente na unidade hospitalar.

## **Estrutura do projeto:**

Este projeto está dividido em três partes:

1.   Análise dos gastos hospitalares totais em todos os Estados Brasileiros

2.   Análise do número de internações em todos os Estados Brasileiros

3.   Análise do número de óbitos e taxa de mortalidade em todos os Estados Brasileiros

Portanto, os objetos delimitados dentro desses tópicos foram:
- Quais estados têm mais gastos hospitalares? 
- Qual a relação de gastos nas regiões brasileiras?
- Os gastos são proporcionais ao tamanho populacional de cada Estado? 
- Há picos de gastos períodos associados com surtos de doenças? 
- O aumento de gastos e internações estão crescendo juntos? 
- Qual a média de internações por ano?
- Qual é a taxa de mortalidade por ano em cada Estado?
- A taxa de mortalidade aumentou após a pandemia de Sars-CoV-2? 

## **Dados utilizados**

**Valor total**

Valor referente às AIH aprovadas no período. Este valor não obrigatoriamente
corresponde ao valor repassado ao estabelecimento, pois, dependendo da situação das unidades, estes recebem recursos orçamentários ou pode haver retenções e pagamentos de incentivos, não aqui apresentados. Portanto, este valor deve ser considerado como o valor aprovado da produção.

**Internações**

Quantidade de AIH aprovadas no período, não considerando as de prorrogação (longa permanência). Este é um valor aproximado das internações, pois as transferências e reinternações estão aqui computadas. 

**Óbitos**

Quantidade de internações que tiveram alta por óbito, nas AIH aprovadas no período.

**Taxa de Mortalidade**

Razão entre a quantidade de óbitos e o número de AIH aprovadas, computadas como
internações, no período, multiplicada por 100.

---

## **Um pouco sobre mim**

Sou bióloga e tenho Doutorado em Biotecnologia pela Universidade de Mogi das Cruzes. Atuo na área de Microbiologia, com ênfase em Biologia Molecular e Genômica. Possuo conhecimentos sólidos das técnicas comumente empregadas em genômica estrutural e genômica funcional. Atualmente, sou Pesquisadora Colaboradora no programa de Biossistemas da Universidade Federal do ABC.

---

## **Onde encontrar meu trabalho?**

[LinkedIn](https://www.linkedin.com/in/valqu%C3%ADria-alencar-786a8911b/)

[ResearchGate](https://www.researchgate.net/profile/Valquiria-Alencar)

[Currículo lattes](http://lattes.cnpq.br/7742338443535710)

---

