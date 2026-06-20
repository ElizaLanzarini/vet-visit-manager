# Gerenciador de Visitas Veterinárias

Sistema web desenvolvido para otimizar o gerenciamento de visitas comerciais realizadas por representantes de produtos veterinários, centralizando informações de clientes, profissionais e histórico de atendimentos em uma única plataforma.

## Sobre o Projeto

Este projeto está sendo desenvolvido para atender uma necessidade real de uma representante comercial do segmento veterinário.

Atualmente, o controle de visitas, contatos e acompanhamentos é realizado por meio de planilhas e registros manuais, dificultando a organização das informações, o acompanhamento periódico dos clientes e a visualização das atividades pendentes.

A aplicação tem como objetivo centralizar esses dados em uma única plataforma, proporcionando maior controle sobre as visitas realizadas, histórico de interações, acompanhamento dos clientes e planejamento das próximas ações comerciais.

O projeto foi concebido a partir de entrevistas e observações do processo de trabalho da futura usuária da solução, buscando reproduzir necessidades reais do dia a dia da operação.

## Problema de Negócio

Entre os principais desafios identificados estão:

- Controle manual das visitas realizadas;
- Dificuldade no acompanhamento do histórico de contatos;
- Informações distribuídas entre planilhas, anotações e aplicativos diversos;
- Falta de visibilidade sobre visitas pendentes ou atrasadas;
- Dificuldade para planejar roteiros e retornos aos clientes;
- Tempo excessivo gasto em atividades administrativas.

## Objetivos

- Centralizar informações de clientes e visitas;
- Melhorar o acompanhamento das atividades comerciais;
- Reduzir a dependência de controles manuais;
- Facilitar o planejamento de visitas futuras;
- Disponibilizar histórico completo de interações com cada cliente;
- Aumentar a produtividade e organização das atividades em campo.

## Funcionalidades Implementadas (MVP)

### Gestão de Clientes

- Cadastro de clínicas veterinárias;
- Consulta e atualização de informações dos clientes;
- Armazenamento de dados de contato e localização.

### Gestão de Contatos

- Cadastro de profissionais vinculados às clínicas;
- Registro de informações de contato;
- Associação de múltiplos contatos a um mesmo cliente.

### Gestão de Visitas

- Registro de visitas realizadas;
- Armazenamento de observações e resultados;
- Histórico completo de interações;
- Controle da data da última visita.

### Controle de Status

- Visita concluída;
- Visita pendente;
- Visita atrasada.

### Consulta de Informações

- Busca de clientes;
- Filtros para localização rápida de registros;
- Painel resumido para acompanhamento das atividades.

## Tecnologias Utilizadas

### Front-end

- HTML5
- CSS3
- JavaScript
- React (planejado para versões futuras)

### Back-end

- Node.js
- Express.js

### Banco de Dados

- MySQL
- MariaDB

## Arquitetura do Projeto

Estrutura inicial planejada para organização da aplicação:

```text
src/
├── controllers/
├── services/
├── repositories/
├── models/
├── routes/
├── middlewares/
└── database/
```

## Próximas Evoluções

- Sistema de autenticação e controle de acesso;
- Calendário integrado para planejamento de visitas;
- Lembretes automáticos de retorno aos clientes;
- Dashboard com indicadores e métricas;
- Exportação de relatórios em PDF e Excel;
- Interface responsiva para dispositivos móveis;
- Geolocalização de clientes;
- Backup e recuperação de dados;
- Histórico avançado de relacionamento com clientes.

## Status do Projeto

🚧 Em desenvolvimento

Atualmente em fase de definição e implementação das funcionalidades do MVP.

## Aprendizados e Desafios

Além de atender uma necessidade real de negócio, este projeto também representa uma oportunidade para aplicar conhecimentos em:

- Levantamento e análise de requisitos;
- Modelagem de banco de dados;
- Desenvolvimento Full Stack;
- Arquitetura de software;
- Boas práticas de organização de código;
- Transformação de processos manuais em soluções digitais.

## Autora

**Eliza Lanzarini**

Analista de Projetos Pleno, formada em Análise e Desenvolvimento de Sistemas (ADS) e pós-graduanda em Desenvolvimento Web Full Stack com foco em PHP.

Atua na análise de requisitos, definição de regras de negócio e desenvolvimento de soluções para sistemas da área da saúde, aplicando neste projeto conceitos de engenharia de software e desenvolvimento Full Stack para resolver um problema real do segmento veterinário.

## Considerações

Este projeto está sendo desenvolvido para uso real e contínuo por uma profissional do segmento veterinário, com foco na melhoria da gestão de visitas comerciais e organização do relacionamento com clientes.

Seu desenvolvimento é orientado por necessidades reais de negócio, permitindo a evolução constante da solução conforme novos requisitos forem identificados.
