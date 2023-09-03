# Git e Github: Primeiros Passos:

## Como instalar?

```bash
sudo apt install git

/**/Como saber a versão?**
git --version
```

## Configurando sua conta

```bash
git config --global user.name "Márcio José"
git config --global user.email "meuemail@github.com"
```

## Iniciando um repositório

```bash
mkdir meurepo //Criando a pasta do repositório
cd meurepo //Comando para ir até o repositório
code .  //Comando para abrir sua pasta/repositório no visual code
```

Ainda no Visual Studio Code, pressione CTRL + ‘ para abrir o terminal ou acesse via menu Terminal > New Terminal

Na nova janela que se abrirá, execute este comando

```bash
git  init
```

## Adicionando Itens

Para adicionar um item específico

```bash
git add .\README.md
```

Para adicionar todos os itens

```bash
git add --all
```

## Comitando

Termo usando para se comprometer as alterações no código

```bash
git commit -m "Adicionando arquivo README.md"
```

Neste caso, vamos comitar e comentar usando o parâmetro -m

## Ligando os Repositórios

Adicionando uma origem na qual o repositório ira mandar suas alterações os baixar alterações feitas por colaboradores 

```bash
git remote add origin https://github.com/USUARIO/meu-primeiro-repositorio.git
```

## Enviando arquivos

```bash
git push -u origin master
```

O parâmetro -u especifica que você quer essa branch como padrão para quando você fazer git push ela mande para a master como padrão

## Atualizando arquivos

```bash
git pull
```

Nesse caso ele atualizará os arquivos tendo como referência a branch master, pois ela foi definida como padrão

## Clonando um Repositório

```bash
git clone https://github.com/USUARIOmeu-primeiro-repositorio.git
```

Autor: @Márcio José 

Github: @[https://github.com/ImMarcio](https://github.com/ImMarcio)