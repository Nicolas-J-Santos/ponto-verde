# 🌱 Ponto Verde

**Ponto Verde** é uma iniciativa de alunos da EACH-USP para conscientizar sobre o **descarte correto de lixo eletrônico** e divulgar **pontos de coleta**, principalmente na cidade de São Paulo.

🔗 **Site no ar:** https://nicolas-j-santos.github.io/ponto-verde/

O projeto nasceu na disciplina de **Resolução de Problemas** (EACH-USP, 2024), a partir da pesquisa *"A normalização da obsolescência programada e seus impactos no meio ambiente"*, orientada pela Profa. Claudia Ines Garcia.

## Por que isso importa

A obsolescência programada encurta a vida útil de celulares, computadores e outros aparelhos e aumenta o volume de lixo eletrônico. Descartados de forma incorreta, esses aparelhos liberam metais como chumbo, mercúrio, cádmio e lítio, que contaminam o solo e a água e fazem mal à saúde humana.

Contam como lixo eletrônico: celulares, computadores, pilhas, baterias, lâmpadas e outros aparelhos elétricos e eletrônicos.

## O que o projeto oferece

- 🗺️ **Lista de pontos de coleta no Google Maps**, para baixar pelo QR Code ou pelo botão do site: [abrir lista](https://maps.app.goo.gl/ptLif2sVixPEpRBQ7)
- 🌐 **Landing page**, a vitrine da iniciativa
- 📬 **Formulário de feedback**, para a comunidade sugerir novos pontos ou avisar sobre informações erradas

## Estrutura do repositório

```
ponto-verde/
├── index.html        # página principal
├── style.css         # estilos (cores e fontes do Figma)
├── faleconosco.php   # versão antiga do formulário (só funciona em servidor com PHP)
├── README.md
└── images/           # logo, QR Code, ondas, fotos dos fundadores e ícones
```

## Como rodar

O site é só HTML e CSS, então não precisa instalar nada:

1. Baixe ou clone o repositório:
   ```bash
   git clone https://github.com/Nicolas-J-Santos/ponto-verde.git
   ```
2. Abra o `index.html` no navegador.

Para publicar, dá para usar o **GitHub Pages**: *Settings → Pages → Branch: main → / (root)*.

## Formulário de feedback

O GitHub Pages não executa PHP, então o formulário usa o [FormSubmit](https://formsubmit.co), que encaminha as respostas para `pontoverde.ajuda@gmail.com`.

> ⚠️ Depois do **primeiro envio**, o FormSubmit manda um e-mail de ativação para `pontoverde.ajuda@gmail.com`. É só clicar no link uma vez.

O arquivo `faleconosco.php` foi mantido para quem hospedar o site num servidor com PHP. Nesse caso, troque o `action` do formulário no `index.html` para `faleconosco.php`.

## Design

- **Cores:** verde `#21763D`, verde claro `#64B57F`, creme `#FFFCEB`
- **Fontes:** [Bogart](https://www.cdnfonts.com/bogart-trial.font) (títulos) e [ABeeZee](https://fonts.google.com/specimen/ABeeZee) (textos)
- **Formas:** ondas e blobs gerados no [Haikei](https://haikei.app)
- O protótipo foi feito no Figma.

## Fundadores

| Nome | Perfil |
|---|---|
| Andressa Nardy | [LinkedIn](https://www.linkedin.com/in/andressa-nardy-503926245/) |
| Daniel Santos | [LinkedIn](https://www.linkedin.com/in/daniel-henrique-dos-santos-04ba24a2) |
| Nícolas Santos | [LinkedIn](https://www.linkedin.com/in/nicolas-josue-santos) |
| Rafael Rossi | [GitHub](https://github.com/Rafael-S-Rossi) |
| Victor Vendramel | [LinkedIn](https://www.linkedin.com/in/victor-sleiman-b098332b3) |

## Contato

Encontrou um ponto de coleta que não está na lista ou alguma informação errada? Use o formulário do site ou escreva para **pontoverde.ajuda@gmail.com**.
