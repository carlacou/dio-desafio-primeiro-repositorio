### Desafio de Projeto Git/Github

Repositório criado para Desafio de Projeto

# GIT
### Estados
Modificado (modified);
Preparado (staged/index)
Consolidado (comitted);

### Ajuda
**Geral**

git help

### Principais Comandos

**git init** -> inicializar um repositório

**git status** -> mostra o estado do nosso repositório, os arquivos alterados ou não.

**git add** -> arquivos modificados devem ser adicionadospelo comando git add + nome do arquivo, ser houver vários apenas o comando (git add .).

**git commit** -> salvar as alterações. Após o comando inserimos -m para digitarmosuma mensagem sobre a mudança. Mensagem entre " " (aspas).

**git remote** -> criação do repositório remoto.

**git remote -v** -> local do endereço do repositório remoto.

**git push -u origin main** ->  primeiro envio para repositório remoto.

**git branch -M main** -> alterando repositório Master para o Main.

**git log** -> histórico de atualizações.

**git clone** -> O Git clone é um comando para baixar o código fonte existente de um repositório remoto (como o Github, por exemplo).

**git branch** -> Com branches, vários desenvolvedores podem trabalhar em paralelo no mesmo projeto simultaneamente. Pode-se usar o comando git branch para criar, listar e excluir branches.

**git Ckeckout** -> Este é um dos comandos Git mais usados. Para trabalhar em uma branch, primeiro você precisa mudar para ela. Usamos o git checkout principalmente para alternar de um branch para outro. Também podemos usá-lo para verificar arquivos e commits


**git pull** -> O comando git pull é usado para obter atualizações do repositório remoto. Este comando é uma combinação de git fetch e git merge, o que significa que, quando usamos o git pull, ele recebe as atualizações do repositório remoto git fetch e aplica imediatamente as alterações mais recentes no seu local git merge.

**git merge** -> Quando você conclui o desenvolvimento em sua branch e tudo funciona bem, a etapa final é mesclar as branches, isso é feito com o comando git merge.

**git revert** -> Existem várias maneiras de desfazer nossas alterações local ou remotamente (depende do que precisamos), mas devemos usar esses comandos com cuidado para evitar problemas.
 Uma maneira segura de desfazer os commits é usando git revert.

**git log -- oneline** -> visualiza todos os commits, sendo cada um ocupando uma única linha(forma resumida). 

**git diff** -> visualiza as alterações antes de realizar o git add.

**git log -p** -> mostra as alterações feitas, a versão anterior em vermelho e a versão modificada logo abaixo em verde.

**git config --local user.name "nome autor"** -> identificação e configuração do autor do commit.

**git config --local user.email "email"** -> identificação e configuração do email do autor do commit.













