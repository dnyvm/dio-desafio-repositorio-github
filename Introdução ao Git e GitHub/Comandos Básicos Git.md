# Comandos Básicos Git :computer:



**dir (windows) ls (linux)** = _comando para listar diretórios_

**cd (change directory)** = _possibilita a navegação entre as pastas, subir/descer nível nos diretórios, ir para uma pasta específica dentro do sistema operacional_

**cd /** _(a barra para passar um caminho específico)_

**cls (clear screen = windows) e clear ou ctrl + L (linux e mac)** = _comando para limpar a tela no terminal_

**cd W+TAB** = _ele já reconhece a pasta windows e auto completa a palavra, ajuda a livrar de criar nomes grande de pastas, nomes complexos de arquivos e criar algum erro humano_

**mkdir (make directory) + nome da pasta (windows, linux)** = _para criar uma pasta/diretório_

**echo** = _simplesmente printa de volta no terminal um texto que você passa_

**echo texto > texto.txt** = _o símbolo > (maior que) é um redirecionador de fluxo, então ele vai pegar o output (a saída da função echo) e vai jogar um arquivo_

**del + nome do diretório (windows)** = _apaga arquivos (que estão dentro do diretório/pasta)_

**rmdir + nome do diretório + /S + /Q (windows)** = _deleta a pasta/diretório e tudo que tem dentro dela_

**rm –rf + nome do diretório (linux)** = _deleta a pasta/diretório e tudo que tem dentro dela_

**cat + nome do arquivo** = _visualizar o conteúdo dessa chave_

**pwd** = _mostra o caminho da pasta completo_ 

**git clone + caminho ssh** = _clonar o repositório remoto para o seu repositório local_

**git init** = _iniciar o repositório do git_

**git add .** = _mover arquivos, dar início ao versionamento e conhecer os primeiros comandos_

**git commit** = _criar o commit_

**ls –a + enter** = _flag   -a   no comando ls para ver arquivos ocultos_

**-m** = _é uma flag do git commit para escrever uma mensagem_

**git commit –m "msg"** = _move toda essa área de staging para o nosso repositório local -máquina_

**git status** = _ajuda a monitorar os status dos arquivos, vai dizer se o arquivo está untracked, modified, staged, unmodified_

**mv + arquivo + diretório** = _mover o arquivo para dentro desse diretório_

**git config --list** = _para listar todas as configurações que o git conseguir encontrar naquele momento_

**git config --global --unset user.name** = _para alterar o username_ 

**git config --global --unset user.email** = _para alterar o email_ 

_Depois disso_

**git config --global user.name "novo username"**

**git config --global user.email "novo email"**

**q** = _para sair do git config_

**git pull origin master/main** = _para puxar o repositório do github_

**git push origin master/main** = _para empurrar o repositório para o github_



_A seta pra cima vai fazer você navegar por todos os comandos já usados no terminal_ 
