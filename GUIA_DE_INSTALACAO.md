# 📥 Guia de Instalação da Extensão (Arquivo `.crx`)

Este guia ensinará como importar a extensão Estater no seu navegador. Como o arquivo `.crx` não é baixado da loja oficial, o processo requer a ativação do "Modo do Desenvolvedor" no seu navegador.

---

## Método 1: Instalação Padrão (Arrastar e Soltar)

Este é o método mais rápido e costuma funcionar bem em navegadores como **Microsoft Edge**, **Brave** e versões mais brandas do Chromium.

1. **Baixe o arquivo da extensão:**
   Acesse a raiz deste repositório e baixe a versão mais recente (ex: `extensao_v1.2.crx`).
   
2. **Abra a página de Extensões do seu navegador:**
   Abra uma nova aba e digite o seguinte endereço na barra de URLs:
   - **Google Chrome:** `chrome://extensions/`
   - **Microsoft Edge:** `edge://extensions/`
   - **Brave:** `brave://extensions/`

3. **Ative o Modo do Desenvolvedor:**
   No canto superior direito da página de extensões, procure pelo interruptor **"Modo do desenvolvedor"** (Developer mode) e ative-o. 

4. **Instale a extensão:**
   - Abra a pasta do seu computador onde você baixou o arquivo `.crx`.
   - Clique e segure o arquivo.
   - **Arraste o arquivo** para o centro da página de Extensões do navegador e solte.
   - Uma janela de confirmação aparecerá perguntando se deseja instalar. Clique em **"Adicionar extensão"**.

🎉 **Pronto!** A extensão foi instalada com sucesso e está pronta para uso.

> ⚠️ **Atenção Usuários do Google Chrome:** Se o Chrome apresentar o erro `CRX_REQUIRED_PROOF_MISSING` ou disser que a extensão "não pôde ser instalada", vá diretamente para o **Método 2** abaixo.

---

## Método 2: Instalação via Pasta (Modo Descompactado)

O Google Chrome possui políticas de segurança rigorosas que frequentemente bloqueiam a instalação direta de arquivos `.crx` de terceiros. Este método é a **alternativa oficial para desenvolvedores** e funciona 100% das vezes.

1. **Prepare uma pasta definitiva:**
   Crie uma pasta no seu computador onde a extensão ficará guardada para sempre (ex: `Documentos/Extensao_Estater`). **Não exclua essa pasta depois**, ou a extensão deixará de funcionar.

2. **Renomeie o arquivo baixado:**
   Pegue o arquivo `extensao_v1.2.crx` baixado e altere a extensão no final para `.zip`. Vai ficar assim: `extensao_v1.2.zip`.
   *(Dica: Se o seu Windows não mostra o ".crx" no nome, vá no Explorador de Arquivos em: Visualizar > Mostrar > Extensões de nomes de arquivos).*

3. **Extraia os arquivos:**
   Mova o arquivo `.zip` para a pasta que você criou no Passo 1. Clique com o botão direito nele e selecione **"Extrair Tudo..."** (ou use o WinRAR/7-Zip).

4. **Carregue no Navegador:**
   - Volte para a página de Extensões do navegador (`chrome://extensions/`).
   - Certifique-se de que o **"Modo do desenvolvedor"** está ativado no canto superior direito.
   - No canto superior esquerdo, clique no botão **"Carregar sem compactação"** (Load unpacked).
   - Selecione a pasta onde os arquivos foram extraídos e confirme.

🎉 **Pronto!** O navegador carregará o código-fonte diretamente e a extensão será ativada sem restrições de loja.
