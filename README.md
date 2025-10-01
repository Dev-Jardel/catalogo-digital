Catálogo de Produtos Digitais com Painel Admin
Este projeto é uma plataforma web completa para a venda de produtos digitais, como e-books e cursos. Ele foi desenvolvido com foco em uma experiência de usuário limpa para o cliente e um gerenciamento simples e poderoso para o administrador, sem a necessidade de tocar no código para atualizar o catálogo.

<h2 align="center">Visão do Cliente</h2>
<p align="center">
  <img src="https://i.imgur.com/tVeETgw.jpeg" width="600">
</p>

<h2 align="center">Visão do Administrador</h2>
<p align="center">
  <img src="https://i.imgur.com/Cs5zXiN.jpeg" width="600">
</p>


✨ Funcionalidades Principais
Visão do Cliente (index.html)
Catálogo Interativo: Exibição dos produtos em formato de cards.

Filtro por Categorias: Barra lateral que permite filtrar os produtos de forma dinâmica.

Detalhes do Produto: Janela modal com imagem ampliada, descrição formatada e preço promocional (de/por).

Botão de Compra: Redirecionamento direto para o link de pagamento do produto.

Design Responsivo: Totalmente adaptável para desktops, tablets e celulares.

Visão do Administrador (admin.html)
Acesso Seguro: Página de login separada para garantir que apenas o administrador possa gerenciar os produtos.

CRUD Completo:

Adicionar: Formulário para cadastrar novos produtos, incluindo nome, descrição, preços (antigo e atual), categoria, imagem e link de compra.

Editar: Modificar qualquer informação de um produto existente.

Excluir: Remover produtos do banco de dados privado.

Publicação com Um Clique: Um botão "Publicar" que sincroniza a lista de produtos privados com o catálogo público que os clientes veem.

🚀 Tecnologias Utilizadas
Frontend: HTML5, CSS3 e JavaScript (ES6 Modules).

Estilização: Tailwind CSS - para um design moderno e responsivo de forma rápida.

Backend & Banco de Dados: Firebase

Firestore: Como banco de dados NoSQL para armazenar os dados dos produtos de forma segura.

Authentication: Para o sistema de login do administrador.

Hosting: Para a hospedagem do site.

Storage: Para o armazenamento das imagens dos produtos.

🔧 Como Executar Localmente
Para testar este projeto no seu próprio ambiente, siga os passos:

Clone o repositório:

git clone [https://github.com/Dev-Jardel/catalogo-digital](https://github.com/Dev-Jardel/catalogo-digital.git)

Configure suas chaves do Firebase:

Crie um projeto no Firebase.

Nos arquivos index.html e admin.html, substitua o objeto firebaseConfig pelas chaves do seu projeto.

Configure as Regras de Segurança do Firestore para permitir leitura pública e escrita autenticada.

Crie um usuário no Firebase Authentication para ser o administrador.

Use o Emulador Local do Firebase:

Instale o Firebase CLI: npm install -g firebase-tools.

Na pasta do projeto, inicie o servidor local:

firebase serve --only hosting

Acesse http://localhost:5000 para a visão do cliente e http://localhost:5000/admin.html para o painel de admin.