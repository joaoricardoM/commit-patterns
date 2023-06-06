# commit-patterns

<h1 align="center">
📄<br>commit patterns - ENG-US
</h1>

## Type and Description

The semantic commit has the structural elements below (types), which inform the intent of your commit to the user of your code.

- `feat`- Commits of type feat indicate that your piece of code is including a **new feature** (relates to the MINOR of semantic versioning).

- `fix` - Fix-type commits indicate that your committed code snippet is **solving a problem** (bug fix), (related to the semantic versioning PATCH).

- `docs` - Commits of type docs indicate that there have been **changes in the documentation**, for example in the Readme of your repository. (Does not include code changes).

- `test` - Commits of type test are used when **changes to tests** are performed, either by creating, modifying or deleting unit tests. (Does not include code changes)

- `build` - Build-type commits are used when making changes to **build files and dependencies**.

- `perf` - Commits of type perf serve to identify any code changes that are related to **performance**.

- `style` - Commits of type style indicate that there were changes regarding **code formatting**, semicolons, trailing spaces, lint... (Does not include code changes).

- `refactor` - Commits of the refactor type refer to changes due to **refactorings that do not change its functionality**, such as, for example, a change in the format of how a certain part of the screen is processed, but which maintained the same functionality, or performance improvements due to a code review.

- `chore` - Chore commits indicate **task updates** to build, admin settings, packages... like adding a package to gitignore. (Does not include code changes).

- `ci` - Commits of type ci indicate changes related to **continuous integration** (_continuous integration_).

## ☑️ Recommendations

- Add a title consistent with the title of the content;
- We recommend that the first line should have a maximum of 4 words;
- To describe in detail, use the description of the commit;
- Use an emoji at the beginning of the commit message representing the commit;
- A link needs to be added in its most authentic form, ie: without link shorteners and affiliate links;

## 🍧 Commit Addons

- **Footnote:** Usually information about the reviewer and trello or jira card number
    Example: Reviewed-by: Elisandro Mello Refs #133
- **Body** : more precise descriptions of what is contained in the commit, showing impacts and the reasons why the code changes were used, as well as essential instructions for future interventions.
    Example: see the issue for details on typos fixed.
- **Descriptions**: a brief description of the change
  Example: correct minor typos in code
 
 ## 💻 Examples
 
 <table>
  <thead>
    <tr>
      <th>Git command</th>
      <th>Result on GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m ":tada: initial commit"</code>
      </td>
      <td>🎉 Initial commitl</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":books: docs: README Update"</code>
      </td>
      <td>📚 docs: README update</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bug: fix: Infinite loop at line 50"</code>
      </td>
      <td>🐛 fix: Infinite loop on line 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":sparkles: feat: Login page"</code>
      </td>
      <td>✨ feat: Login page</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bricks: ci: Modification in Dockerfile"</code>
      </td>
      <td>🧱 ci: Modification in Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":recycle: refactor: Passando para arrow functions"</code>
      </td>
      <td>♻️ refactor: Passando para arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":zap: perf: Improved response time"</code>
      </td>
      <td>⚡ perf: Improved response time</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":boom: fix: Reversing inefficient changes"</code>
      </td>
      <td>💥 fix: Reversing inefficient changes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":lipstick: feat: Form CSS styling"</code>
      </td>
      <td>💄 feat: Form CSS styling</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":test_tube: test: Creating new test"</code>
      </td>
      <td>🧪 test: Creating new test</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bulb: docs: Comments on the LoremIpsum() function"</code>
      </td>
      <td>💡 docs: Comments on the LoremIpsum() function</td>
    </tr>
  </tbody>
</table>



<h1 align="center">
📄<br>commit patterns - PT-BR
</h1>

## Tipo e Descrição

O commit semântico possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.

- `feat`- Commits do tipo feat indicam que seu trecho de código está incluindo um **novo recurso** (se relaciona com o MINOR do versionamento semântico).

- `fix` - Commits do tipo fix indicam que seu trecho de código commitado está **solucionando um problema** (bug fix), (se relaciona com o PATCH do versionamento semântico).

- `docs` - Commits do tipo docs indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

- `test` - Commits do tipo test são utilizados quando são realizadas **alterações em testes**, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

- `build` - Commits do tipo build são utilizados quando são realizadas modificações em **arquivos de build e dependências**.

- `perf` - Commits do tipo perf servem para identificar quaisquer alterações de código que estejam relacionadas a **performance**.

- `style` - Commits do tipo style indicam que houveram alterações referentes a **formatações de código**, semicolons, trailing spaces, lint... (Não inclui alterações em código).

- `refactor` - Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

- `chore` - Commits do tipo chore indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

- `ci` - Commits do tipo ci indicam mudanças relacionadas a **integração contínua** (_continuous integration_).

## ☑️ Recomendações

- Adicione um título consistente com o título do conteúdo;
- Recomendamos que na primeira linha deve ter no máximo 4 palavras;
- Para descrever com detalhes, usar a descrição do commit;
- Usar um emoji no início da mensagem de commit representando sobre o commit;
- Um link precisa ser adicionado em sua forma mais autêntica, ou seja: sem encurtadores de link e links afiliados;

## 🍧 Complementos de Commits

- **Rodapé:** Geralmente uma informação sobre o revisor e numero de card de trello ou jira 
  Exemplo: Reviewed-by: Elisandro Mello Refs #133
- **Corpo** : descrições mais precisas do que está contido no commit, apresentando impactos e os motivos pelos quais foram empregadas as alterações no código, como também instruções essenciais para intervenções futuras. 
  Exemplo: see the issue for details on typos fixed.
- **Descrições**:  uma descrição sucinta da mudança
  Exemplo: correct minor typos in code

## 💻 Exemplos

<table>
  <thead>
    <tr>
      <th>Comando git</th>
      <th>Resultado no GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m ":tada: Commit inicial"</code>
      </td>
      <td>🎉 Commit inicial</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":books: docs: Atualizaçao do README"</code>
      </td>
      <td>📚 docs: Atualizaçao do README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bug: fix: Loop infinito na linha 50"</code>
      </td>
      <td>🐛 fix: Loop infinito na linha 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":sparkles: feat: Pagina de login"</code>
      </td>
      <td>✨ feat: Pagina de login</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bricks: ci: Modificaçao no Dockerfile"</code>
      </td>
      <td>🧱 ci: Modificaçao no Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":recycle: refactor: Passando para arrow functions"</code>
      </td>
      <td>♻️ refactor: Passando para arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":zap: perf: Melhoria no tempo de resposta"</code>
      </td>
      <td>⚡ perf: Melhoria no tempo de resposta</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":boom: fix: Revertendo mudanças ineficientes"</code>
      </td>
      <td>💥 fix: Revertendo mudanças ineficientes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":lipstick: feat: Estilizaçao CSS do formulario"</code>
      </td>
      <td>💄 feat: Estilizaçao CSS do formulario</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":test_tube: test: Criando novo teste"</code>
      </td>
      <td>🧪 test: Criando novo teste</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bulb: docs: Comentários sobre a função LoremIpsum( )"</code>
      </td>
      <td>💡 docs: Comentários sobre a função LoremIpsum( )</td>
    </tr>
  </tbody>
</table>

<div align="center">
  <br/>
    <div>
      <h1>Open Source</h1>
      <sub>Copyright © 2023 - <a href="https://github.com/joaoricardoM">João Ricardo</sub></a>
    </div>
    <br/>
    💖
</div>
