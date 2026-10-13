# JB_Folha_eSocial_s1000

URL: https://wiki.jbsoft.com.br/tiki-index.php?page=JB_Folha_eSocial_s1000

# 1. S-1000 - Informações do Empregador/Contribuinte/Órgão Público

Data da última atualização: 17/05/2021

### Tabela de conteúdo

- 1. S-1000 - Informações do Empregador/Contribuinte/Órgão Público

- 1.1. Conceito do evento

- 1.2. Prazo de envio

- 1.3. Conferência dos dados da empresa

- 1.4. Auditoria dos dados

- 1.5. Envio do evento para o ambiente oficial

- 1.6. Informações adicionais

- 1.6.1. Empresa mudou a forma de tributação

- 1.6.2. Empresa era presumido e mudou para o Simples Nacional, o que faço?

- 1.6.3. Já havia ENVIADO rescisões e folhas antes de enviar a mudança de tributação. O que faço?

- 1.6.4. Envei a classificação tributária errada. E agora o que faço?

## 1.1. Conceito do evento

- Evento onde são fornecidas as informações cadastrais e outros dados necessários ao preenchimento e validação dos demais eventos do eSocial, inclusive para apuração das contribuições previdenciárias devidas ao RGPS e para depósito do FGTS. Esse é o primeiro evento que deve ser transmitido pelo declarante.

## 1.2. Prazo de envio

- Deve ser enviado no início da utilização do eSocial e pode ser alterada no decorrer do tempo, hipótese em que deve ser enviado este mesmo evento com a informação nova, quando da sua ocorrência.

Outra hipótese de envio é no mês da constituição, caso a empresa tenha sido constituída após o início da obrigatoriedade de utilização do eSocial.

## 1.3. Conferência dos dados da empresa

- Antes de iniciar o processo de envio do evento S-1000, é necessário conferir os dados da empresa.

Os dados enviados para o eSocial e sua respectiva localização no sistema, podem ser conferidos aqui.

## 1.4. Auditoria dos dados

- O formulário de auditoria é o "05343 - S-1000 - Auditoria das informações do empregador" que, além de "traduzir" os erros, possui botões de acesso rápido para os formulários e campos com erros.

Vídeo do processo de auditoria:

## 1.5. Envio do evento para o ambiente oficial

- Após realizado o processo completo de saneamento dos dados, então, deve-se realizar o envio do evento para o ambiente oficial.

Para realizar este processo, mude o ambiente para o oficial, se estiver usando o ambiente de teste, conforme descrito no item configurar ambiente para envio e, estando no pacote 00184-Cadastro de empresas clique no botão eSocial. Ou, vá ao pacote 05283-Geração de eventos para o eSocial, informe a empresa no campo de pesquisa "Empresa" e escolha o evento S-1000.

Quando o envio é realizado de forma individualizada, não haverá consulta se existem vínculos com a empresa que está sendo gerada, ou seja, se o usuário está usando o envio individualizado é porque ele deseja enviá-lo mesmo que não tenham empregados vinculados.

Não há problema em enviar todos, mesmo que não tenham vínculos. A JB Software, via pacote 05283-Geração de eventos para o eSocial, optou por não enviar registros sem vínculo unicamente para reduzir o volume de processamento em lote, deixando o processo mais rápido.

Vídeo do processo de envio do evento e acompanhamento do retorno na mensageria:

Para Microempreendedor Invidual - MEI existem algumas particularidades para o cadastro no sistema, as quais podem ser acompanhadas nesta página.

## 1.6. Informações adicionais

### 1.6.1. Empresa mudou a forma de tributação

- Deve-se enviar, um evento S-1000 de alteração da classificação tributária da empresa.

Para isso, acessar no pacote "00184 - Cadastro de empresas" > botão Configurações > Gerais > eSocial/EFD Reinf e indicar uma nova competência para a classificação tributária.

### 1.6.2. Empresa era presumido e mudou para o Simples Nacional, o que faço?

- No primeiro dia, da competência que houve opção pela mudança de regime, deve enviar o evento S-1000 de alteração de classificação tributária para 01, 02 ou 03. A data de alteração deve ser igual à data da mudança de opção, ou seja o primeiro dia do mês da competência.

Alertamos que é necessária a mudança antes do envio dos eventos que contenham cálculos (S-1200, S-2299, S-2399, etc.), pois o eSocial apura os cálculos patronais no momento do envio de cada evento de cálculo.

### 1.6.3. Já havia ENVIADO rescisões e folhas antes de enviar a mudança de tributação. O que faço?

- Retifica todos os eventos após enviar o evento de alteração.

Obs: Qualquer alteração de classificação tributária segue a mesma dinâmica, ou seja, de envio de alteração do S-1000 e retificação dos eventos de cálculos se já haviam sido enviados antes do envio de alteração.

### 1.6.4. Envei a classificação tributária errada. E agora o que faço?

- Neste caso é necessário retrificar o evento S-1000.

Porém para isso ocorrer, não pode haver nenhum evento de remuneração, pagamento ou fechamento no portal.

Veja aqui como proceder.
