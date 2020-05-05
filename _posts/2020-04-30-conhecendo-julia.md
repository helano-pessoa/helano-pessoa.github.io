---
layout: single
title: "Conhecendo Julia"
date: 2020-04-30
permalink: /posts/conhecendo-julia/
tags: [Julia]
#comments: true
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

Princesinha da Ciência de Dados

Podemos escolher baixar o JuliaPro na versão LTS ou a versão estável mais recente. Neste tutorial e para postagens futuras, irei utilizar a versão estável mais recente (*v1.4.1-1 no momento em que escrevo*).



- **Passo 1:** baixe o <a href="https://juliacomputing.com/products/juliapro" target="_blank">JuliaPro</a>
  - *OBS: você deve entrar com login e senha em uma conta de sua preferência*

- **Passo 2:** abra um terminal do linux e digite os seguintes comandos para instalar pre-requisitos.

 ```
 $ sudo apt-get -y install xclip
 $ sudo apt-get -y install libgconf-2-4
 ```

- **Passo 3:** abra o terminal do linux na pasta onde está o arquivo e digite o seguinte comando:

 ```
 $ sudo chmod +x JuliaPro-X.X.X-X_build-XX.sh
 ```
 - **Passo 4:** agora podemos iniciar de fato a instalação:

 ```
 $ sudo chmod +x JuliaPro-X.X.X-X_build-XX.sh <pasta>
 ```
 Do you want to configure your JuliaPro to work with your private JuliaTeam package server? [Yes/No(default)]

 ```
 <juliapro>./Launch_JuliaPro
 ```


 ```julia
 print("Hello, World!")
 ```