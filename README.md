# ⚙️ My User Settings & Development Environment / Meus User Settings & Ambiente de Desenvolvimento

[English](#-english-version) | [Português](#-versão-em-português)

---

# 🇺🇸 English Version

This repository stores my personal **VS Code** configuration settings (`settings.json`), tailored for a development workflow focused on **C#** and **TypeScript**, prioritizing a highly minimalist, distraction-free interface with full focus on pure code.

---

## 🎨 Workflow & Style

The goal of these settings is to eliminate visual clutter and maximize screen space:
* **Minimalist Interface:** Activity bar moved to the bottom, no status bar, no minimap, no vertical scrollbars, no cluttered indentation guides, using the native **Dark Modern (Dark 2026)** color theme combined with the **Symbols** icon theme.
* **Focus & Performance:** AI tools and built-in chats completely disabled for a clean, manual coding experience.
* **Typography & Layout:** **JetBrains Mono** font at a large size (`18`), with a strict line width limit (`110` columns) guided by visual rulers and auto-wrapping. *(Note: You need to have the JetBrains Mono font installed on your system)*.
* **Automation:** Auto-save (`afterDelay`), auto-format on save (`formatOnSave`), and clean inline error handling via **ErrorLens** (focused strictly on critical errors).

---

## 🔌 Required Extensions & Prerequisites

To make your environment look and feel exact, make sure you have:

1. **Font:** Download and install [JetBrains Mono](https://www.jetbrains.com/lp/mono/) on your operating system.
2. **[C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)** (`ms-dotnettools.csdevkit`) — Complete support and code formatting for C#.
3. **[Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)** (`esbenp.prettier-vscode`) — Default code formatter for TypeScript and JavaScript.
4. **[ErrorLens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)** (`usernamehw.errorlens`) — Highlights compilation and linting errors directly on the code line.
5. **[Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols)** (`miguelsolorio.symbols`) — Clean and elegant file icon theme.

---

## 🚀 How to Apply and Run

To apply this style and configuration to your VS Code, follow these steps:

### 1. Clone or download the repository
Clone this repository to your local machine or copy the configuration file.

### 2. Locate your VS Code settings folder
The VS Code `settings.json` file is located based on your operating system:
* **Windows:** `%APPDATA%\Code\User\settings.json`
* **macOS:** `$HOME/Library/Application Support/Code/User/settings.json`
* **Linux:** `$HOME/.config/Code/User/settings.json`

*(Quick tip: In VS Code, open settings by pressing `Ctrl + Shift + P` (or `Cmd + Shift + P` on Mac), type **"Preferences: Open User Settings (JSON)"**, and press Enter)*.

### 3. Update Settings
Replace the content of your local `settings.json` with the file from this repository (it includes `"workbench.iconTheme": "symbols"`).

### 4. Install Extensions via Terminal
If you prefer installing all extensions at once using your terminal, run:

```bash
code --install-extension ms-dotnettools.csdevkit
code --install-extension esbenp.prettier-vscode
code --install-extension usernamehw.errorlens
code --install-extension miguelsolorio.symbols
```

You are all set!

---

<a name="versão-em-português"></a>
# 🇧🇷 Versão em Português

Este repositório armazena as minhas configurações pessoais de **VS Code** (`settings.json`), ajustadas para um fluxo de desenvolvimento focado em **C#** e **TypeScript**, priorizando uma interface altamente minimalista, sem distrações e com foco total no código puro.

---

## 🎨 Fluxo de Trabalho e Estilo

O objetivo destas configurações é eliminar a poluição visual e maximizar o espaço da tela:
* **Interface Minimalista:** Barra de atividades movida para a parte inferior, sem barra de status, sem minimapa, sem barras de rolagem verticais, sem guias de indentação poluídas, utilizando o tema de cores nativo **Dark Modern (Dark 2026)** combinado com o tema de ícones **Symbols**.
* **Foco e Desempenho:** Ferramentas de IA e chats integrados completamente desativados para uma experiência de codificação limpa e manual.
* **Tipografia e Layout:** Fonte **JetBrains Mono** em tamanho grande (`18`), com limite rígido de largura de linha (`110` colunas) orientado por réguas visuais e quebra automática. *(Nota: é necessário ter a fonte JetBrains Mono instalada no seu sistema)*.
* **Automação:** Salvamento automático (`afterDelay`), formatação automática ao salvar (`formatOnSave`) e tratamento de erros limpo e direto na linha via **ErrorLens** (focado estritamente em erros críticos).

---

## 🔌 Extensões e Pré-requisitos Necessários

Para que o seu ambiente fique com a aparência e o comportamento exatos, certifique-se de ter:

1. **Fonte:** Baixe e instale a [JetBrains Mono](https://www.jetbrains.com/lp/mono/) no seu sistema operacional.
2. **[C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)** (`ms-dotnettools.csdevkit`) — Suporte completo e formatação de código para C#.
3. **[Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)** (`esbenp.prettier-vscode`) — Formatador de código padrão para TypeScript e JavaScript.
4. **[ErrorLens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)** (`usernamehw.errorlens`) — Destaca erros de compilação e de linting diretamente na linha do código.
5. **[Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols)** (`miguelsolorio.symbols`) — Tema de ícones de arquivo limpo e elegante.

---

## 🚀 Como Aplicar e Executar

Para aplicar este estilo e configuração ao seu VS Code, siga estes passos:

### 1. Clone ou baixe o repositório
Clone este repositório na sua máquina local ou copie o arquivo de configuração.

### 2. Localize a pasta de configurações do VS Code
O arquivo `settings.json` do VS Code fica localizado dependendo do seu sistema operacional:
* **Windows:** `%APPDATA%\Code\User\settings.json`
* **macOS:** `$HOME/Library/Application Support/Code/User/settings.json`
* **Linux:** `$HOME/.config/Code/User/settings.json`

*(Dica rápida: No VS Code, abra as configurações pressionando `Ctrl + Shift + P` (ou `Cmd + Shift + P` no Mac), digite **"Preferences: Open User Settings (JSON)"** e pressione Enter)*.

### 3. Atualize as Configurações
Substitua o conteúdo do seu `settings.json` local pelo arquivo deste repositório (ele inclui `"workbench.iconTheme": "symbols"`).

### 4. Instale as Extensões via Terminal
Se preferir instalar todas as extensões de uma só vez pelo terminal, execute:

```bash
code --install-extension ms-dotnettools.csdevkit
code --install-extension esbenp.prettier-vscode
code --install-extension usernamehw.errorlens
code --install-extension miguelsolorio.symbols
```

Pronto, seu ambiente está configurado!
