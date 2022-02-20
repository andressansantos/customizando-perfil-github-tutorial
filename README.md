# Tutorial Fácil de Customização do Perfil do GitHub

<p align="left">Esse tutorial tem o objetivo de ajudar as pessoas a desenvolverem seus proprios perfis personalizados do Github, de maneira mas simplificada possível</p>

Categorias

<p align="center">

---
## Índice

- Primeiros passos
  - [Requisitos](#requisitos)
  - [Criando](#criando)
  - [Customizando](#customizando-readme)
- [Link Utilizados](#links-utilizados)

</p>

---


### Requisitos
  
  - Único requisito para prosseguir nesse tutorial é ter uma conta criada no site [GitHub](https://github.com/).

### Criando 
  
  - Primeiro passo é criar seu diretório de perfil Github. Para isso, clique em + ap lado de sua foto de perfil e após em <b>New Repository</b>
  
![Animação](https://user-images.githubusercontent.com/45522652/154861171-b41edef0-0941-4659-b427-5e67714c57e7.gif)
  
  - Feito isso, você colocar o nome desse novo repositório. Ele precisa ser necessariamente igual ao seu nome de perfil do GitHub. 
  Como o meu é <b>andressansantos</b> foi esse que coloquei.
  
![create-repo](https://user-images.githubusercontent.com/45522652/154861425-caf48252-dd1f-4a02-a7ac-77580e7a5b07.gif)
  
  Por fim, marque a opção <b>Add a README file</b> e por ultimo, no botão <b>Create</b>
 
### Customizando Readme
  
  Ele veem totalmente vazio ao ser criado.
  Nele, você poderá colocar uma breve descrição do que você trabalha/estuda hoje.
  Assim como em HTML, o Markdown como liguagem de marcação possuí os mesmos recursos que juntos com o HTML te dão maior flexibilidade.
  Por isso, utilize os mesmos quando necessário sabiamente.
  
  A primeira coisa importante é conhecer um pouco de Markdown. E para isso, você poderá acessar o [link aqui para ter um tutorial mais completo](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open).
  
  Crie uma breve apresentação, e se quiser coloque emoticons. Poderá utilizar o site [EmojiPedia](https://emojipedia.org) para isso.
  ![edit-perfil](https://user-images.githubusercontent.com/45522652/154861984-106fddae-e33f-472c-a5da-33850dff17d5.gif)

  Agora, utilizaremos as informações do [GitStats](https://github.com/anuraghazra/github-readme-stats#themes), um repositório no GitHub para colocar as estatisticas no nosso perfil.
  
  Comecemos colocando uma < div > e dentro dela, colocaremos a informação do tema que queremos e nosso usuario.

  ```
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=andressansantos&show_icons=true&theme=tokyonight"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=andressansantos&layout=compact&theme=tokyonight"/>
  ```
  Não esqueça de mudar no campo <b>username</b> para o nome do seu usuário de Githube. Na ultima parte, de Theme ao final do código, poderá escolher o que 
  desejar na pagina do [GitStats](https://github.com/anuraghazra/github-readme-stats#themes).
    
 E esse será o resultado:
<div>
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=andressansantos&show_icons=true&theme=tokyonight"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=andressansantos&layout=compact&theme=tokyonight"/>
</div>
    
 Adicione as redes sociais, para recrutadores ou outras pessoas queiram entrar em contato com você. Para isso, coloque o código conforme exemplo:

```
    [![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/n9KBKHPA3H)
```

  Nesse código, a primeira parte é o nome da rede, a segunda parte o link no post do Dev.To e a terceira parte o link da sua rede. Nesse meu caso, foi da comunidade no Discor do Ehmuitodrama.  
  Para ter acesso a todos os Badges de redes sociais, acesse ao [post completo com mais de 150 Badges no Dev.to](https://dev.to/envoy_/150-badges-for-github-pnk)
    
  E esse será o resultado ao acabar e colocar o link e verificando no preview.
    
    [![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/n9KBKHPA3H)

 Agora iremos para a última parte que é adicionar as tecnologias que estamos aprendendo/dominando/trabalhando. Nessa parte, utilizaremos o site [Dev Icon](https://devicon.dev)
    O código que utilizaremos sempre será o <b>SVG</b>
    
  ```
  <img align="center" alt="Andressa-html" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/>
  ```
    
No código passado, colocamos um nome, além de dimensões utilizando a tag <b>img</b> do HTML. A seguir no src, colocando a imagem do <b>SVG</b>
    
E o resultado será esse:

<img align="center" alt="Andressa-html" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/>

---

### Links utilizados    
    
  A seguir, listareis todos os sites consultados para a criação de Readme. 
    
   [Emoticon:](https://emojipedia.org)
   
   [Criação de Gifs ScreenToGif:](https://www.screentogif.com)
   
   [Icones Tecnologias:](https://devicon.dev)
   
   [Post Dev.To de Badges:](https://dev.to/envoy_/150-badges-for-github-pnk)
   
   [Criador de Gif com sua foto:](https://picrew.me/image_maker/338224)
   
   [Repositório do Github Stats:](https://github.com/anuraghazra/github-readme-stats)
   
    
    
    
  
    
    
  
  
  
  
  
