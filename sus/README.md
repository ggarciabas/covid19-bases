# BASE Dados Abertos : DATASUS

## Objetivo:

Criar uma base onde se possa ter a informação da quantidade de unidades para cada categoria (CO_ATIVIDADE_PRINCIPAL) que existe em cada cidade e por estado.

Ex.: 

ESTADO; CIDADE; AP_019; AP_024; ...

PR; Curitiba; 2; 1; ...

SP; Osasco; 1; 3; ...

## Tabela de estabelecimentos

**Campos disponíveis**

"CO_UNIDADE"; "CO_CNES"; "NU_CNPJ_MANTENEDORA"; "TP_PFPJ"; "NIVEL_DEP"; "NO_RAZAO_SOCIAL"; "NO_FANTASIA"; "NO_LOGRADOURO"; "NU_ENDERECO"; "NO_COMPLEMENTO"; "NO_BAIRRO"; "CO_CEP"; "CO_REGIAO_SAUDE"; "CO_MICRO_REGIAO"; "CO_DISTRITO_SANITARIO"; "CO_DISTRITO_ADMINISTRATIVO"; "NU_TELEFONE"; "NU_FAX"; "NO_EMAIL"; "NU_CPF"; "NU_CNPJ"; "CO_ATIVIDADE"; "CO_CLIENTELA"; "NU_ALVARA"; "DT_EXPEDICAO"; "TP_ORGAO_EXPEDIDOR"; "DT_VAL_LIC_SANI"; "TP_LIC_SANI"; "TP_UNIDADE"; "CO_TURNO_ATENDIMENTO"; "CO_ESTADO_GESTOR"; "CO_MUNICIPIO_GESTOR"; "TO_CHAR(DT_ATUALIZACAO,'DD/MM/YYYY')"; "CO_USUARIO"; "CO_CPFDIRETORCLN"; "REG_DIRETORCLN"; "ST_ADESAO_FILANTROP"; "CO_MOTIVO_DESAB"; "NO_URL"; "NU_LATITUDE"; "NU_LONGITUDE"; "TO_CHAR(DT_ATU_GEO,'DD/MM/YYYY')"; "NO_USUARIO_GEO"; "CO_NATUREZA_JUR"; "TP_ESTAB_SEMPRE_ABERTO"; "ST_GERACREDITO_GERENTE_SGIF"; "ST_CONEXAO_INTERNET"; "CO_TIPO_UNIDADE"; "NO_FANTASIA_ABREV"; "TP_GESTAO"; "TO_CHAR(DT_ATUALIZACAO_ORIGEM,'DD/MM/YYYY')"; "CO_TIPO_ESTABELECIMENTO"; "CO_ATIVIDADE_PRINCIPAL"; "ST_CONTRATO_FORMALIZADO"

### CO_ATIVIDADE_PRINCIPAL

Tem a descrição dos códigos no arquivo *tbAtividade202002.csv*.

Filtrar para as seguintes atividade:

* "019"; "ANALISES LABORATORIAIS DE VIGILANCIA EM SAUDE"; "Ações e serviços de análises laboratoriais de interesse à saúde pública, relacionadas a vigilância epidemiológica, vigilância em saúde ambiental, saúde do trabalhador e vigilância sanitária, vinculado a órgãos ou entidades da Administração Pública direta ou indireta, da União, dos Estados, do Distrito Federal ou dos Municípios, e das fundações mantidas pelo poder Público."
* "024"; "LOGISTICA DE INSUMOS"; "Compreende o armazenamento e distribuição, sem fins comerciais, para os estabelecimentos de saúde, de medicamentos, imunobiológicos, kit de diagnóstico, produtos químicos e equipamentos de controle vetorial ou produtos para a saúde.
* "026"; "HOSPITALIDADE"; "Serviços que visam alojar temporariamente e apoiar indivíduos que necessitam permanecer fora de sua residência/moradia para acessar serviços de saúde não ofertados em sua localidade de origem, podendo dispor de atividades assistenciais simples, principalmente relacionados a cuidados básicos."
* "001"; "CONSULTA AMBULATORIAL"; "Atendimento dispensado a indivíduos cuja condição de saúde estável lhes permita comparecer ao estabelecimento e retornar ao local de origem, realizado por profissionais de saúde de nível superior, com a finalidade de fornecer parecer, instrução ou examinar determinada situação, afim de decidir sobre um plano de ação ou prescrição terapêutica dentro da sua área de atuação."
* "002"; "APOIO DIAGNOSTICO"; "Ações e serviços que se utilizam de recursos físicos e tecnológicos (ex: Raios X, Ultrassonografia, Ressonância Magnética, Análises Clínicas/ Laboratoriais, Eletrocardiografia, Endoscopia,etc) com o objetivo de auxiliar, de forma complementar, a determinação da natureza de uma doença ou estado, ou a diferenciação entre elas, melhorando a tomada de decisão assistencial."
* "007"; "ASSISTENCIA A EMERGENCIAS"; "Cuidados destinados a pacientes de demanda espontânea com agravos que necessitam de atendimento imediato por risco iminente de morte."
* "008"; "ENTREGA/DISPENSACAO DE MEDICAMENTOS"; "Conjunto de ações relativas ao fornecimento de medicamentos diretamente ao paciente e a orientação para o seu uso racional, mediante apresentação de prescrição por profissional habilitado."
* "009"; "INTERNACAO"; "Cuidados ou tratamentos prestados a um indivíduo, por razões clínicas e/ou cirúrgicas, que demandem a ocupação de um leito por um período igual ou superior a 24 horas."
* "012"; "ATENCAO BASICA"; "Conjunto de ações e serviços longitudinais de saúde no âmbito individual e coletivo, de caráter territorial e comunitário, que abrange o cuidado/tratamento, a promoção e proteção da saúde, a prevenção de agravos, a vigilância em saúde, a reabilitação e a redução de danos à saúde, coordenando ou integrando o cuidado fornecido em outros pontos de atenção."
* "016"; "PROMOCAO DA SAUDE, PREVENCAO DE DOENCAS E AGRAVOS E PRODUCAO DO CUIDADO"; "Conjunto de ações e serviços de saúde, de caráter individual ou coletivo, compreendendo práticas corporais, artísticas e culturais, práticas integrativas e complementares, atividades físicas, promoção da alimentação saudável ou educação em saúde."
* "017"; "IMUNIZACAO"; "Conjunto de ações que objetivam a administração de vacinas para estimulação da resposta imune do hospedeiro, incluindo quaisquer preparações para a profilaxia imunológica ativa."

### CO_ESTADO_GESTOR

Tabela com descrição em *tbEstado202002.csv*.

### CO_MUNICIPIO_GESTOR

Tabela com descrição em *tbMunicipio202002.csv*.
