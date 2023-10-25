Caso o `$` esteja presente nas informações de console do terminal, significa que o usuário logado não tem privilégios de administrador.

O comando `pwd` mostra o diretório atual que o terminal está, começando da pasta raiz do linux (`/`).

O comando `ls` mostra os arquivos locais que o terminal está executando.
* Parâmetro `-a`: Mostra também os arquivos ocultos no diretório atual (que começam com `.`).
* Parâmetro `-l`: Detalha os arquivos e os mostra no seguinte formato:

    | Permissões | ? | ? | ? | Bytes | Última Modificação | Nome do arquivo |
    | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
    | dxwxr-xr-x | 3 | ubuntu | ubuntu | 4096 | MONTH DAY TIME | . |
    | dxwxr-xr-x | 3 | ubuntu | ubuntu | 4096 | MONTH DAY TIME | .. |
    | dxwxr-xr-x | 1 | ubuntu | ubuntu | 0 | MONTH DAY TIME | example |
> Um comando equivalente a `ls -al` é o `ll`, onde a saída de execução no console é a mesma mostrada acima

O parâmetro `--help` mostra uma página de ajuda no próprio console do **Linux**, descrevendo o uso do comando e informando os parâmetros que podem ser utilizados.

Outro comando utilizado no mesmo sentido é o `man COMMAND_NAME`, EX.:`man ls`, o terminal abre uma página do manual de uso mais detalhado do comando passado como argumento no `COMMAND_NAME`.
> Para sair da página de ajuda, basta apertar a tecla `q` de *quit* para sair do manual.