# Atividade Prática: Construindo o "Portal EcoVida"
# Tema: Um portal de notícias e dicas sobre sustentabilidade e vida saudável.

# Objetivo Final: Desenvolver um site responsivo, semanticamente correto e visualmente atraente que se adapte perfeitamente a desktops, tablets e smartphones.

# 1. Visão Geral do Projeto
Você foi contratado para criar a primeira versão do site EcoVida, um portal dedicado a compartilhar notícias, artigos e guias práticos para um estilo de vida mais sustentável e saudável. O cliente exige um site moderno, acessível e que funcione bem em qualquer dispositivo.

# 2. Estrutura e Conteúdo da Página (HTML Semântico)
Sua missão é construir a página inicial (index.html) com a seguinte estrutura, utilizando exclusivamente tags semânticas para definir cada seção (<header>, <nav>, <main>, <section>, <article>, <aside>, <footer>, etc.).

# Seções Obrigatórias:

## Cabeçalho (Header):

- Deve conter o logotipo (use um placeholder com a palavra ECOVIDA dentro de um <h1>) e o menu de navegação principal: Início, Notícias, Dicas, Receitas, Contato.

## Conteúdo Principal (Main):

- Seção Herói (Hero Section): Uma seção de destaque no topo da página com um título grande (<h2>) chamando o usuário, ex: "Bem-vindo ao Futuro Sustentável", e um breve subtítulo.

## Seção de Destaques (Featured Articles):

- Título da seção: Em Destaque.

- Exiba 3 artigos em destaque. Cada artigo deve ter:

- Uma imagem relacionada (use placeholders de tamanho uniforme, ex: 400x250px), Um título (<h3>), Um pequeno resumo (1 ou 2 linhas) e Um link "Leia Mais".

## Seção de Notícias Recentes (Latest News):

- Título da seção: Últimas Notícias.

- Exiba 6 notícias recentes. Cada notícia deve ter:

- Uma imagem menor (placeholder de tamanho uniforme, ex: 200x200px), Um título (<h3>), A data de publicação (use a tag <time>) e Um link "Leia Mais".

## Lateral (Aside):

- Esta seção deve ficar ao lado da "Seção de Notícias Recentes".

- Categoria "Sobre o Blog": Um pequeno texto de apresentação do EcoVida.

## Categoria "Newsletter": Um formulário simples para inscrição, contendo um campo para e-mail (placeholder="Seu e-mail") e um botão "Inscrever-se".

## Rodapé (Footer):

- Dividido em 3 colunas:

- Coluna 1: Um texto de copyright (ex: "© 2023 EcoVida. Todos os direitos reservados.").

- Coluna 2: Um menu de links rápidos (ex: Sobre Nós, Política de Privacidade, Termos de Uso).

- Coluna 3: Links para redes sociais (use ícones ou texto para Facebook, Instagram, Twitter). Os links podem ser placeholder (#).

# 3. Estilização Visual (CSS e Flexbox)
 Aplique CSS para criar um layout visualmente agradável e organizado. Use a metodologia Flexbox para posicionar e alinhar os elementos.

- Diretrizes de Estilo (A decisão final de cores e fontes é sua, mas siga estas regras):

- Paleta de Cores: Defina uma paleta baseada no tema "eco". Use pelo menos:

- Uma cor primária (ex: um verde para botões e destaques).

- Uma cor de fundo clara para o conteúdo.

- Uma cor de texto escura e legível.

- Cores de fundo alternadas para diferentes seções para dar respiro visual.

- Tipografia: Escolha duas fontes do Google Fonts: uma para os títulos e outra para o corpo do texto.

- Layout com Flexbox:

- O menu de navegação deve ser uma linha horizontal de itens, igualmente espaçados.

- A seção "Em Destaque" deve exibir os 3 artigos lado a lado, em uma linha.

- A área que contém a "Seção de Notícias Recentes" e a "Barra Lateral" (<aside>) deve ser uma flex container, onde as notícias ocupam mais espaço.

- A seção "Últimas Notícias" deve ser um grid de 2 colunas e 3 linhas (usando flexbox wrap ou CSS Grid, se souber) para organizar os 6 artigos.

- O rodapé deve ter suas 3 colunas lado a lado.

## Regras de Alinhamento:

- Todos os textos devem estar perfeitamente alinhados.

- As imagens dentro dos cards de artigo devem ser consistentes em tamanho e não distorcidas.

- Os botões e links devem ter um estilo consistente (padding, bordas, cores de hover).

# 4. O Desafio Final: Responsividade
- Esta é a parte mais importante. O site deve se adaptar a diferentes tamanhos de tela. Use media queries para aplicar as seguintes regras:

- Breakpoint para Tablets (max-width: 768px):

- A seção "Em Destaque" deve quebrar de 3 colunas para 2 colunas.

- A área principal (notícias + sidebar) deve quebrar para uma coluna. A barra lateral deve aparecer abaixo das notícias.

- O rodapé deve quebrar de 3 colunas para 2 colunas (a coluna de copyright pode ficar sozinha em uma nova linha ou você pode rearranjá-las).

- Breakpoint para Smartphones (max-width: 480px):

- O menu de navegação deve se transformar em um menu "hamburguer" vertical (simulado - você pode simplesmente empilhar os itens verticalmente e escondê-los, mostrando um ícone para abrir, ou apenas deixar os itens empilhados). Se for muito complexo, apenas empilhe os itens do menu verticalmente.

- A seção "Em Destaque" e a grid de "Últimas Notícias" devem se tornar uma única coluna.

- As imagens devem redimensionar para ocupar 100% da largura do container.

- O rodapé deve se tornar uma única coluna, com cada seção empilhada verticalmente.

# 5. Critérios de Avaliação
- Seu trabalho será avaliado com base nos seguintes pontos:

- HTML Semântico: Uso correto das tags section, article, header, footer, nav, etc.

- Organização e Estrutura: Código bem indentado, organizado e comentado (se necessário).

- Aplicação do Flexbox: Uso eficiente das propriedades do Flexbox para criar os layouts solicitados.

- Consistência Visual: Cores, fontes e espaçamentos harmoniosos e consistentes em toda a página.

- Responsividade: O site se adapta corretamente nos três breakpoints (Desktop, Tablet, Mobile) sem quebrar o layout ou dificultar a leitura.

- Mãos à obra! O sucesso do portal EcoVida depende do seu código.
