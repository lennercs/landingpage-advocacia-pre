# ⚖️ Advocacia Previdenciária

Um site institucional, elegante e totalmente responsivo desenvolvido para a **Dra.**, advogada especialista em Direito Previdenciário. O projeto foi estruturado com foco em conversão (Landing Page), permitindo que potenciais clientes conheçam as áreas de atuação e agendem consultas facilmente.

---

## 📱 Demonstração do Layout

O design foi construído pensando na experiência do usuário (UX), garantindo uma navegação fluida tanto em computadores quanto em dispositivos móveis (Mobile First/Responsivo).

* **Topo Premium:** Barra de navegação fixa com efeito de vidro fosco (`backdrop-filter`) e menu hambúrguer nativo para celulares.
* **Cards de Serviços:** Grid moderno que se adapta automaticamente, organizando as áreas de atuação de 2 em em 2 nas telas menores.
* **Seções de Conversão:** CTAs (Call to Action) estratégicos direcionando o usuário para o atendimento via WhatsApp.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando tecnologias web nativas, garantindo leveza, alta performance e um carregamento extremamente rápido:

* **HTML5:** Estruturação semântica de todas as seções (Nav, Main, Header, Section, Footer).
* **CSS3:** Estilização avançada utilizando variáveis globais (`:root`), layouts modernos com **CSS Grid** e **Flexbox**, além de `@media queries` para total responsividade.
* **JavaScript (Vanilla):** Lógica nativa para controle de estado do menu mobile (abrir/fechar), sem a necessidade de bibliotecas externas pesadas.

---

## ⚙️ Funcionalidades Destaque (Código Nativo)

### 📌 Menu Hambúrguer Inteligente
Em vez de utilizar frameworks, o menu mobile foi desenvolvido manipulando diretamente o DOM (Document Object Model) através do método `classList.toggle('active')`. Isso garante que o site permaneça leve e limpo.

### 📊 Grid Responsivo Dinâmico
Utilização da propriedade `grid-template-columns: repeat(auto-fit, minmax(140px, 1fr))` para fazer com que os cards de serviços se organizem perfeitamente em duplas em telas pequenas, aproveitando ao máximo o espaço vertical do celular.

---

## ✒️ Desenvolvedor

* **Lenner Cristian** - *Desenvolvimento Fullstack* - [Meu GitHub](https://github.com/)
