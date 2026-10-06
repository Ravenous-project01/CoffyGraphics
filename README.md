

<div align="center">

  <img src="docs/logo.svg" alt="CoffyGraphics Logo" width="160" height="160">

  # ☕ CoffyGraphics

  **Uma IDE visual moderna, leve e intuitiva para prototipagem e design de interfaces em JavaFX.**

  [![Java](https://img.shields.io/badge/Java-17%2B-orange?style=for-the-badge&logo=openjdk)](https://www.oracle.com/java/)
  [![JavaFX](https://img.shields.io/badge/JavaFX-21-blue?style=for-the-badge&logo=java)](https://openjfx.io/)
  [![Maven](https://img.shields.io/badge/Maven-Build-red?style=for-the-badge&logo=apachemaven)](https://maven.apache.org/)
  [![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## 🌟 Sobre o Projeto
O **CoffyGraphics** foi concebido para simplificar a criação e visualização de interfaces gráficas em **JavaFX**. Combinando a agilidade de um editor *drag-and-drop* com a robustez da ecossistema Java, o CoffyGraphics permite desenhar telas, manipular componentes em tempo real e integrar rapidamente o resultado ao seu fluxo de desenvolvimento.

Coffy graphics é um projeto de ide java pra desenvolvimento de apps em projeto maven, eu fiz esse projeto porque tava cansado de depender do windowbuilder e do scennebuilder. se quiser usar esse projeto sinta-se a vontade!!!!

---

## ✨ Principais Recursos

- 🎨 **Canvas Interativo (Drag & Drop):** Posicione e organize elementos visuais diretamente na tela com suporte a movimentação e atalhos rápidos (como remoção com `DELETE`).
- 🧩 **Paleta de Componentes:** Adição rápida de Botões, Labels e outros controles nativos JavaFX.
- 📐 **Edição de Curvas Bézier:** Suporte a manipulação de formas vetoriais e elementos gráficos avançados.
- ⚡ **Execução Integrada:** Execute comandos do Maven (`mvn compile`, `mvn exec:java`) diretamente da interface sem sair da aplicação.
- 📂 **Gerenciador de Workspace:** Organize múltiplos projetos JavaFX com seleção dinâmica de diretórios.
- 📜 **Gerador FXML & Código:** Exporte o design visual diretamente para estrutura de arquivos FXML limpa e compatível.

---

## 🚀 Como Instalar e Executar

> ⚠️ **Nota de Compatibilidade:** Os scripts de instalação e inicialização automática fornecidos operam **exclusivamente no Windows**[cite: 4, 5]. O suporte nativo para distribuições **Linux** está em planejamento para futuras atualizações.

---

### Pré-requisitos
- **JDK 17** ou superior instalado e configurado nas Variáveis de Ambiente (`PATH`).
- **Apache Maven** instalado e configurado no `PATH`.
- **PowerShell 5.1+** (padrão no Windows 10/11).

---

### Métodos de Instalação (Windows)

#### Opção 1: Via Script Lançador Batch (`INSTALAR.bat`) — *Recomendado*

1. Baixe os arquivos do instalador e certifique-se de que o `Instalar.ps1` e o `INSTALAR.bat` estejam na **mesma pasta**[cite: 4, 5].
2. Dê um **duplo clique** sobre o arquivo **`INSTALAR.bat`**[cite: 4].
3. O script executará o PowerShell em segundo plano (`-ExecutionPolicy Bypass`) para construir a estrutura do projeto em `%USERPROFILE%\CoffyGraphics` e criar um atalho na Área de Trabalho[cite: 4, 5].

---

#### Opção 2: Via Terminal PowerShell (`Instalar.ps1`)

1. Abra o **PowerShell** no diretório onde os scripts foram baixados.
2. Execute o comando abaixo:
   ```powershell
   powershell -NoProfile -ExecutionPolicy Bypass -File "Instalar.ps1"
