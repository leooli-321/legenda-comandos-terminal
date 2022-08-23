# legenda-comandos-terminal
Aqui está uma breve legenda para os comandos do terminal. Lembre de usar o comando "grep" para encontrar com mais fácilidade ;)

.
.
#### Legenda dos comandos para o terminal ####
.
.

- `pwd` (**p**rint **w**orking **d**irectory): exibe qual é o seu diretório corrente
.

- `ls` (**l**i**s**t files): lista o que está no seu diretório corrente.
.

- `cd <diretório de destino>` (**c**hange **d**irectory): altera o diretório corrente para o diretório de destino.
.

- `cd ..`: volta para o diretório anterior. Ex: se você está em `/diretorio-pai/diretorio-filho` e executa `cd ..`, o seu diretório corrente passa a ser `/diretorio-pai`.
.

- `cd ../../../`: volta três diretórios. Você pode fazer `../` quantas vezes quiser. O número de vezes determinará quantos diretórios você vai voltar pra trás.
.

- `mkdir <nomedodiretório>` (**m**a**k**e **dir**ectory): cria um novo diretório no diretório corrente.
.

- `touch [nome do arquivo].extensão`: cria um novo arquivo 
(.md extensão de texto).
.

- `grep' - Usado para encontrar palavras dentro de um arquivo de texto.
Usado da seguinte maneira:


'grep' [palavra à ser encontrada] {nome do arquivo à ser buscado} 


Para procurar TODOS os arquivos no diretório atual, use um asterísco (*) ao invés do nome do arquivo no final do comando 'grep'

'grep' [palavra para a busca] {*}


o comando 'grep' é exigente perante à formatação de letras maiúsculas e minúsculas (tenha isso em mente), então o operador [-i] é usado para ignorar a sensibilidade de caixa. Exemplo:

'grep' (-i) [palavra a ser buscada] {nome do arquivo à ser buscado}


Para fazer uma busca em subdiretórios, você pode incluir o operador [-r] após o comando 'grep'. Exemplo:

'grep' (-r) [palavra desejada] {nome da busca à ser feita}


Também é possível fazer uma busca "invertida" com o operador "-v", no caso de você desejar excluir um caráctere de sua busca. Exemplo:

'grep' (-v) [caractere à ser IGNORADO] {nome da busca à ser feita}

Mais sobre o comando 'grep': https://phoenixnap.com/kb/grep-command-linux-unix-examples
.

- `rm` (remover): remove/exclui pastas e arquivos (use com cautela).
.

- `cp` (copy/copiar): copia/duplica pastas e arquivos.
.

- `mv` (mover): usado para mover/arrastar pastas e arquivos.
.

- `head` (cabeçalho): este comando exibe as primeiras 10 linhas da composição de um arquivo.

você pode usar o operador [-n] para específicar a quantidade de linhas que deseja ser exibidas. Exemplo:

"'head' (-n) 10" irá exibir 10 linhas

