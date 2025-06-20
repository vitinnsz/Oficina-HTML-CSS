# 🚀 Oficina de HTML & CSS para Professores | Prefeitura

## Construindo um Portfólio Digital do Zero (24/06/2025)

Sejam muito bem-vindos, educadores!

Este repositório contém o projeto que construiremos juntos em nossa oficina no dia **24 de junho**. O objetivo é dar o primeiro passo no universo do desenvolvimento web, criando uma página de portfólio moderna e funcional, utilizando apenas **HTML** e **CSS**.

Este projeto foi pensado para ser um ponto de partida claro e visualmente impactante. Ao final da nossa oficina, você não apenas terá esta página pronta, mas entenderá os blocos de construção fundamentais da web e estará capacitado(a) a personalizar e expandir seu próprio espaço digital.

[Prévia do Projeto](https://prnt.sc/anZgXbHqsBIO)(https://prnt.sc/anZgXbHqsBIO){ target="_blank" }

---

## 🎯 O que vamos aprender?

Analisando o código deste portfólio, vamos explorar conceitos essenciais para qualquer pessoa que queira criar para a web:

1.  **Estrutura com HTML Semântico**: Vamos entender como organizar o conteúdo de uma página usando tags como `<section>`, `<h1>`, `<p>`, `<img>` e `<a>`, dando significado e estrutura ao nosso site.

2.  **Estilização com CSS Inline**: Para este primeiro projeto, aplicaremos todo o nosso estilo diretamente no HTML (`style="..."`). Discutiremos as vantagens (simplicidade e tudo em um só lugar) e as desvantagens (manutenção e boas práticas) dessa abordagem, preparando o terreno para o próximo passo: folhas de estilo externas.

3.  **Layouts Modernos com Grid**: Veremos como a propriedade `display: grid` do CSS nos permite criar galerias de projetos alinhadas e responsivas de forma simples e poderosa.

4.  **Efeitos Visuais e Interatividade**: Aprenderemos a usar propriedades como `background`, `box-shadow`, `border-radius` e `linear-gradient` para criar um visual atraente. Além disso, adicionaremos um toque de interatividade com `hover` para dar vida aos elementos quando o usuário interage com eles.

5.  **Responsividade Básica**: Discutiremos o conceito por trás da tag `<meta name="viewport">` e como o layout com `grid-template-columns: repeat(auto-fit, ...)` já nos ajuda a ter um site que se adapta a diferentes tamanhos de tela.

---

## 💻 Como Executar o Projeto

Para visualizar este portfólio em sua máquina, siga os passos abaixo. É mais simples do que parece!

1.  **Crie uma pasta principal:** Em sua área de trabalho ou documentos, crie uma pasta chamada `meu-portfolio`.
2.  **Crie a pasta de recursos:** Dentro de `meu-portfolio`, crie outra pasta chamada `assets`. É aqui que você colocará suas imagens.
3.  **Adicione as imagens:** Baixe 3 ou 4 imagens de sua preferência (pode ser sua foto, imagens de projetos, etc.) e salve-as dentro da pasta `assets`. **Renomeie-as** para os nomes usados no código (`luizinho.jpeg`, `facial.jpg`, etc.) ou altere os nomes no código para corresponder aos seus arquivos.
4.  **Crie o arquivo HTML:** Dentro da pasta `meu-portfolio` (e fora da pasta `assets`), crie um arquivo de texto e salve-o com o nome `index.html`.
5.  **Copie e cole:** Abra o arquivo `index.html` com um editor de texto (como Bloco de Notas, VS Code, Sublime Text) e cole todo o código fornecido na oficina.
6.  **Abra no navegador:** Encontre o arquivo `index.html` em sua pasta e dê um duplo clique. Ele abrirá automaticamente no seu navegador padrão (Google Chrome, Firefox, etc.) e... *voilà*! Seu site está no ar (localmente)!

---

## 💡 Analisando o Código: A Anatomia de um Card de Projeto

Vamos quebrar um dos nossos "cards" de projeto para entender como HTML e CSS trabalham juntos.

```html
<div style="background:#121212; border-radius:12px; padding:20px; box-shadow:0 0 12px rgba(0,255,195,0.1); transition:0.3s ease;" onmouseover="this.style.transform='scale(1.03)'; this.style.boxShadow='0 0 25px rgba(0,255,195,0.3)'" onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 0 12px rgba(0,255,195,0.1)'">
    
    <img src="./assets/facial.jpg" alt="Projeto 1" style="width:100%; height:160px; object-fit:cover; border-radius:8px;">
    
    <h3 style="margin-top:15px;">Reconhecimento Facial com IA</h3>
    
    <p style="color:#aaa; font-size:14px;">Selecionado entre os 12 melhores na ProjWeek. Projeto com Python, HTML, ML do Facebook e Google Cloud.</p>

</div>
```

---

<p align="right"><sub>feito por: <a href="https://www.victordeveloper.com" target="_blank">www.victordeveloper.com</a></sub></p>