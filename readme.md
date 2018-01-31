# Git course

Este é um repositório com comandos básicos do Git e para que servem.

- __git config__ --list -> lista todas as opções de configuração do git pela linha de comando.
- __git init__ -> inicializa um repositório do git (é utilizado quando criamos um diretório e queremos que ele se torne um repositório git).
- __git add__ *filename* -> adiciona o arquivo para ser comitado.
- __git add__ -m "" *filename* -> adiciona o arquivo com possibilidade de colocar uma mensagem no commit.
- __git commit__ *filename* -> comita as alterações do arquivo.
- __git commit__ -am -> adiciona todos os arquivos modificados e permite colocar a mensagem no commit.
- __git log__ -> mostra o log de ações do repositório.
- __git log__ --decorate -> trás mais informações no log, como branches, merges, etc.
- __git shortlog__ -> mostra um log resumido com autor do commit, com quantas interações e respectivas mensagens.
- __git log__ --graph -> mostra um log com os acontecimentos entre as branches, merges, etc.
- __git show__ "HASH_DO_COMMIT" -> mostra o que aconteceu com os arquivos daquele commit em específico, o que foi adicionado, o que foi modificado, etc. 
- __git diff__ -> mostra as diferenças nos arquivos que foram mexidos. (Usar antes do commit é interessante para ver as mudanças).
- __git diff__ --name-only -> mostra apenas os nomes dos arquivos que foram modificados.
- __git reset__ HEAD *filename* ou git reset HEAD -> tira da fila dos arquivos adicionados (arquivos que foram adicionados no stage pelo __git add__).
- __git reset --soft__ -> volta as alterações feitas em um commit feito de forma incorreta e deixa os arquivos no status "modified". * Deve-se escolher um commit antes do feito incorrtamente.
- __git reset --mixed__ -> volta as alterações feitas em um commit feito de forma incorreta e deixa os arquivos no status "not staged". * Deve-se escolher um commit antes do feito incorrtamente.
- __git reset --hard__ -> volta as alterações feitas em um commit feito de forma incorreta e remove todas as alterações feitas nos arquivos. * Deve-se escolher um commit antes do feito incorrtamente.
- __git checkout__ *filename* -> volta o arquivo como era antes das mudanças feitas (usar esse comando antes de comitar as alterações).
- __git remote__ -> mostra o repositório remoto que o git está ligado.
- __git remote__ -v -> mostra o endereço do git no repositório remoto.
- __git push__ -> envia as modificações para o servidor
- __git push__ -u origin master -> indica para qual branch o push deve ir.