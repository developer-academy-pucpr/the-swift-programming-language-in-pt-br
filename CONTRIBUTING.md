# Como contribuir

Você pode participar de diversas maneiras: 
* Traduzindo novas páginas;
* Revisando páginas e termos já traduzidos;
* Sugerindo alterações no projeto;
* Respondendo issues com gentileza e ajudando outros participantes com as dúvidas;

## Por onde começar? 

1. [Configure seu repositório](#configure-seu-repositório)
2. Entenda o [Fluxo de Contribuição](#fluxo-de-contribuição)
3. Leia nossas [Recomendações de Estilo](#recomendações-de-estilo)
4. [Escolha o tópico](https://github.com/developer-academy-pucpr/the-swift-programming-language-in-pt-br/issues/1) que irá traduzir e comente em sua issue. 

## Configure seu repositório

>❗️Como esse projeto envolve apenas tradução, é possível trabalhar diretamente do navegador. Caso seja seu caso, faça o fork e não se esqueça de criar branches e mensagens de commit claras.

#### 1. Faça o [fork e o clone do repositório](http://gabsferreira.com/forkando-e-clonando-um-repositorio-no-github/)


#### 2. Faça a referência ao repositório oficial após o fork:

```
git remote add upstream git@github.com:developer-academy-pucpr/the-swift-programming-language-in-pt-br.git
```

## Fluxo de Contribuição

#### 1. Crie uma nova branch para suas alterações. Por exemplo: 

```
git checkout -b traducaoX
```

#### 2. Traduza ou faça alterações. 

Agora é a hora de brilhar! Lembrando sempre de aplicar nossas recomendações de estilo. 


#### 3. Após finalizar, faça o commit. 


```
git add . 
git commit -m “acrescenta tradução dos tópicos X e Y”
git push origin traducaoX
``` 
>❗️**Escreva uma mensagem clara do que foi feito.**


#### 4. Envie o Pull Request! 🎉

Preencha as informações e… UHULLLL! Parabéns!

Agora é aguardar a revisão e o merge. Em alguns casos, podemos pedir alguma alteração. Enquanto isso, você pode escolher outra parte do livro e continuar ajudando! 

#### 5. Após o Pull Request... 
Atualize seu repositorio com o repositório oficial: 
```
git fetch upstream
git rebase upstream/master
git push -f origin master
``` 

## Recomendações de Estilo 
- **Não traduza termos técnicos e blocos de código**
- Caso tenha qualquer tipo de dúvida, abra uma *Issue* com a label **dúvida**  que faremos o possível para te ajudar.
- Casos de palavras em inglês ou outras linguagens, em que não há sentido em fazer sua tradução, utilize o formato itálico. exemplo: *Closures*
- Notas de rodapé devem ser criadas como quote do markdown, usando o sinal de > na frente;
> nota de rodapé
- Blocos de código:
    - Utilize um apóstrofe (\` ... código... \`) para indicar um pedaço de código no meio de um texto (`var hello = "hello"`).
    - Utilize três apóstrofe com o nome da linguagem de programação depois (\`\`\`Swift  {novalinha} ...código... \`\`\`), para indicar um bloco de código:
```Swift
            var hello = "hello"
```
#### Organização de PRs e Issues
- Para organizar e facilitar a continuação da tradução em casos de tradução parcial, pedimos que tradução seja feita por subcapítulos. Antes de terminar a tradução parcial e dar o PR, escreva o titulo do próximo subcapítulo no arquivo.
- Não é necessário traduzir todo um capitulo do livro para fazer o pull request, caso pare na metade de um capitulo, ao fazer o *Pull Request* adicione a label de tradução parcial e coloque no titulo de seu PR qual capitulo e subcapítulo foi traduzido,por exemplo `operadoresBasicos.md / Operadores Aritméticos`. 
    -   Em caso de mais de um subcapítulo traduzido, escreva o nome do último e especifique quais foram traduzidos no corpo do PR.
- Especifique as mudanças, revisaremos o PR e caso haja alguma alteração a ser feita (erro de tradução em um termo por exemplo), solicitaremos a mudança para o usuário, após a adequação daremos o *merge* e atualizaremos o status geral do projeto.
- Antes de começar a tradução verifique na *Issue* de status geral do projeto se a tradução desse capítulo/subcapítulo já não está em andamento.
- Para evitar que traduções sejam abandonadas após abertura de uma issue: caso a tradução de um capítulo fique mais de uma semana em andamento e nenhuma atualização de seu status seja comunicada (dando PR ou comentando nas *Issues*), consideraremos que a tradução deste capítulo/subcapítulo não está mais em andamento e seu status voltará para "aguardando".

### 

## Leituras de Apoio  
Caso você esteja precisando de uma ajudinha, dê uma olhada nesses textos: 

- [Git e GitHub: por onde começar?](https://medium.com/reprogramabr/git-e-github-por-onde-começar-ca88a783c223)
- [Entendendo Git: Branches](https://medium.com/@Juliobguedes/entendendo-git-branches-parte-2-3778f4258843)
- [Como Criar um Pull Request no GitHub](https://www.digitalocean.com/community/tutorials/como-criar-um-pull-request-no-github-pt) 
- [CheatSheet para Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#headers)


