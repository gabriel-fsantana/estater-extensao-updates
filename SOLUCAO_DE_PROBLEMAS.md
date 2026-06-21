# 🛠️ Solução de Problemas

Se você encontrar dificuldades ao instalar ou usar a extensão Estater, verifique as soluções para os problemas mais comuns abaixo.

### 1. Erro: "Package is invalid: CRX_REQUIRED_PROOF_MISSING"
**Motivo:** O Google Chrome exige que todas as extensões em formato compilado `.crx` possuam uma prova criptográfica (um recibo) garantindo que vieram da Chrome Web Store. Como a nossa distribuição é via GitHub, o Chrome rejeita o arquivo em instalações normais.
**Solução:** A forma correta de contornar isso nas versões modernas do Chrome é utilizando o **Método 2 (Modo Descompactado)** do nosso Guia de Instalação.

### 2. A extensão desapareceu ou parou de funcionar após eu reiniciar o PC
**Motivo:** Se você instalou pelo Método 2 (Modo Descompactado), o navegador precisa ler os arquivos locais toda vez que inicia. Você provavelmente apagou a pasta onde extraiu os arquivos, ou extraiu na pasta "Downloads" e a limpou acidentalmente.
**Solução:** Extraia os arquivos novamente em um local permanente (como a pasta Documentos ou uma pasta dedicada no C:) e repita o processo "Carregar sem compactação". Nunca apague essa pasta.

### 3. As atualizações automáticas não estão funcionando
**Motivo:** As atualizações automáticas via `atualizacao.xml` funcionam perfeitamente para arquivos `.crx` instalados de forma corporativa ou em navegadores com restrições desativadas. No entanto, se a extensão foi instalada pelo Método 2 (Modo Descompactado), as atualizações não serão baixadas automaticamente.
**Solução:**
Você precisará realizar atualizações manuais:
1. Baixe a nova versão do repositório.
2. Altere a extensão para `.zip` e extraia.
3. Copie os novos arquivos e **substitua** os antigos dentro da pasta permanente da sua extensão.
4. Vá em `chrome://extensions/` e clique no ícone de "Atualizar" (🔄) no card da extensão, ou simplesmente reinicie o navegador.

### 4. Aviso de "Desativar extensões em modo do desenvolvedor"
**Motivo:** Ocasionalmente, o Chrome exibe um pop-up sugerindo desativar extensões que não são da loja oficial para sua segurança.
**Solução:** Apenas ignore e feche o aviso ou clique em "Cancelar". Sua extensão continuará funcionando normalmente.
