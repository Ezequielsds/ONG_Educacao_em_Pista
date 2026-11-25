# Educação em Pista

Protótipo acadêmico de site institucional, inspirado no [Instituto Ayrton Senna](https://institutoayrtonsenna.org.br/) (ONG real, fundada em novembro de 1994).

> **Aviso:** este projeto é um trabalho de faculdade e não representa o site oficial do Instituto Ayrton Senna. Não recebe doações, não coleta dados e não envia mensagens de verdade.

## Integrantes

- Caio Santos Alencar - 47052830
- Davi de Souza - 47169826
- Ezequiel Soares da Silva - 47205521
- Gabriel Ferraz Aguiar Tricai - 47142014
- Italo Guilherme Silva Nunes - 47189771

## Objetivo

Divulgar a causa da educação pública e os programas Se Liga, Acelera Brasil e Fórmula da Vitória, em um site responsivo e interativo feito só com HTML, CSS e JavaScript básico.

## Ideia visual

O site usa o universo do automobilismo, ligado à história de Ayrton Senna: as cores do capacete (amarelo, verde e azul), a faixa quadriculada de chegada e um circuito cujas curvas representam etapas da educação.

## Páginas

| Arquivo | Conteúdo |
|---|---|
| `index.html` | Causa, motivo da educação, três programas e botão "Como posso participar?" |
| `sobre.html` | História (linha do tempo), missão, público atendido e objetivos |
| `projetos.html` | Três programas reais, cada um com imagem e forma de a comunidade contribuir |
| `contato.html` | Formulário com validação, orientações de participação e aviso de envio simulado |

## Funcionalidades em JavaScript

Duas funcionalidades, cada uma em seu arquivo (`js/participacao.js` e `js/formulario.js`):

1. **Interação adicional:** na página inicial, o botão "Como posso participar?" mostra e esconde um painel. O texto do botão muda a cada clique.
2. **Formulário validado:** na página de contato, o evento `submit` é tratado com `addEventListener()` e `preventDefault()`. O código confere nome (3+ caracteres), e-mail válido, assunto preenchido e mensagem (10+ caracteres, depois de `trim()`). O erro ou a confirmação aparece na própria página. A confirmação é simulada: nada é enviado nem guardado.

## Estrutura de arquivos

```
ONG_Educacao_em_Pista/
├── index.html
├── sobre.html
├── projetos.html
├── contato.html
├── css/
│   └── estilos.css
├── js/
│   ├── participacao.js
│   └── formulario.js
├── img/          (pista.svg e três ilustrações das frentes)
├── GUIA_APRESENTACAO.md
└── README.md
```

## Como executar

1. Baixe ou clone o repositório (ou descompacte o ZIP).
2. Abra o `index.html` no navegador.
3. Use o menu para navegar entre as páginas.

Não precisa instalar nada. A fonte usada é Arial, disponível no computador. Não há dependências.

## Tecnologias

- HTML5 semântico
- CSS3 (Flexbox, `box-sizing` e `@media`)
- JavaScript básico (funções, if/else, eventos e DOM)

## Fontes e créditos

- [Site oficial do Instituto Ayrton Senna](https://institutoayrtonsenna.org.br/)
- Relatórios anuais do Instituto (2023 e 2024), publicados no site oficial: fundação em 1994, missão, frentes de atuação e eduLab21.
- Propmark, "Instituto Ayrton Senna comemora 30 anos com filme narrado por Galvão Bueno" (2024): dados dos 30 anos (mais de 36 milhões de atendimentos em mais de 3 mil cidades).
- Textos escritos pela equipe a partir das fontes acima, com palavras próprias. Os números são os divulgados pelo Instituto e podem ter sido atualizados.
- Ilustrações em `img/`: arte vetorial (SVG) original, criada para este projeto.

### Fontes dos três programas

Consultadas em 29/10/2026. Os textos são resumos; as sugestões de participação são orientações do protótipo, não ofertas oficiais de vagas.

- [Se Liga](https://institutoayrtonsenna.org.br/o-que-fazemos/disseminacao-escala/se-liga/)
- [Acelera Brasil](https://institutoayrtonsenna.org.br/o-que-fazemos/disseminacao-escala/acelera-brasil/)
- [Fórmula da Vitória](https://institutoayrtonsenna.org.br/o-que-fazemos/disseminacao-escala/formula-da-vitoria/)

## Versão simplificada

CSS com cores diretas, fonte Arial e blocos numerados. Cada funcionalidade tem um arquivo JavaScript próprio, carregado apenas na página em que é usada. Veja o [GUIA_APRESENTACAO.md](GUIA_APRESENTACAO.md) para estudar o código.
