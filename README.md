# CRUD
Este repositório foi feito para realizar o teste prático para se tornar um Aprendiz Back-end do Grupo de Comunicação O POVO.

## Instalação: 
- Clonar o repositótio do git 
- Criar um banco de dados
- Criar no banco a tabela utilizando o código abaixo:

CREATE TABLE clientes (
  id int(11) NOT NULL,
  name varchar(80) NOT NULL,
  cpf varchar(20) NOT NULL,
  address varchar(250) NOT NULL,
  telephone varchar(100) NOT NULL,
  email varchar(50) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

## Utilização:
Na página inicial encontra-se a listagem dos clientes cadastrados, suas respectivas informações e o botão de cadastrar um novo cliente. 

Na página de cadastro será requisitado as informações do cliente, depois de preencher os dados, clicando em "Cadastrar" o aluno será adicionado ao banco de dados.

Clicando no botão "Mais informações" irá para uma página onde exibe as informações do aluno selecionado e na mesma página tem a opções de editar aluno e excluir.

Ao clicar em "Editar" seguira para uma página onde será requisitado os dados para a edição do cadastro.

Ao clicar em "Excluir" os dados do aluno seram excluidos.
