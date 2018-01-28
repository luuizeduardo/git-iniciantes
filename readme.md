# Git course

Comandos do git:

- git config --list -> lista todas as opções de configuração do git pela linha de comando.
- git init -> inicializa um repositório do git (é utilizado quando criamos um diretório e queremos que ele se torne um repositório git).
- git add "filename" -> adiciona o arquivo para ser comitado.
- git add -m "" "filename" -> adiciona o arquivo com possibilidade de colocar uma mensagem no commit.
- git commit "filename" -> comita as alterações do arquivo.
- git commit -am -> adiciona todos os arquivos modificados e permite colocar a mensagem no commit.
- git log -> mostra o log de ações do repositório.
- git log --decorate -> trás mais informações no log, como branches, merges, etc.
- git shortlog -> mostra um log resumido com autor do commit, com quantas interações e respectivas mensagens.
- git log --graph -> mostra um log com os acontecimentos entre as branches, merges, etc.
- git show "HASH_DO_COMMIT" -> mostra o que aconteceu com os arquivos daquele commit em específico, o que foi adicionado, o que foi modificado, etc. 
- git diff -> mostra as diferenças nos arquivos que foram mexidos. (Usar antes do commit é interessante para ver as mudanças).
- git diff --name-only -> mostra apenas os nomes dos arquivos que foram modificados.
- git reset HEAD "filename" ou git reset HEAD -> tira da fila dos arquivos adicionados (arquivos que foram adicionados no stage pelo "git add).
- git reset --soft -> volta as alterações feitas em um commit feito de forma incorreta e deixa os arquivos no status "modified". * Deve-se escolher um commit antes do feito incorrtamente.
- git reset --mixed -> volta as alterações feitas em um commit feito de forma incorreta e deixa os arquivos no status "not staged". * Deve-se escolher um commit antes do feito incorrtamente.
- git reset --hard -> volta as alterações feitas em um commit feito de forma incorreta e remove todas as alterações feitas nos arquivos. * Deve-se escolher um commit antes do feito incorrtamente.
- git checkout "filename" -> volta o arquivo como era antes das mudanças feitas (usar esse comando antes de comitar as alterações).