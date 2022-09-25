# O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados

  A geração de dados no mundo atualmente é gigantesca a cada ano que passa dobra a quantidade de dados que são formados,
  para isso importante profissionais e ferramentas que trabalham em conjunto para performar, manipular, preparar e aplicar esses dados para
  adquirir informações atravez de consultas. 
  
## Definição de Bancos de dados Relacionais(SQL) e NoSQl e a diferença entre eles
 
  
  OS Bancos de dados Relacionais são aplicados quando se tem dados armazenados que se relacionam entre eles ou seja uma informação pode ser gerada atravez de diversas relações em uma estrutura rigida em tabela com atributos e tuplas compondo os dados persistidos.
  Normalmente os BDs Relacionais tem uma escalabilidade vertical onde exige mais Hardware para armazenar os dados conforme haja aumento do mesmo
  
  Ja os NoSQl são aplicados a contextos especificos onde ha grande volume de dados (BIG DATA) em que se tem grande flexibilidade e não fique somente limitado as condições rigidades de estrutura onde esses dados seram organizados.
  OBS:( o termo NoSQL significa que não é somente SQL)
  
  ### BDs Relacionais usam o padrão ACID
  
  * Atomicidade
  * Consistência
  * Isolamento
  * Durabilidade

  ### NoSQl usam o padrão BASE
  
  * Basicamente Disponível (Basically Available)
  * Estado suave (Soft state)
  * Consistência Eventual (Eventual consistency)
  
  Um detalhe bastante importante é que os NoSQl não vieram para substituir os relacionais, muito pelo contrario eles se complementam e a aplicabilidade de cada um vai depender do contexto onde ele estara inserido.
  
  Muitos pergutam como se faz consultas em um BD NoSQl, para consultas é importante manter chaves autodescritivas para facilitação na hora de efetuar Querys(consultas).
  
 ## SGBDs e a importancia de saber onde aplicar
 
 
 Cada SGBD (Sistema de Gerenciamento de Banco de Dados) tem suas particularidades e dependendo do tipo dele seja ele NoSQl ou SQL vai a criterio de regras de negocio e 
 como os dados vão se comportar, o importante é saber o conceito e saber qual ferramenta utilizar no contexto certo. Sendo assim importante estabelecer criterios        tecnicos nas hora de escolher o SGBD.
 
 
 ## DATALAKE
 
 
 DataLake  é um repositorio de informações em grande quantidade de forma pura onde esses podem ser consumidos futuramente em alguma aplicação futura
 o papel do Engenheiro de dados esta muito atribuido a como ele ira preparar os dados e como ele ira manter para que um cientista de dados possa coletar e aplicar esses dados nisso o ENG de dados usa de diversas ferramentas ETL.
 
 O que é ETL?
 ETL é um tipo de data integration em três etapas (extração, transformação, carregamento) usado para combinar dados de diversas fontes.
 
 Nisso o papel do Engenheiro é importante por estar alinhado tanto com o negocio da empresa como a infraestrutura onde esses dados seram armazenados, processados, transformados, aplicados e mantidos.
 
 
 By: Yuri Henrique Da Silva
 
 
 
