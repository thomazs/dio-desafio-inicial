# Desafio Inicial da DIO

![Text/Format :: Markdown](https://img.shields.io/badge/Format-Markdown-yellowgreen) ![Study:: DIO](https://img.shields.io/badge/StudyOn-DIO-blue)

Este é o repositório criado para prática dos conhecimentos repassados sobre GIT / GITHUB. Foram aplicados recursos / conhecimentos apresentados durante o curso, tais como:

- Iniciar um repositório diretamente no GITHUB
- *Clonar* o repositório em um ambiente local
- Atualizar conteúdo do repositório
- Adicionar o conteúdo para a área de stage
- Gravar as atualizações (*commit*)
- Enviar novas informações ao GITHUB (*push*)


## Primeiros Passos

Criação do repositório no GITHUB, de forma que o repositório seja público.

Logo após, *clonar* o repositório em ambiente local:
> git clone https://github.com/thomazs/dio-desafio-inicial.git

Logo após realizar a alteração do arquivo README.md adicionando os primeiros passos, salvando o arquivo, e na sequencia visualizamos o arquivo editado:
> git status

> > On branch main
> 
> > Your branch is up to date with 'origin/main'.
> > 
> > Changes not staged for commit:
> 
> >  (use "git add <file>..." to update what will be committed)
> 
> >  (use "git restore <file>..." to discard changes in working directory) 
> 
> >        modified:   README.md 
> > 
> > no changes added to commit (use "git add" and/or "git commit -a")
> > 


Após a alteração, e vendo que o arquivo havia sido editado, enviamos o mesmo a área de stage:
> git add . 


Gravamos as atualizações:
> git commit -m "Commit inicial"


E enviamos o conteúdo novamente ao GITHUB:
> git push origin main


## Atualizando Informações

Realizamos pequenos ajustes, modificando novamente o arquivo README.md, aplicando a atualização (enviando para a área de stage) e enviamos novamente estas alterações:
> git add .

> git commit -m "Commit de correcoes"

> git push 

Esse processo foi realizado algumas vezes para treinar os passos apontados. 


## Adição de Badges e Extras

Foram adicionados alguns badges (imagens que identificam características ou recursos dos repositórios) ao repositório corrente, além de um arquivo indicando [Extras](https://github.com/thomazs/dio-desafio-inicial/blob/main/EXTRAS.md), apenas para complementar (ter outros arquivos) no repositório. 

