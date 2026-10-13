# JB_Folha_eSocial_config_iniciais

URL: https://wiki.jbsoft.com.br/tiki-index.php?page=JB_Folha_eSocial_config_iniciais

# 1. CONFIGURAÇÕES INICIAIS

### Tabela de conteúdo

- 1. CONFIGURAÇÕES INICIAIS

- 1.1. Definir a data e grupo de início da obrigatoriedade do eSocial

- 1.2. Indicar o ambiente para envio de teste ou oficial (homologação)

- 1.2.1. 1 - Produção (oficial)

- 1.2.2. 2 - Teste

- 1.3. Cadastrar o Certificado digital para assinar os XMLs

## 1.1. Definir a data e grupo de início da obrigatoriedade do eSocial

Data da última atualização: 19/05/2026

- Indicar o Grupo e data de início da obrigatoriedade do eSocial:

- Primeiro passo:

Para indicar, é necessário saber a qual grupo a empresa pertence. Para isto, pode-se seguir dois caminhos:

- a) Interpretação da legislação vigente;

- b) Consulta no Portal do eSocial, conforme vídeo abaixo.

Para enquadramento do Grupo, a RFB usou a forma de tributação em 01/07/2018 e para as empresas novas após estas data, a opção tributária declarada na constituição.

- Segundo passo:

No pacote 05191-Configurações da empresa referentes à folha de pagamento > Aba eSocial > "Data de implantação do eSocial" e indicar o grupo a qual tem obrigatoriedade.

O acesso a este pacote pode ser realizado também pelo pacote 00184-Cadastro de empresas > Botão Configurações > Folha de Pagamento.

## 1.2. Indicar o ambiente para envio de teste ou oficial (homologação)

- No sistema JB Folha é possível enviar eventos ao ambiente de testes ou ao ambiente oficial do eSocial.

Como funciona? 

A configuração do ambiente pode ser configurando através do pacote 05191-Configurações da empresa referentes à folha de pagamento, na aba eSocial.

Na aba eSocial e no campo "Ambiente de envio dos eventos", deve ser indicado qual ambiente os eventos devem ser enviados, seguindo as instruções a seguir:

### 1.2.1. 1 - Produção (oficial)

- Este é o ambiente oficial, aquele conhecido "com validade jurídica". Ou seja, a partir do momento que os eventos são enviados para ele, e este retornar com o recibo de entrega, é porque a obrigação foi cumprida. Foi realizada a entrega, de forma efetiva, ao fisco.

Após a entrega, a mudança de informações somente poderá ser realizada por:

- Exclusão e reenvio (restrito a alguns eventos e que não tenham dependências);

- Retificação;

- Alteração.

É aconselhável enviar para o ambiente oficial somente depois de:

- Efetuar o saneamento dos dados;

- Processar a auditoria das informações;

- Ter realizado o envio dos eventos para o ambiente de teste.

### 1.2.2. 2 - Teste

- As informações entregues para este ambiente não têm validade jurídica e podem ser limpas a qualquer momento para realização de novos envios. Todas as informações vão, por padrão, com o ano de 2017, conforme segue:

- Eventos de tabelas: 01/2017.

- Eventos não periódicos (S-2200): 03/2017.

Caso não tenha configuração efetuada, o sistema considera como se fosse Teste.

Enquanto não for enviado nenhum evento para o Ambiente Oficial, e a configuração permanecer como Teste, em todos os pacotes onde houver o botão eSocial, ao clicá-lo será gerado um evento para o Ambiente de Testes. Porém, após o envio de qualquer evento para o ambiente oficial, não será mais possível retornar a configuração para Teste, pois esta ficará bloqueada.

Para testar, é necessário acessar o pacote 05283-Geração de eventos para o eSocial, selecionar o evento desejado e clicar no botão "Enviar teste".

Mas como certificar que o evento foi enviado como Teste?

No pacote 05371-Painel de mensageria do eSocial), ou no pacote 05341-Gerenciamento de eventos do eSocial), há uma coluna indicando para qual ambiente o evento foi enviado, conforme pode ser observado nas imagens a seguir:

## 1.3. Cadastrar o Certificado digital para assinar os XMLs

- Informações importantes sobre certificados

No MOS - Manual de Orientação do eSocial existem várias explicações relativas à Certificação Digital para o envio dos eventos.

Para poder enviar os eventos no formato XMLs ao portal do eSocial, oficial ou de teste, é necessário assiná-los digitalmente. Para isto, é preciso adicionar a assinatura no banco de dados do JB Folha para que o servidor tenha acesso a ela em qualquer momento.

Isso pode ser feito acessando o pacote 00020-Cadastro de certificados digitais e realizando os passos ali indicados.

Importante certificar-se no e-Cac, em caso de haver procuração, que esta esteja cadastrada e marcada com todos os poderes ou que os grupos do eSocial englobem o evento que está sendo enviado.

- Certificado da empresa

Quando o certificado for da empresa, para o tipo e-CNPJ ou e-PJ da empresa, o eSocial somente aceita a assinatura digital da Matriz.

Mesmo quando o envio é realizado por uma filial, o CNPJ de transmitente deve ser o da Matriz, assim como a assinatura digital.

- Certificado de procurador e-CPF ou e-CNPJ

Se a empresa não possuir certificado, é possível fazer o envio dos dados por meio de procurador com e-CPF ou e-CNPJ, desde que a pessoa, física ou jurírica, tenha procuração registrada no portal da Receita Federal - RFB, com indicação de "Todos os Poderes" ou com os Grupos do eSocial destacados no título "Certificação Digital" do MOS.

O procurador pode ser:

- Um dos sócios;

- O representante de um dos sócios;

- O contador pessoa física;

- Um terceiro;

- O escritório de contabilidade, ou;

- Outra empresa.

- Para verificar como inserir a assinatura de um procurador, acesse aqui.
