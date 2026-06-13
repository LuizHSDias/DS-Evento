# Sistema Evento (EM DESENVOLVIMENTO!)

Projeto desenvolvido como solução do desafio **Modelo de Domínio e ORM** da formação Desenvolvedor Moderno da DevSuperior.

## 📖 Sobre o Projeto

O sistema tem como objetivo gerenciar informações de participantes e atividades de um evento acadêmico.

As atividades podem representar palestras, cursos, oficinas e outras modalidades, possuindo nome, descrição, preço e blocos de horários. Os participantes podem se inscrever em diversas atividades e cada atividade pode possuir vários participantes.

O projeto foi desenvolvido utilizando Spring Boot, JPA/Hibernate e banco de dados H2.

## 🏗️ Modelo de Domínio

O sistema é composto pelas seguintes entidades:

- Participante
- Atividade
- Categoria
- Bloco

### Relacionamentos

- Participante ↔ Atividade (Many-to-Many)
- Atividade → Categoria (Many-to-One)
- Atividade → Bloco (One-to-Many)

## 🚀 Tecnologias Utilizadas

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Banco de Dados H2
- Maven

## ✅ Funcionalidades

- Cadastro de participantes
- Cadastro de atividades
- Cadastro de categorias
- Cadastro de blocos de horário
- Relacionamento entre participantes e atividades
- Seeding automático da base de dados