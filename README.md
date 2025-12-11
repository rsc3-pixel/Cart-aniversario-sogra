# Cartão de Aniversário Virtual

Um cartão de aniversário interativo desenvolvido com tecnologias Web, apresentando animações 3D CSS e efeitos de partículas com JavaScript.

## Sobre o Projeto

Este projeto consiste em uma página web estática que simula um cartão de aniversário físico. Ao ser clicado, o cartão realiza uma animação de "abertura" em 3D e dispara uma chuva de confetes virtuais. O objetivo foi criar uma experiência digital carinhosa e interativa para celebrar o aniversário de um ente querido.

## Tecnologias Utilizadas

* **HTML5:** Estrutura semântica.
* **CSS3:**
    * Flexbox para layout.
    * `transform-style: preserve-3d` e `perspective` para o efeito de virar a carta.
    * `@keyframes` para animações de flutuação e pulsação.
    * Variáveis CSS (`:root`) para fácil personalização de cores.
* **JavaScript (Vanilla):**
    * Manipulação do DOM para controle de classes (abrir/fechar).
    * **HTML5 Canvas API** para renderização e física das partículas de confete.

## Funcionalidades

* **Interatividade:** Clique para abrir/fechar o cartão.
* **Animação 3D:** Efeito realista de virada de página.
* **Sistema de Partículas:** Chuva de confetes coloridos gerada dinamicamente via Canvas quando o cartão abre.
* **Responsividade:** O Canvas se ajusta automaticamente ao redimensionar a janela.

## Como Usar / Personalizar

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SEU-USUARIO/NOME-DO-REPO.git](https://github.com/SEU-USUARIO/NOME-DO-REPO.git)
    ```

2.  **Edite a mensagem:**
    Abra o arquivo `index.html` e procure pela classe `.message-body` para alterar o texto de felicitações.

3.  **Personalize as cores:**
    No arquivo `index.html` (seção `<style>`), altere as variáveis na raiz:
    ```css
    :root {
        --primary-color: #d4a373; /* Cor dos títulos */
        --bg-color: #fce1e4;      /* Cor de fundo da página */
    }
    ```


