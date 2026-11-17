# Tech Nexo — Site institucional

Site institucional responsivo da Tech Nexo, feito em HTML, CSS e JavaScript puro.

## Como visualizar
Abra `index.html` no navegador.

## Como configurar o WhatsApp
No final do arquivo `index.html`, procure:
```js
const WHATSAPP_NUMBER = "";
```
Insira o número com código do país e DDD, somente números. Exemplo fictício:
```js
const WHATSAPP_NUMBER = "5511999999999";
```
Enquanto o campo estiver vazio, os botões de contato abrem o e-mail de demonstração `contato@technexo.com.br`. Troque também `CONTACT_EMAIL` pelo e-mail real antes de publicar.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub, por exemplo `tech-nexo`.
2. Envie `index.html` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)`, depois salve.
6. Aguarde a publicação. O GitHub mostrará o endereço do site nessa mesma tela.

## Antes de divulgar
- Configure WhatsApp e e-mail reais.
- Substitua os conceitos do portfólio por projetos reais à medida que forem concluídos.
- Revise os textos e os serviços oferecidos para refletir exatamente o que a agência entrega.
- A fonte do Google Fonts é externa; o site continua funcional com fontes alternativas se ela não carregar.
