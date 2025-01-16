# Contador de palavras de textos
Programa para contagem de palavras repetidas em arquivos de texto utilizando JavaScript e node.js, através do curso da Alura "JavaScript com Node.js: criando sua primeira biblioteca"\
Projeto utiliza promessas, códigos assíncronos, bloco try/catch, funções de manejo de erros, bibliotecas nativas (como a fs) e importadas (como a Commander e Chalk)
##Como usar
Dentro do terminal do Node.js, executar o arquivo cli.js (dentro da pasta src) selecionando o caminho do arquivo de texto que deseja analisar utilizando o comando "-t", e o caminho que quer salvar o resultando utilizando comando "-d".\
###Exemplo:
node src/cli.js -t arquivos/texto-kanban.txt -d ./resultados/
####Resultado:
Arquivo txt com as palavras repetidas de cada parágrafo.
