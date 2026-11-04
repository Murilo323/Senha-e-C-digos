# CryptoLab — Criptografia e Descriptografia

Projeto educativo em HTML, CSS e JavaScript que demonstra criptografia e descriptografia de texto no navegador.

## Como executar
1. Baixe ou clone este repositório.
2. Abra `index.html` em um navegador moderno.
3. Para usar a Web Crypto API, publique em HTTPS (por exemplo, GitHub Pages) ou execute em `localhost`.

## Tecnologia
- Web Crypto API
- AES-GCM com chave de 256 bits
- Nonce aleatório de 12 bytes
- UTF-8 para transformar texto em bytes
- Base64 apenas para exibir/copiar os bytes resultantes (Base64 não é criptografia)

## Publicar no GitHub Pages
1. Crie um repositório público no GitHub.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)`, depois salve.
6. Aguarde o endereço do GitHub Pages aparecer nessa tela.

## Aviso
Demonstração educacional. A chave é mantida apenas na memória da página e se perde ao recarregar. Não use para armazenar ou proteger senhas reais ou dados confidenciais.
