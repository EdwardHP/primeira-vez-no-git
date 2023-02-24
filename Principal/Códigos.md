# Como Funciona

Qualquer coisa referente ao git se usa **git** no código.

Para iniciar precisa usar um código **git init** para criar uma pasta .git no local.

Depois referenciar seu gmail e nome usando os códigos **git config --global user.email "o seu email"** e **git config --global user.name "seu nome"**.

### Sistema de Save

Para salvar os arquivos criados ou modificados é necessário usar o código **git add *** e depois **git commit -m "titulo da sua escolha"**.

### Enviar para o GitHub

Quando você quiser passar seus arquivos locais para o repositório remoto basta usar alguns comandos (certifique de ter salvo suas alterações desejadas), primeiro é preciso falar em qual https os seus arquivos vão ser transferidos no caso em qual repositório do GitHub, depois de criar o seu repositório é preciso pegar o https dele para que você possa passar seus arquivos para lá. Os comandos são **git remote add origin o seu https** depois precisa empurrar esses seus arquivos para o local desejado nesse caso use **git push origin master**.
