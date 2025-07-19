# E-Food: Seu Aplicativo de Pedidos de Comida Online


Este é um projeto de aplicativo web de pedidos de comida online (Food Delivery App) desenvolvido com React, que simula um sistema de listagem de restaurantes, visualização de cardápios e um fluxo de compra completo, desde a adição de itens ao carrinho até a finalização do pedido com dados de entrega e pagamento.

# 🚀 Visão Geral do Projeto

O E-Food oferece uma experiência de usuário fluida para explorar restaurantes, visualizar seus pratos e realizar pedidos de forma intuitiva. O foco principal foi a implementação de um carrinho de compras robusto e um processo de checkout em múltiplas etapas, garantindo a validação dos dados e a comunicação eficiente com uma API.

# ✨ Funcionalidades Principais

- Listagem de Restaurantes: Exibe uma lista de restaurantes disponíveis com informações básicas e avaliações.

- Página de Restaurante: Ao selecionar um restaurante, o usuário pode visualizar seu cardápio completo, incluindo descrições detalhadas e preços.

- Modal de Detalhes do Produto: Ao clicar em um item do cardápio, um modal interativo exibe mais detalhes do produto (imagem, descrição, preço) e permite adicioná-lo ao carrinho.

- Carrinho de Compras Dinâmico:

- Adição e remoção de itens em tempo real.

- Cálculo automático do valor total do pedido.

- Verificação inteligente de carrinho vazio, impedindo o avanço para o checkout sem itens.

- Fluxo de Checkout Multi-etapas:

- Entrega: Formulário detalhado para coletar informações do recebedor e endereço de entrega.

- Pagamento: Formulário seguro para coletar dados do cartão de crédito.

- Validação de formulário em tempo real utilizando as bibliotecas Formik e Yup, fornecendo feedback imediato ao usuário.

- Navegação intuitiva entre as etapas (voltar ao carrinho, ir para entrega, ir para pagamento).

- Integração com API Fake: Envio dos dados completos do pedido (produtos do carrinho, informações de entrega e detalhes de pagamento) para uma API simulada.

- Confirmação de Pedido: Após a finalização bem-sucedida, uma tela de confirmação exibe o ID único do pedido retornado pela API.

- Design Responsivo: Layout adaptável e otimizado para uma experiência de usuário consistente em diversos tamanhos de tela, incluindo desktops, tablets e celulares (modos retrato e paisagem).

# 🛠️ Tecnologias Utilizadas
- React: A biblioteca JavaScript líder para construção de interfaces de usuário reativas e componentizadas.

- Redux Toolkit: Simplifica o gerenciamento de estado global da aplicação, tornando-o mais eficiente e fácil de manter.

- Redux Toolkit Query (RTK Query): Uma poderosa ferramenta para gerenciamento de dados assíncronos, cache de API e simplificação de requisições HTTP.

- Styled Components: Permite escrever CSS diretamente em JavaScript, proporcionando estilos componentizados e dinâmicos.

- Formik: Facilita a criação e manipulação de formulários em React, lidando com estado, validação e submissão.

- Yup: Uma biblioteca de validação de schemas JavaScript, utilizada em conjunto com Formik para validação robusta dos dados de entrada.

- API Fake (Vercel): Um serviço utilizado para simular um backend, permitindo o desenvolvimento e teste completos do fluxo de compra.


# 👩‍💻 Acessando o Projeto:

Para acessar o projeto, entre no link: https://e-food2.vercel.app/
