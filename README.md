# Aula 10 - Menu Dropdown com TailwindCSS

Este projeto demonstra a criação de um menu de navegação responsivo com dropdown utilizando TailwindCSS e ícones do Phosphor Icons. O objetivo é apresentar um cabeçalho moderno, com transições suaves e um menu suspenso estilizado.

## Funcionalidades

- **Menu de navegação responsivo**: Layout flexível, adaptável a diferentes tamanhos de tela.
- **Dropdown animado**: O menu "Serviços" exibe opções adicionais ao passar o mouse, com animação de transição.
- **Ícone animado**: O ícone de seta (arrow) gira suavemente 180° ao interagir com o dropdown.
- **Estilização com TailwindCSS**: Utilização de utilitários Tailwind para espaçamento, cores, fontes e efeitos.
- **Ícones modernos**: Uso do Phosphor Icons para ícones visuais no menu.

## Estrutura dos Arquivos

- `index.html`: Página principal contendo o cabeçalho, menu de navegação e estilos customizados.
- `tailwind.config.js`: Arquivo de configuração do TailwindCSS (caso queira customizar ainda mais as classes).
- `README.md`: Este arquivo de documentação.

## Como funciona o código

### 1. Inclusão de Dependências
- **TailwindCSS**: Importado via CDN para facilitar o uso das classes utilitárias.
- **Phosphor Icons**: Importado via CDN para uso dos ícones SVG.

### 2. Estrutura HTML
- O `<header>` contém o nome do site e o menu de navegação.
- O menu possui três opções: Home, Serviços (com dropdown) e Contato.
- O dropdown "Serviços" exibe uma lista de serviços ao passar o mouse.

### 3. Estilização e Animações
- **Dropdown**: O menu suspenso é inicialmente invisível e aparece com transição suave ao passar o mouse.
- **Cores e Sombras**: Utilização de gradientes, sombras e bordas arredondadas para um visual moderno.

### 4. Acessibilidade e Responsividade
- O layout utiliza classes do Tailwind para garantir espaçamento e alinhamento responsivo.
- O menu é facilmente adaptável para dispositivos móveis (pode ser expandido para mobile menu se necessário).

## Como executar

1. Basta abrir o arquivo `index.html` em qualquer navegador moderno.
2. Não é necessário instalar dependências locais, pois tudo é carregado via CDN.

## Personalização
- Para alterar as opções do menu, edite os itens dentro das tags `<ul class="dropdown-menu">`.
- Para mudar as cores ou adicionar mais efeitos, edite as classes Tailwind ou o bloco `<style>` no `<head>`.

## Créditos
- [TailwindCSS](https://tailwindcss.com/)
- [Phosphor Icons](https://phosphoricons.com/)

---

Sinta-se à vontade para customizar este template para seus próprios projetos!