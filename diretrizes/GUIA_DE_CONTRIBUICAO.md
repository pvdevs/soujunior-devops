# Guia de Contribuição

Obrigado por se interessar em contribuir com a SouJunior! Ficamos muito felizes em ter você aqui.

Cada contribuição, por menor que seja, tem um impacto significativo para nossa equipe e para toda a comunidade. Com a sua ajuda, podemos crescer juntos e criar ainda mais oportunidades para todos!

---

## Código de Conduta

Por favor, certifique-se de que leu e entendeu nosso [Código de Conduta](./CODIGO_DE_CONDUTA.md).

---

## Diretrizes para Contribuidores

### Primeiros Passos

1. Fork o repositório.
2. Clone o repositório para sua máquina local.
3. Siga as instruções do repositório para instalar e rodar a aplicação.
4. Crie uma branch para sua contribuição.

---

### Padrão de Commits

Adotamos o formato Conventional Commits para garantir consistência e clareza nas mensagens de commit. Esse padrão facilita o entendimento das mudanças realizadas no projeto e ajuda na organização do histórico de commits.

**Práticas**:

- Use mensagens claras e concisas.
- Siga o formato definido pelo Conventional Commits, utilizando tipos como `feat` para novas funcionalidades e `fix` para correções de bugs.

**Exemplos**:

- `feat(paginacao): adiciona suporte para navegação entre páginas`
- `fix(css): corrige alinhamento de botões na página inicial`

---

### Branching

Utilizamos a estratégia de [Trunk-based Development](https://www.atlassian.com/continuous-delivery/continuous-integration/trunk-based-development), onde todas as alterações são feitas diretamente na branch main. Essa abordagem ajuda a manter o código-fonte limpo e reduz a complexidade de gerenciar múltiplas branches.

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

Os títulos dos Pull Requests devem seguir um padrão semelhante ao utilizado nas mensagens de commit, baseado no [Conventional Commits](https://www.conventionalcommits.org/pt-br/). Isso ajuda a manter consistência e clareza em todo o processo de contribuição.

**Regras para Títulos de Pull Requests**:

- **Forma Ativa e Imperativa**: Escreva no presente, como se estivesse dando uma ordem (e.g., "adiciona suporte").
- **Sem Ponto Final**: Não use ponto no final do título.
- **Clareza**: O título deve ser claro e direto, permitindo que outros entendam a mudança de forma rápida.
- **Consistência com Conventional Commits**: Utilize os mesmos tipos definidos no padrão de commits, como `feat`, `fix`, `docs`, `refactor`, entre outros.

**Exemplos de Títulos Ruins** (para evitar):

- `Arrumei um bug`
- `Adicionando novas features`
- `Atualização`

**Exemplos de Títulos Bons** (para seguir):

- `feat(cadastro): adiciona confirmacao de email`
- `fix(login): corrige recuperacao de senha`

Seguir esse padrão garante que os títulos dos Pull Requests sejam informativos e consistentes, facilitando o entendimento e a organização do histórico de mudanças no projeto.

### Features Grandes

Para features grandes:

- Divida a feature em pequenas partes.
- Abra um Pull Request para cada parte.
- Forneça documentação relevante.

## Recebendo Ajuda

Se você precisar de ajuda:

- Abra uma issue ou inicie uma discussion.
- Descreva claramente o problema ou dúvida.
- Seja paciente e aberto a feedback.
- Aprenda com as sugestões e críticas construtivas.
