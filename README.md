# Gerador de QRCode

Um gerador de QRCode **gratuito, simples e 100% local** — você digita um texto ou link, clica em **Gerar** e baixa o PNG. Sem cadastro, sem e-mail, sem senha, sem pagamento.

## Por quê?

Parece absurdo, mas muitos sites na internet exigem que você crie uma conta (com e-mail e senha) ou até assine um plano pago só para gerar um QRCode. Um QRCode nada mais é do que uma imagem codificada a partir de um texto — uma tarefa que o seu próprio navegador consegue fazer em milissegundos, sem enviar nada para servidor nenhum.

Este projeto é uma resposta a isso: **você não precisa entregar seus dados pessoais para gerar um QRCode**.

## Como usar

1. Baixe o arquivo [`gerar-qrcode.html`](gerar-qrcode.html) no seu computador.
2. Dê dois cliques nele para abrir direto no navegador (Chrome, Firefox, Edge, Safari...).
3. Digite o texto ou link no campo central.
4. Clique em **Gerar** (ou aperte `Enter`).
5. Clique em **Baixar** para salvar o QRCode como PNG.

Pronto. Sem instalar nada, sem internet, sem conta.

## Privacidade

Tudo acontece no seu navegador. O texto que você digita **nunca sai do seu computador** — não há servidor, não há envio de dados, não há rastreamento. Você pode até desconectar da internet e continuar gerando QRCodes normalmente.

A única dependência é a biblioteca [qrcodejs](https://github.com/davidshimjs/qrcodejs), carregada via CDN, que apenas desenha o QRCode na tela.

## Licença

[MIT](LICENSE) — sinta-se livre para usar, modificar e distribuir.

