#  Primeiros conceitos do Git
Repositório criado para o projeto da Digital Inovationn One sobre os aprendizados do Git/Github.

Confesso que quando terminei o curso explicando como tudo funciona, se me perguntassem essa seria exatamente a minha reação: WTFF??

![what-whoa](https://user-images.githubusercontent.com/97559065/155356541-89a12d47-6e29-4d40-a1e6-9ed44ece4525.gif)

- Masss muita calma nessa hora, pesquisar os conceitos e fazer anotações no caderno me ajudam muito a entender para que as coisas funcionam e fixar os conhecimentos na cabeça, então vou compartilhar com você os primeiros conceitos do GIT.

## _O GIT ele funciona a partir de alguns objetos internos, sendo eles:_

# BLOB
BLOB e uma abreviação de Binary Large Object, quando adicionamos um GIT com arquivo _file.txt o GIT 
cria um objeto BLOB contendo o conteudo do arquivo, BLOB são, portanto o tipo de objeto GIT para armazenar arquivos. (Guarda apenas o SHA1)

# TREE
O tipo de objeto é tree, e em vez de ter os valores simples, como o blob, a tree é um conjunto de valores de índices apontando para os objetos,
juntamente com um modo (tipicamente 100644 para arquivos e 100755 para diretórios).

# COMMIT 
São criados com o comando git commit para capturar o estado de um projeto naquele momento. O commit dos instantâneos do Git sempre é feito no repositório local, muito diferente do SVN, no qual se faz o commit de uma cópia do trabalho no repositório central.

# GIT BASH
É um aplicativo para ambiente do Microsoft Windows que oferece camada de emulaçao para experiência de linha de comando GIT.

# BASH
Acrônimo para "Bourne Again Shell"

# SHELL
São aplicativos terminais usados como interface em sistemas operacionais por meio de comandos gravados.

Muita coisa para assimilar, ne? mas conforme você vai utilizando cada função, os conceitos vão fazendo mais sentindo, nada que uma boa pratica não resolva. Até a prox!

![boy-kid](https://user-images.githubusercontent.com/97559065/155360313-c671bef5-774f-47cd-9038-aaa8217e0442.gif)



## LINKS ÚTEIS
[Git commit versus SVN commit](https://www.atlassian.com/br/git/tutorials/saving-changes/git-commit)
