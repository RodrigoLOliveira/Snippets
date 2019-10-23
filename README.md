# Snippets
 
Repositório para compartilhamento de alguns spinnets que podem facilitar o processo de desenvolvimento de projetos ASP.NET CORE.

## O que é um Snippets?
Snippets de código são pequenos blocos de código reutilizável que podem ser inseridos em um arquivo de código usando um comando do menu do clique com o botão direito (menu de contexto) ou uma combinação de teclas de atalho.

## Como importar um Snippets?

1. No seu Visual Studio (estou usando o 2019), usando o Gerenciador de Snippets de Código. Abra-o escolhendo **Ferramentas > Gerenciador de Snippets de Código.**
2. Clique no botão Importar.
3. Vá para o local em que você salvou o snippet de código, selecione-o e clique em Abrir.
4. A caixa de diálogo Importar Snippet de Código é aberta, solicitando que você escolha onde deseja adicionar o snippet entre as opções no painel à direita. Uma das opções deve ser Meus Snippets de Código. Selecione-a e clique em Concluir e, em seguida, em OK.

## Como criar meu proprio Snippets?

1. Crie um XML e adicione o seguinte código a ele:
```
<?xml version="1.0" encoding="utf-8"?>
<CodeSnippets xmlns="http://schemas.microsoft.com/VisualStudio/2005/CodeSnippet">
    <CodeSnippet Format="1.0.0">
        <Header>
            <Title></Title>
        </Header>
        <Snippet>
            <Code Language="">
                <![CDATA[]]>
            </Code>
        </Snippet>
    </CodeSnippet>
</CodeSnippets>
```
2. Dentro de cdata ( ![CDATA[**AQUI**]] ) você irá inserir o código que deseja chamar posteriormente.

3. Então salve o arquivo com o nome MEUSnippets.snippet
4. Agora só importar como explicado no proceso anterior.
