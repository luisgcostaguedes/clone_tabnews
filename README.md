# clone_tabnews

### Tudo o que será feito durante o curso do curso.dev, será atualizado aqui, inclusive com algumas opções que irei adotar por conta própria, lembrando que este arquivo sofrerá diversas mudanças em decorrer das atualizações

### Primeiros passos

Primeiro arquivo que criamos foi este que vai conter todos os passos para a criação completa do "Tabnews"

### Utilizando o NODE

Para isso instalamos o NVM que pode ser instalado através do seguinte link:

- [NODE / NVM](https://github.com/nvm-sh/nvm#install--update-script)

### Visualizar versões disponíveis e em seguida instalar a desejada

Sempre optar para uma versão LTS

```
nvm ls-remote
```

### Padronizar a versão usada

Criamos o arquivo ".nvmrc" que tem como função instalar no ambiente de desenvolvimento a versão do node que será usada como padrão, evitando assim que haja divergências.

### Após a criação do .nvmrc

Executaremos o comando:

```
nvm install
```

Assim o mesmo vai ver a versão que vai estar definida no arquivo e a instalará
