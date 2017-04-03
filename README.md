 Controle-de-Projetos-Grupo-4
Grupo destinado ao trabalho da matéria de Projeto de Software da Universidade Federal de Goiás (UFG) - Grupo 4


Tema 04 - Sistema de Controle de Projetos

O Objetivo do presente trabalho é projetar uma aplicação para controlar os projetos desenvolvidos por uma empresa, possibilitando para isso a alocação de colaboradores, o controle da situação atual dos projetos e o cadastro de departamentos. Os requisitos que devem ser atendidos neste projeto são os descritos a seguir:


1. A entidade principal do sistema é o projeto. Um projeto possui um nome, data de inicio e de conclusão, um orçamento, uma descrição e uma situação. Esta situação pode ser: em andamento, em atraso, paralisado, cancelado, concluido). 
2. Um projeto quando instanciado assume a situação de “em andamento”. A alteração na situação do projeto deve informar quando foi efetuada e a motivação para a alteração e quem efetuou a alteração;
3. Projetos são desenvolvidos por Departamentos. Departamentos possuem os seguintes atributos: nome, descrição, orçamento, email e telefone. (a soma dos orçamentos dos projetos não pode ser maior que o orçamento do departamento).
4. Os colaboradores que são alocados aos projetos estão lotados nos departamentos e cada departamento tem um gerente, que é um colaborador;
5. Colaboradores possuem os seguintes atributos: Nome, CPF, Sexo, Data de Nascimento, remuneração, e-mail, endereço e telefone. 
1. Telefones são identificados pelo seu tipo (fixo ou móvel), pelo número e pela operadora;
2. O Endereco é composto do tipo (rua, avenida, alameda, etc), nome, número, complemento, bairro, cep, cidade, estado). O endereço deve ser persistido no sistema, porém os dados devem ser obtidos através de consulta ao WebServices dos Correios. Caso o endereço não exista nos correios, o sistema deve permitir o cadastramento do mesmo.
3. Um colaborador pode estar alocado a mais de um projeto.
4. A alocação de um colaborador a um projeto deve informar a carga horária e a situação desta alocação, que pode estar ativa ou encerrada.
5. Todos os colaboradores devem estar alocados a pelo menos um projeto do departamento.
6. O sistema deverá informar listar os projetos por departamento, sendo filtrados por sua respectiva situação;
7. O sistema deverá ser capaz de informar quais os colaboradores estão ou estiveram alocados a um projeto em determinado período;
8. O sistema deverá ser capaz de verificar se os orçamentos do projetos não ultrapassam o orçamento do departamento.
