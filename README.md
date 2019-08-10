# Pydata Manaus - VH Summit: Governo e Tecnologia
Repositório dedicado ao conjunto de datasets para auxiliar os participantes da oficina de raspagem de dados públicos do VH Summit: Governo e Tecnologia.

<!-- toc -->

  * [Repositório de dados eleitorais](#repositório-de-dados-eleitorais)
  * [SICONV: uso de verba do governo federal por municípios e estados (e universidades, institutos, ...) via convênios](#siconv-uso-de-verba-do-governo-federal-por-municípios-e-estados-e-universidades-institutos--via-convênios)
  * [Compras Governamentais](#compras-governamentais)
  * [Nuvem Cívica](#nuvem-cívica)
  * [Portal da Transparência da Prefeitura de Manaus](#portal-da-transparência-da-prefeitura-de-manaus) 
  * [Portal da Transparência do Governo do Amazonas](#portal-da-transparência-do-governo-do-amazonas) 
  * [Receitas e Despesas Públicas – Portal da Transparência](#receitas-e-despesas-públicas-portal-da-transparência) 
  * [Sanções – Portal da Transparência](#sanções-portal-da-transparência) 
  * [Dirigentes de Empresas – Portal da Transparência](#dirigentes-de-empresas-portal-da-transparência) 
  * [Programas Sociais Bolsa Família – Portal da Transparência](#programas-sociais-bolsa-família-portal-da-transparência) 
  * [Cartões de Pagamento – Portal da Transparência](#cartões-de-pagamento-portal-da-transparência) 
  * [Seguro Defeso – Portal da Transparência](#seguro-defeso-portal-da-transparência)
  * [Pedidos e Respostas do e-SIC](#pedidos-e-respostas-do-e-sic)
  * [Webservice do e-OUV](#webservice-do-e-ouv)
  * [Relatórios da CGU](#relatórios-da-cgu)
  * [Dados sistematizados sobre parlamentares, seus gastos, parentes, empresas onde eles gastaram e discursos](#dados-sistematizados-sobre-parlamentares-seus-gastos-parentes-empresas-onde-eles-gastaram-e-discursos)
  * [Projeto Brasil.IO](#projeto-brasilio)
  * [Projeto Colaboradados](#projeto-colaboradados)
  * [Portal ConectaGov](#portal-conectagov)
  * [Contribuindo](#contribuindo)
  * [DATASUS](#datasus)
  * [Prefeitura Municipal de Manaus](http://www.transparenciamunicipalaam.com.br/saopaulodeolivenca/)
  * [Câmara Municipal de Manaus](http://www.ale.am.gov.br/saopaulodeolivenca/transparencia/)
  * [Prefeitura Municipal de Parintins](http://www.transparencia-am.com.br/SAOSEBASTIAODOUATUMA/PM/frm_inst.html)
  * [Câmara Municipal de Parintins](http://www.ale.am.gov.br/saosebastiaodouatuma/transparencia/)
  * [Câmara Municipal de Borba](http://www.transparencia-am.com.br/SILVES/PM/silves.html)
  * [Prefeitura Municipal de Humaitá](http://www.ale.am.gov.br/silves/transparencia/)
  * [Câmara Municipal de Humaitá](https://www.transparenciamunicipalaam.com.br/tabatinga/)
  * [Prefeitura Municipal de Juruá](http://www.transparenciamunicipalaam.com.br/tabatinga-camara/)
  * [Câmara Municipal de Juruá](https://www.transparenciamunicipalaam.com.br/tapaua/)
  * [Prefeitura Municipal de Manicoré](http://www.transparenciamunicipalaam.com.br/tapaua-camara/)
  * [Câmara Municipal de Manicoré](https://prefeituradetefe.com.br/portal-da-transparencia-municipal-de-tefe/)
  * [Prefeitura Municipal de Presidente Figueiredo](http://www.ale.am.gov.br/tefe/transparencia/)
  * [Prefeitura Municipal de Tonantins](http://www.transparenciamunicipalaam.com.br/tonantins/?view=default)
  * [Assembléia Legistativa - Prefeitura Municipal de Tonantins](http://www.ale.am.gov.br/tonantis/transparencia/)
  * [Prefeitura Municipal de Uarini](http://www.transparenciamunicipalaam.com.br/uarini/?view=default)
  * [Câmara Municipal de Uarini](http://www.ale.am.gov.br/uarini/transparencia/)
  * [Câmara Municipal de Urucará](http://www.transparencia-am.com.br/URUCARA/PM/urucara.php)
  * [Câmara Municipal de Urucará](http://www.ale.am.gov.br/urucara/transparencia/)
  * [Câmara Municipal de Urucurituba](http://www.transparenciamunicipalaam.com.br/urucurituba/?view=default)
  * [Câmara Municipal de Urucurituba](http://www.ale.am.gov.br/urucurituba/transparencia/)

<!-- tocstop -->

---

### Repositório de dados eleitorais
?    | ! |
 --- | --|
*O que é* | O Repositório de dados eleitorais é uma compilação de informações brutas das eleições, desde as de 1945, voltada para pesquisadores, imprensa e pessoas interessadas em analisar os dados de eleitorado, candidaturas, resultados e prestação de contas. |
*Formato* | CSV |
*Url*     | http://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1/repositorio-de-dados-eleitorais |
*Dicas*   |  |
*Projetos usando* |  | 

---

### SICONV: uso de verba do governo federal por municípios e estados (e universidades, institutos, ...) via convênios
?    | ! |
 --- | --|
*O que é* | Boa parte das obras estruturantes e grandes serviços dos municípios e estados é feito com verba federal obtida via convênios. O SICONV tem dados abertos detalhados sobre os convênios celebrados, licitações e pagamentos envolvidos, se a prestação de contas foi aceita ou houve problema, e o cronograma disso tudo. Tem também informação dizendo se a verba do convênio é resultante de uma emenda parlamentar de um deputado federal ou senador. |
*Formato* | CSVs |
*Url*     | http://portal.convenios.gov.br/download-de-dados  |
*Dicas*   | Há um MER na página. Os csvs são atualizados diariamente. Esses csvs são mais completos que a API de convênios. Prestação de contas rejeitada é sinal de que o convênio não foi executado corretamente. Deputados alocam verbas via emendas parlamentares que acabam sendo executadas como convênios. |
*Projetos usando* | [As Diferentonas](https://github.com/nazareno/diferentonas-server/), [Na emenda dos deputados](https://github.com/CelioBarros/NaEmendaDeputado), Quase todos [os apps que participaram do hackathon do MJ](https://github.com/LabPi) |

---
### Nuvem Cívica
?    | ! |
 --- | --|
*O que é* | API de acesso para diversas fontes de dados abertos governamentais.|
*Formato* | API REST (json) |
*Url*     | https://github.com/AppCivicoPlataforma/AppCivico |
*Dicas*   | Tem informações georreferênciadas sobre escolas e estabelecimentos de saúde públicos/privados do país (coletados através do DATA SUS e INEP). Há tembém informações sobre os remédios fabricados no Brasil (ANVISA). Além disso, há API para consulta de postos do Site Nacional de Empregos (SINE)|
*Projetos usando* |  |

---

### Portal da Transparência da Prefeitura de Manaus
?    | ! |
 --- | --|
*O que é* | Trata da divulgação, em tempo real, de informações pormenorizadas sobre a execução orçamentária e financeira da Prefeitura de Manaus. Por meio da pesquisa, é possível, detalhar todos os documentos emitidos pelas unidades gestoras do Poder Executivo Municipal no decorrer da execução das suas despesas, inclusive, pela fase em que a despesa está: empenho, liquidação e pagamento.|
*Formato* | download de arquivos pdf, doc, xls e odt |
*Url*     | https://transparencia.manaus.am.gov.br/transparencia/v2/#/home |
*Dicas*   | Observe que no canto superior direito da tela encontra-se um ícone com a opção “download”. Clicando-se nesse ícone são apresentadas as opções de importação nos formatos. |
*Projetos usando* |  |

---

### Portal da Transparência do Governo do Amazonas
?    | ! |
 --- | --|
*O que é* | Trata da divulgação, em tempo real, de informações pormenorizadas sobre a execução orçamentária e financeira das entidades do Governo do Estado do Amazonas. Por meio da pesquisa, é possível, detalhar todos os documentos emitidos pelas unidades gestoras do Poder Executivo Estadual no decorrer da execução das suas despesas, inclusive, pela fase em que a despesa está: empenho, liquidação e pagamento.|
*Formato* | download de arquivos pdf, doc, csv, xls e odt |
*Url*     | http://www.transparencia.am.gov.br |
*Dicas*   | Nem todos os arquivos estão no formato csv. |
*Projetos usando* |  |

---

### Receitas e Despesas Públicas – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Transferências de recursos federais, constitucionais, legais ou voluntárias, para estados, municípios, Distrito Federal, instituições privadas com e sem fins lucrativos e ao exterior, realizados pelos órgãos e entidades da Administração Pública Federal, que executam as despesas pelo Sistema Integrado de Administração Financeira do Governo Federal (Siafi). |
*Formato* | API REST |
*Url*     | http://www.transparencia.gov.br/swagger-ui.html#/Despesas32P250blicas|
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* | Para onde foi o meu dinheiro? |

---

### Sanções – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | No Portal da Transparência, sanções são punições aplicadas a pessoas físicas, pessoas jurídicas e servidores públicos federais, decorrentes da relação com o Poder Executivo Federal, como: Cadastro de Empresas Inidôneas e Suspensas (CEIS) – Empresas e pessoas físicas impedidas de participar de licitações ou de celebrar contratos com a Administração, em todas as esferas e nos três Poderes; Cadastro Nacional de Empresas Punidas (CNEP) – Empresas que sofreram punições previstas na Lei nº 12.846/2013; Entidades Privadas Sem Fins Lucrativos Impedidas (CEPIM) – Entidades privadas sem fins lucrativos que estão impedidas de celebrar convênios, contratos de repasse ou termos de parceria com a Administração Pública; Expulsões da Administração Federal (CEAF) – Servidores civis do Poder Executivo Federal e da Câmara dos Deputados punidos com demissão, destituição ou cassação de aposentadoria. |
*Formato* | API REST |
*Url*     | http://www.portaltransparencia.gov.br/sancoes |
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* |  |

---

### Servidores Civis e Militares do Executivo Federal – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Informações sobre cargo, função, situação funcional e remuneração dos servidores civis e militares, bem como dos agentes públicos do Poder Executivo Federal. |
*Formato* | API REST |
*Url*     | http://www.transparencia.gov.br/swagger-ui.html#/Servidores32do32Poder32Executivo32Federal |
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* |  |

---

### Dirigentes de Empresas – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Informações sobre ocupantes de cargos de gerência e direção em empresas estatais e subsidiárias. |
*Formato* | CSV |
*Url*     | http://www.portaldatransparencia.gov.br/download-de-dados/dirigentes/201806 |
*Dicas*   |  |
*Projetos usando* |  |

---

### Programas Sociais Bolsa Família – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Informações sobre as transferências de recursos federais diretamente repassados a cidadãos, referentes ao pagamento do Bolsa Família, realizadas pelo Ministério do Desenvolvimento Social, por meio da Caixa Econômica Federal. |
*Formato* | API REST |
*Url*     | http://www.transparencia.gov.br/swagger-ui.html#/Bolsa32Fam237lia |
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* |  |

---

### Cartões de Pagamento – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Conheça os gastos realizados por meio de cartões de pagamento. O Cartão de Pagamento do Governo Federal é utilizado para despesas de pequeno vulto ou despesas eventuais que exijam pronto pagamento. O Cartão de Compras Centralizadas é utilizado para aquisição de passagens aéreas e o  da Defesa Civil para ações de socorro, assistência às vítimas e restabelecimento de serviços essenciais. |
*Formato* | API REST |
*Url*     | http://www.transparencia.gov.br/swagger-ui.html#/Gastos32por32meio32de32cart227o32de32pagamento |
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* |  |

---

### Seguro Defeso – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | O seguro-desemprego do pescador artesanal é uma assistência financeira temporária concedida aos pescadores profissionais artesanais que, durante o período de defeso (aquele em que os animais protegidos normalmente se reproduzem), são obrigados a paralisar a atividade para preservação da espécie e sustentabilidade da atividade pesqueira na região. Para ter direito, o trabalhador deve comprovar que exerce a pesca, do pescado protegido, de maneira ininterrupta, seja sozinho ou em regime de economia familiar. |
*Formato* | API REST |
*Url*     | hhttp://www.transparencia.gov.br/swagger-ui.html#/Seguro32Defeso |
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* |  |

---

### Pedidos e Respostas do e-SIC
?    | ! |
 --- | --|
*O que é* | Base de dados dos pedidos e respostas realizados no Poder Executivo Federal, por meio do e-SIC, com base na Lei de Acesso à Informação.|
*Formato* | CSV e XML |
*Url*     | http://www.consultaesic.cgu.gov.br/busca/_layouts/15/DownloadPedidos/DownloadDados.aspx |
*Dicas*   | O arquivo Pedidos contém dados sobre as solicitações, incluindo o conteúdo dos pedidos e respostas. Já o arquivo Recursos fornece o conteúdo, dentre outros dados, dos recursos apresentados pelo solicitante quando ele entende que não foram concedidas a informação ou o motivo para a negativa. O arquivo solicitante fornece informações individualizadas, exceto nome, sobre os autores dos pedidos. Atualização diária |
*Projetos usando* | Achados e Pedidos |

---

### Webservice do e-OUV
?    | ! |
 --- | --|
*O que é* |Webservice para registro e consulta de manifestações de ouvidoria (denúncias, reclamações, sugestões etc.) direcionadas às ouvidorias do governo federal, incluindo a Ouvidoria-Geral da União da CGU.|
*Formato* | |
*Url*     | [Neste link](https://github.com/hackfestcc/dados-hackfestcc/blob/master/etc/e-ouv---documentacao-webservices.docx) |
*Dicas*   |O documento disponível no link acima explica como acessar os serviços e conectar seu aplicativo ao e-OUV. Por meio do serviço, um aplicativo para detectar irregularidades em obras federais pode, por exemplo, registrar diretamente uma denúncia para a CGU. Importante: o e-OUV permite o registro apenas de manifestações para órgãos do Poder Executivo Federal. Assim, se a obra ou serviço for realizado apenas com recursos estaduais, por exemplo, a denúncia deve ser encaminhada a órgãos estaduais como ouvidoria do Governo do Estado, Tribunal de Contas ou Ministério Público estadual.|
*Projetos usando* | Reclame Aqui |

---

### Relatórios da CGU
?    | ! |
 --- | --|
*O que é* | Relatórios de fiscalização em estados e municípios, auditorias anuais de contas de órgãos federais, avaliações de programas federais, entre outros. |
*Formato* |PDF |
*Url*     | http://auditoria.cgu.gov.br/public/relatorio/consultar.jsf?windowId=9db |
*Dicas*   |É possível baixar um ou mais arquivos ou exportar a lista de resultados em formato csv. |
*Projetos usando* | |

---

### Dados sistematizados sobre parlamentares, seus gastos, parentes, empresas onde eles gastaram e discursos
?    | ! |
 --- | --|
*O que é* | Dados da câmara e de outras fontes, incluindo geolocalização das empresas onde parlamentares gastaram, seus parentes, seus assessores e mais coisa que parece bem legal, sistematizado pelo pessoal da Operação Serenata de Amor  |
*Formato* | csvs compactados como xz  |
*Url*     | https://github.com/datasciencebr/serenata-toolbox/|
*Dicas*   |   |
*Projetos usando* | https://serenatadeamor.org |

---

### Projeto Brasil.IO
?    | ! |
 --- | --|
*O que é* | Projeto para tornar acessíveis os dados brasileiros de interesse público e temos como valores principais a transparência e colaboração. |
*Formato* | API REST |
*Url*     | https://brasil.io/api/datasets |
*Dicas*   | Disponibiliza aplicações especiais que cruzam dados de diversos datasets e facilitam o trabalho investigativo. Mais informações no [github do projeto](https://github.com/turicas/brasil.io) |
*Projetos usando* |  |

---


### Projeto Colaboradados
?    | ! |
 --- | --|
*O que é* | O banco colaborativo de bases de dados |
*Url*     | https://colaboradados.github.io |
*Dicas*   | Iniciativa colaborativa que busca reunir, demonstrar, investigar e monitorar o acesso à informação no Brasil. Mais informações no [github do projeto](https://github.com/colaboradados) |
*Projetos usando* |  |

---

### Portal ConectaGov
?    | ! |
 --- | --|
*O que é* | Um catálogo recheado de API’s governamentais. |
*Formato* | API REST |
*Url*     | https://catalogo.conecta.gov.br/store/ |
*Dicas*   |  |
*Projetos usando* |  |

---

### DATASUS
?    | ! |
 --- | --|
*O que é* | O Departamento de Informática do Sistema Único de Saúde (DATASUS) surgiu em 1991 com a criação da Fundação Nacional de Saúde (Funasa), pelo Decreto 100 de 16.04.1991, publicado no D.O.U. de 17.04.1991 e retificado conforme publicado no D.O.U. de 19.04.1991. Na época, a Fundação passou a exercer a função de controle e processamento das contas referentes à saúde que antes era da Empresa de Tecnologia e Informações da Previdência Social (DATAPREV). Foi então formalizada a criação e as competências do DATASUS, que tem como responsabilidade prover os órgãos do SUS de sistemas de informação e suporte de informática, necessários ao processo de planejamento, operação e controle. |
*Formato* | DBC |
*Url*     | http://www2.datasus.gov.br/DATASUS/index.php?area=0901 |
*Dicas*   | Através da instalação da biblioteca read.dbc no R é possível facilitar a análise dos dados disponibilizados pelo DATASUS.  |
*Projetos usando* |  |

---
