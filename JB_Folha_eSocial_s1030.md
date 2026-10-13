# JB_Folha_eSocial_s1030

URL: https://wiki.jbsoft.com.br/tiki-index.php?page=JB_Folha_eSocial_s1030

### S-1030/S-1035/S-1040 - Funções e cargos

Este evento foi descontinuado a partir da versão S-1.0 do eSocial. Suas informações serão prestadas diretamente nos eventos S-2200 ou S-2300.

As informações abaixo servem apenas para histórico de como era realizado no sistema enquanto o evento esteve vigente no eSocial. 

- Tratamentos gerais

- Conferência dos dados das funções:

Antes de iniciar o processo de envio do evento S-1030, é necessário conferir os dados dos cargos. Atenha-se, principalmente, se o CBO indicado corresponde às atividades principais executadas por quem está alocado neste cargo.

O pacote que precisa ser ajustado é o 5290.

Foram inclusos neste formulário os campos início e fim de vigências dos cargos. A finalidade é desabilitar o uso nos casos em que o cargo não é mais utilizado. Assim, caso um trabalhador esteja sendo admitido em data posterior a data de fim, o cargo não será mais mostrado para alocação do trabalhador.

Quando o(s) evento(s) S-1030, S-1040 e S-1045 forem gerados pelo pacote 5283, o sistema gerará apenas os registros dos cargos que são utilizados para empregados ativos desde a data de início da empresa no eSocial.

Agora, se o usuário vai no pacote 5290, em um cargo que está finalizado, por exemplo, e clica no botão enviar e autoriza a remessa para o eSocial, o evento será enviado mesmo assim.

Por quê?

Porquê no pacote de cadastro o controle é sempre do usuário. Ou seja, é o usuário que determina se quer que enviar o evento para o eSocial, e não a aplicação.

Esta opção pode ser útil nos casos em que o trabalhadro foi demitido antes da vigência do eSocial e a empresa precisa pagar verbas retroativas e o cargo que o trabalhador estava já não está mais em vigência, como é o caso de Stock Options.

- Auditoria dos dados:

Existem duas formas de auditar os dados para saber se passarão no eSocial.

A primeira, é enviando os eventos para o ambiente de teste.

A segunda, é utilizando o formulário de auditoria:

- "5349 - Auditoria da tabela de cargos/empregos públicos", para auditar o evento S-1030.

- "5348 - Auditoria da tabela de carreiras públicas", para auditar o evento S-1035.

- "5351 - Auditoria da tabela de funções/cargos em comissão", para auditar o evento S-1040.

Estes pacotes, além de "traduzir" os erros, possuem botões de acesso rápido para os formulários e campos com erros.

- Envio do evento de teste:

Antes de realizar o envio oficial, é prudente realizar o envio para o ambiente de testes.

Para isto, confira a forma de envio de testes em configurar ambiente para envio.

O evento S-1030 é obrigatório para todos os tipos de empresas. Já os eventos S-1035 e S-1040 são exclusivos para órgão ou empresas públicas e/ou de economia mista.

- Envio do evento para o ambiente oficial:

Após realizado o processo completo de saneamento dos dados, então, deve-se realizar o envio do evento para o ambiente oficial.

Para realizar este processo, mude o ambiente para o oficial, se estiver usando o ambiente de teste, conforme descrito no item configurar ambiente para envio e, estando no pacote 5290 clique no botão eSocial para envio da função corrente. Para envio de todas as funções, vá ao pacote 5283 e escolha o(s) evento(s) S-1030, S-105 e S-1040.

Quando o envio é realizado de forma individualizada, não haverá consulta se existem vínculos com o empregado, ou seja, se o usuário está usando o envio individualizado é por que ele deseja enviá-lo mesmo que não tenham empregados vinculados.

Caso queira enviar todos os cargos com vínculo de uma só vez, utilize o formulário 5283 indique a empresa e escolha o evento S-1030, S-1035 e S-1040.

Não há problema em enviar todos mesmo que não tenham vínculos. A JB Software, via pacote 5283, optou por não enviar registros sem vínculo para reduzir o volume de processamento em lote e deixar o processo mais rápido

- Alteração de função ou cargo no empregado

- Caso um trabalhador seja movimentado de um cargo para outro, a alteração deve ser realizada no cadastro do trabalhador, pacote 5027, na aba "Contrato", no campo "Cargo/Ocupação", clicar no botão do livrinho e indicar o novo cargo.

Caso o cargo não exista, cadastrar um novo, enviar para o eSocial e aguardar o retorno como OK, antes de enviar a alteração individual do trabalhador, para não ocorrer retorno de erro de que o cargo não existe.

Quando for salvar o empregado, o sistema solicitará se a mudança se refere a uma retificação ou uma alteração. Como estamos tratando de uma movimentação de cargo, que pode ser por mérito ou promoção, deve-se enviar um S-2206 indicando a data de início de vigência, ou seja, a partir de quando o trabalhador está sendo alocado no novo cargo.

- Alteração no cadastro de funções e cargos: Efeitos

- O conceito de tabela e ligações estrangeiras, nasce com os banco de dados relacionais para evitar redundância de informações. Assim, quando um cargo é vinculado para um trabalhador e há uma alteração de descrição ou CBO, nas regras de programação, estas alterações são refletidas de forma automática e imediata no cadastro do trabalhador.

Porém, para o eSocial, este conceito não foi reconhecido. Quando há uma alteração no cadastro de uma tabela é necessário passar, trabalhador a trabalhador, enviando uma alteração.

Não há esclarecimento em documentação oficial como MOS, leiautes ou Notas Técnicas. Nos e-mails que circulam no Fórum da Fenainfo, houve uma pergunta neste sentido e, para nossa surpresa, a resposta do desenvolvedor de uma das empresas do G28 foi bem inusitada e no sentido acima. O mesmo posicionamento obtivemos em palestras realizadas pelos integrantes do projeto (MTE e RFB). Ou seja, a indicação é de que há necessidade de uma alteração contratual para que a mudança cadastral tenha reflexo no Retrato do Vínculo (S-2200/S-2300: Ficha do trabalhador). Encaminhamos uma consulta oficial, e obtivemos o mesmo retorno (transcrita abaixo).

ENTÃO, CASO UM CARGO SEJA MODIFICADO, apesar de no XML do S-2200/S-2300 somente ser indicado o código, é necessário ir no formulário de cadastro de TODOS os trabalhadores (5027) que utilizam este cargo e enviar um S-2206/2306 como retificação ou alteração para confirmar o código e atualizar o retrato do vínculo. Sendo que, para alteração, é necessário indicar a competência em que a o novo cargo passa a ter efeito.

- Vejamos parte da discução:

==================================================================
Pergunta Original:
==================================================================
From: ......
Sent: Monday, April 16, 2018 08:35
To: forumesocial@fenainfo.org.br
Subject: Dúvida de retificação
------------------------------------------------------------------
Olá.

.....

Num caso semelhante, tenho o S1030 enviado com CBO X. E vários S2200 referenciando à este cargo. Se descobrir que o CBO inicialmente enviado no S1030 não deveria ser X, mas sim Y, tenho que retificar o 
S1030. Os S2200 que foram com este cargo devem ser retificados também, ainda que o XML seja idêntico?

Grato pelas respostas...

==================================================================
Pergunta Original:
==================================================================
From: ....
Sent: Em 16 de abril de 2018 10:35
To: forumesocial@fenainfo.org.br
Subject: RE: Dúvida de retificação
------------------------------------------------------------------

Bom dia......

Caso se perceba que o CBO no evento S-1030 foi errado, e deveria ser '2222-33' desde o princípio, deve-se alterar o S-1030 com a data de validade original corrigindo a informação. Logo, deve-se SIM, mandar retificações de S-2200 e S-2206 para que no <contrato> que é o retorno do S-2200 tenha a informação atualizada. O mesmo vale para Horários e Turnos. Caso isso não seja feito, caracteriza-se "alteração indireta do contrato de trabalho", segundo instrução do Ministério do Trabalho.

Abraço

F....

- Segue nossa consulta ao sítio do eSocial e seu retorno:

==================================================================
====================================================================================================
PERGUNTA REALIZADA POR MEIO DE CONSULTA AO GRUPO GESTOR DO eSOCIAL
====================================================================================================
---------- Mensagem encaminhada ----------
De: Esocial Producao <esocial-producao@esocial.gov.br>
Data: 10 de maio de 2018 14:37
Assunto: Re: S-2200 – Cadastramento Inicial do Vínculo e Admissão/Ingresso de Trabalhador
Para: schmeda@gmail.com


Olá, boa tarde!

A informação procede.
Alterações de tabela não altera a informação em eventos já enviados.

Att

eSocial
INSS

--------------------------------------------------------
De: "Contato eSocial" <contato@esocial.gov.br>
Para: "Destinatários" <esocial-producao@esocial.gov.br>
Cc: esocial-producao@esocial.gov.br
Enviadas: Terça-feira, 24 de abril de 2018 14:09:40
Assunto: S-2200 – Cadastramento Inicial do Vínculo e Admissão/Ingresso de Trabalhador

AMBIENTE DE PRODUÇÃO EMPRESAS

Indique o problema encontrado
Dúvida
Razão Social
JB SOFTWARE LTDA
CNPJ
82.891.821/0001-20
E-mail
schmeda@gmail.com
Nome do responsável
Márcio Schmeling
Telefone de contato
(49) 3366-1621
Sua mensagem
Bom dia, 

Na nossa empresa, um cargo fictício de código "1" e descrição "ABCD" foi enviado com um CBO específico "6543-21" no evento S-1030. Vários empregados foram enviados através do evento S-2200 referenciando este cargo de código "1". 

Entretanto, mais tarde percebi que o CBO do cargo "1" deveria ser "6666-45", então remeti uma retificação deste cargo (evento S-1030). 

Nesta situação, pelo fato do evento S-2200 só referenciar o código, entendemos que não seria necessário enviar uma alteração (S-2206) ou retificação do evento S-2200, pois não há alteração de informações para geração do XML, o conteúdo é exatamente igual. Já que pela normalização das tabelas, a informação foi alterada indiretamente no evento S-1030. 

Porém, mesmo não havendo instruções no leiaute e no MOS do eSocial, alguns colegas têm comentado que o Ministério do Trabalho exige que haja retificações também dos eventos S-2200 ou S-2206, pois o retrato do vínculo está presente no retorno dos eventos S-2200 e S-2206 (conforme manual do desenvolvedor V.1.6.4), portanto ele precisa ser atualizado também. 

Gostaríamos de confirmar se estas afirmações procedem, pois entendemos que isto não deveria ser necessário. 

Att.

- Como localizar todos os trabalhadores que utilizam este cargo?

No formulário 5027, botão imprimir, visualize o relatório 12 e com o CTRL+F localize pela descrição do cargo todos os empregados que utilizam o cargo modificado.

Anote em uma planilha e vá para o pacote 5027,clique no botão eSocial e envie um evento S-2206 ou S-2306 para cada um dos trabalhadores envolvidos.
