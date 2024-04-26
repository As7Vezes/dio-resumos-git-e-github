
# DIO | Resumos Git e GitHub

Repositórios para armazenar resumos sobre Git e GitHub do curso Versionamento de Código com Git e GitHub  da 
[Digital Innovation One](https://www.dio.me/)

## 📚 Documentação 

- [Documentação Git](https://git-scm.com/doc)
- [Documentação do GitHub](https://docs.github.com)

## 💻 Resumos das Aulas

| Aulas | Resumos |
|-------|---------|
| Granvando Alterações no Repositório Local | [Resumos](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/santander-2024-backend-com-java&tab=undefined&moduleId=undefined)|

```
git init
```

## 🔍 Referências 
- [Digital Innovation One]()

## 💻 Comandos

### Comando para restaurar as alterações do aquivos caso edite ele sem querer:

```
git restore <fileName>
```

### Alterar a mensagem do último commit 

```
git commit --amend -m "<message>"
```

### git reset --soft Defazer o commit e retornar para o commit anterior
#### obs: Você tem que copiar o hash do commit em que você quer retornar. 

#### o git reset soft pega os arquivos do commit em que você quer desafazer o commit em coloca denovo na área de preparação para para o commit dele novament.
```
git reset --soft <commitHash>
```

### git reset --mixed Defazer o commit e retornar para o commit anterior
#### obs: Você tem que copiar o hash do commit em que você quer retornar. 

#### o git reset --mixed pega os arquivos do commit em que você quer desafazer o commit e coloca como se eles não fosse nem colocados pra área de preparação do commit.
```
git reset --mixed <commitHash>
```

### git reset --hard Defazer o commit.
#### obs: Você tem que copiar o hash do commit em que você quer retornar. 

#### o git reset --hard ignora os arquivos alterados do commit anterior e desfaz o commit por completo
```
git reset --hard <commitHash>
```

### git reset <nome do arquivo> tirar algum arquivo específico do commit.
```
git reset <nome do arquivo>
```