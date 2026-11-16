# Portfólio Pessoal - Desenvolvimento Web

**Aluno:** Jean Marco Carneiro
**Link do site publicado:** 

## 📝 Descrição do Portfólio
Este projeto consiste em uma página web responsiva desenvolvida como portfólio pessoal para apresentar minha trajetória, habilidades técnicas, projetos desenvolvidos e meios de contato profissional.

## 🚀 Tecnologias Utilizadas
* **HTML5:** Estruturação semântica do conteúdo.
* **CSS3:** Estilização personalizada, transições e animações.
* **Bootstrap 5:** Criação de layout responsivo, barra de navegação, cards e barras de progresso.
* **JavaScript:** Interatividade e validação no envio do formulário de contato.
* **GitHub Pages:** Hospedagem gratuita do site estático.

## ⚙️ Explicação do Funcionamento do Projeto
O site funciona como uma *Single Page Application* (página única) dividida em quatro seções principais:
1. **Menu de Navegação:** Fixado no topo (`sticky-top`), permite navegar rapidamente entre as seções com rolagem suave.
2. **Perfil:** Apresenta foto, nome, resumo profissional e botão de chamada para ação.
3. **Habilidades:** Exibe o nível de domínio nas ferramentas estudadas.
4. **Projetos:** Mostra uma galeria em grid com cartões descritivos dos trabalhos realizados.
5. **Contato:** Formulário funcional que exibe uma confirmação via JavaScript ao ser enviado, além de links para redes sociais.

## ✨ Recurso Novo Adicionado
Foram adicionados **dois recursos novos** além do modelo base visto em aula:
1. **Nova Seção de Habilidades:** Implementada com barras de progresso visuais para demonstrar o nível de conhecimento em cada tecnologia.
2. **Animações e Efeitos Visuais (`hover`):** Efeitos de elevação, sombra e escala nos cartões de projetos, foto de perfil e botões ao passar o mouse.

## 🛠️ Como o Recurso foi Implementado
* **Seção de Habilidades:** Utilizou-se o componente `progress` e `progress-bar` do Bootstrap 5 aliado ao sistema de grid (`container`, `row`, `col-md-8`).
* **Animações:** Foram criadas classes CSS personalizadas (`.card-projeto`, `.btn-animado` e `.foto-perfil`) utilizando a propriedade `transition` combinada com a pseudo-classe `:hover` e funções de `transform` (`translateY`, `scale` e `rotate`).
