# 📥 Guia de Instalação da Extensão

Siga as instruções abaixo para adicionar a extensão Estater ao seu navegador. Como não estamos usando a loja oficial, o processo requer a ativação do "Modo do Desenvolvedor".

---

## Passo 1: Fazer o Download

Caso você ainda não tenha baixado o arquivo, faça o download da versão mais recente clicando no link direto abaixo:

👉 **[Download Direto: extensao_v1.2.crx](https://github.com/gabriel-fsantana/estater-extensao-updates/raw/main/extensao_v1.2.crx)**

*(O arquivo será salvo na sua pasta de "Downloads")*

---

## Passo 2: Instalação Padrão (Arrastar e Soltar)

Este é o método mais rápido e funciona bem na maioria dos navegadores (como Edge, Brave e algumas versões do Chrome).

1. **Abra a página de Extensões do seu navegador:**
   Abra uma nova aba e digite o seguinte endereço:
   - **Google Chrome:** `chrome://extensions/`
   - **Microsoft Edge:** `edge://extensions/`
   - **Brave:** `brave://extensions/`

2. **Ative o Modo do Desenvolvedor:**
   No canto superior direito da tela de extensões, procure pelo interruptor **"Modo do desenvolvedor"** (Developer mode) e ative-o. 

3. **Instale a extensão:**
   - Abra a pasta de Downloads do seu computador, onde o arquivo `extensao_v1.2.crx` foi salvo.
   - Clique no arquivo, segure e **arraste-o** para o centro da página de Extensões do navegador.
   - Solte o botão do mouse. Uma janela perguntará se deseja adicionar a extensão. Clique em **"Adicionar extensão"**.

🎉 **Pronto!** A extensão foi instalada.

> ⚠️ **Atenção (Usuários do Google Chrome):** Se o Chrome bloquear a instalação dizendo `CRX_REQUIRED_PROOF_MISSING` ou "não pôde ser instalada", vá para o **Passo 3** abaixo.

---

## Passo 3: Método Alternativo para Google Chrome (Modo Descompactado)

Se o Método Padrão falhou devido aos bloqueios de segurança do Google Chrome, use esta alternativa oficial que funciona 100% das vezes:

1. **Prepare uma pasta permanente:**
   Crie uma pasta no seu computador onde a extensão ficará guardada (ex: `Documentos/Extensao_Estater`). **Não exclua essa pasta depois**.

2. **Renomeie o arquivo baixado:**
   Vá na pasta Downloads, encontre o `extensao_v1.2.crx` e **renomeie o final do arquivo de `.crx` para `.zip`**. O arquivo ficará como `extensao_v1.2.zip`.
   *(Se o seu Windows não mostra o ".crx" no nome, vá no Explorador de Arquivos em: Visualizar > Mostrar > Extensões de nomes de arquivos).*

3. **Extraia os arquivos:**
   Mova o arquivo `.zip` para a pasta permanente que você criou. Clique com o botão direito nele e selecione **"Extrair Tudo..."**.

4. **Carregue no Navegador:**
   - Volte para a página de Extensões do navegador (`chrome://extensions/`).
   - Certifique-se de que o **"Modo do desenvolvedor"** está ativado no topo.
   - Clique no botão **"Carregar sem compactação"** (Load unpacked) no canto superior esquerdo.
   - Selecione a pasta onde os arquivos acabaram de ser extraídos e clique em "Selecionar Pasta".

🎉 **Pronto!** A extensão aparecerá instalada e funcionando normalmente.
