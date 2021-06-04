<h1 align="center">

<img src="https://raw.githubusercontent.com/NaySoares/ignews/3a3c97be7441ffab3babe045d6b5d27d58012c9b/public/images/avatar.svg" alt="" width="100px"/>

</h1>

<p align="center">
  IGNEWS - Portal de notícias 📰🚀
  <br>
  <br>

---

<p align="center">
  <a href="#sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#começando">Começando</a> &#xa0; &#xa0; | &#xa0;
  <a href="#imagens">Imagens</a> &#xa0; &#xa0;
</p>

<br>

## Sobre ##

O projeto ig.news é um blog onde os usuários podem ter acesso ao conteúdo de cada postagem de acordo com o status de sua assinatura.<br>
O blog possui um sistema de compra integrado com o STRIPE, e após o usuário realizar o pagamento, sua inscrição estará ativa e pronta para visualizar o conteúdo completo
de todo o blog. Caso o usuário não deseje optar pela assinatura, ele terá acesso limitado ao conteúdo das postagens. E todos os dados necessários para se fazer verificações
de assinaturas ou dados dos usuários, estão salvos no banco de dados FaunaDB.
<br>
<br>
Essa é uma aplicação Serverless, ou seja, todo o processo que dependeria de um backend foi integrado dentro do front e seguindo o padrão da JAMStack.
<br>
As postagens são feitas pelo painel do Prismic CMS e integradas diretamente pelo front.


## Tecnologias ##

As seguintes tecnologias foram utilizadas no projeto:

- [Next.js](https://nextjs.org/)
- [Prismic CMS](https://prismic.io/)
- [Stripe](https://stripe.com/)
- [FaunaDB](https://fauna.com/)

## Requerimentos ##

- [Node](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/lang/en/)

## Começando ##

```bash
# Clone this project
$ git clone https://github.com/khalleb/ignews

# Access
$ cd ignews

# Install dependencies
$ yarn install

# Run the project
$ yarn dev

# The server will initialize in the <http://localhost:3000>
```
## Imagens ##

<h1 align="center">
    <img alt = "Web app" src = "./.img/ignews01.jpg" width = "500px" />
    <img alt = "Web app" src = "./.img/ignews03.jpg" width = "500px" />
    <img alt = "Web app" src = "./.img/ignews04.jpg" width = "500px" />
</h1>
