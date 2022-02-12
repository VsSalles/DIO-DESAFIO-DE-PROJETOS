**git init** Inicia o git e cria um repositório dentro do diretório atual

**git add *** Inicia o Versionamento/ move o arquivo direto para staged (pronto para ser “comitado”

**git commit -m** “nome do commit” comando para criar um commit

**git config --list** Lista toda a configuração global

**git config --global user.name** VsSalles altera namenick da conf global

**Tracked** ou **Untracked**(arquivos que o git ainda não tem ciencia
dentro de tracked ou seja arquivos rastreado pelo git pode se subdividir em três partes **unmodifield**, **Modifield** e  **Staged**

**unmodifield** - Quando o arquivo Não foi modificado
 **Modifield** -  Quando o arquivo foi modificado ele passa de **unmodifield** para **Modifield**, qualquer modificação seja uma vírgula o arquivo passa para **modifield** pois o git compara o sha1 dos dois arquivos e vê que um ta diferente assim entende-se que foi modificado (toda vez que é salvo o arquivo gera um novo sha1…)

conceito Chave **Staged**

**Staged** - onde fica os arquivos que estão se preparando para fazer parte de outro tipo de agrupamento
no caso fazer parte do commit onde ocorre a junção das informações e se torna um commit, depois os arquivos volta para untracked e esse ciclo sempre se repete

**git status** mostra o status do arquivo(modificado,nãomodificado,staged..)
