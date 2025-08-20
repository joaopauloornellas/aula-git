# Comandos Git
Neste arquivos será apresentado os comandos git para uso futuro

## No primeiro uso em um computador para que o GIT avise e saiba quem fez as alterações é necessário configurar o usuário nas configurações globas do git. 
```bash

git config --global user.name "João Paulo dos Santos Ornellas"

git config --global user.email "jpaulo.it@gmail.com"
```

### Estando dentro de uma pasta use o comando abaixo para inicia o git. Somente da primeira vez
```bash
git init
```

#### Após a inicializacao devemos digitar o comando code ./ e o nome do arquivo como no exemplo abaixo.
```bash
code ./comandos-md
```

##### Para consultar o status do git usar o comando, onde iremos verificar que o git nao estara add, constando em vermelho.
```bash
git status
```
###### Em seguida devemos add o git com o comando abaixo
```bash
git add .
```

###### git commit -m usamos para dar instrucoes ao usuario
```bash
git commit -m "Escrever a mensagem""

