# Feynman English — teste de reconhecimento de voz

Este pacote é somente para testar o reconhecimento de voz por HTTPS.
Ele NÃO altera o app principal.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub, por exemplo:
   `feynman-voice-test`

2. Envie estes arquivos para a raiz do repositório:
   - `index.html`
   - `.nojekyll`

3. No GitHub, abra:
   **Settings → Pages**

4. Em **Build and deployment**, escolha:
   **Deploy from a branch**

5. Em **Branch**, escolha:
   **main** e pasta **/(root)**

6. Salve.

7. Depois de o GitHub publicar, abra o endereço HTTPS fornecido,
   de preferência no Chrome do Android.

8. Na página:
   - toque em **TESTAR PERMISSÃO DO MICROFONE**
   - autorize o microfone
   - depois toque em **FALAR**

## Importante

Erros de permissão, rede ou microfone NÃO entram na taxa de reconhecimento.
A taxa só mede frases realmente processadas pelo reconhecedor.
