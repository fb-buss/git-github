**git init**: Inicia um novo repositório Git no diretório atual.<br>
**git clone [URL]**: Clona um repositório existente do Git para sua máquina local.<br>
**git add . [arquivo]**: Adiciona alterações de arquivos ao índice (staging area) para serem incluídas no próximo commit.<br>
**git commit -m "[mensagem]"**: Registra as alterações dos arquivos na área de preparação com uma mensagem explicativa das mudanças feitas.<br>
**git status**: Exibe o estado atual do repositório, incluindo arquivos modificados, adicionados e não rastreados.<br>
**git push [remote] [branch]**: Envia as alterações locais para o repositório remoto.<br>
**git pull**: Atualiza o repositório local com as últimas alterações do repositório remoto.<br>
**git branch**: Lista todas as branches locais e destaca a branch atual, mostrando o fluxo de trabalho do projeto.<br>
**git branch [nome]**: Cria uma nova ramificação (branch) para desenvolver novas funcionalidades isoladamente.<br>
**git checkout [nome_branch]**: Muda para a ramificação especificada.<br>
**git merge [nome_branch]**: Combina as alterações de uma ramificação com outra (normalmente mesclando uma branch de desenvolvimento com a principal).<br>
**git log**: Exibe o histórico de commits do repositório.<br>
**git remote -v**: Lista os repositórios remotos configurados, exibindo suas URLs e nomes.<br>
**git fetch**: Recupera as últimas alterações do repositório remoto, atualizando o seu repositório local, mas não faz merge automaticamente, deixando você revisar as alterações antes de integrá-las ao seu código.<br>
**git reset [arquivo]**: Desfaz as alterações no arquivo especificado, removendo-o do índice (staging area), mas mantendo as alterações nos arquivos locais.<br>
**git rm [arquivo]**: Remove um arquivo do repositório e o inclui no próximo commit, sinalizando que você deseja excluí-lo permanentemente.<br>
**git diff**: Mostra as diferenças entre as alterações feitas nos arquivos que ainda não foram adicionadas ao índice, permitindo revisar as alterações antes de confirmá-las.<br>
**git remote add [nome-remoto] [URL]**: Adiciona um repositório remoto com um nome específico, permitindo que você se conecte e compartilhe seu repositório local com outros repositórios hospedados na nuvem.<br>
**git push origin main**: Envia as alterações locais para o repositório remoto chamado "origin" e para a branch principal main, atualizando o repositório online com suas contribuições.<br>
