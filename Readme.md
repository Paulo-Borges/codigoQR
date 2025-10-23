# 🔗 Cartão QR Code

Um projeto simples de cartão de QR Code desenvolvido como um desafio do **Frontend Mentor**.

Este projeto demonstra habilidades básicas de **HTML** e **CSS** para criar um componente de cartão responsivo e visualmente agradável.

## 🚀 Tecnologias Utilizadas

- **HTML5:** Estrutura semântica da página.
- **CSS3:** Estilização, layout (Flexbox) e responsividade básica.
- **Fontes do Google:** Utilização da fonte `Outfit`.

---

## ✨ Funcionalidades

- **Design Responsivo:** O cartão é centralizado e se ajusta bem em diferentes tamanhos de tela.
- **Estilização:** Aplicação de sombras, bordas arredondadas e uso de cores baseadas nas especificações do desafio.
- **Fontes Personalizadas:** Importação de fontes para um design consistente.

---

## 🎨 Design e Estrutura

### Cores

O projeto utiliza as seguintes cores primárias e neutras (conforme as especificações do Frontend Mentor):

- **Cor Principal do Título (Dark Blue):** `hsl(218, 44%, 22%)`
- **Cor do Texto Secundário (Grayish Blue):** `hsl(220, 15%, 55%)`
- **Cor de Fundo (Light Gray):** `hsl(212, 45%, 89%)`
- **Cor de Fundo do Cartão (White):** `hsl(0, 0%, 100%)`

### Fontes

- **Família:** `Outfit`, sans-serif
- **Pesos:** 400 (regular) e 700 (negrito)

### 📂 Estrutura do Arquivo

/ ├── index.html ├── style.css ├── image-qr-code.png └── README.md

---

## 🖥️ Preview (Visualização)

_Insira uma imagem ou GIF da sua aplicação final aqui._

---

## ⚙️ Código e Estilo (Trechos Relevantes)

### HTML (`index.html`)

A estrutura é simples, usando classes para organizar o layout.

```html
<div class="container">
  <div class="base">
    <div class="imagem">
      <img src="image-qr-code.png" alt="QR Code" />
    </div>

    <p class="principal">Improve your front-end skills by building projects</p>
    <p class="secundario">
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </div>
</div>
CSS (style.css) O body ou o elemento principal (que no seu caso é .container) é
centralizado usando Flexbox, e o cartão (.base) recebe as definições de tamanho
e estilo. CSS .container { /* Centraliza o cartão vertical e horizontalmente na
tela */ max-width: 90rem; display: flex; background-color: hsl(212, 45%, 89%);
justify-content: center; align-items: center; /* Margem para simular
centralização na view */ margin: 6.25rem auto; } .base { width: 18.75rem; /*
Largura fixa do cartão */ background: hsl(0, 0%, 100%); border-radius: 20px;
padding: 15px 5px 25px 5px; box-shadow: 1px 2px 10px hsl(220, 15%, 55%); } img {
width: 90%; /* QR Code ocupa 90% da largura do cartão */ margin: 0 auto;
border-radius: 10px; } .principal { color: hsl(218, 44%, 22%); font-weight: 700;
font-size: 20px; } /* ... Estilos Secundários ... */ 🤝 Contribuições Sinta-se à
vontade para sugerir melhorias, como otimizações de CSS ou melhorias de
acessibilidade. Faça um Fork do projeto. Crie uma Branch para sua feature (git
checkout -b feature/melhoria). Faça o Commit de suas alterações (git commit -m
'feat: Adiciona nova feature'). Faça o Push para a Branch (git push origin
feature/melhoria). Abra um Pull Request. 📝 Licença Este projeto está sob a
licença MIT. Veja o arquivo LICENSE (se existir) para mais detalhes.
```
