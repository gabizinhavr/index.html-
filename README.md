Descrição
Este projeto é a primeira entrega de um sistema web completo desenvolvido para Organizações Não Governamentais (ONGs), aplicando fundamentos de HTML5. A plataforma fictícia "ONG Solidária" visa fornecer uma presença digital profissional, permitindo gerenciar atividades, divulgar projetos, captar recursos e engajar voluntários. Nesta fase inicial, focamos na criação de estruturas semânticas, formulários interativos e integração de multimídia, estabelecendo a base sólida para futuras expansões com CSS3, JavaScript e outras tecnologias.

O projeto é educacional e simula um ambiente de desenvolvimento profissional, com ênfase em semântica HTML5, responsividade futura e acessibilidade.

Funcionalidades Implementadas
Página Inicial (index.html): Apresenta informações sobre a ONG, incluindo missão, visão, valores e contato. Inclui navegação básica e uma imagem otimizada.
Projetos Sociais (projetos.html): Descreve oportunidades de voluntariado e formas de doação, com seções organizadas e imagens ilustrativas.
Cadastro (cadastro.html): Formulário complexo com campos obrigatórios (Nome Completo, E-mail, CPF, Telefone, Data de Nascimento, Endereço, CEP, Cidade e Estado). Inclui validação nativa HTML5, agrupamento lógico com <fieldset> e "máscaras" via atributos pattern e placeholder (ex.: formato brasileiro para CPF: 000.000.000-00).
Todas as páginas utilizam estrutura semântica completa (ex.: <header>, <main>, <section>, <footer>), hierarquia de títulos lógica (H1 a H3) e imagens em múltiplos formatos para otimização.

Estrutura do Projeto

Run
Copy code
/
├── index.html              # Página inicial da ONG
├── projetos.html           # Página de projetos sociais, voluntariado e doações
├── cadastro.html           # Página de formulário de cadastro
├── assets/
│   └── images/             # Pasta para imagens otimizadas (JPG, PNG, WebP)
│       ├── logo-ong.jpg
│       ├── logo-ong.webp
│       ├── projeto-voluntariado.jpg
│       ├── projeto-voluntariado.webp
│       ├── doacao.png
│       ├── doacao.webp
│       ├── cadastro.jpg
│       └── cadastro.webp
└── README.md               # Este arquivo
Como Executar/Visualizar
Clone ou baixe o repositório: git clone https://github.com/seuusuario/plataforma-ong.git (substitua pelo seu link real).
Abra qualquer arquivo HTML (ex.: index.html) em um navegador web moderno (Chrome, Firefox, etc.).
Navegue entre as páginas usando os links no <nav>.
Nota: Como esta é a primeira entrega focada em HTML5, não há CSS ou JavaScript avançado. O layout é básico (sem estilos visuais), mas pronto para integração futura.

Tecnologias Utilizadas
HTML5: Estrutura semântica, formulários com validação nativa, elementos multimídia (<picture> para imagens responsivas).
Validação: Todos os arquivos HTML passam na validação do W3C Validator. Teste cada página fazendo upload do código fonte.
Validação e Otimização
W3C Validator: Confirme a conformidade acessando o link acima e validando cada arquivo HTML.
Imagens: Otimizadas para web (tamanhos reduzidos, múltiplos formatos para compatibilidade). Use ferramentas como TinyPNG para compressão.
Acessibilidade: Estrutura semântica facilita navegação por leitores de tela; validação nativa em formulários auxilia usuários com deficiências.
Contribuição
Este é um projeto educacional. Para sugestões ou melhorias, abra uma issue no repositório GitHub

Licença
Este projeto é para fins educacionais e não possui licença específica. Use e modifique conforme necessário para aprendizado.
