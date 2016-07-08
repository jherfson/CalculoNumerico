# Cálculo Numérico: Um Livro Colaborativo

Este é um livro colaborativo sobre tópicos de métodos e análise numérica, normalmente estudados em cursos de graduação das áreas exatas e da terra na disciplina de cálculo numérico.

Caso queira colaborar, escreva para:
     (livro_colaborativo@googlegroups.com)

## Licença
Este trabalho está licenciado sob a Licença Creative Commons Atribuição-CompartilhaIgual 3.0 Não Adaptada. Para ver uma cópia desta licença, visite (http://creativecommons.org/licenses/by-sa/3.0/) ou envie uma carta para Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

##Sobre o código fonte
O código fonte está escrito em Latex e as referências bibliográficas em BibTex, testados em computador Linux com o pacote TexLive. O texto está em formatação iso-latin-1.

##Compilando
O código pode ser compilado usando os compiladores padrão latex, bibtex, etc.. Alternativamente, está disponível um Makefile na pasta principal, de forma que pode-se compilar o código com:

$ make

Isto gerará o livro em formato PDF (main.pdf). Também, caso prefira em formatodo DVI, pode-se compilar com:

$ make dvi

Para limpar os arquivos temporários gerados durante a compilação, digite:

$ make clean