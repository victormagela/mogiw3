# mogiw3 - projeto
Projeto para faculdade, desenvolvimento de um website para a empresa fícticia, MogiW3. Com foco em tecnologias Front-End.


# MogiW3
- Empresa fícticia que rpesta serviços de desenvolvimento web
- Criação de sites, apps, E-Commerce, SEO.

# Estrutura
- Header com logo da empresa e menu de navegação, e footer com nome da empresa e copyright em todas as páginas
- 5 páginas
- Home: Hero Section chamativo, uma breve descrição dos serviços oferecidos, um CTA, e um footer
- Serviços: Cards com os serviços oferecidos organizados em um grid visual, permitindo ao usuário escolher entre visualiação em cards ou em lista. Botões com opção de troca entre elas criados com interatividade de JS.
- Carreira: Informações a respeito de candidatura para trabalhar para a empresa
- Blog/Notícias: Artigos sobre tecnologia, novidades da área, notícias sobre a empresa
- Sobre: Breve portfolio pessoal e resumido do desenvolvedor; apresentação profissional, conhecimentos técnicos, interesses, foto, contato
- Páginas serão acessadas via um menu no header das páginas.


# Página Home
- Concluída.
- Hero responsivo com imagem, textos, e um botão que na verdade é um link com fundo animado em gradiente.
- Seção com cards de serviços, descrevendo resumidamente alguns dos serviços oferecidos pela empresa.
- Seção CTA com fundo gradiente.

# Página Serviços
- Concluída.
- Feita com Grid que separa em duas linhas, a primeira contendo o título da seção e botões que controlam como o conteúdo da página é exibido.
- Seção de conteúdo que disponibiliza todos os serviços da empresa, com descrição e um botão que direto ao contato com a empresa semelhante ao botão no Hero da primeira página.
- Essa seção pode ser visualizada em forma de cards, cada serviço sendo um card, ou como uma lista empilhada.

# Página Carreiras
- Concluída.
- Propõe ao usuário se candidatar à uma vaga na empresa com título e texto chamativos.
- Botão que abre o modal do formulário feito com borda animada usando pseudoelementos
- Modal quando abre escurece ligeiramente a tela ao redor e aplica um efeito de blur nos elementos, trava o usuário dentro dele. Feito com acessibilidade em mente, com autofocus e bordas que mostram o elemento focalizado para usuários de teclado, o botão de fechar janela possui um Aria Label que traduz a intenção deste para usuário de leitores de tela. O modal em si pode ser fechado a qualquer momento a tecla ESC ou clicando em qualquer parte fora do formulário.
- Pensando em UX, quando submetido o formulário, uma mensagem de confirmação aparece como "toaster" comunicando que o formulário foi enviado com sucesso. Esta notificação possui uma animação de entrada e saída, e tempo de vida curto até ser retirada da árvore de elementos.