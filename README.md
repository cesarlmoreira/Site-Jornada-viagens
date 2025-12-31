## Projeto de Site - Jornada Viagens

🌐 Projeto de Layout Responsivo - Jornada Viagens
Este projeto consiste no desenvolvimento de uma landing page de viagens, com foco na aplicação de técnicas de Responsividade e Arquitetura CSS Modular. O objetivo principal foi criar uma interface fiel ao design original, que se adapta fluidamente a diferentes tamanhos de tela (Mobile, Tablet e Desktop).

🎨 Design do Projeto
O layout foi desenvolvido com base no protótipo disponibilizado no Figma. Você pode conferir o design original no link abaixo:

🖌️ Protótipo (Figma): Acesse o Projeto Jornada Viagens

🚀 Tecnologias Utilizadas
HTML5: Estruturação semântica do conteúdo.

CSS3: Estilização visual e layouts.

📋 Atividades e Habilidades Demonstradas
1. 📱 Design Responsivo (Mobile First)
O projeto foi estruturado para oferecer a melhor experiência em qualquer dispositivo.

Adaptação de Mídia: Uso de diferentes versões de imagens para otimização e direção de arte (<picture>, srcset), utilizando arquivos específicos para cada tela (ex: hero-mobile.jpg, hero-desktop.jpg).

Media Queries: Ajuste preciso de breakpoints para celulares, tablets e desktops.

2. 🎨 Arquitetura CSS Modular
O CSS foi organizado em módulos baseados nas seções da página, facilitando a manutenção e escalabilidade:

header.css: Estilos do cabeçalho e navegação.

hero.css: Estilização da área de destaque principal.

packages.css: Grid de pacotes de viagem.

form.css: Estilização de formulários.

global.css: Variáveis (CSS Variables), resets e tipografia padrão.

3. ✒️ Tipografia e Assets
Fontes: Utilização da fonte Montserrat (Variable Font) para garantir identidade visual moderna.

Organização: Estrutura de pastas separando assets (fontes, imagens) dos arquivos de código.

📂 Estrutura de Pastas

├── index.html          # Markup semântico principal
├── /assets
│   ├── /fonts          # Typography (Variable fonts)
│   └── /img            # Assets otimizados (Mobile/Tablet/Desktop)
└── /styles
    ├── global.css      # Reset, variáveis e tipografia base
    ├── header.css      # Navbar responsiva
    ├── hero.css        # Hero section com bg adaptativo
    ├── packages.css    # Grid layout para cards
    ├── form.css        # Estilização de inputs/buttons
    └── footer.css
