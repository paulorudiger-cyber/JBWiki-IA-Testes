# JB_Folha_eSocial_s2230

URL: https://wiki.jbsoft.com.br/tiki-index.php?page=JB_Folha_eSocial_s2230

# 1. S-2230 - Afastamento Temporário

Data da última atualização: 18/05/2021

### Tabela de conteúdo

- 1. S-2230 - Afastamento Temporário

- 1.1. Conceito do evento

- 1.2. Prazo de envio

- 1.3. Conferência dos dados dos afastamentos

- 1.4. Agendamento do envio

- 1.5. Envio do evento para o ambiente oficial

- 1.6. Alteração e retificação do evento

- 1.6.1. Alteração

- 1.6.2. Retificação

- 1.7. Observações

## 1.1. Conceito do evento

- Evento utilizado para informar os afastamentos temporários dos trabalhadores, por quaisquer dos motivos elencados na “Tabela 18 – Motivos de Afastamento” do eSocial, bem como eventuais alterações e prorrogações.

Caso o empregado/servidor possua mais de um vínculo, é necessário o envio do evento para cada um deles.

## 1.2. Prazo de envio

- O evento de afastamento temporário deve ser informado nos seguintes prazos:

- a) Afastamento temporário ocasionado por acidente de trabalho ou doença decorrente do trabalho com duração não superior a 15 dias, deve ser enviado até o dia 15 (quinze) do mês subsequente da sua ocorrência.

- b) Afastamento temporário ocasionado por acidente de trabalho, acidente de qualquer natureza, ou doença com duração superior a 15 dias deve ser enviado até o 16º dia da sua ocorrência.

- c) Afastamentos temporários ocasionados pelo mesmo acidente ou doença não relacionados ao trabalho, que ocorrerem dentro do prazo de 60 dias e totalizarem, no somatório dos tempos, duração superior a 15 dias, independentemente da duração de cada afastamento, devem ser enviados, individualmente, até o dia em que são completados 16 dias de afastamento.

- d) Afastamento por acidente ou doença relacionados ou não ao trabalho, com qualquer duração, quando ocorrer dentro do prazo de 60 dias do retorno de afastamento anterior pela mesma doença, que tenha gerado recebimento de auxílio-doença, deve ser enviado no primeiro dia do novo afastamento.

- e) Afastamento por inatividade de trabalhador avulso, portuário ou não portuário, pelo código 34 da Tabela 18 deve ser enviado a partir do 91º dia de inatividade.

- f) Demais afastamentos devem ser enviados até o dia 15 (quinze) do mês subsequente ao da sua ocorrência.

- g) Términos de afastamento devem ser enviados até o dia 15 (quinze) do mês subsequente à competência em que ocorreu o retorno.

## 1.3. Conferência dos dados dos afastamentos

- Ao efetuar o cadastro de um afastamento pelo pacote 05022-Cadastro de situações/afastamentos, o próprio sistema já efetua as validações e emite mensagens de aviso, para evitar que faltem informações ao eSocial.

Para os afastamentos que foram realizados antes da inserção do campo "Motivo de afastamento eSocial" e que tem não tem data de fim informada, ou a data fim está dentro do período da obrigatoriedade do eSocial, devem conferir se o campo possui informação para não gerar erro no envio do evento S-2200.

Os dados enviados para o eSocial e sua respectiva localização no sistema, podem ser conferidos aqui.

## 1.4. Agendamento do envio

- Este evento possui envio agendado ao eSocial.

Como assim?

Assim que você cadastrar um novo afastamento/situação para o trabalhador no pacote 05022-Cadastro de situações/afastamentos, o evento já será agendado no sistema.

Clique aqui e veja todos os detalhes.

## 1.5. Envio do evento para o ambiente oficial

- Para realizar este processo, estando no pacote 05022-Cadastro de situações/afastamentos, clique no botão eSocial, selecione a opção de Abertura ou de Fechamento. Ou, vá ao pacote 05283-Geração de eventos para o eSocial, aba 2-Não periódicos, informe o período (já virá atualizado com o período corrente - serão filtrados os empregados ativos no período informado), a empresa e o(s) trabalhador(es) desejados. Escolha o evento S-2230 na grade e clique no botão Enviar Oficial.

## 1.6. Alteração e retificação do evento

### 1.6.1. Alteração

- A única possibilidade de envio de alteração do evento S-2230 ocorre quando for alterada a informação do campo “Motivo afastamento eSocial”, do código 01-Acidente/Doença do trabalho para o 03-Acidente/Doença não relacionada ao trabalho ou 03 para 01. Nesta situação será emitida a seguinte mensagem de confirmação:

Com essa alteração será necessário enviar um novo evento "S-2230-Afastamento temporário" de retificação. No leiaute existe o campo infoRetif com as informações de retificação do afastamento temporário, que podem ser informadas pelo botão “Inf. Retificação”. Deseja cadastrar essas informações agora?

Caso selecionar a opção Sim, o pacote de Informações de retificação do afastamento temporário será aberto para o usuário preencher.

Caso selecionar a opção Não, mostra a mensagem de envio do evento de retificação.

### 1.6.2. Retificação

- Para as demais situações, apenas é possível efetuar a retificação, quando, então, será exibida a mensagem:

Para as informações alteradas, não há possibilidade de enviar eventos de alteração, apenas de retificação.

Confirmar: confirma o envio da retificação deste evento S-2230 para o ambiente do eSocial

Retornar: retorna a informação anterior e não salva a alteração, com isso não há retificações para ser enviadas ao ambiente do eSocial.

## 1.7. Observações

- Apesar do MOS mostrar vários prazos de envio dos eventos de afastamento, optamos por enviar os eventos todos os afastamentos, independente do número de dias, para facilitar a operação do sistema e do eSocial.

- Os eventos de início de afastamento são separados dos eventos de fim do afastamento. Ou seja, é necessário enviar um evento S-2230 para o início e outro para indicar a data de fim. Esse controle é feito pelo sistema ao gerar os eventos pelo pacote 05283-Geração de eventos para o eSocial.

- Veja atentamente o item "Informações adicionais" deste evento no MOS - Manual de Orientação do eSocial.
