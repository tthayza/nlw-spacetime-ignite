<h1 align='center'><strong> CÁPSULA DO TEMPO ⏳🚀👩🏻‍🚀✨<h1></strong>
<h2><strong> Sobre o projeto<h2></strong>

<p align='justify'>Página desenvolvida com Backend, Frontend e Banco de Dados na Next Level Week Spacetime da RocketSeat. Esse projeto visa ser uma cápsula do tempo na qual são armazenadas memórias, contendo o registro em imagem e um texto descritivo.</p>

<p align="center">
  <img src="./.github/preview.png">
</p>

<h2><b> Funcionalidades</b> </h2>

<h3><strong>✅ Autenticação com GitHub</h3></strong>

<p align='justify'> Ao se conectar à página para que o usuário seja logado, ao clicar em '<strong>crie sua conta</strong>' ocorrerá um redirecionamento para autenticar-se com o GitHub. E, assim, será possível obter os dados do usuário como o nome e foto. Para isso foi utilizada a tecnologia NextAuth.js.</p>

<h3><strong> ✅ Listagem de memórias</h3></strong>

<p align='justify'>Ao se conectar com a página, já estando autenticado com o GitHub, o usuário terá como página principal a listagem de suas memórias cadastradas. Essa funcionalidade é feita por meio de uma busca no banco de dados carregando o token do usuário logado, e retornando um array de memórias e então elas são mapeadas e organizadas na interface final. Caso esse array esteja vazio, a página sugerindo para o usuário criar uma nova memória será renderizada. </p>

<h3><strong>✅  Criação de nova memória</h3></strong>

<p align='justify'> Para criar uma nova memória, basta que o usuário clique no botão cadastrar lembrança ou então, para a primeira memória clicar em 'criar agora' ao lado direito da página. Será solicitado o arquivo em mídia, um texto descritivo e um check caso seja desejado tornar a memória pública.</p>

#

<h2><b> Utilizando localmente </b> </h2>

<p>Para rodar o projeto em sua máquina local basta clonar o projeto, acessar as pastas e instalar as dependências seguindo os seguintes comandos em seu terminal de preferência: </p>

<h4><strong>Para o server:</strong></h4>

<pre>
git clone https://github.com/tthayza/ nlw-spacetime-ignite.git 
cd nlw-spacetime-ignite
cd server
npm install
npm run dev
</pre>

<h4><strong>Para a web:</strong></h4>
<pre>
cd ..
cd web 
npm install
npm run dev
</pre>
<hr>
<h2><b> Tecnologias Utilizadas</b></h2>
 <h3 > Esse projeto foi desenvolvido com as seguintes tecnologias: </h3>

<p align='center'>TypeScript  |  TailwindCSS  |  React  |  Next.js 13  |  NextAuth  |  Prisma  |  Figma  |  Fastify </p>
