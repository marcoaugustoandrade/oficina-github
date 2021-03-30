# Instruções para o uso do Git e GitHub

1º Criar o repositório no GitHub e clonar no computador
git clone https://github.com/marcoaugustoandrade/oficina-github.git

2º Criar o arquivo .gitignore e listar todos os arquivos e pastas que você não quer deixar públicos no GitHub

3º Colocar os arquivos modificados na área de stage
git add nome-do-arquivo
git add .

4º Criar uma nova versão dos arquivos
git commit -m "Explicação sobre o que foi alterado"

5º Enviar as novas versões para o repositório no GitHub
git push -u origin master

git status => verificar o status dos arquivos
git log => lista as versões (commits)