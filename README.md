# Lazy Load com JavaScript

Este projeto demonstra a técnica de Lazy Loading em imagens utilizando JavaScript puro. O objetivo é carregar imagens em baixa resolução inicialmente e substituí-las por versões de alta qualidade quando entram na área visível da página.

## 🚀 Tecnologias Utilizadas

- **HTML5**: Estrutura da página.
- **CSS3**: Estilização da interface.
- **JavaScript**: Implementação do Lazy Load usando Intersection Observer.

## 🛠 Como Funciona

1. As imagens na página são carregadas com uma largura mínima (`w=10`), ou seja, em baixa qualidade.
2. Quando a imagem entra no campo de visão do usuário, o script substitui a URL da imagem para carregar uma versão em alta qualidade (`w=1000`).
3. Isso melhora o desempenho da página, reduzindo o tempo de carregamento inicial.


## 📷 Preview

![Uploading lazy-load-js.png…]()
