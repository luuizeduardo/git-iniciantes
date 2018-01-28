# Git course

Comandos do git:

- git config --list -> lista todas as opções de configuração do git pela linha de comando
- git init -> inicializa um repositório do git (é utilizado quando criamos um diretório e queremos que ele se torne um repositório git).
- git add "filename" -> adiciona o arquivo para ser comitado.
- git add -m "" "filename" -> adiciona o arquivo com possibilidade de colocar uma mensagem no commit
- git commit "filename" -> comita as alterações do arquivo
- git log -> mostra o log de ações do repositório
- git log --decorate -> trás mais informações no log, como branches, merges, etc
- git shortlog -> mostra um log resumido com autor do commit, com quantas interações e respectivas mensagens
- git log --graph -> mostra um log com os acontecimentos entre as branches, merges, etc
- git show "HASH_DO_COMMIT" -> mostra o que aconteceu com os arquivos daquele commit em específico, o que foi adicionado, o que foi modificado, etc. 
- git diff -> mostra as diferenças nos arquivos que foram mexidos. (Usar antes do commit é interessante para ver as mudanças)
- git diff --name-only -> mostra apenas os nomes dos arquivos que foram modificados.
- git reset HEAD "filename" ou git reset HEAD -> tira da fila dos arquivos adicionados (arquivos que foram adicionados no stage pelo "git add).