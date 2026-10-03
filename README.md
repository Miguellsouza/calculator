# 🧮 Calculadora

Uma calculadora web simples e elegante, com visual em *glassmorphism* sobre um fundo de montanhas em preto e branco.

## 🔗 Acesse o site

**👉 [https://miguellsouza.github.io/calculator/](https://miguellsouza.github.io/calculator/)**

## ✨ Funcionalidades

- Operações básicas: soma (`+`), subtração (`-`), multiplicação (`*`) e divisão (`/`)
- Números decimais com o botão de ponto (`.`)
- Botão **C** para limpar o visor
- Botão de **apagar** o último caractere digitado
- Botão **=** para calcular o resultado
- Visual com efeito de vidro (`backdrop-filter: blur`) e sombra suave

## 🛠️ Tecnologias

- **HTML5**: estrutura da página
- **CSS3**: estilização (flexbox, `backdrop-filter`, `box-shadow`)
- **JavaScript**: lógica da calculadora
- **[Font Awesome 7](https://fontawesome.com/)**: ícones dos botões

## 📁 Estrutura do projeto

```
calculator/
├── index.html                                      # Página principal e script
├── estilizacaocalculadora.css                      # Estilos da calculadora
├── background.jpg                                  # Imagem de fundo original
├── background_upscayl_3x_upscayl-standard-4x.png   # Fundo em alta resolução (usado no CSS)
└── logo.webp                                       # Ícone da aba (favicon)
```

## 🚀 Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/miguellsouza/calculator.git
   ```
2. Entre na pasta:
   ```bash
   cd calculator
   ```
3. Abra o arquivo `index.html` no navegador (basta dar dois cliques).

Não é necessário instalar nada. O projeto roda direto no navegador. Só é preciso conexão com a internet para carregar os ícones do Font Awesome.

## 💡 Ideias para melhorias futuras

- Substituir o `eval()` por um interpretador de expressões mais seguro
- Tratar expressões inválidas (ex.: `5++`) e divisão por zero
- Adicionar suporte ao teclado
- Incluir porcentagem, parênteses e histórico de cálculos
- Deixar o layout totalmente responsivo para celulares

## 👤 Autor

Feito por [@miguellsouza](https://github.com/miguellsouza).
