

# Sintaxe Básica de Gravação e Formatação no GitHub

## Introdução
O GitHub suporta Markdown, uma linguagem de marcação leve que facilita a formatação de texto. Abaixo estão os principais elementos de formatação que você pode usar nos seus arquivos README, issues, pull requests e outros documentos no GitHub.

## Títulos
Para criar um título, adicione de um a seis símbolos # antes do texto do título. O número de # que você usa determina o nível hierárquico e o tamanho da face de tipos do título.

```
# Título de Nível 1
## Título de Nível 2
### Título de Nível 3
```
# Título de Nível 1
## Título de Nível 2
### Título de Nível 3


## Estilo do Texto
Markdown permite aplicar estilos variados ao texto:

| Estilo  | Sintaxe  | Código  | Exemplo Renderizado |
|---------|----------|---------|---------------------|
| Negrito | `**` ou `__` | ```**texto em negrito**``` ou ```__texto em negrito__``` | **texto em negrito** ou __texto em negrito__ |
| Itálico | `*` ou `_`  | ```*texto em itálico*``` ou ```_texto em itálico_``` | *texto em itálico* ou _texto em itálico_ |
| Riscado | `~~`       | ```~~texto riscado~~``` | ~~texto riscado~~ |


## Texto de Referência
Você pode citar outros textos usando >.

```
> Esta é uma citação.
```
> Esta é uma citação.


## Citar Código

### Código Inline
Para chamar código ou um comando dentro de uma frase, use crases simples (`). O texto entre as crases não será formatado. Você também pode usar o atalho de teclado Comando+E (Mac) ou Ctrl+E (Windows/Linux) para inserir as crases.

Exemplo:
```
Use `git status` to list all new or modified files that haven't yet been committed.
```
Renderizado: Use git status to list all new or modified files that haven't yet been committed.

### Bloco de Código
Para formatar código ou texto em um bloco distinto, use três crases (```) antes e depois do código.

Exemplo:
```
git status
git add
git commit
```


## Links
Crie links usando `[texto do link](URL)`.

``` 
[Google](https://www.google.com)
``` 
[Google](https://www.google.com)


### Links de Seção
Você pode criar links para seções específicas do seu documento.

``` 
[Ir para Títulos](#titulos)
``` 
[Ir para Títulos](#titulos)

### Links Relativos
Links relativos são úteis para navegar dentro do repositório.

``` 
[Leia-me](./README.md)
``` 
[Leia-me](./README.md)


## Imagens
Adicione imagens usando ![texto alternativo](URL da imagem).

``` 
![Logo do GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```  
![Logo do GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)


## Listas
Crie listas ordenadas e não ordenadas com facilidade.

### Lista não ordenada:
``` 
- Item 1
- Item 2
``` 
- Item 1
- Item 2

### Lista ordenada:
``` 
1. Primeiro item
2. Segundo item
``` 
1. Primeiro item
2. Segundo item

### Listas de Tarefas
Listas de tarefas são úteis para acompanhar o progresso.

```
- [x] Tarefa concluída
- [ ] Tarefa pendente
```
- [x] Tarefa concluída
- [ ] Tarefa pendente


## Alertas
```
> [!NOTE]
> Informações úteis que os usuários devem saber, mesmo ao percorrer o conteúdo.

> [!TIP]
> Conselhos úteis para fazer as coisas melhor ou mais facilmente.

> [!IMPORTANT]
> Informações-chave que os usuários precisam saber para alcançar seu objetivo.

> [!WARNING]
> Informações urgentes que precisam da atenção imediata do usuário para evitar problemas.

> [!CAUTION]
> Avisos sobre riscos ou resultados negativos de certas ações
```
> [!NOTE]
> Informações úteis que os usuários devem saber, mesmo ao percorrer o conteúdo.

> [!TIP]
> Conselhos úteis para fazer as coisas melhor ou mais facilmente.

> [!IMPORTANT]
> Informações-chave que os usuários precisam saber para alcançar seu objetivo.

> [!WARNING]
> Informações urgentes que precisam da atenção imediata do usuário para evitar problemas.

> [!CAUTION]
> Avisos sobre riscos ou resultados negativos de certas ações


# Trabalhar com Formatação Avançada

## Criar uma Tabela
Você pode criar tabelas para organizar dados de forma estruturada.

```
| Coluna 1 | Coluna 2 |
|----------|----------|
| Dado 1   | Dado 2   |

```
| Coluna 1 | Coluna 2 |
|----------|----------|
| Dado 1   | Dado 2   |



## Formatar Conteúdo Dentro da Tabela
É possível adicionar formatação dentro das células da tabela.

```
| **Coluna 1** | _Coluna 2_ |
|--------------|------------|
| **Negrito**  | _Itálico_  |
```
| **Coluna 1** | _Coluna 2_ |
|--------------|------------|
| **Negrito**  | _Itálico_  |



## Usar o Git
Fazer Push de Commits para um Repositório Remoto
Para enviar suas mudanças para um repositório remoto, utilize:

```
git push origin main
```


## Obter Alterações de um Repositório Remoto
Para atualizar seu repositório local com as mudanças do remoto, utilize:

```
git pull origin main
```

## Dividir uma Subpasta em um Novo Repositório
Você pode transformar uma subpasta de um repositório em um novo repositório independente.

```
git subtree split -P pasta/subpasta -b nova-branch
git push origin nova-branch:main
```


## Sobre Merges de Subárvore do Git
Merges de subárvore permitem combinar históricos de dois repositórios diferentes.

```
git subtree add --prefix=pasta-remota/ https://github.com/usuario/repositorio-remoto.git main
```


## Sobre a Troca de Base do Git
Rebase é uma técnica para aplicar commits de uma branch sobre outra, facilitando um histórico mais linear.

```
git rebase main
```

# Conclusão
Com esse guia, você está pronto para criar e formatar documentos no GitHub de maneira eficiente e usar Git para gerenciar seu código.

Fontes de Produção: 
Ilustrações de capa: gerada pela lexica.art
Conteúdo gerado por: ChatGPT e revisões humanas

### Links Utilizados 📌
| Site | Link |
|------|------|
|Lexica |[Link](https://lexica.art)
|Medium |[Link](https://medium.com)
|ChatGPT |[Link](https://chatgpt.com)
