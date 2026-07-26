# PS3 PKG Toolbox

Uma ferramenta simples para **extrair e criar arquivos PKG de PlayStation 3 diretamente no Android**.

O PS3 PKG Toolbox utiliza uma interface gráfica simplificada baseada no projeto **TermuxUI**, permitindo executar as principais operações da ferramenta sem a necessidade de utilizar comandos manualmente no terminal.

## Funcionalidades

### 📦 Extrair PKG

Extraia o conteúdo de arquivos `.pkg` do PS3 diretamente para uma pasta escolhida no dispositivo.

Você pode selecionar:

- O arquivo PKG que deseja extrair
- A pasta onde os arquivos extraídos serão salvos

---

### 🌐 Extrair PKG via URL

Permite extrair um PKG diretamente a partir de uma URL.

Basta informar o endereço do arquivo PKG e escolher onde os arquivos extraídos serão salvos.

> **Observação:** a extração através de URL pode ser mais lenta dependendo da velocidade e estabilidade da conexão com o servidor que hospeda o arquivo.

---

### 🛠️ Build Custom PKG

Crie um **PKG Custom** a partir de uma pasta contendo os arquivos desejados.

O processo gera automaticamente o arquivo:

`CUSTOM-INSTALLER_00-0000000000000000.pkg`

Você pode escolher a pasta onde deseja salvar o PKG gerado.

---

### 🏪 Build Retail PKG

Crie um **PKG Retail** a partir de uma pasta contendo os arquivos do pacote.

Durante o processo, será necessário informar:

- A pasta contendo os arquivos do PKG
- O **Content ID** do jogo ou aplicativo
- A pasta onde os PKGs gerados serão salvos

---

### 🔑 Build Retail PKG com RAP

Permite criar um **PKG Retail utilizando um arquivo RAP** para realizar a assinatura do pacote.

Você deverá informar:

- A pasta contendo os arquivos do PKG
- O **Content ID**
- O arquivo RAP correspondente
- A pasta onde os PKGs gerados serão salvos

---

## Instalação

Antes de utilizar o PS3 PKG Toolbox pela primeira vez, é necessário instalar as dependências através da opção **Instalar dependências**.

O aplicativo realizará automaticamente a configuração do ambiente necessário para executar as ferramentas de PKG.

Após a instalação das dependências, as funções de extração e criação de PKGs estarão disponíveis.

---

## ⚠️ Importante: Termux Original

O PS3 PKG Toolbox é baseado em uma versão personalizada do ambiente **Termux**.

Por esse motivo, **se você já possui o aplicativo Termux original instalado no seu dispositivo, desinstale-o antes de instalar o PS3 PKG Toolbox**.

Isso é necessário porque o aplicativo utiliza o mesmo ambiente e os mesmos componentes internos do Termux, podendo ocorrer conflitos caso as duas versões estejam instaladas simultaneamente.

> **Recomendação:** remova o Termux original antes de instalar o PS3 PKG Toolbox.

---

## Suporte

O PS3 PKG Toolbox foi desenvolvido para facilitar o trabalho com arquivos PKG de PlayStation 3 diretamente em dispositivos Android, oferecendo uma interface gráfica simples para as principais operações de extração e criação de pacotes.

O aplicativo é baseado no projeto **TermuxUI-Frontend**.

---

## Source

- **PS3 PKG Toolbox** — Interface e integração para Android  
- **TermuxUI-Frontend** — Base do frontend e interface gráfica  
  https://github.com/TermuxUI/TermuxUI-Frontend  

- **PS3-PKG-Module** — Ferramentas utilizadas para manipulação e criação dos arquivos PKG  
  https://github.com/PS3-Tools/PS3-PKG-Module  
```
