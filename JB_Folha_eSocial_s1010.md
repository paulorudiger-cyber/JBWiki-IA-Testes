# JB_Folha_eSocial_s1010

URL: https://wiki.jbsoft.com.br/tiki-index.php?page=JB_Folha_eSocial_s1010

# 1. S-1010 – Tabela de Rubricas

Data da última atualização: 17/05/2021

### Tabela de conteúdo

- 1. S-1010 – Tabela de Rubricas

- 1.1. Conceito do evento

- 1.2. Prazo de envio

- 1.3. Relacionamento das verbas do JB folha X Rubricas do eSocial

- 1.4. Auditoria tributária

- 1.4.1. Conferência verba a verba

- 1.4.2. Auditoria da JB Software

- 1.5. Auditoria dos dados do evento

- 1.6. Envio do evento para o ambiente oficial

## 1.1. Conceito do evento

- Apresenta o detalhamento das informações das rubricas constantes da folha de pagamento do declarante, permitindo a correlação destas com as constantes da “Tabela 3 – Natureza das Rubricas da Folha de Pagamento” do eSocial.

As informações consolidadas desta tabela são utilizadas para validação dos eventos de remuneração dos trabalhadores.

## 1.2. Prazo de envio

- Este evento deve ser enviado antes dos eventos relacionados à remuneração do trabalhador: S-1200, S-2299 e S-2399.

## 1.3. Relacionamento das verbas do JB folha X Rubricas do eSocial

- Antes de iniciar qualquer processo de envio das verbas para o portal do eSocial é necessário fazer o relacionamento das verbas do JB Folha com a tabela de Rubricas do eSocial, de acordo com a Tabela 3 no leiaute do eSocial.

Este relacionamento é efetuado através do pacote 05295-Relacionamento de verbas com as naturezas de rubricas do eSocial.

Os dados enviados para o eSocial e sua respectiva localização no sistema, podem ser conferidos aqui.

## 1.4. Auditoria tributária

- Para evitar notificações é importante conferir a tributação das verbas do JB Folha dentro do padrão de interpretação governamental.

Dois processos precisam ser realizados:

- Conferência verba a verba e

- Utilização da auditoria da JB Software.

### 1.4.1. Conferência verba a verba

- Implica em passar cada uma das verbas, no pacote 05051-Tabela de verbas, verificando se os campos de tributação estão corretamente configurados para os seguintes tributos:

- INSS

- FGTS

- IRRF

### 1.4.2. Auditoria da JB Software

- Nos debruçamos sobre a tabela de Rubricas e a legislação, com apoio de algumas consultorias e incluímos em nossa aplicação o entendimento tributário preponderante para uma gama grande de rubricas.

Assim, após realizar o relacionamento individual o processo de auditoria é chamado e são mostradas as divergências tributárias, se houverem.

A auditoria pode ser chamada, também, a qualquer momento pelo formulário 05298-Auditoria tributária das verbas por natureza de rubrica e as divergências, se houverem, podem ser alteradas chamando o botão ação.

Obs.: Não é porque a verba aparece com divergência que ela deve ser modificada. O processo tem como intuito auxiliar as empresas a encontrar as verbas que podem gerar complicações futuras. É o colaborador que fará os ajustes, o conhecedor da utilização da verba, e deverá alterá-la com base no seu entendimento ou de acordo com as definições da empresa e/ou consultoria tributária.

Até porque, podem haver verbas tributadas e não tributadas que precisam ser vinculadas à mesma Rubrica, como a exemplo do Auxilio Educação.

Veja mais informações sobre as configurações de incidências no pacote 05296-Incidência das naturezas de rubricas.

## 1.5. Auditoria dos dados do evento

- O formulário de auditoria é o "05346 - Auditoria da tabela de rubricas", que, além de "traduzir" os erros, possui botões de acesso rápido para os formulários e campos com erros.

## 1.6. Envio do evento para o ambiente oficial

- Após realizado o processo completo de saneamento dos dados, então, deve-se realizar o envio do evento para o ambiente oficial.

Para realizar este processo a partir do pacote 05051-Tabela de verbas clique no botão eSocial. Ou, vá ao pacote 05283-Geração de eventos para o eSocial, informe a empresa no campo de pesquisa “Empresa” e escolha o evento S-1010.

Quando o envio é realizado de forma individualizada, não haverá consulta se existem cálculos com esta verba, ou seja, se o usuário está usando o envio individualizado é porque ele deseja enviá-lo mesmo que não tenham cálculos efetuados.

Não há problema em enviar todas, mesmo que não tenham vínculos. A JB Software, via pacote 05283, optou por não enviar registros sem cálculo nos últimos 12 meses, unicamente para reduzir o volume de processamento em lote, deixando o processo mais rápido
