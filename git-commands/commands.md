**git init**: Inicia um novo repositório Git no diretório atual.
**git clone [URL]**: Clona um repositório existente do Git para sua máquina local.
**git add . [arquivo]**: Adiciona alterações de arquivos ao índice (staging area) para serem incluídas no próximo commit.
**git commit -m "[mensagem]"**: Registra as alterações dos arquivos na área de preparação com uma mensagem explicativa das mudanças feitas.
**git status**: Exibe o estado atual do repositório, incluindo arquivos modificados, adicionados e não rastreados.
**git push [remote] [branch]**: Envia as alterações locais para o repositório remoto.
**git pull**: Atualiza o repositório local com as últimas alterações do repositório remoto.
**git branch**: Lista todas as branches locais e destaca a branch atual, mostrando o fluxo de trabalho do projeto.
**git branch [nome]**: Cria uma nova ramificação (branch) para desenvolver novas funcionalidades isoladamente.
**git checkout [nome_branch]**: Muda para a ramificação especificada.
**git merge [nome_branch]**: Combina as alterações de uma ramificação com outra (normalmente mesclando uma branch de desenvolvimento com a principal).
**git log**: Exibe o histórico de commits do repositório.
**git remote -v**: Lista os repositórios remotos configurados, exibindo suas URLs e nomes.
**git fetch**: Recupera as últimas alterações do repositório remoto, atualizando o seu repositório local, mas não faz merge automaticamente, deixando você revisar as alterações antes de integrá-las ao seu código.
**git reset [arquivo]**: Desfaz as alterações no arquivo especificado, removendo-o do índice (staging area), mas mantendo as alterações nos arquivos locais.
**git rm [arquivo]**: Remove um arquivo do repositório e o inclui no próximo commit, sinalizando que você deseja excluí-lo permanentemente.
**git diff**: Mostra as diferenças entre as alterações feitas nos arquivos que ainda não foram adicionadas ao índice, permitindo revisar as alterações antes de confirmá-las.
**git remote add [nome-remoto] [URL]**: Adiciona um repositório remoto com um nome específico, permitindo que você se conecte e compartilhe seu repositório local com outros repositórios hospedados na nuvem.
**git push origin main**: Envia as alterações locais para o repositório remoto chamado "origin" e para a branch principal main, atualizando o repositório online com suas contribuições.
