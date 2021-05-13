![111013025-bd4c2700-837c-11eb-96bd-e35dd94de39d](https://user-images.githubusercontent.com/70667966/118026267-00078c80-b337-11eb-9ff1-0ef3b2a55343.png)

<h1 align="center"> Watch Me </h1>
<p> Resolução do desafio complementar do primeiro capítulo da trilha React JS no Ignite, pela Rocketseat. </p>

<h2 align="center"> Objetivo </h2>
O objetivo deste projeto é componentizar a aplicação para filmes Watch Me.
<p></p>

<p> O componente Content.tsx deve conter a parte do conteúdo da aplicação, demonstrado pelo contorno vermelho. </p>
<p align="center">
  <img width="100%" height="100%" src="https://user-images.githubusercontent.com/70667966/118026697-7a381100-b337-11eb-8cf7-0cb5839a4975.png"/>
</p>

<p> O componente Sidebar.tsx deve conter a seleção de gêneros do filme, também demonstrado pelo contorno vermelho. </p>
<p align="center">
    <img width="100%" height="100%" src="https://user-images.githubusercontent.com/70667966/118026715-815f1f00-b337-11eb-8a7a-8c7aec3f75b2.png"/>
</p>

<h2 align="center"> Demonstração do projeto </h2>
<p align="center">
    <img width="70%" height="70%" src="https://user-images.githubusercontent.com/70667966/118027942-de0f0980-b338-11eb-89ac-5fe2b3d1e178.gif"/>
</p>
<p></p>

<p> Para solucionar o problema, utilizei o hook useContext(), já que os dois componentes precisavam receber informações da mesma API e para não precisar criar <em>tipagens</em>
repetidas no TypeScript. </p>

<h2 align="center"> Para testar a aplicação </h2>
<p> Para testar a aplicação é necessários dois terminais, um para executar o projeto e o outro para a API </p>

<p> 1 - Para instalar as dependências </p>

> npm install

<p> 2 - Em um dos terminais, inicie a API </p>

>cd Watch-me
> yarn server

<p> 3 - No segundo terminal, inicie o projeto </p>

>cd Watch-me
> yarn dev
