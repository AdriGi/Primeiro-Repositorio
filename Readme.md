Primeiro repositório usado para testar comandos do git e github. O conteúdo pode ser encontrado no arquivo em curso_de_Git.pdf, além disso todas as anotações foram baseadas nas aulas do Willian Justen de Vasconcellos, [Git e Github para iniciantes](https://www.udemy.com/course/git-e-github-para-iniciantes/). O material encontra-se em pdf, mas também pode ser visto neste Readme.

Mais sobre mim pode ser encontrado nesse [link](https://www.linkedin.com/in/adriano1996/)

Me chama pra um bico

Obrigado

# Curso de Git e Github

## Seção 1: Entendendo o que é o Git e Github

Controle de versão: Sistema com a finalidade de gerenciar diferentes versões de um documento. É possível voltar para versões anteriores de um mesmo arquivo. Existem mais de um sistema além do git. 

No caso do sistema git ele não verifica as diferenças do arquivo, ele tira snapshot dos estados do arquivo em diferentes versões.
O sistema de versionamento é responsável por “versionar” os arquivos do seu projeto, os outros sistemas trabalham com a diferença dos arquivos, enquanto o git trabalha com o estado dos arquivos.

Github: É o serviço de web compartilhado para projetos que utilizam o Git para versionamento. É um local na web que vai armazenar os projetos do git. O git é o sistema de controle de versão, enquanto o Github é apenas um local remoto para armazenamento.

## Seção 2: Configurando o Git

O git guarda as informações em três lugares: git config do sistema como um todo, git config do usuário e o git config do projeto específico.
Nome de usuário: `git config --global user.name “nome”`

Email: `git config --global user.email “email”`

Definir o editor: `git config --global core.editor NomeDoEditor`

Para saber o nome de usuário basta colocar `git config --global user.name`, de modo similar com os outros comando. Caso queira saber tudo basta: `git config --list`


## Seção 3: Essencial do Git
### Inicializando um repositório

Usará o comando de criar pasta: `mkdir`
Exemplo: `mkdir git-course`

Para fazer o repositório parte do ecossistema do git precisa usar o comando `git init` dentro da pasta em questão, a partir desse comando todas mudanças serão acompanhadas. Aparecerá uma pasta .git. Pode usar o comando `ls -la` e verá também. Dentro do diretório git verá que tem algumas pastas onde: temos config (guarda a configuração do respositório), HEAD (qual branche padrão), branches (branches existentes), description, hooks (gatilhos para fazer algumas ações).

### Usando o editor do terminal
Pode usar um editor de texto separado, assim o terminal entra apenas na parte do git.

Para abrir um arquivo direto no terminal pode usar: `vi NomeDoArquivo.md` ou
usar `vim NomeDoArquivo.md`

Para inserir texto basta aperta a letra **i**, depois de escrever tudo aperta a tecla **esc** (sai do modo de inserção), **:** (indica que vai iniciar comando),  **w** (indica que é para escrever e salvar) e **q** (indica sair), no fim aperta **enter**.

### O ciclo de vida dos status de seus arquivos

<img src = imagens/ciclo_de_vida.png>




