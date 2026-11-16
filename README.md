# Agendador de Horários

Este é um projeto pessoal que estou fazendo para aprender Spring Boot na prática. A ideia é criar uma API para marcar horários de atendimento: qual serviço, com qual profissional, para qual cliente e em que dia e hora.

Ainda estou no começo, então muita coisa vai mudar por aqui. 🚧

## Onde estou agora

Até agora criei o projeto com Spring Boot e Maven, a classe `Agendamento` (que vira a tabela no banco) e o repositório com Spring Data JPA. Os dados ficam no H2, um banco em memória, então tudo some quando a aplicação fecha.

Ainda não tem endpoints, então por enquanto não dá para usar a API de verdade.

## O que quero fazer a seguir

- Criar os endpoints para marcar, listar e cancelar agendamentos
- Impedir dois agendamentos no mesmo horário para o mesmo profissional
- Escrever testes
- Trocar o H2 por um banco de verdade

## Tecnologias

Java 21, Spring Boot, Spring Data JPA, H2, Lombok e Maven.

## Como rodar

Você precisa ter o Java 21 instalado.

```bash
git clone https://github.com/borges705/agendador-horarios.git
cd agendador-horarios
./mvnw spring-boot:run
```

No Windows, use `mvnw.cmd spring-boot:run`.

## Sobre mim

Sou o Vinícius, estudante de Análise e Desenvolvimento de Sistemas. Meu GitHub: [borges705](https://github.com/borges705)
