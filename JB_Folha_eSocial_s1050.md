# JB_Folha_eSocial_s1050

URL: https://wiki.jbsoft.com.br/tiki-index.php?page=JB_Folha_eSocial_s1050

### S-1050 - Horários

Este evento foi descontinuado a partir da versão S-1.0 do eSocial. Suas informações serão prestadas diretamente no evento S-2200.

As informações abaixo servem apenas para histórico de como era realizado no sistema enquanto o evento esteve vigente no eSocial. 

- Tratamentos gerais

- Conferência dos dados dos horários:

Antes de iniciar o processo de envio do evento S-1050, é necessário conferir os dados dos horários.

O pacote que precisa ser ajustado é o 5906.

- Auditoria dos dados:

Existem duas formas de auditar os dados para saber se passarão no eSocial.

A primeira, é enviando os eventos para o ambiente de teste.

A segunda, é utilizando o formulário de auditoria "5350 - Auditoria da tabela de horários/turnos de trabalho, que, além de "traduzir" os erros, possui botões de acesso rápido para os formulários e campos com erros.

- Envio do evento de teste:

Antes de realizar o envio oficial, é prudente realizar o envio para o ambiente de testes.

Para isto, confira a forma de envio de testes em configurar ambiente para envio.

- Envio do evento para o ambiente oficial:

Após realizado o processo completo de saneamento dos dados, então, deve-se realizar o envio do evento para o ambiente oficial.

Para realizar este processo, mude o ambiente para o oficial, se estiver usando o ambiente de teste, conforme descrito no item configurar ambiente para envio e, estando no pacote 5906 clique no botão eSocial para envio do horário corrente. Para envio de todos os horários, vá ao pacote 5283, informe a empresa proprietária dos horários e escolha o evento S-1050.

Quando o envio é realizado de forma individualizada, não haverá consulta se existem vínculos com o empregado, ou seja, se o usuário está usando o envio individualizado é por que ele deseja enviá-lo mesmo que não tenham empregados vinculados.

Não há problema em enviar todos mesmo que não tenham vínculos. A JB Software, via pacote 5283 optou por não enviar registros sem vínculo para reduzir o volume de processamento em lote e deixar o processo mais rápido.

- Alteração de horário do empregado

- Caso um trabalhador tenha seu horário de trabalho modificado, a alteração deve ser realizada no cadastro do trabalhador, pacote 5027, na aba "Auxiliares", no campo "Horário", pesquisando e indicando o novo código de horário dele.

Caso não haja um cadastro de horário para enquadramento, cadastrar um novo, enviar para o eSocial e aguardar o retorno como OK, antes de enviar a alteração individual do trabalhador, para não ocorrer retorno de erro que o horário não existe.

Quando for salvar o empregado, o sistema solicitará se a alteração se refere a uma retificação ou uma alteração. Como estamos tratando de mudança, deve-se enviar uma alteração indicando a data de início de vigência (S-2206), ou seja, a partir de quando o trabalhador deverá cumprir o novo horário.
