# Lista de Exercícios II: Terminal e Git

> O objetivo deste exercício é consolidar e aprofundar os conceitos para o uso do terminal e
cada um de seus diferentes comandos, bem como criar nosso primeiro repositório em GIT.

### Exercício Prático: Repositórios em Git e Github

#### 1. Abra o terminal e execute as seguintes atividades:
<p>a. Escolha uma pasta para criar nosso repositório local e vá até ela.</p>
<p>cd /Users/veloliveira/Documents/bootcamp</p>

<p>b. Uma vez dentro da pasta, inicie um repositório git local.</p>
<p>git init</p>

<p>c. Uma vez criado o repositório, defina nossas credenciais (usuário e email).</p>
<p>git config user.name "evycoliveira" e git config user.email evelyn.oliveira@mercadolivre.com</p>
<p>git config --global user.name "evycoliveira" e git config --global user.email evelyn.oliveira@mercadolivre.com</p>

<p>d. Crie um arquivo chamado “teste1.txt” e coloque algum texto “aleatório” dentro dele.</p>

<p>e. Adicione o arquivo criado ao stage.</p>
<p>git add Git-I/git.txt</p>

#### 2. Crie um repositório no GitHub, obtenha sua URL e faça o seguinte:
<p>a. Configure no repositório local o endereço do repositório remoto para poder compartilhar os arquivos posteriormente.</p>
<p>git remote add origin git@github.com:evycoliveira/java-bootcamp.git</p>

<p>b. Verifique o status do repositório local para ver o status do arquivo “teste1.txt”.</p>
<p>git remote -v</p>
<p>git status</p>

<p>c. Se tudo estiver ok, envie o arquivo “teste1.txt” para o repositório remoto.</p>
<p>git add Git-I/git.txt</p>
<p>git commit -m "Iniciando estudos com Git"</p>
<p>git push origin develop</p>

<p>d. Acesse o GitHub e veja se o arquivo chegou com sucesso ao repositório remoto.</p>
