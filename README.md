# Ignews 💛🚀

&nbsp;

![mock1](https://user-images.githubusercontent.com/71772559/113495090-3e529600-94c5-11eb-953c-53ab4f71fc15.png)

## 📚 Informações sobre o projeto

* O projeto ig.news é um blog onde os usuários podem ter acesso ao conteúdo de cada postagem de acordo com o status de sua assinatura.O blog possui um sistema de compra integrado com o STRIPE, e após o usuário realizar o pagamento, sua inscrição estará ativa e pronta para visualizar o conteúdo completo de todo o blog. Caso o usuário não deseje optar pela assinatura, ele terá acesso limitado ao conteúdo das postagens. E todos os dados necessários para se fazer verificações de assinaturas ou dados dos usuários, estão salvos no banco de dados FaunaDB. 
* Essa é uma aplicação Serverless, ou seja, todo o processo que dependeria de um backend foi integrado dentro do front e seguindo o padrão da JAMStack.
* As postagens são feitas pelo painel do Prismic CMS e integradas diretamente pelo front.

&nbsp;

## 💻 O que tem no projeto?

* Integração com o Prismic CMS, para trabalhar com toda a parte do sistema do blog.
* Integração com o Stripe para a parte dos pagamentos das inscrições.
* Integração com o NextAuth para a parte do login com o Github.
* Sistema de verificação de assinatura, o conteúdo exibido varia entre usuários com/sem assinatura paga.
* Dados são salvos no bando do FaunDb.
* Uso do sistema estático do Next.js, onde os posts são mantidos no cache para um melhor carregamento.

&nbsp;

![mock2](https://user-images.githubusercontent.com/71772559/113495232-84f4c000-94c6-11eb-81fe-4dfb37d29e44.png)

&nbsp;

## 🛠️ Tecnologias/Ferramentas utilizadas

* [React](https://pt-br.reactjs.org/E)
* [Next.js](https://nextjs.org/)
* [NextAuth](https://next-auth.js.org/)
* [Prismic CMS](https://prismic.io/)
* [Stripe](https://stripe.com/en-br)
* [Fauna](https://fauna.com/)

&nbsp;

<img src="![ignewstici](https://user-images.githubusercontent.com/61629953/181025825-4746abda-4b71-4f6b-8f65-53b61378a28b.gif)" width="100%" />

&nbsp;
## :white_check_mark: Requerimentos ##

- [Node](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/lang/en/)

&nbsp;

## 🎯 O que é Arquitetura Serverless?
* Arquitetura Serverless, ou “computação sem servidores”, é uma arquitetura de computação orientada a eventos. Sua principal proposta é permitir que as empresas de software criem e mantenham seus aplicativos web sem se preocupar com a infraestrutura em que esses aplicativos estão rodando.
* Utilizando uma plataforma Serverless, o time de desenvolvimento da software house não precisa gerenciar a infraestrutura de servidores, como provisionamento, capacidade de processamento, sistemas de armazenamento, atualização dos servidores, entre muitas outras configurações recorrentes: todas essas funções ficam a cargo do provedor cloud.
* Com esse trabalho periférico mitigado, os desenvolvedores passam a ter mais mais tempo para se dedicar a suas funções primárias, entregando muito mais software em um mesmo período.
* Apesar de ser a vantagem mais óbvia da arquitetura Serverless, o tempo ganho pelo dev é apenas um dos destaques da arquitetura Serverless.

&nbsp;

## 👩‍💻 Static generation 
* O HTML é gerado no momento da construção e será reutilizado a cada pedido. Esta é a abordagem ideal porque os arquivos HTML e JSON gerados são armazenados em cache pelo CDN para melhor desempenho. Há duas funções que a estrutura fornece para trabalhar com dados externos: 1) getStaticProps - Coloque seus dados externos para serem pré-renderizados aqui. 2)getStaticPaths - Obter rotas com base em dados externos. Isto tem a ver com roteamento dinâmico e é usado em conjunto com getStaticProps.

&nbsp;

## 👩‍💻 Server-side generation (SSR)
* O HTML para a página é gerado em cada solicitação. getServerSideProps é a função que é usada quando o SSR é necessário para a renderização do conteúdo da página.


## ⚙️ Instalação
```
# Abra um terminal e copie este repositório com o comando
$ git clone https://github.com/GBDev13/ignews.git
```

```
# Acesse a pasta da aplicação
$ cd ignews

# Crie um arquivo .env.local e coloque as variáveis
# de ambiente baseado no arquivo .env.example 

# Instale as dependências
$ yarn

# Inicie a aplicação
$ yarn start

```

&nbsp;

### 🔗 Link para o projeto online


[Ignews](https://ignews-tcapris.vercel.app/)
<p><strong>Aviso</strong>, o Stripe possui um token de teste que dura apenas alguns dias e não irei atualizar o mesma quando vencer, então não será testar o sistema de compra.</p>

&nbsp;


---

<p align="center">Feito com 💛 por Ticiana Capris</p>
 
