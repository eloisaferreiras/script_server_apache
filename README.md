# Projeto -Script de Provisionamento de um Servidor Web (Apache)

IAC: (Infrastructure as Code), refere-se ao gerenciamento e provisionamento da infraestrutura por meio de códigos, em vez de processos manuais. Ou seja, pode-se criar scripts para agilizar alguns processos, ou manutenções em Sistemas Operacionais, Cloud e demais serviços de infraestura. 

-------------------------------

 Para a criação desse projeto utilizamos o CMD no linux, na distros Ubuntu. 


Foi realizado o seguinte plano das tasks: 

- [x]  Restaurar  snapshot ;
- [x]  atualizar servidor;
- [x]  instala o apache2;
- [x]  instalar o unzip;
- [x]  baixar a aplicação do github ()  no diretório tmp ;
- [x]  copiar os arquivos da aplicação no diretório apache padrão;
- [x]  subir script para o github.

<h1>Resultados: </h1>

Configuração do server: 
---
Para atualizar o servidor:

apt-get update  
![image](https://github.com/eloisaferreiras/script_server_apache/assets/73046034/4b681772-c6fd-49ef-9202-780426768397)


instalar o apache 2 ( nesse caso já estava instalado ) então só atualizou 
![image](https://github.com/eloisaferreiras/script_server_apache/assets/73046034/2d2a163d-46fa-44a6-93b0-aa401dfed45e)


Instalação o unzip : 
---
![image](https://github.com/eloisaferreiras/script_server_apache/assets/73046034/b96b82c2-26f8-4ee6-b4e9-e7557f4ce8e5)


entrar no diretorio tmp e baixar o arquivo no gituhub 
![image](https://github.com/eloisaferreiras/script_server_apache/assets/73046034/1f47fe1b-1a36-4420-8bf4-9d1b0d10de12)


descompactar o arquivo zip 
![image](https://github.com/eloisaferreiras/script_server_apache/assets/73046034/b3ae324e-5006-428f-b76c-882e1a32e343)

copiar arquivo do diretório tmp para o diretório padrão apache 
![image](https://github.com/eloisaferreiras/script_server_apache/assets/73046034/d29a7f77-50d1-4e8c-bfea-63a970ebe236)

  
