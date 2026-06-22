# 🛡️ Gerador de Senhas Seguras

Uma aplicação web simples, rápida e extremamente segura para geração de senhas aleatórias fortes. Construída puramente com HTML, CSS e JavaScript Vanilla.

## ✨ Funcionalidades
- **Segurança Avançada:** Utiliza a API nativa `window.crypto` do navegador, garantindo que a aleatoriedade seja criptograficamente segura.
- **Complexidade Forçada:** Cada senha gerada possui obrigatoriamente letras maiúsculas, minúsculas, números e caracteres especiais.
- **Ajuste de Tamanho:** Permite escolher dinamicamente o tamanho da senha entre 8 e 32 caracteres usando um slider intuitivo.
- **Cópia com um Clique:** Botão integrado para copiar a senha gerada diretamente para a área de transferência.
- **Interface Responsiva:** Visual moderno construído com foco no Modo Escuro (Dark Mode), totalmente adaptável para dispositivos móveis e desktops.

## 🚀 Como Executar o Projeto

Como o projeto utiliza apenas arquivos estáticos do ecossistema Web tradicional, você não precisa instalar nenhuma dependência.

1. Faça o clone deste repositório ou baixe os arquivos.
2. Abra o arquivo `index.html` diretamente em qualquer navegador web (Chrome, Firefox, Edge, Safari, etc.).

## 🔒 Por que este gerador é seguro?
Ao contrário de scripts comuns que usam `Math.random()` (que é previsível e inadequado para segurança), este projeto implementa a API **Web Crypto (`crypto.getRandomValues`)**. Isso significa que os números gerados provêm de fontes de entropia do hardware do sistema operacional, inviabilizando ataques de engenharia reversa para adivinhar os padrões das senhas geradas.

## 🛠️ Tecnologias Utilizadas
- HTML5
- CSS3 (Variáveis CSS, Flexbox, UI Dark)
- JavaScript Vanilla (Web Crypto API)

---
Desenvolvido para fins de segurança e praticidade. Sinta-se livre para clonar e hospedar no seu GitHub Pages!
