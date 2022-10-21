# **Comando Basico CMD, Git/GitHub**



## CMD Window

- DIR = Listar arquivos e pasta Local
- CD "local" = Change Directory
- CD .. = Volta Diretório
- CLS = Limpa o Prompt de comando
- MKDIR "Nome do Arquivo" = Cria pasta com o nome colocado
- Echo "Texto" = Printa na tela o texto escrito
- Echo "Texto" > "nome do arquivo".txt = Cria arquivo em bloco de notas com texto dentro
- ">" = É um redirecionador de fluxo, ele pega o output da função e tranforma em um arquivo
- DEL = Deleta os arquivos dentro, mas nao as Pastas
- RM DIR /s /q = Remove tudo, até mesmo as pastas



## GIT

- Open ssl sha1 "Nome do Arquivo" = Gera o conjunto de 40 caracteres encriptografado, sendo assim ele garante e identifica que o arquivo/conjunto não sofreu alteração
- Git init = Inicia um repositório do Git (na maquina local), sendo assim cria a pasta oculta .git fazendo que ele inicie o gerenciamento de versionamento do repositório
- Git add = Adiciona a versão dentro do Git init
- Git commit = gera a Commit que irá versionar o arquivo em questão
- Git add * = Adiciona toda a pasta em questão no repositório, também pode ser utilizamos Git add .   | O ponto (.) no final faz o mesmo que o asterisco (*)
- Git commit -m " "texto" " = Vai realizar o commit com o texto que indica a atualização realizada
- ls = Lista todos os arquivo, similar ao DIR do cmd
- ls -a = Lista até arquivos ocultos
- Git status = indica o status do diretório, se está alterado ou está versionado corretamente
- MV "nome do arquivo" "diretório" = Move o arquivo para o diretório indicado, um metodo agil é utilizar "./" no inicio do diretório pois indica que é a partir do diretório atual do arquivo
- Git remote add origin "https" = Adiciona o local no GitHub para salvar no repertório fazendo que nao seja necessário digitar o site milhões de vezes
- Git remote remove origin = Apaga todos sites salvos do GitHub
- Git remote -v = Mostra a lista de todos os locais para o GitHub salvos
- Git push origin master = Manda seu commit pro GutHub
- Git push origin main = Ironicamente igual o master
- Git pull origin master = Recebe os arquivos que estão salvos no GitHub
- Git clone "https" = Clona os arquivos selecionados do GitHub no seu repertório fisico
- Git config --global user.email "email" = atrela um email ao seu commit | o Global faz com que seu Git faça pra todos seus commits
- Git config --global user.name "nome" = atrela um nome ao seu commit | o Global faz com que seu Git faça pra todos seus commits
- Git config --list = Mostra seus dados salvos ao Git, como nome e email

###  

