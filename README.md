# Notes_BancoDeDados

> CREATE DATABASE "EscrevaONomeDoBancoDeDados" ; // cria um banco de dados
<p> SHOW DATABASES;
<p> USE "EscrevaONomeDoBancoDeDados" ; // usa o banco de dados 
<p> CREATE TABLE; // nome da tabela

_____________________________________________________________________
Esquema - esqueleto // estado inicial do banco de dados

### Arquitetura de 3 esquemas:
* Catálogo
* Isolamento
* Views

_
Cash
_
Modelo relacional - SQL
DDL - Data Definition Language "views"
DML -

Interfaces:
Web clients, app mobile, forms, GUI, NLI, Pesquisa Keyword, Speech input/output, Interfaces (naive(repetitiva)/DBA(DBA Staff)

Modelo Conceitual (Entidades,Relacionamentos, atributos) - principal foco em esquema
Entidade == objeto - possui atributos

Atributo - atômico(simples)
Ex: CPF, RG, nome
Atributo Composto: adress(Street adress, city, state, zipcode, number home)

Simples/Valorados
Ex:
idade, cores, grau acadêmico

Valorado(valor)
car -> cor -> azul || verde || cinza || branco

Constraints - cardinalidade
1:1, 1:N, N:N, N:1

Entidade: classe/objeto 
Relacionamento: agregações(associação)
Atributos: propriedades elementares

Entidade Fraca
