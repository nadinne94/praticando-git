# Passo a passo git

## Fork e Pull Request

1º abra a pasta onde queira salvar o repositorio clonado
2º vá até o repositório que deseja clona e "fork"

- ao criar o fork, você será direcionado para o repositório bifurcado dentro da sua própria github

3º copia a url desse repositório (o repositória do seu git) e clone

git clone link-do-seu-repositório

4º navegue até a pasta clonado e digite o comando: code . 
-irá abrir o vs code
-dentro do vs code abra o terminal, verifique se o caminho é o do repositório clonado 

5º Rastrear o repositório original

git remote add --track master upstream (link do repositório original) fetch upstream

exemplo: git remote add --track master upstream [https://github.com/squad-rita-levi-montalcini/praticando-git.git] fetch upstream

6º Criar nova branch
git checkout -b (nome da nova branch) 

7º Adicionando alterações
-realize alguma alteração do repositório e depois adicione e commit as mudanças

git add .
git commit -m "mensagem de commit"
git push -u origin (nome da branch criada)

8º Pull Request
Vá para a guia Pull Requests do repositório original e crie uma nova pull request