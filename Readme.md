### Letras de Música

Projeto Python simples, mas funcional, que demonstra a criação de uma aplicação web de busca de letras de músicas.

<h3>Recursos Principais</h3>

Interface Web Intuitiva: Desenvolvida com Streamlit, oferecendo uma experiência de usuário limpa e fácil de usar.

Busca de Letras: Permite a busca por Artista e Título da Música.

Integração com API: Consome a API Lyrics OVH para buscar os dados das letras em tempo real.

<h3>🛠️ Tecnologias Utilizadas</h3>

Python: Linguagem de programação principal.

Streamlit: Para a criação da interface web e componentes interativos.

Requests: Para a comunicação HTTP com a API externa.

Lyrics OVH API: Fonte de dados para as letras das músicas.


<h3>Funcionamento</h3>

O usuário insere o nome do artista e da música na interface do Streamlit. A aplicação constrói a requisição HTTP usando a biblioteca requests e a envia para a API Lyrics OVH. A resposta, contendo a letra da música, é então formatada e exibida na tela do Streamlit.

Feito para estudos, com base no video: https://youtu.be/_03CKMuvIxU?si=E6K_12VCSpqXr5-2