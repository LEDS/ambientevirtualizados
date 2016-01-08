# Ambientes Virtuais utilizados pelo LEDS
Esse repositório contem os ambientes virtuais utilizados nos projetos do LEDS. Para facilitar a instalação e a configuração de tais ambientes utilizamos a ferramenta [Docker](https://www.docker.com/) e [DockerCompose](https://www.docker.com/docker-compose).

 É importante comentar que no caso das feramentas que necessitam de uma certa configuração de banco de dados é necessário modificar o arquivo __docker-compose.yml__. Por motivo de segurança não deixamos as senhas e usários pré-configurados nesse arquivo. Dessa forma, é necessário substituir as seguintes __tags__ do arquivo citado:

 * __user__ : usuário do banco de dados
 * __password__ : password do usuário do banco de dados;
 * __database_name__ : nome do banco de dados a ser criado;

Segue a lista de ambientes virtualizados:
* __Pentaho 5.4__: é uma solução open-source de analise e integração de dados;
* __Sonar 5.2__: é uma plataforma open-source de gerenciamento da qualidade de código de software;
