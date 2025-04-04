# Guia de Contribuição

Obrigado por se interessar em contribuir com a SouJunior! Ficamos muito felizes em ter você aqui.

Cada contribuição, por menor que seja, tem um impacto significativo para nossa equipe e para toda a comunidade. Com a sua ajuda, podemos crescer juntos e criar ainda mais oportunidades para todos!

---

## Código de Conduta

- Seja amigável e respeitoso com todos os membros da comunidade.
- Mantenha uma comunicação clara e construtiva.
- Seja paciente e inclusivo, considerando diferentes níveis de conhecimento e experiências.
- Comportamentos tóxicos ou discriminatórios não serão tolerados.

---

## Diretrizes para Contribuidores

### Primeiros Passos

1. Fork o repositório.
2. Clone o repositório para sua máquina local.
3. Siga as instruções do repositório para instalar e rodar a aplicação.

---

### Padrão de Commits

- Use o formato [Conventional Commits](https://www.conventionalcommits.org/pt-br/) para suas mensagens de commit.
- Mantenha as mensagens claras e concisas.
- Use os seguintes tipos de commits:
  - `feat` para novas funcionalidades.
  - `fix` para correções de bugs.
  - `docs` para atualizações na documentação.
  - `style` para alterações no estilo do código.
  - `refactor` para refatorações.
  - `perf` para melhorias de performance.
  - `test` para adição de testes.
  - `build` para alterações na build.
  - `ci` para alterações na configuração de CI.
  - `chore` para alterações no processo de compilação ou em ferramentas e bibliotecas auxiliares, como a geração de documentação

---

### Branching

- [Trunk-based Development](https://www.atlassian.com/continuous-delivery/continuous-integration/trunk-based-development): Utilizamos essa estratégia, onde todas as alterações são feitas diretamente na branch `main`. Isso ajuda a manter o código-fonte limpo e evita a complexidade de gerenciar muitas branches.
- **Práticas**:
  - Não usamos feature branches.
  - Todas as alterações devem ser baseadas na branch `main`.
  - Mantenha as alterações pequenas e focadas.

### Abrindo um Pull Request

Antes de abrir um Pull Request:

- Certifique-se de que suas alterações estão na branch correta.
- Verifique se suas alterações resolveram a issue correspondente (caso aplicável).
- Forneça uma descrição clara das mudanças.
- Mantenha as alterações concisas, criando Pull Requests menores e focados
- Verifique se os testes passam (caso aplicável).

**Por que fazer PRs menores?**

- Revisão Rápida: PRs menores são mais fáceis de revisar, permitindo que os mantenedores entendam rapidamente as mudanças.
- Feedback Claros: Com mudanças focadas, o feedback é mais direcionado e construtivo.
- Menos Complexidade: Evita complicações durante o merge.
- Iteração Rápida: Permite que você iterate mais rapidamente com base no feedback recebido.

---

### Títulos de Pull Request

Use o seguinte formato para os títulos dos Pull Requests:

```
tipo: breve-descrição
```

**Regras para Títulos de Pull Requests**:

- **Forma Ativa e Imperativa**: Escreva no presente, como se estivesse dando uma ordem (e.g., "adiciona suporte").
- **Sem Ponto Final**: Não use ponto no final do título.
- **Clareza**: O título deve ser claro e direto, permitindo que outros entendam a mudança de forma rápida.

**Exemplo**:

```
feat(cadastro): adiciona confirmacao de email
```

**Exemplos de Títulos Ruins** (para evitar):

- `Arrumei um bug`
- `Adicionando novas features`
- `Atualização`

**Exemplos de Títulos Bons** (para usar):

- `feat(cadastro): adiciona confirmacao de email`
- `fix(login): corrige recuperacao de senha`
- `refactor(cadastro): refatora confirmacao de email`

### Features Grandes

Para features grandes:

- Divida a feature em pequenas partes.
- Abra um Pull Request para cada parte.
- Forneça documentação relevante.

### Recebendo Ajuda

Se você precisar de ajuda:

- Abra uma issue ou inicie uma discussion.
- Descreva claramente o problema ou dúvida.
- Seja paciente e aberto a feedback.
- Aprenda com as sugestões e críticas construtivas.
