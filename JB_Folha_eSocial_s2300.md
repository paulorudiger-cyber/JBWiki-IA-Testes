# JB_Folha_eSocial_s2300

URL: https://wiki.jbsoft.com.br/tiki-index.php?page=JB_Folha_eSocial_s2300

# 1. S-2300 – Trabalhador Sem Vínculo de Emprego/Estatutário - Início

Data da última atualização: 18/05/2021

### Tabela de conteúdo

- 1. S-2300 – Trabalhador Sem Vínculo de Emprego/Estatutário - Início

- 1.1. Conceito do evento

- 1.2. Prazo de envio

- 1.3. Conferência dos dados do trabalhador

- 1.4. Situações diversas

- 1.4.1. Qual a categoria do TSVE para Sócio/Proprietários de Empresa, Membros de Conselho e CBO?

- 1.4.2. Sócio/Proprietário precisa ter cargo e CBO?

- 1.4.3. Qual CBO devo utilizar?

- 1.4.4. Ministro de confissão religiosa (padres, pastores, rabinos, etc.)

- 1.4.5. Síndico de condomínios

- 1.5. Agendamento do envio

## 1.1. Conceito do evento

- Este evento é utilizado para prestar informações cadastrais relativas a trabalhadores que não possuem vínculo de emprego/estatutário com o declarante.

O evento S-2300 será utilizado em dois momentos

a) para carga dos dados dos TSVEs ativos no momento de início da obrigatoriedade dos eventos não periódicos ao eSocial ou

b) no momento da Admissão ou Ingresso de TSVE.

É obrigatório o envio do evento S-2300 para as seguintes categorias de trabalhadores:

- 201-Trabalhador Avulso Portuário

- 202-Trabalhador Avulso Não Portuário

- 304-Servidor público exercente de mandato eletivo, inclusive com exercício de cargo em comisão

- 305-Servidor Público indicado para conselho ou órgão deliberativo, na condição de representante do governo, órgão ou entidade da administração pública

- 308-Conscritos

- 401-Dirigente Sindical - informação prestada pelo Sindicato

- 410-Trabalhador cedido/exercício em outro órgão/juiz auxiliar - Informação prestada pelo cessionário/destino

- 721-Contribuinte individual - Diretor não empregado, com FGTS

- 722-Contribuinte individual - Diretor não empregado, sem FGTS

- 723-Contribuinte individual - empresários, sócios e membro de conselho de administração ou fiscal

- 731-Contribuinte individual - Cooperado que presta serviços por intermédio de Cooperativa de Trabalho

- 734-Contribuinte individual - Transportador Cooperado que presta serviços por intermédio de cooperativa de trabalho

- 738-Contribuinte individual - Cooperado filiado a Cooperativa de Produção

- 761-Contribuinte individual - Associado eleito para direção de Cooperativa, associação ou entidade de classe de qualquer natureza ou finalidade, bem como o síndico ou administrador eleito para exercer atividade de direção condominial, desde que recebam remuneração

- 771-Contribuinte individual - Membro de conselho tutelar, nos termos da Lei nº 8.069, de 13 de julho de 1990

- 901-Estagiário

- 902-Médico Residente

Obs. muito importante:

Para as categorias de cooperados, categorias 731, 734 e 738, era hábito cadastrar como contribuintes individuais pelo pacote 05061-Cadastro de Prestadores de Serviços, gerando um RPA para estes trabalhadores no pacote 05227-Cadastro de RPAs.

A partir do advento do eSocial não será mais possível realizar o processo por este cadastro simplificado, pois para o eSocial eles somente são aceitos no evento S-2300, com uma carga inicial, de forma semelhante aos empregados.

Desta forma, para quem tem cooperados é necessário cadastrá-los no pacote 05027-Cadastro do trabalhador (empregados e TSVE) e indicar as verbas para ser inseridas no cálculo da folha, e não mais por meio de um RPA.

Para os demais prestadores de serviços de forma autônoma, não serão enviados dados cadastrais, somente o evento S-1200 e S-1210 com dados básicos.

## 1.2. Prazo de envio

- Deve ser transmitido até o dia 15 (quinze) do mês subsequente ao da sua ocorrência.

## 1.3. Conferência dos dados do trabalhador

- Antes de iniciar o processo de envio do evento S-2300, é necessário conferir os dados do trabalhador, de forma semelhante ao evento S-2200.

Os dados enviados para o eSocial e sua respectiva localização no sistema, podem ser conferidos aqui.

As informações abaixo, podem ser consultadas clicando no respectivo link, pois são iguais às do evento S-2200.

- Revisão dos dados dos trabalhadores

- Auditoria dos dados

- Envio do evento para o ambiente oficial

Observação

Apenas os TSVs cadastrados no 05027-Cadastro de empregados serão enviados através do S-2300. Ao selecionar o botão eSocial no pacote 5027, o sistema habilitará a opção S-2200 ou S-2300, conforme a categoria do trabalhador. 

## 1.4. Situações diversas

### 1.4.1. Qual a categoria do TSVE para Sócio/Proprietários de Empresa, Membros de Conselho e CBO?

- A Categoria deve seguir as instruções contidas na coluna Representante da Entidade, da tabela de Naturezas Jurídicas, contida no Anexo V da IN RFB 1634/2016.

Com base neste dispositivo, não há uma única resposta para esta questão, é preciso analisar a natureza e avaliar se ela deve ser representada por Administrador, Presidente, Administrador, Sócio, Proprietário, etc.

De acordo com as nossas pesquisas, catalogamos que as seguintes Naturezas Jurídicas 206, 207, 208, 212, 213, 223, 224, 225, 226, 230 e 231, que, pela definição técnica do MOS o TSVE deve ser inserido com a categoria "723 - Contribuinte individual - empresários, sócios e membros de conselho de administração ou fiscal".

### 1.4.2. Sócio/Proprietário precisa ter cargo e CBO?

- Sim, em razão das especificações contidas na Tabela de Resumo dos Registros, destacada no grupo "cargoFuncao", que indica como obrigatório, exceto para as categorias 901, 903 e 904.

### 1.4.3. Qual CBO devo utilizar?

- Existem vários CBOs que tem como sinônimo "Sócio", "Empregador", "Proprietário", "Lojista", "Atacadista"

Acessem o pacote 05036 ou no pacote 05290 (neste, no Lkp de pesquisa do CBO 2002, pressione F4 ou clique no botão com 3 pontos):

- Mudem o campo de pesquisa para Descrição e

- No campo Filtrar, digitem Sócio ou Empregador ou Proprietário.

Retornarão algumas categorias CBOs para utilização:

- 1412 - No ramo de indústria.

- 1414 - No ramo de comércio e serviço.

- 1415 - No ramo de turistmo.

- 61 - Nos ramos de rurais.

- Para localizar melhor qual CBO utilizar, faça uma nova pesquisa:

- No pacote 05290, no Lkp de pesquisa do CBO 2002, pressione F4 ou clique no botão com 3 pontos.

- Mude a condição do campo "Pesquisar por" para CBO.

- No campo Condição, mude para "Iniciando com".

- Digite a inicial do grupo que deseja analisar, tal como "1412", "1414", "1415", etc.

- Localize uma descrição próxima do desejado dentro da Família de acordo com a atividade da empresa.

Não existe uma descrição para cada ramo de negócio, então localize alguma descrição próxima ou por analogia.

Por exemplo, para os sócios da JB Software não localizamos um Sócio ou Proprietário de empresa de software. Porém, encontramos na família de CBO "1414 - GERENTES DE OPERACOES COMERCIAIS E DE ASSISTENCIA TECNICA", os sinônimos de LOCADOR/ALUGADOR e como nossa atividade principal é Locação de Software, que se equipara a Bens Móveis, nós seguimos por esta linha, sendo que então adotamos o 1414-10.

### 1.4.4. Ministro de confissão religiosa (padres, pastores, rabinos, etc.)

- Tendo em vista que para esta atividade existem tratamentos específicos, vimos aqui indicar como informar estes trabalhadores no JB Folha para atender as necessidades do eSocial. Como exemplos de ministros, podemos citar, entre outros: padres, pastores, rabinos, sacerdotes, obreiros, cooperadores, presbíteros, anciãos, coroinhas, etc.

Vejamos o texto destacado no Inciso II, § 1º, art. 1º da Lei 6.696/1979

"&sect; 1º São equiparados aos trabalhadores autônomos:'
...
II - os ministros de confissão religiosa, e os membros de institutos de vida consagrada e de congregação ou ordem religiosa, estes quando por elas mantidos, salvo se:
a) filiados obrigatoriamente à previdência social em razão de outra atividade;
b) filiados obrigatoriamente a outro regime oficial de previdência social, militar ou civil, ainda que na condição de inativo.

- No JB Folha é possível tratar este tipo de trabalhador de duas formas: RPA ou cadastrando no pacote 05027. Leia as duas formas antes de definir qual é a que melhor se adecua ao seu caso.

- Cadastrando no 05027:

Esta opção deve ser utilizada quando o ministro de confissão religiosa recebe verbas além daquelas destinadas ao ofício de confissão religiosa, que precisam ser destacadas em documento e/ou possuem tributação de INSS e FGTS.

No RPA não há como destacar múltiplas verbas com tratamentos tributários distintos, assim é preciso cadastrar o TSVE para poder fixar ou digitar estas verbas adicionais para demonstrar no recibo e recolher os valores previdenciários.

Quando tratamos de verbas adicionais, podemos destacar as verbas de auxílio moradia, auxílio educação, como palestras fora do meio religioso, etc.

Para usar esta metodologia deve-se:

a) Cadastrar o ministro no pacote 05027, seguindo todas as necessidades destacadas para outros TSVEs.

b) Indicar que não deverá participar da RAIS (aba Complementares, o campo "Contar da RAIS).

c) Indicar a categoria 781 (aba Contrato, o campo "Categoria do Trabalhador).

d) Colocar no salário o valor que ele recebe por esta atividade (aba Contrato, o campo "Valor do Salário", Clicar no Livrinho).

Neste caso, ao realizar o cálculo da folha, o sistema irá inserir a verba com a característica 4ZC - CONGRUAS, PREBENDAS E AFINS, não fará cálculo do INSS desconto do trabalhador, nem do INSS patronal sobre esta verba, pois o seu recolhimento previdenciário deve ser realizado como contribuinte individual (o conhecido carnê).

Para as demais verbas digitadas, o sistema obedecerá as incidências indicadas no cadastro de cada verba.

- Cadastrando no 05061 para geração de RPA:

Conforme informações do MOS: "Quando o Ministro de confissão religiosa receber retribuição por tarefa ele deve ser cadastrado na categoria 701–Contribuinte individual - Autônomo em geral, exceto se enquadrado em uma das demais categorias de contribuinte individual e não na categoria 781–Ministro de confissão religiosa ou membro de vida consagrada, de congregação ou de ordem religiosa, que é reservada apenas para aquele que, em face do seu mister religioso ou para sua subsistência, recebe valor fornecido em condições que independam da natureza e da quantidade do trabalho executado."

Então, nessa situação onde ele recebe por tarefa, NÃO deve ser cadastrado no 05027, sendo obrigatório seu cadastro como prestador de serviço no pacote 05061, com Categoria 13 e Categoria do eSocial como 701.

Veja instruções detalhadas para o lançamento, conforme a situação no evento S-1200.

### 1.4.5. Síndico de condomínios

- O tratamento de sindicos é similar aos pró-laboristas, a única diferença é a categoria do trabalhador que deve ser 761.

Esta informação está no pacote pacote 05027, aba Contrato, o campo "Categoria do Trabalhador"

## 1.5. Agendamento do envio

- Este evento possui envio agendado ao eSocial.

Como assim?

Assim que você cadastrar um novo TSVE no pacote 05027-Cadastro do trabalhador (Empregados e TSVE), o evento já será agendado no sistema.

Clique aqui e veja todos os detalhes.
