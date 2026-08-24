# ⚙️ My User Settings & Development Environment / Meus User Settings & Ambiente de Desenvolvimento

[English](#english) | [Português](#português)

---

<a name="english"></a>
# 🇺🇸 English Version

This repository stores my personal **VS Code** configuration settings (`settings.json`), tailored for a development workflow focused on **C#** and **TypeScript**, prioritizing a highly minimalist, distraction-free interface with full focus on pure code.

---

## 🎨 Workflow & Style

The goal of these settings is to eliminate visual clutter and maximize screen space:
* **Minimalist Interface:** Activity bar moved to the bottom, no status bar, no minimap, no vertical scrollbars, no cluttered indentation guides, powered by **Min Theme** combined with the **Symbols** icon theme (both created by Miguel Solorio).
* **Focus & Performance:** AI tools and built-in chats completely disabled for a clean, manual coding experience.
* **Typography & Layout:** **JetBrains Mono** font at a large size (`18`), with a strict line width limit (`110` columns) guided by visual rulers and auto-wrapping.
* **Automation:** Auto-save (`afterDelay`), auto-format on save (`formatOnSave`), and clean inline error handling via **ErrorLens** (focused strictly on critical errors).

---

## 🔌 Required Extensions

To make your environment look and feel exact, install the following extensions in VS Code:

1. **[C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)** (`ms-dotnettools.csdevkit`) — Complete support and code formatting for C#.
2. **[Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)** (`esbenp.prettier-vscode`) — Default code formatter for TypeScript and JavaScript.
3. **[ErrorLens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)** (`usernamehw.errorlens`) — Highlights compilation and linting errors directly on the code line.
4. **[Min Theme](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.min-theme)** (`miguelsolorio.min-theme`) — Minimalist dark/light color theme.
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

*(Quick tip: In VS Code, open settings by pressing `Ctrl + Shift + P` (or `Cmd + Shift + P` on Mac), type **"Preferences: Open User Settings (JSON)"**, and press Enter).*

### 3. Update Settings
Make sure your `settings.json` includes the theme and icon definitions:
```json
"workbench.colorTheme": "Min Dark",
"workbench.iconTheme": "symbols"
```
Replace the content of your local `settings.json` with the file from this repository.

### 4. Install Extensions via Terminal
If you prefer installing all extensions at once using your terminal, run:

```bash
code --install-extension ms-dotnettools.csdevkit
code --install-extension esbenp.prettier-vscode
code --install-extension usernamehw.errorlens
code --install-extension miguelsolorio.min-theme
code --install-extension miguelsolorio.symbols
```

You are all set!

---
---

<a name="português"></a>
# 🇧🇷 Versão em Português

Este repositório armazena as minhas configurações pessoais (`settings.json`) do **VS Code**, ajustadas para um fluxo de desenvolvimento focado em **C#** e **TypeScript**, priorizando uma interface altamente minimalista, sem distrações e com foco total no código puro.

---

## 🎨 O Estilo de Trabalho

O objetivo destas configurações é eliminar poluição visual e otimizar o espaço da tela:
* **Interface Minimalista:** Barra de atividades na parte inferior (`bottom`), sem barra de status, sem minimapa, sem barras de rolagem verticais, sem guias de indentação poluídas e utilizando o **Min Theme** combinado ao tema de ícones **Symbols** (ambos criados por Miguel Solorio).
* **Foco e Desempenho:** Recursos de IA e chats integrados totalmente desativados para uma experiência limpa e manual.
* **Tipografia e Layout:** Fonte **JetBrains Mono** em tamanho grande (`18`), com limite rígido de largura de linha (`110` colunas) orientado por réguas visuais e quebra automática.
* **Automação:** Salvamento automático (`afterDelay`), formatação automática ao salvar (`formatOnSave`) e tratamento de erros limpo e direto na linha via **ErrorLens** (focado apenas em erros críticos).

---

## 🔌 Extensões Necessárias

Para que o ambiente funcione exatamente como configurado, instale as seguintes extensões no seu VS Code:

1. **[C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)** (`ms-dotnettools.csdevkit`) — Suporte completo e formatação de código em C#.
2. **[Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)** (`esbenp.prettier-vscode`) — Formatador padrão para TypeScript e JavaScript.
3. **[ErrorLens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)** (`usernamehw.errorlens`) — Exibe os erros diretamente na linha do código.
4. **[Min Theme](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.min-theme)** (`miguelsolorio.min-theme`) — Tema visual minimalista de cores.
5. **[Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols)** (`miguelsolorio.symbols`) — Tema de ícones limpo e elegante.

---

## 🚀 Como Aplicar e Rodar

Para aplicar este estilo de trabalho e configurações no seu VS Code, siga os passos abaixo:

### 1. Clonar ou baixar o repositório
Clone este repositório na sua máquina ou copie o arquivo de configuração.

### 2. Localizar a pasta de configurações do VS Code
O arquivo `settings.json` do VS Code fica localizado dependendo do seu sistema operacional:
* **Windows:** `%APPDATA%\Code\User\settings.json`
* **macOS:** `$HOME/Library/Application Support/Code/User/settings.json`
* **Linux:** `$HOME/.config/Code/User/settings.json`

*(Dica rápida: No VS Code, você pode abrir o arquivo de configurações pressionando `Ctrl + Shift + P` (ou `Cmd + Shift + P` on Mac), digitar **"Preferences: Open User Settings (JSON)"** e pressionar Enter).*

### 3. Substituir as Configurações
Certifique-se de que o seu `settings.json` inclua as definições de tema e ícones:
```json
"workbench.colorTheme": "Min Dark",
"workbench.iconTheme": "symbols"
```
Substitua o conteúdo do seu `settings.json` pelo arquivo deste repositório.

### 4. Instalar as Extensões via Terminal
Se preferir instalar todas as extensões de uma só vez pelo terminal, execute os comandos abaixo:

```bash
code --install-extension ms-dotnettools.csdevkit
code --install-extension esbenp.prettier-vscode
code --install-extension usernamehw.errorlens
code --install-extension miguelsolorio.min-theme
code --install-extension miguelsolorio.symbols
```

Pronto! Seu ambiente estará configurado com o mesmo padrão visual e de desenvolvimento.
