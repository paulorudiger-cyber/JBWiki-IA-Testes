# JB_Folha_eSocial_s1250

URL: https://wiki.jbsoft.com.br/tiki-index.php?page=JB_Folha_eSocial_s1250

# 1. S-1250 - Aquisição de Produção Rural

Data da última atualização: 19/05/2021

### Tabela de conteúdo

- 1. S-1250 - Aquisição de Produção Rural

- 2. Como informar as aquisições de produção rural a partir da versão Simplificada do eSocial?

- 3. Conceito do evento:

- 4. Prazo de envio:

- 5. Informações por campo do leiaute:

- 6. Origem de busca de dados

- 6.1. 1-JB Folha (pacote 05062):

- 6.2. 2-JB Cepil (pacote 03270):

- 6.3. 3-ERP externo (arquivo XML):

- 7. FAQ - Como devem ser prestadas as informações quando o produtor rural pessoa física for optante pela contribuição sobre a folha de pagamentos?

# 2. Como informar as aquisições de produção rural a partir da versão Simplificada do eSocial?

- Ei, agora é pelo evento R-2055 da EDF-Reinf. Clique aqui para saber mais.

As informações abaixo servem apenas para histórico de como era realizado no sistema enquanto o evento S-1250 esteve vigente no eSocial. 

# 3. Conceito do evento:

- São as informações relativas à aquisição de produção rural de origem animal ou vegetal, adquiridas de Pessoas Físicas, com retenção de valores ou obrigação de pagamento de SENAR.

São considerados responsáveis pelo envio, todos os adquirentes tais como empresa adquirente, consumidora, consignatária, cooperativa e, inclusive, a pessoa física intermediária.

OBS: O JB Folha não faz o tratamento para adquirentes Entidade inscrita no PPA - Programa de Aquisição de Alimentos, nem para comprador CONAB - Companhia Nacional de Abastecimento.

# 4. Prazo de envio:

- Deve ser enviado até o dia 07 do mês seguinte ou antes do envio do fechamento dos eventos periódicos (evento S-1299 – Fechamento dos Eventos Periódicos), o que ocorrer primeiro. Antecipa-se o envio deste evento para o dia útil imediatamente anterior quando não houver expediente bancário.

- Alteração temporária de prazo:

- Consulte, clicando aqui, a alteração temporária de prazo, trazida pela Nota Orientativa 2019.18, que vai do período de Maio/2019 até a primeira competência em que o recolhimento do FGTS se fizer pela nova guia GRFGTS.

# 5. Informações por campo do leiaute:

- No arquivo abaixo são mostrados todos os campos enviados ao eSocial e os respectivos pacotes e itens que precisam ser revisados.

- Informações para o evento S-1250.

    ESocial S 1250 Para Clientes

# 6. Origem de busca de dados

- A origem de busca de dados para geração das informações para o evento, podem ser diversas e devem ser configuradas no pacote 05191 > eSocial > Produção rural > seção "Fonte de dados para o S-1250 - Aquisição de Produção Rural", sendo que a explanação de cada tipo está descrita a seguir:

- 1-JB Folha (pacote 05062)

- 2-JB Cepil (pacote 03270)

- 3-ERP externo (arquivo XML)

## 6.1. 1-JB Folha (pacote 05062):

- Quando o cliente não utiliza o sistema JB Cepil e o ERP não envia o evento e não disponibiliza os arquivos XMLs, então, não resta outra saída senão digitar as informações no sistema JB Folha para cumprir esta obrigação.

Desta forma, para que o sistema gere as informações, será necessário acessar o pacote "05062 - Movimentação dos Prestadores de Serviços" e inserir um registro, por produtor, por competência, que totalize os valores relativos às compras. Ou seja, uma vez por mês é necessário informar, por produtor, a soma de todas as notas de compra de produtor rural pessoa física.

Para que o sistema interprete e gere de forma correta o evento, será necessário que, no pacote 05061-Cadastro de prestadores de serviços, sejam observadas as configurações:

- Categoria:

Ela deve estar igual a 00-Segurado Especial ou 99-Comercialização de produção rural.

Caso o prestador não esteja com esta configuração, ele não será considerado na busca para geração, ou seja, ficará fora do evento S-1250.

- Tributação da Contribuição Previdenciária:

A opção deve ser indicada de acordo com a opção de tributação do produtor:

- 1-Sobre a comercialização da sua produção:

Segue as antigas diretrizes do FUNRURAL, onde há retenção de INSS sobre as notas de compra de produção rural, ou seja, tem tributação nos termos do §13, art. 25, da Lei 8.212/1991 e do art. 25, §7°, da Lei 8.870/1994.

Neste caso, será calculado o valor da retenção para os campos vrCPDescPR, vrRatDescPR e vrSenarDesc, considerando as alíquotas de 1,2% para CPP, 0,2% de SENAR e 0,1% de RAT.

- 2-Sobre a folha de pagamento:

Segue a opção inserida no §13, art. 25, da Lei 8.212/1991, de calcular os valores previdenciários sobre a folha dos empregados, em lugar de reter sobre sua produção, gerando no campo vrSenarDesc o valor aplicando 0,2% sobre a base informada (SENAR).

Neste caso, o produtor pessoa física, deve entregar aos seus compradores uma declaração indicativa de sua opção. A empresa compradora, de forma acessória, declarará apenas o valor relativo ao SENAR no campo "28 - vrSenarDesc" e indicará a opção do produtor no campo "29 - indOpcCP" do evento S-1250, conforme leiaute 2.5 11/2018. Porém, indicamos que os valores de SENAR não estão sendo integrados no eCac, sendo necessário emitir GPS avulsa relativa aos valores conforne instruções do eSocial.

## 6.2. 2-JB Cepil (pacote 03270):

- Quando o cliente utiliza o sistema JB Cepil, as notas relativas às compras de produtores Rurais já são escrituradas. Portanto, as informações serão buscadas daquela base para geração.

Sendo necessário efetuar as seguintes configurações:

- No pacote 05208-Configurações gerais JB Folha > menu Diretórios, indicar o "Diretório JB Cepil (windows)" para que o JB Folha busque as configurações de conexão do banco de dados.

- O usuário que fará a geração do S-1250, deverá estar cadastrado também no JB Cepil e, se necessitar realizar manutenções, deve ter permissão de acesso ao pacote 03270 das empresas com aquisição de produção rural.

No JB Cepil, deve-se escriturar as notas com os respectivos valores de retenção nos seguintes moldes:

- No pacote 3002:

- A conta de compra de produção rural deve estar indicada no campo "Quanto as retenções, a conta:" deve estar com "2- É base de retenção a recolher".

- Na aba "4 - Dados do fornecedor" deve:

- "Tipo de inscrição":

- Deve ser indicado como "2 - CPF".

- Caso esteja com "1 - CNPJ":

- Marcar a opção "Produtor rural"

- Preencher o campo ao lado "CPF Produtor Rural

- "Tributação contr. previdenciária": campo deve estar indicado conforme explanações a seguir:

- 1-Sobre a comercialização da sua produção:

Nesta caso, segue as diretrizes do antigo Funrural, realizando a retenção e informando de forma integral nos termos do §13, art. 25, da Lei 8.212/1991 e do art. 25, §7°, da Lei 8.870/1994.

- 2-Sobre a folha de pagamento:

Segue a opção do §13, art. 25, da Lei 8.212/1991, de calcular os valores previdenciários sobre a folha dos empregados, em lugar de reter sobre sua produção, porém, na escrituração, deve-se indicar como valor retido, exclusivamente o valor do SENAR.

Neste caso o Produtor pessoa física deve entregar aos seus compradores declaração indicativa de sua opção e a empresa realizará apenas a retenção do SENAR sobre os valores das notas.

- No pacote 3270:

Escriturar a nota fiscal de entrada, indicando o fornecedor pessoa física cadastrado no pacote 3002, com as indicações acima e,

- Quando for comercialização isenta de acordo com a Lei 13.606/2018:

Deve-se indicar como "1-Sim" no campo "Produção isenta (Lei 13.606/2018", na aba "Dados Básicos > Geral". Quando este campo é informado, o campo 20 - indAquis, será enviado com o código "4 - Aquisição da produção de produtor rural pessoa física ou segurado especial em geral - Produção Isenta (Lei 13.606/2018)"

A análise se a operação se enquadra nas disposições desta legislação é avaliação tributária de responsabilidade do profissional contábil, pois nosso foco, como fornecedores de software, é explanar o uso da aplicação e não a regulamentação.

- Se houve retenção, escriturar os dados no formulário de retenções, indicando:

- Base de cálculo

- Alíquota

- Valor retido - Este será o valor que será atribuído assim:

a) Se o produtor optou pela tributação pelo faturamento, o valor será atribuido integralmente como SENAR.

b) Para os demais, se houver valor de retenção, vai ratear os valores entre vrCPDescPR, vrRatDescPR e vrSenarDesc, considerando 1,2% para CPP, 0,2% de SENAR e 0,1% de RAT.

- Obs.: Somente será gerado no S-1250 as retenções lançadas com os códigos de impostos 0923 e 0924.

- Obs.: Para aparecer o código 0923 e 0924 bo pacote 3270, primeiro precisa configurar no pacote 3450> aba INSS- RF Cód. recolhimento.

## 6.3. 3-ERP externo (arquivo XML):

- Esta opção deve ser utilizada quando o ERP gera o arquivo XML. O valor de base de cálculo e distribuição dos valoresde vrCPDescPR, vrRatDescPR e vrSenarDesc, é de inteira responsabilidade do ERP, pois o JB Folha somente fará o processo de serviço de envio.

Porém, como alguns ERPs não tem um serviço de assinatura, envio e busca do status do evento no eSocial, é possível delegar esta fução para a JB Software realizar, informando esta condição no campo "Responsável envio":

- 1 - JB Software

Para que a JB Software consiga enviar estes eventos é necessário:

- Configurar a "Pasta dos XMLs":

Indicar a pasta onde o ERP ou o usuário irá copiar os eventos. Lembrando que os XMLs devem ser gerados no padrão do eSocial.

- Nome padrão do arquivo:

Para que o controle de mensageria possa realizar a transmissão é necessário que o nome do arquivo siga o seguinte padrão: eSocialS1250_Inscriçãoestabelecimento_competênciaAno.

Neste caso, como será o controle de mensageria que enviará os eventos, ao gerar o evento de fechamento (S-1299), o sistema da JB Software saberá se há ou não registros de produção Rural para alimentar o campo "21 - evtAqProd"

- 2 - ERP externo

Esta é a situação em que o ERP fará a geração do XML do evento S-1250, fará a transmissão e o controle diretamente em sua aplicação, sendo assim, esta configuração é necessária para que o JB Folha, ao gerar o evento de fechamento (S-1299), indique que há eventos Produção Rural no campo "21 - evtAqProd".

# 7. FAQ - Como devem ser prestadas as informações quando o produtor rural pessoa física for optante pela contribuição sobre a folha de pagamentos?

- Veja na página das FAQ do eSocial.
