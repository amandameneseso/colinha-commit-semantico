<h1>Colinha - Commit Semântico</h1>

<p>Essa colinha foi baseada em dois documentos:</p>

<a href="https://karma-runner.github.io/6.3/dev/git-commit-msg.html">Karma Runner</a> <br>
<a href="https://www.conventionalcommits.org/en/v1.0.0/">Conventional Commits</a>

<h1>Formato:</h1>

<p>Os commits devem ser escrito com o seguinte formato, onde o type é obrigatório e pode ser consultado no próximo tópico e a descrição descreve a ação daquele commit mais detalhadamente:</p>

<code>&lt;type&gt;: &lt;description&gt;</code>

<h1>Type</h1>

<p>O type pode ser um desses tipos:</p>

<table>
    <thead>
        <tr>
            <th>Prefixo</th>
            <th>Descrição</th>
            <th>Significado</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>feat</strong></td>
            <td>Features</td>
            <td>Uma nova funcionalidade</td>
        </tr>
        <tr>
            <td><strong>fix</strong></td>
            <td>Correções de Erros</td>
            <td>Uma correção de bug</td>
        </tr>
        <tr>
            <td><strong>docs</strong></td>
            <td>Documentação</td>
            <td>Apenas mudanças na documentação</td>
        </tr>
        <tr>
            <td><strong>style</strong></td>
            <td>Estilos</td>
            <td>Mudanças em relação à estilização</td>
        </tr>
        <tr>
            <td><strong>refactor</strong></td>
            <td>Refatoração de Código</td>
            <td>Uma alteração de código que não corrige um bug nem adiciona uma funcionalidade</td>
        </tr>
        <tr>
            <td><strong>perf</strong></td>
            <td>Melhorias de Performance</td>
            <td>Uma alteração de código que melhora o desempenho</td>
        </tr>
        <tr>
            <td><strong>test</strong></td>
            <td>Testes</td>
            <td>Adição de testes em falta ou correção de testes existentes</td>
        </tr>
        <tr>
            <td><strong>build</strong></td>
            <td>Builds</td>
            <td>Mudanças que afetam o sistema de build ou dependências externas (exemplos de escopos: gulp, broccoli, npm)</td>
        </tr>
        <tr>
            <td><strong>ci</strong></td>
            <td>Integrações Contínuas</td>
            <td>Alterações em arquivos e scripts de configuração de CI (exemplos de escopos: Travis, Circle, BrowserStack, SauceLabs)</td>
        </tr>
        <tr>
            <td><strong>chore</strong></td>
            <td>Tarefas</td>
            <td>Outras mudanças que não modificam arquivos de código-fonte ou de teste</td>
        </tr>
        <tr>
            <td><strong>revert</strong></td>
            <td>Reverter</td>
            <td>Reverte um commit anterior</td>
        </tr>
    </tbody>
</table>
