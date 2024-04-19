# Lab01-Data-warehouse-DSA
Lab 01 - Data Warehouses: Design and implementation
Para esse lab estaremos usando a ferramenta Star UML. Essa ferramenta permite criar diagramas de entidade e relacionamento;

-Modelo de negócio: Empresa de outsourcing;

1° Entidade: Funcionários
Atributos: Func_ID [PK]:INTEGER, Nome:CHAR, Departamento:CHAR [FK], Especialidade:CHAR, Nível:CHAR, Remoto_Local:CHAR, Supervisor:CHAR, Avaliação_atual:INTEGER, Avaliação_Anterior:INTEGER, Data_Admissão:DATE, Data_Demissão:DATE

2° Entidade: Departamento 
Atributos: Departamento [PL]:CHAR, Project_ID:INTEGER, Gerente [FK]:CHAR

3° Entidade: Projetos
Atributos: Proejct_ID [PK]:INTEGER, Localização:CHAR

4°  Entidade: Plano de Saúde  
Atributos: Func_ID:INTEGER [PK], Dependentes:CHAR

![image](https://github.com/Gabriel-Brenner/Lab01-Data-warehouse-DSA/assets/15240579/33c3db91-2793-4929-a520-caac4375a066)

