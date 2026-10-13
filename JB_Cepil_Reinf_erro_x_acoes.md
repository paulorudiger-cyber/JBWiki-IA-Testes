# JB_Cepil_Reinf_erro_x_acoes

URL: https://wiki.jbsoft.com.br/tiki-index.php?page=JB_Cepil_Reinf_erro_x_acoes

# EFD Reinf - Erros e possíveis ações para correção

Aqui serão listados alguns erros de retorno do Portal da Reinf.

Destacaremos algumas correções possíveis, porém nem sempre conseguiremos mapear todos os erros e soluções pois o volume de validações não destacadas nos manuais é elevada e somente poderemos ir relacionando aqui, conforme nos forem reportados as validações do portal via suporte.

### Tabela de conteúdo

- EFD Reinf - Erros e possíveis ações para correção

- 1. Genéricos

- 1.1. Erro: 101- Aguardando fila de processamento do lote.

- 1.2. Erro: MS1037-Não foi enviado evento R-1070 com validade vigente no período de apuração informado para o número de processo

- 2. Evento R-2055 - Aquisição de produção rural

- 2.1. Erro: MS1080-O Valor da contribuição para o Senar com exigibilidade suspensa é obrigatório se não tiverem sido informados o valor da contribuição previdenciária com exigibilidade suspensa e o valor da contribuição para Gilrat com exigibilidade suspensa.

# 1. Genéricos

## 1.1. Erro: 101- Aguardando fila de processamento do lote.

- Quando, no evento R-2099, o status de envio fica em 101 - Aguardando fila de processamento do lote, significa que o lote foi enviado para o Portal da Reinf e está em processamento, ou seja, ainda não foi validado e não obteve retorno do lote. Essa informação NÃO é gerada pelo JB Cepil. Esse retorno é do próprio portal da Reinf.

Segue imagem do evento no Portal:



Para conferir se realmente o evento está em processamento é importante acessar o sitio do e-Cac: https://cav.receita.fazenda.gov.br/autenticacao/login

Acesse o portal com o certificado digital ou com o código de acesso. Após o acesso selecione a opção Declarações e Demonstrativos -> Acessar EFD-Reinf -> Eventos periódicos -> Fechamento/Reabertura dos Eventos Periódicos.

Nos casos de demora pelo Portal, nossa sugestão é que você entre em contato diretamente com a RFB mencionando a situação e, se possível, fornecendo imagens e/ou documentos que comprovem a demora por parte do portal.

## 1.2. Erro: MS1037-Não foi enviado evento R-1070 com validade vigente no período de apuração informado para o número de processo

- Esta mensagem ocorre quando é enviado um evento periódico R-2010 a R-2060, com um processo relacionado mas o evento R-1070 referente este processo ainda não foi gerado.

Verifique no pacote 03424 - Consulta eventos EFD Reinf, na aba R-1070, como está o STATUS do evento, correspondente ao número do processo identificado na mensagem de erro.

Se o evento não foi enviado, gere o evento R-1070 pelo pacote 03821 - Geração e Transmissão EFD-REINF ou acesse o pacote 03210 - Cadastro de processos, selecione o processe e clica no botão EFD-Reinf.

Se o evento já está enviado, mas não está com STATUS 201 - Lote processado com sucesso, verifique a mensagem de advertência, corrija a situação e gere novamente o evento R-1070.

# 2. Evento R-2055 - Aquisição de produção rural

## 2.1. Erro: MS1080-O Valor da contribuição para o Senar com exigibilidade suspensa é obrigatório se não tiverem sido informados o valor da contribuição previdenciária com exigibilidade suspensa e o valor da contribuição para Gilrat com exigibilidade suspensa.

- Esta mensagem ocorre quando no evento foi informado um processo mas não foi informado valor em nenhum dos campos de valores que deixararm de ser retidos (vlrCPNRet,vlrRatNRet, vlrSenarNRet).

Pode ocorrer essa situação quando, no lançamento de retenção relacionado a aquisição de produtor rural foi informado um processo, mas não foi informado no cadastro do processo qual contribuição (Contribuição previdênciária, RAT ou SENAR) deixou de ser retida em função do processo ou no lançamento da retenção não foi informado o valor que deixou de ser retido.

O que conferir neste caso? 

Verificar se no cadastro do processo no pacote 03210 - Cadastro deprocessos foi marcado a contribuição abrangida pelo processo, no campo Abrangência p/ R-2055.
