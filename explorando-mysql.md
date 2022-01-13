### O que é um banco de dados?

Os banco de dados podem ser vistos, de forma direta e resumida, como conjuntos de tabelas. Por sua vez, as tabelas são conjuntos de registros.

Isso nos mostra a sequência lógica para criação de um banco de dados.


2. Crie as tabelas
3. Crie os registros


### Usando o MySQL Workbench?

Agora com o WAMP Server instalado, abra-o.Espere o simbolo ficar verde (Wzinho).

Após o WAMP Server estar aberto e funcionando, abra o MySQL Workbench você observará que já estará aparecendo uma instância local do WAMP Server(**Local Instance Wampmysql**). 

Após clicar nessa instância será aberto o **novo Workbench**.

Nesse momento você deve estar visualizando uma imagem como ![essa](img/criando_banco.PNG).

Pouco a pouco entenderemos essa tela.Note as três regiões em destaque na imagem:
1. No **lado esquerdo** temos uma opção chamada **Schemas**, nela podemos visualizar nosso banco.
2. Na **região central**(número 1) temos o nosso quadro, será nessa região que digitaremos os nossos comandos em SQL.
3. No **lado superior direito** temos o ícone com três janelinhas, podemos usá-las para esconder as abas abertas na tela.

### Principais comandos SQL
1. Criar banco de dados
    `CREATE DATABASE nome_do_banco_de_dados;`
2. 




### Prática para criação do Banco de Dados
Os comandos abaixo foram usados como teste para criação de um banco de dados.

1. `CREATE DATABASE cadastro;`

![Comando para criação do banco de dados](img\criando_banco_de_dados.PNG)

Note os pontos em destaque:
 - a **região central**, onde aparece o número 1, foi a região onde digitamos o comando para criação do banco de dados; 
 - Para executar o comando, clique no **ícone do raio** logo acima do comando digitado;
 - **Para verificar** se o comando foi executado com sucesso, note a instrução que aparece na aba localizada na parte **inferior da tela**;
 - Na **aba da lateral esquerda**, na porção superior, existe um ícone utilizado para atualizar o sistema. Clique nele e note que aparecerá o novo banco de dados criado, que chamamos de **cadastro**;
  

