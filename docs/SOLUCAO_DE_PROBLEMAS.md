# 🛠️ Solução de Problemas

Se encontrar dificuldades, veja as soluções comuns:

### 1. Erro: "Package is invalid: CRX_REQUIRED_PROOF_MISSING"
**Motivo:** O Google Chrome exige que extensões `.crx` possuam um recibo da Chrome Web Store.
**Solução:** Utilize o **Passo 3 (Modo Descompactado)** do nosso Guia de Instalação.

### 2. A extensão desapareceu ou parou de funcionar
**Motivo:** Se você usou o Modo Descompactado, o navegador lê os arquivos locais. Se você deletou a pasta onde extraiu a extensão, ela deixará de funcionar.
**Solução:** Extraia os arquivos novamente em um local seguro (como a pasta Documentos) e repita o processo "Carregar sem compactação". Nunca apague essa pasta.

### 3. Como atualizar manualmente?
Se a atualização automática não funcionar no Modo Descompactado:
1. Baixe a nova versão `.crx` do [nosso repositório](https://github.com/gabriel-fsantana/estater-extensao-updates).
2. Renomeie para `.zip` e extraia.
3. Copie os novos arquivos e cole dentro da sua pasta permanente da extensão, substituindo os antigos.
4. Vá em `chrome://extensions/` e clique em Atualizar (🔄).
