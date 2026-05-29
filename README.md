# TechPortal

Portal de notícias tecnológicas desenvolvido como atividade avaliativa da disciplina de Design de Interfaces para a Web Mobile no IFNMG — Campus Montes Claros.

## 🛠️ Tecnologias utilizadas

- HTML5 semântico
- CSS3 puro (sem bibliotecas externas)

## 📐 Técnicas aplicadas

- **Mobile-First**: CSS base construído para smartphones, com Media Queries expandindo para desktop
- **CSS Grid**: seção de destaques com layout assimétrico — notícia principal ocupa duas linhas e uma coluna maior
- **Flexbox**: listagem de notícias secundárias com `flex-wrap: wrap` e `flex: 1 1 250px`
- **clamp()**: tipografia fluida nos títulos das notícias principais
- **vmin**: padding do cabeçalho dimensionado em unidade de viewport
- **box-sizing: border-box**: prevenção de scroll horizontal

## 📱 Responsividade

| Tela | Comportamento |
|------|--------------|
| Mobile (< 1024px) | Layout em coluna única, cards empilhados |
| Desktop (≥ 1024px) | Grid assimétrico, navbar horizontal |

## 👨‍💻 Autor

Bryan — bkjs@aluno.ifnmg.edu.br
