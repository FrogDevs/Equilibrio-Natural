# Equilíbrio Natural - Website

[![Languages](https://img.shields.io/github/languages/count/FrogDevs/Equilibrio-Natural)](https://github.com/FrogDevs/Equilibrio-Natural-Website)
[![TopLanguage](https://img.shields.io/github/languages/top/FrogDevs/Equilibrio-Natural)](https://github.com/FrogDevs/Equilibrio-Natural-Website)
[![Files](https://img.shields.io/github/directory-file-count/FrogDevs/Equilibrio-Natural)](https://github.com/FrogDevs/Equilibrio-Natural-Website)
[![RepoSize](https://img.shields.io/github/repo-size/FrogDevs/Equilibrio-Natural)](https://github.com/FrogDevs/Equilibrio-Natural-Website)
[![LinesCode](https://img.shields.io/tokei/lines/github/FrogDevs/Equilibrio-Natural)](https://github.com/FrogDevs/Equilibrio-Natural-Website)
[![MIT License](https://img.shields.io/github/license/FrogDevs/Equilibrio-Natural)](https://choosealicense.com/licenses/mit/)
![Logos](https://i.imgur.com/E5pg9Hj.png)

[**>>> Read also in English**](en_readme.md)

Site de divulgação para a empresa Equilíbrio Natural. Landing page em formato SPA (Single Page Application) com informações importantes sobre a empresa, como, formas de contato e disponibilidade de produtos em loja.

## Captura de tela

![App Screenshot](https://i.imgur.com/e1wDuUZ.png)

## Apêndice

* [Agradecimentos](#agradecimentos)
* [Atribuições](#atribuições)
* [Recursos](#recursos)
* [Tech Stack](#tech-stack)
* [Lições Aprendidas](#lições-aprendidas)
* [Otimizações](#otimizações)
* [Demo](#demo)
* [Rodar localmente](#rodar-localmente)
* [Usado por](#usado-por)
* [Relacionados](#relacionados)
* [Membro responsável](#membro-responsável)
* [Licença](#licença)

## Agradecimentos

Deixamos essa dedicatória a empresa Equilíbrio Natural a qual confiou em nossas habilidades para divulgação, gestão e automação de seu empreendimento. E a ETEC Jardim Ângela por nos proporcionar a busca pelo conhecimento necessário na realização desse trabalho.

## Atribuições:

- [unDraw](https://undraw.co)
- [Desing no Figma](https://www.figma.com/community/file/1183921990401059288)
- [Formsubmit](https://formsubmit.co/)
- [Netlify](https://www.netlify.com/)
- [Unsplash: Primeira imagem](https://unsplash.com/photos/fb7yNPbT0l8)
- [Unsplash: Segunda imagem](https://unsplash.com/photos/1DMNn6gBbwQ)

## Recursos

- ✨ Cards interativos
- 📧 Envio de e-mail
- 🔎 Consulta de lojas físicas
- 🔗 Integração com o [App](https://github.com/FrogDevs/Equilibrio-Natural-ControleEstoque)
- 🛍️ Disponibilidade de produtos

## Tech Stack

**Front-end:** [Vite](vitejs.dev), [Vue](vuejs.org) e [TailwindCSS](tailwindcss.com)

**Back-end:** [Vue Router](router.vuejs.org) e [Firebase](https://firebase.google.com)

## Lições aprendidas

**Quais desafios foram enfrentados e como foram sobressaídos?**

Integrar a API Firestore Database no projeto. A maneira encontrada de incluir dados em tempo real vindos da database foi instalando o SDK do Firebase/Firestore e usando o método ```onSnapshot()```.

## Otimizações

**Que otimizações foram feitas no código?**

O gerenciador de pacotes **Pnpm** foi escolhido para o projeto por oferecer *cold e hot cache*. Pnpm é 3x mais rápido e eficiente do que o Npm e mais rápido do que o Yarn. Lidar com inúmeras bibliotecas e módulos foi uma tarefa mais fácil e segura com essa ferramenta.

**Vite** é uma ferramenta com a utilidade de cuidar do bundle da aplicação. Fornece melhores técnicas de otimização, resultando em uma maior performance na aplicação tanto em forma de desenvolvimento quanto de produção para o usuário final.

Ao construir aplicações com um bundler, o pacote JavaScript pode tornar-se bastante grande, e assim afetar o tempo de carregamento da página. É mais eficiente dividir os componentes de cada rota em pedaços separados, e só os carregarmos quando a rota for visitada. Tendo em vista isso, foi usado uma técnica conhecida como *Lazy Load Routes*. **Vue Router** oferece suporte nativo a técnica. [Leia mais.](https://router.vuejs.org/guide/advanced/lazy-loading.html)

O site foi construido usando o conceito de *Mobile First*. Esse conceito se refere a criação de qualquer projeto que prioriza a experiência em dispositivos móveis, enquanto são feitas adaptações para resoluções maiores. Isso permite que o site seja completamente responsivo e adaptável a outras resoluções de telas, permitindo uma maior inclusão de clientes.

## Demo

Utilizamos a Netlify para a implementação online do site

- [Deploy](https://equilibrionatural.netlify.app)
- [Deploy para o TCC (banco de dados alternativo)](https://equilibrionaturaltcc.netlify.app)

## Rodar localmente

***Nota**: É necessário pussuir o gerenciador de pacotes Pnpm. [Veja como instalar.](https://pnpm.io/installation)*

Clone o projeto

```bash
  git clone https://github.com/FrogDevs/Equilibrio-Natural-Website.git
```

Vá ao diretório do projeto

```bash
  cd Equilibrio-Natural-Website
```

Instale as depêndencias

```bash
  pnpm i
```

Inicie o servidor

```bash
  pnpm dev
```

## Usado por

Este projeto é usado pela seguinte companhia

- [Equilíbrio Natural](https://equilibrionatural.netlify.app)

## Relacionados

Veja outro projeto relacionado

- [Equilíbrio Natural - Controle de Estoque](https://github.com/FrogDevs/Inventory-Control)

## Membro responsável

- **Web Design e Front-end:** [@viniciuscosta](https://vinicius-costa-links.vercel.app)

## Licença

- [MIT](LICENSE)<br><br>

<p align="right">“Você deve ter paixão por uma ideia ou problema que quer resolver. Se você não tem paixão suficiente desde o começo, não vai aguentar a pressão.”</p>
<p align="right">Steve Jobs</p>
