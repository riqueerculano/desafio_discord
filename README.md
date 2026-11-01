# 🎮 Discord Landing Page - Desafio CSS Responsivo

Desafio da DIO - Um clone responsivo da página inicial do Discord desenvolvido com **HTML5** e **CSS3**, focando na aplicação prática de **CSS Grid Layout**, **Flexbox** e **Mobile First**. Projeto desenvolvido como parte do desafio prático da [Digital Innovation One (DIO)](https://www.dio.me/).

---

## 📌 Sobre o Projeto

O objetivo deste projeto foi recriar a estrutura visual da landing page do Discord, aplicando conceitos modernos de layout web, organização de componentes HTML semânticos e responsividade para diferentes tamanhos de tela.

### 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação semântica do conteúdo (`header`, `main`, `section`, `picture`, `footer`).
- **CSS3**:
  - **CSS Grid Layout**: Utilizado no alinhamento bidimensional fluído das seções de conteúdo no desktop.
  - **Flexbox**: Utilizado na organização do hero header, botões de ação e cartões de conteúdo.
  - **Media Queries**: Responsividade adaptada para desktop, tablet e dispositivos móveis.
  - **Variáveis CSS (`:root`)**: Padronização da paleta de cores e tipografia.
- **Google Fonts**: Tipografia com as fontes *Luckiest Guy* e *Open Sans*.

---

## 📐 Estrutura do Layout

- **Cabeçalho / Hero (`.hero`)**: Estruturado com Flexbox, apresentando a chamada principal, texto explicativo e botões de download e acesso rápido.
- **Seções de Conteúdo (`.feature-card`)**: Organizadas com CSS Grid no desktop para exibir alternadamente imagens explicativas e textos informativos.
- **Seção de Destaque (`.feature-highlight`)**: Apresentação centralizada da tecnologia de voz e vídeo com imagem expandida.
- **Rodapé (`.footer`)**: Seção final responsiva contendo a marca e informações institucionais.

---

## 📱 Responsividade

A página adapta-se dinamicamente conforme a largura da viewport seguindo a metodologia Mobile First:

- **< 1000px**: Layout em coluna única, botões ajustados à largura da tela e imagens alinhadas ao centro.
- **>= 1000px**: Grade em duas colunas (`grid-template-columns`), inversão alternada da ordem de texto/imagem e botões organizados em linha.

---

## 📸 Demonstração

🔗 [Clique aqui para visualizar o projeto online](https://riqueerculano.github.io/desafio_discord/)

---

## 🚀 Como Executar o Projeto

Clone este repositório:

```bash
git clone https://github.com/riqueerculano/desafio_discord.git
```

Navegue até a pasta do projeto:

```bash
cd seu-repositorio
```

Abra o arquivo `index.html` no seu navegador de preferência.

---

Feito por Henrique Erculano
