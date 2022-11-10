# Curso_Banco_Dados_Oracle
  Material utilizado no curso de Banco de Dados Oracle.

# Primeira Aula (Apresentação, Detalhes sobre Oracle, História da Oracle, Historia SQL, Padronização e ETC)
# Segunda Aula (Instalação do serviço de gerenciamento de banco de dados e de sua IDE)
  download programa arquitetura: https://bestofbi.com/architect-download/
  download programa oracle xpress: https://www.oracle.com/br/database/technologies/xe-downloads.html
  download programa SQL Developer: https://www.oracle.com/database/sqldeveloper/technologies/download/ 

# Configurando Oracle Xpress
  Instalação com criação de senha Master (Lembrem-se de anotar esta senha)
  
# Configurando Oracle SQL Developer
  Instalação comum (apertar "next" em todas as etapas)
  
  Abrindo a aplicação vamos na janela "Conexão de Banco de Dados" em seguida "Criar conexão manualmente", 
  escolha um nome para dar para a "Conexão",
  
  Em seguida escolhemos o "Nome do Usuário" e "Senha" de acesso a este banco de dados, 
  geralmente é usado o mesmo usuário e senha criada na instalação anterior
  (usuario "system" e senha configurada na instalação).
  
  Nome do Host deverá ser inicialmente o "localhost" e Porta "1521" por padrão.
  
  Encerraremos essa configuração realizando a conexão através do botão "Conectar" da janela recém configurada.
  
  Somente após se conectar que conseguiremos obter todas as informações na janela ao lado.
  
# Entidades da Conexão
  Tablespace = Entidade mais importante, é nossa área de armazenamento de tabelas.
  
  Tabela = Local onde armazenaremos os dados.
  
  Campo = Por comparação seria como a coluna de uma tabela.
  
  Registro = Por comparação seria como a linha de uma tabela.
  
  Tipo de dado = Definição atribuida aos valores configurados em um campo, atribuindo um tipo de dados que permite ser carregado para um registro.
  
  Restrição de tamanho = Definição da valor máximo suportado pelo tipo de dado configurado ou pelo campo da tabela.
  
  Definição para Nulos = Definição que determina a possibilidade se determinado campo pode ou não permitir valores nulos.
  
  Chaves Primarias = Marcação que define que os dados são unicos em relação a todos os registros de uma tabela. 
  Elas não precisam ser obrigatórios e nem precisam ser únicas dentro de um registro.
  
  Procedures = Funções criadas dentro do banco de dados, podendo usar estruturas condicionais e outras regras de processamento, 
  geralmente para sua construção utilizamos uma linguagem específica, a PL/SQL.
  
  Triggers = Uma especie de comando, de acordo com inclusão, alteração ou exclusão de dados do registro de uma tabela.
