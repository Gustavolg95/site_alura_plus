# 📺 Alura Plus

Site promocional responsivo da **Alura Plus** — plataforma de cursos de tecnologia e idiomas — desenvolvido durante curso da [Alura](https://www.alura.com.br/).

---

## 📸 Visão Geral

Landing page que apresenta os planos de assinatura da Alura Plus, incluindo o **Combo+** (Alura+ e Alura Língua), com seções que destacam compatibilidade de dispositivos, funcionalidades e informações de assinatura.

---

## ✨ Funcionalidades

- Layout em grid de duas colunas para as seções de conteúdo
- Design totalmente **responsivo** (adaptado para mobile, tablet e desktop)
- Efeitos de hover nos botões e links
- Variáveis CSS para fácil manutenção de cores e fontes
- Imagem de fundo na seção principal
- Footer com links institucionais

---

## 🗂️ Estrutura do Projeto

```
AluraPlus/
│
├── index.html          # Estrutura da página
├── styles.css          # Estilos e responsividade
│
└── imagens/
    ├── Background.png  # Imagem de fundo da seção principal
    ├── Combo.png        # Logo do Combo+
    ├── Plataformas.png  # Dispositivos com Alura+ aberto
    ├── Telas.png        # Telas do Alura+ e Alura Língua
    ├── Notebook.png     # Notebook com curso aberto
    ├── Logo.png         # Logo da Alura+ (footer)
    ├── tv.png           # Ícone de TV
    ├── computador.png   # Ícone de computador
    └── celular.png      # Ícone de celular/tablet
```

---

## 🎨 Design System

As cores e fontes são gerenciadas via variáveis CSS:

| Variável | Valor | Uso |
|---|---|---|
| `--cor-de-fundo` | `#00030C` | Background da página |
| `--branco-principal` | `#FFFFFF` | Textos e títulos |
| `--cinza-secundario` | `#C0C0C0` | Textos secundários |
| `--botão-azul` | `#167BF7` | Botão primário |
| `--botao-azul-efeito` | `#0fcef5` | Hover do botão |
| `--fonte_principal` | `Inter` | Fonte base |

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (Grid, Flexbox, variáveis CSS, media queries)
- Google Fonts (Inter)

---

## 📱 Responsividade

O layout se adapta em dois breakpoints:

- **≤ 768px** — colunas colapsam para uma coluna, imagens se ajustam, footer empilhado
- **≤ 480px** — fontes reduzidas para melhor leitura em telas pequenas

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/alura-plus.git
   ```

2. Abra o arquivo `index.html` diretamente no navegador ou use o **Live Server** no VS Code.

> Nenhuma dependência ou instalação necessária.
