<div align="center">

# Sistema de Chamados de TI

Aplicação web para registrar e acompanhar solicitações de suporte técnico.

<p>
  <img alt="Status" src="https://img.shields.io/badge/status-em%20desenvolvimento-f59e0b?style=for-the-badge">
  <img alt="Projeto Integrador" src="https://img.shields.io/badge/projeto-integrador-0B5CAD?style=for-the-badge">
  <img alt="Etapa 2" src="https://img.shields.io/badge/etapa%202-desenvolvimento-7c3aed?style=for-the-badge">
</p>

Projeto Integrador de **Boas Práticas de Desenvolvimento de Software**  
Análise e Desenvolvimento de Sistemas — Senac

</div>

## Sobre

O projeto surgiu da necessidade de organizar solicitações de suporte de TI que muitas vezes são feitas por mensagens, ligações ou diretamente para a equipe responsável.

A proposta é reunir essas solicitações em uma aplicação web onde seja possível cadastrar e acompanhar chamados, visualizar sua prioridade e atualizar o andamento do atendimento.

A primeira etapa do Projeto Integrador foi dedicada ao planejamento. Nesta segunda etapa, o grupo está desenvolvendo a aplicação.

## Funcionalidades

A primeira versão prevê:

- cadastro de chamados;
- listagem e consulta;
- edição e exclusão;
- prioridade baixa, média ou alta;
- status aberto, em atendimento ou resolvido;
- pesquisa e filtros;
- registro de prazo para atendimento.

O fluxo principal será:

```text
Novo chamado
    ↓
Armazenamento
    ↓
Consulta
    ↓
Atendimento
    ↓
Resolvido
```

## Tecnologias

| Tecnologia | Uso |
| --- | --- |
| HTML5 | Estrutura das páginas |
| CSS3 | Interface |
| JavaScript | Funcionalidades e regras da aplicação |
| LocalStorage | Armazenamento dos chamados no navegador |
| Git e GitHub | Versionamento e colaboração |

Nesta versão não será utilizado backend. Os registros serão armazenados no `localStorage` do navegador.

Por isso, os dados ficam associados ao navegador e ao endereço em que a aplicação está sendo executada e não são compartilhados entre usuários ou dispositivos.

## Como executar

O projeto não exige instalação de dependências.

Clone o repositório:

```bash
git clone https://github.com/rafaelcairess/sistema-chamados-ti.git
```

Entre na pasta:

```bash
cd sistema-chamados-ti
```

Depois, abra o arquivo `index.html` no navegador.

## Estrutura

A estrutura poderá mudar durante o desenvolvimento.

```text
sistema-chamados-ti/
├── index.html
├── css/
│   └── style.css
├── js/
│   ├── app.js
│   ├── storage.js
│   └── validation.js
├── assets/
├── docs/
├── CONTRIBUTING.md
└── README.md
```

## Equipe

| Integrante | GitHub | Responsabilidade |
| --- | --- | --- |
| Antonio Agricola Dorneles | A definir | A definir |
| Sheila Cristina Zanin | A definir | A definir |
| Igor Fagundes Batista | A definir | A definir |
| Herica Franklin Ramalho | A definir | A definir |
| Vitor Hugo Benatti Pedrassolli | A definir | A definir |
| Mateus Malezan Tasquetto | A definir | A definir |
| Rafael Pereira Caires Pires | [@rafaelcairess](https://github.com/rafaelcairess) | HTML, CSS e GitHub |
| Joao Vitor Oliveira Goncalves | A definir | A definir |

As responsabilidades serão atualizadas conforme a divisão das tarefas da segunda etapa.

## Andamento

### Etapa 1

- [x] Definição do tema
- [x] Definição do problema
- [x] Objetivo do sistema
- [x] Levantamento das funcionalidades
- [x] Escolha das tecnologias
- [x] Planejamento da implementação
- [x] Primeira entrega

### Etapa 2

- [ ] Estrutura HTML
- [ ] Interface CSS
- [ ] Cadastro de chamados
- [ ] Armazenamento com LocalStorage
- [ ] Listagem dos chamados
- [ ] Edição e exclusão
- [ ] Status, prioridade e filtros
- [ ] Validações
- [ ] Testes
- [ ] Documentação final

## Documentação

Os materiais de planejamento e desenvolvimento ficam na pasta [`docs`](docs/).

- [Etapa 1](docs/etapa-1.md)
- [Requisitos](docs/requisitos.md)
- [Planejamento](docs/planejamento.md)
- [Decisões do projeto](docs/decisoes.md)

As orientações para alterações no repositório estão em [`CONTRIBUTING.md`](CONTRIBUTING.md).
