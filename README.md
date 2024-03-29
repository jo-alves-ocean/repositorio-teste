# repositorio-teste
Repositório teste #2

## Configurando nome de usuário e email

```
git config user.name "nome_de_usuário"
```

```
git config user.email "emaildousuário@gmail.com"
```
## Verificando nome de usuário e email

```
git config user.name
```

```
git config user.email
```

## Criando um repositório

```
git init
```

## Clonando um repositório

```
git clone link_do_repositório
```

## Verificando status

```
git status
```

## Adicionando arquivos/mudanças na staging area

```
git add nome_do_arquivo
```

## Verificando mudanças que não estão na staging area

```
git diff
```

## Realizando commit

```
git commit -m "mensagem de commit"
```

## Verificando status do repositório

```
git log
```

## Unindo commits

```
git rebase -i hash_do_commit
```

## Corrigindo mensagem de commit

```
git commit --amend -m "mensage_de_commit"
```

## Desfazendo uma alteração que ainda não está na staging area

```
git restore nome_do_arquivo
```

## Desfazendo uma alteração que está na staging area

```
git restore --staged nome_do_arquivo
```

## Desfazendo uma alteração que foi commitada

```
git revert hash_do_commit
```

## Salvando temporariamente

```
git stash
git stash list
git stash apply número
git stash drop número
git stash pop
```

## Criando um repositório remoto

```
git remote add origin link_do_repositório
git branch -M main
git push -u origin main
```

## Trabalhando com repositórios remotos

```
git fetch
git pull
git push
```
