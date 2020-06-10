---
layout: single
title: "Conhecendo Julia"
date: 2020-04-30
permalink: /posts/conhecendo-julia/
tags: [Julia]
comments: true
excerpt: "Julia"
#header:
#  teaser: "/images/home.png
---

![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/julia.png){: .align-center}

<p style='text-align: justify;'> 

Quem trabalha com computação científica, normalmente deseja alta performance da linguagem de programação no desenvolvimento de suas aplicações. No entanto, especialistas tem migrado para linguagens que oferecem mais dinâmica e produtividade, embora sejam consideradas menos performáticas.</p>

<p style='text-align: justify;'> 

Agora, imagine se existisse uma linguagem que consegue entregar essas duas características que parecem tão antagônicas: produtidade e performance. Sim, essa linguagem existe, e o nome dela é <a href="https://julialang.org/" target="_blank">Julia</a>.</p>

```
"Walks like Python. Runs like C"
```

<p style='text-align: justify;'> 

Julia é uma linguagem de alto nível, criada pelos cientistas Jeff Bezanson, Stefan Karpinski, Viral B. Shah e Alan Edelman em 2012. Embora jovem, a pricensinha da Ciência de Dados vem ganhando adeptos ao redor do mundo. No Brasil, há uma comunidade de usuários bastante ativa chamada <a href="https://t.me/juliabrasil" target="_blank">Julia Brasil</a>.</p>

<p style='text-align: justify;'> 
A seguir mostrarei como baixar e instalar o JuliaPro para criarmos nosso primeiro código em Julia, uma versão disponível para quem deseja otimizar seu trabalho na linguagem ao proporcionar um ambiente de desenvolvimento feito para programar em Julia. Esse tutorial é para usuários do Linux, mas usuários de outros sistemas podem baixar e instalar o JuliaPro facilmente pelo executável disponível no <a href="https://juliacomputing.com/products/juliapro" target="_blank">site</a>.</p>

Podemos escolher baixar o JuliaPro na versão LTS ou a versão estável mais recente. Neste tutorial e para postagens futuras, irei utilizar a versão estável mais recente (*v1.4.1-1 no momento em que escrevo*).

- **Passo 1:** baixe o <a href="https://juliacomputing.com/products/juliapro" target="_blank">JuliaPro</a>
  - *OBS: você deve entrar com login e senha em uma conta de sua preferência*

- **Passo 2:** abra um terminal do linux e digite os seguintes comandos para instalar pre-requisitos.

```
$ sudo apt-get -y install xclip
$ sudo apt-get -y install libgconf-2-4
```

- **Passo 3:** vá para a pasta onde está o arquivo de instalação e digite o seguinte comando para liberar permissões:

```
$ sudo chmod +x JuliaPro-X.X.X-X_build-XX.sh
```
 - **Passo 4:** agora podemos iniciar de fato a instalação:

```
$ ./JuliaPro-X.X.X-X_build-XX.sh <pasta onde julia ficará>
```

 - **Passo 5:** você será perguntado sobre configuração de um time privado no JuliaTeam package server, nesse momento iremos clicar enter e seguir com a instalção sem habilitar esta configuração:

```
$ Do you want to configure your JuliaPro to work with your private JuliaTeam package server? [Yes/No(default)]
```

 - **Passo 6:** vá para a pasta onde JuliaPro está e execute o seguinte comando:

```
$ ./Launch_JuliaPro
```

 - **Passo 7:** e finalmente podemos executar nosso primeiro código em Julia :)

```julia
print("Hello, World!")
```

Agora que conseguimos criar nosso primeito código em Julia, podemos continuar os estudos.

Até a próxima!