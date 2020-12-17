# AWS Lambda com DynamoDB

Um experimento referente a uma função lambda simples implementada em Java. Quando a mesma é disparada (pode-se simular isso pelo console da AWS), é inserido um registro no banco de dados referente aos dados de uma pessoa. A função espera receber como parametro uma string json contendo os seguintes atributos: id, firstName, lastName

### Instalação e compilação
Entre na pasta do projeto e execute o comando `mvn install`. O comando pedirá para o Maven (gerenciador de projetos java) que baixe todas as dependências do projeto (as mesmas estão definidas no arquivo de configuração pom.xml) e compilá-las. Ao final será gerado na pasta target um executável Jar que deverá ser submetido a AWS.

### Para re-compilar
caso precise compilar e gerar novamente o executável JAR, execute o comando `mvn package`.
