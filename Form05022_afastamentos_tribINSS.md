# Form05022_afastamentos_tribINSS

URL: https://wiki.jbsoft.com.br/tiki-index.php?page=Form05022_afastamentos_tribINSS

# Pacote 05022 - Afastamentos: Tratamento diferenciado de INSS

Separamos nesta página a explanação do tratamento relativo aos afastamentos de Licença Maternidade e dos auxílios de até 15 dias frente às definições dos pareceres SEI nº 18361/2020/ME e SEI nº 16120/2020/ME.

### Tabela de conteúdo

- Pacote 05022 - Afastamentos: Tratamento diferenciado de INSS

- 1. Comunicado importante

- 2. Live 1: Instruções sobre GFIP 8.4 de 24/12/2020 com manual de 04/01/2021

- 3. Live 2: Afastamentos por doença ou acidente de trabalho: o que mudou

- 4. Licença maternidade

- 5. Afastamentos por motivo de doença ou acidente de trabalho

- 5.1. Atestados 05-Lic Med pg empresa e 07-Lic Acid Trab pg empresa sem recebimento de benefício - até 15 dias

- 5.1.1. Exemplo 10 dias de afastamento dentro do mês

- 5.2. Atestados 06-Auxilio Doenca e 08-Acidente de Trabalho - novo atestado pelo mesmo motivo

- 5.2.1. Exemplo 15 dias de novo afastamento dentro do mês

- 5.3. Atestados 06-Auxilio Doenca e 08-Acidente de Trabalho - mais de 15 dias

- 5.3.1. Passos para refazer a folha quando foi informado que NÃO houve concessão do benefício e depois a perícia concede

- 5.3.2. Passos para refazer a folha quando foi informado que HOUVE concessão do benefício e depois a perícia nega

- 5.3.3. Exemplo afastamento mais de 15 dias com opção 1-Sim no campo "Empregado recebeu o benefício do INSS?" 

- 5.3.4. Exemplo afastamento mais de 15 dias com opção 2-Não no campo "Empregado recebeu o benefício do INSS?" 

- 6. Perguntas Frequentes sobre tratamento diferenciado de INSS nos afastamentos

# 1. Comunicado importante

- Em 01/02/2021 a FAQ 07.23 do eSocial foi atualizada para incluir o texto de que "a contribuição previdenciária patronal, a contribuição de terceiros e o SAT/RAT não incidem sobre esta importância paga pelo empregador referente a esses quinze primeiros dias que antecedem o benefício de auxílio-doença, bem como não há incidência da parte de contribuição previdenciária a cargo do empregado, de acordo com Jurisprudência consolidada do STJ, Parecer SEI Nº 16120/2020/ME."

Ao ser questionada, a resposta da Receita Federal, obtida através do Grupo de Trabalho das Empresas de Softwares Contábeis foi: 
"Na verdade, já havia o entendimento de que não havia a incidência de contribuição previdenciária sobre a parte do segurado, conforme NOTA PGFN/CRJ Nº 115/2017. O Parecer SEI Nº 16120/2020/ME, que inclusive faz referência a essa Nota PGFN, veio definir que também não incide contribuição patronal sobre os 15 primeiros dias que antecedem a concessão do auxílio-doença.

Não havíamos atentando para a NOTA PGFN/CRJ nº 115/2017 quando da elaboração da FAQ. Logo fizemos a atualização dela para estar totalmente alinhada com o entendimento Parecer SEI Nº 16120/2020/ME."

Na prática o que muda no sistema JB Folha é que, para Não tributar a parte do empregado, as verbas abaixo precisam ser configuradas para a opção "Não para todos" no campo "Somar na base do INSS (01)"

- HORAS DIURN LIC MEDICA ATE 15 DIAS (C/BENEFICIO) - 1NA

- HORAS DIURN L.ACID TRAB ATE 15 DIAS (C/BENEFICIO) - 1OA

- HORAS NOT LIC MEDICA ATE 15 DIAS (C/BENEFICIO) - 1XA

- HORAS NOT LIC ACID TRAB ATE 15 DIAS (C/BENEFICIO) - 1YA

Atualmente a orientação completa pode ser consultada na FAQ 10.36 e 10.15 do eSocial.

# 2. Live 1: Instruções sobre GFIP 8.4 de 24/12/2020 com manual de 04/01/2021

- Clique aqui para assistir no Youtube

# 3. Live 2: Afastamentos por doença ou acidente de trabalho: o que mudou

- Clique aqui para assistir no Youtube

# 4. Licença maternidade

- A partir do Parecer SEI Nº 18361/2020/ME, a PGFN - Procuradoria Geral da Fazenda Nacional atestou a inconstitucionalidade da contribuição previdenciária, RAT e Outras entidades, a cargo do empregador sobre o salário maternidade.

No dia 02/12/2020, o eSocial emitiu a Nota Técnica 20/2020, dando divulgação sobre essa definição da PGFN. Nesse momento, o portal do eSocial, ao realizar o retorno dos eventos de cálculo do INSS, passou a retornar os valores isentando a tributação sobre as verbas vinculadas às rubricas de maternidade.

Com os efeitos já recaindo sobre a folha de novembro, quem já havia calculado e entregue os eventos, precisou aguardar a versão do sistema, recalcular e retificar os eventos.

As instruções de como informar essa situação para o SEFIP, por sua vez, só vieram no final do mês de dezembro/2020:

- Enviar no campo "Remuneração sem 13°" o que é base de FGTS: dias trabalhados mais os valores da maternidade.

- Enviar sempre a Ocorrência de agentes nocivos correspondente de múltiplos vínculos.

- Enviar os valores de INSS descontados do segurado.

- Enviar apenas o valor referente aos dias trabalhados no campo "Base de Cálculo da Previdência Social".

Obs.1: A parte do empregado sobre a maternidade, quando paga pela empresa, continua sendo retida normalmente. O FGTS também continua sendo devido..

Obs.2: No pacote 05208-Configurações gerais JB Folha > aba INSS, foi criada a configuração "Contribuição Previdenciária Patronal (CPP) sobre a licença maternidade" para a definição da data de início do tratamento de isenção para a tributação da parte patronal das verbas de maternidade. Dessa forma, caso seja necessário retroagir e recalcular para períodos anteriores, é só alterar essa data antes de efetuar os procedimentos.

Caso não haja configuração, o tratamento será o mesmo que se for selecionada a opção 2-Calcular conforme a opção da verba.

# 5. Afastamentos por motivo de doença ou acidente de trabalho

- O Parecer SEI nº 16120/2020/ME foi emitido no sentido da não incidência da contribuição previdenciária patronal, de contribuições de terceiros e do SAT/RAT sobre a importância paga pelo empregador ao empregado, sobre o período de quinze dias que antecede o auxílio-doença.

Se não houver a concessão do benefício pela Previdência, os dias pagos pela empresa são tributados normalmente.

Sua aplicação é válida a partir de 11/2020, conforme instruções do Manual da GFIP/SEFIP, divulgado no final do mês de dezembro/2020.

Em relação a este assunto existe também a NOTA PGFN/CRJ/No 115/2017. Ela determina a não incidência de contribuição previdenciária, a cargo do empregado, sobre valores pagos a título terço constitucional de férias e remuneração paga pelo empregador nos primeiros dias de afastamento do trabalhador por incapacidade.

## 5.1. Atestados 05-Lic Med pg empresa e 07-Lic Acid Trab pg empresa sem recebimento de benefício - até 15 dias

- Orientações do SEFIP para afastamentos até 15 dias




- Como era até 10/2020:

- Cadastrava as situações 05 ou 07 com código de movimentação do FGTS para o Sefip 38-P3-Afastamento Temporário p/motivo de Doença pago pela empresa ou 36-O3-Afastamento Temporário p/motivo Acid.Trab.empresa.

- O sistema não lançava as verbas de licença de forma separada. Apenas descontava das horas trabalhadas quando eram digitadas.

- Como ficou a partir de 11/2020:

- Os atestados nesta situação não devem ser informados para o SEFIP.

- O sistema passou a calcular as verbas de licença sempre separadamente.

- A tributação das verbas continua sendo integral, inclusive a parte patronal.

### 5.1.1. Exemplo 10 dias de afastamento dentro do mês

- Afastamento de 10 dias por 05-Lic Med pg empresa em 01/2021.

- Salário R$ 1.100,00

- Método Dias do Mês (05016-Cadastro de sindicatos > Dados Complementares II > Forma de cálculo das verbas salariais e de afastamentos)

## 5.2. Atestados 06-Auxilio Doenca e 08-Acidente de Trabalho - novo atestado pelo mesmo motivo




- Como era até 10/2020:

- Sempre que houvesse um segundo atestado pelo mesmo motivo, eram informados os códigos P2 ou O2.

- Era habilitado o campo "Dias atestados anteriores mesmo motivo" para o sistema controlar quando chegasse ao 16º dia para, a partir daí, lançar as verbas do afastamento pago pela Previdência.

- Como ficou a partir de 11/2020:

- Só pode informar os códigos de movimentação do FGTS 11-P2-Novo afastamento temp. mesma Doença -60 dias ou 09-O2-Novo afastamento temp. mesmo Acidente Trabalho quando, no primeiro afastamento, já houve pagamento do benefício.

- Foi desabilitado o campo "Dias atestados anteriores mesmo motivo" e considera direto pela Previdência desde o primeiro dia. Ou seja, esses códigos representam reinício de benefício.

### 5.2.1. Exemplo 15 dias de novo afastamento dentro do mês

- Afastamento de 15 dias por 08-Acidente de Trabalho em 01/2021.

- Salário R$ 1.100,00

- Método Dias do Mês (05016-Cadastro de sindicatos > Dados Complementares II > Forma de cálculo das verbas salariais e de afastamentos)

## 5.3. Atestados 06-Auxilio Doenca e 08-Acidente de Trabalho - mais de 15 dias

- Orientação SEFIP para afastamentos maiores que 15 dias




- Como era até 10/2020:

- Cadastrava nas situações 06 ou 08, com código de movimentação do FGTS 10-P1-Afastamento temporário por Doença pago pela Previdência ou 08-O1-Afastamento temp. p/Acidente Trabalho pago pela Previdência, para o SEFIP.

- O sistema calculava os primeiros 15 dias pela empresa e após lançava as verbas de cada afastamento.

- A tributação das verbas era integral.

- Como ficou a partir de 11/2020:

- Cadastrar as situações 06 ou 08 apenas quando houver possibilidade de a Previdência pagar benefício (via de regra, quando o atestado for maior que 15 dias, ou somado com algum anterior, ultrapasse os 15 dias).

- Mesmo cadastrando com P1 ou O1, são mandados os dias pagos pela empresa como P3 e O3, para não ser necessário o cliente criar duas situações.

- Foi habilitado o campo "Dias atestados anteriores mesmo motivo".

- Sempre serão inseridas verbas de forma separada para os dias pagos pela empresa.

- Ao indicar a opção 1-Sim no campo "Empregado recebeu o benefício do INSS?" serão lançadas as novas verbas que por padrão não tem incidência de INSS. Veja mais detalhes no help deste campo no pacote 05022-Cadastro de situações/afastamentos.

- Para o SEFIP:

- Enviar no campo "Remuneração sem 13°" o que é base de FGTS: dias trabalhados mais os valores pagos pela empresa.

- Enviar a Ocorrência de agentes nocivos correspondente de múltiplos vínculos.

- Enviar os valores de INSS descontados do segurado.

- Enviar apenas o valor referente aos dias trabalhados no campo "Base de Cálculo da Previdência Social".

- Ao indicar 2-Não no campo "Empregado recebeu o benefício do INSS?", serão lançadas as mesmas verbas lançadas quando configurados os afastamentos 05-Lic Med pg empresa e 07-Lic Acid Trab pg empresa sem recebimento de benefício, cujo padrão é que tenha a tributação integral.

Por que isso? Porque a não incidência do INSS ocorre apenas quando houver concessão do benefício.

### 5.3.1. Passos para refazer a folha quando foi informado que NÃO houve concessão do benefício e depois a perícia concede

- IMPORTANTE: Sempre que for informado que não houve concessão do benefício para as situações 06 ou 08, onde passa do 15º dia, e depois a Previdência concede, será necessário:

- Eliminar a folha do trabalhador (normal ou rescisória).

- Ajustar a situação cadastrada no pacote 05022, informando 1-Sim no campo "Empregado recebeu o benefício do INSS?".

- Recalcular a folha para que o sistema insira as verbas corretas, com tratamento para não incidência.

- Reenviar a GFIP para levar os valores como indicado no Manual.

- Reabrir o movimento do eSocial e retificar os eventos dos trabalhadores impactados.

- Caso o DARF Previdenciário ou GPS já tenham sido recolhidos, também é necessário compensar ou pedir restituição dos valores recolhidos a maior.

Veja aqui o artigo Procedimentos para Restituição/Compensação de pagamento ou recolhimento indevido ou a maior ao INSS - (Guiatrabalhista.com.br)

E se eu já mandar sempre com benefício quando for maior que 15 dias?

Correrá o risco de a Previdência negar o benefício, e ter que refazer a folha igual e ainda recolher em atraso.

### 5.3.2. Passos para refazer a folha quando foi informado que HOUVE concessão do benefício e depois a perícia nega

- IMPORTANTE: Sempre que for informado que houve concessão do benefício para as situações 06 ou 08, onde passa do 15º dia, e depois a Previdência NEGA, será necessário:

- Eliminar a folha do trabalhador (normal ou rescisória).

- Ajustar a situação cadastrada no pacote 05022, informando as situações 05-Lic Med pg empresa ou 07-Lic Acid Trab pg empresa para os primeiros 15 dias.

- Para o período que passou dos 15 dias informar faltas, licença não remunerada ou licença remunerada, conforme orientação do setor jurídico de sua empresa.

- Recalcular a folha para que o sistema insira as verbas corretas, conforme a situação.

- Reenviar a GFIP para levar os valores como indicado no Manual.

- Reabrir o movimento do eSocial e retificar os eventos dos trabalhadores impactados.

- Caso o DARF Previdenciário ou GPS tenham sido recolhidos a menor, também é necessário complementar o recolhimento, com os acréscimos, conforme legislação vigente, caso o prazo normal de recolhimento já tenha decorrido.

### 5.3.3. Exemplo afastamento mais de 15 dias com opção 1-Sim no campo "Empregado recebeu o benefício do INSS?" 

- Afastamento de 25 dias por 06-Auxilio Doenca em 01/2021.

- Salário R$ 1.100,00

- Método Dias do Mês (05016-Cadastro de sindicatos > Dados Complementares II > Forma de cálculo das verbas salariais e de afastamentos)

Ao acessar o relatório 3-Bases de cálculo por empregado do Pacote 05057-Relatório dos resumos previdenciários, se pode conferir as bases de cálculo utilizadas para o INSS e FGTS.



### 5.3.4. Exemplo afastamento mais de 15 dias com opção 2-Não no campo "Empregado recebeu o benefício do INSS?" 

- ATENÇÃO: Quando sair o resultado da perícia, nesta situação será necessário efetuar os ajustes na folha, seguindo os passos acima, conforme a situação

- Afastamento de 25 dias por 06-Auxilio Doenca em 01/2021.

- Salário R$ 1.100,00

- Método Dias do Mês (05016-Cadastro de sindicatos > Dados Complementares II > Forma de cálculo das verbas salariais e de afastamentos)

# 6. Perguntas Frequentes sobre tratamento diferenciado de INSS nos afastamentos

- Clique aqui para acessar as Perguntas Frequentes sobre tratamento diferenciado de INSS nos afastamentos
