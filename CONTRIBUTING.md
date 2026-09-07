# Guia de contribuição

Este documento reúne as práticas iniciais para colaborar no projeto. O fluxo poderá ser ajustado pela equipe durante a Etapa 1.

## Antes de começar

1. Atualize sua cópia local da branch principal.
2. Consulte o planejamento e escolha uma tarefa definida pelo grupo.
3. Crie uma branch específica para a alteração.

## Branches

Use nomes curtos que indiquem o tipo e o objetivo do trabalho:

```text
docs/descrever-problema
feat/cadastrar-chamado
fix/validar-prioridade
```

Durante a Etapa 1, a maioria das alterações usará o prefixo `docs/`. Os prefixos `feat/` e `fix/` serão usados quando o desenvolvimento começar.

## Commits

Cada commit deve representar uma alteração coerente e ter uma mensagem objetiva, preferencialmente no infinitivo:

```text
docs: descrever objetivo do projeto
feat: adicionar cadastro de chamados
fix: corrigir filtro por status
```

Evite mensagens genéricas como `alterações`, `ajustes` ou `final`.

## Pull Requests

Antes de abrir um Pull Request:

- revise os arquivos alterados;
- confirme que a mudança atende à tarefa;
- execute os testes aplicáveis;
- atualize a documentação quando necessário.

No Pull Request, descreva o que mudou, por que a mudança foi necessária e como ela foi verificada. Pelo menos outro integrante deve revisar a alteração antes do merge.

## Decisões do grupo

Decisões que afetem escopo, tecnologias ou organização devem ser registradas em [`docs/decisoes.md`](docs/decisoes.md).
