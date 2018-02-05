Validador de arquivos de gravacao da Alura

O arquivo `PADRAO.md` foi movido para o arquivo `src/main/resources/padrao.txt`.

Para importar o projeto na sua IDE favorita basta importar como projeto maven. 

# Passos para atualizar a versão


1. Trocar a versão no [pom.xml](https://github.com/caelum/gnarus-validator/blob/master/pom.xml), por exemplo: vXY.Z
2. Rode na linha de comando, ou na sua IDE favorita:
    `mvn package`
3. Copiar o arquivo `target/revisor-didatica-jar-with-dependencies.jar` para `releases/revisor-didatica-beta.jar`
4. Depois de mergeado na master gerar um [release](https://help.github.com/articles/creating-releases/), com a mesma versão que você colocou no pom *isso é importante pois o app checa isso para ver se está atualizado*

# Utilizando o app

## Utilização no Windows

Para utilizar o app no Windows é necessário ter o git na pasta `C:\git`(caso precise baixar acesse https://git-scm.com/download/win e escolha versão portatil).
E também é necessário ter um pasta `C:\tmp`

