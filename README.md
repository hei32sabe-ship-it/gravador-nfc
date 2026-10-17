# Gravador NFC

Página para gravar o link de avaliação num chip NFC pelo Chrome do Android (Web NFC).

Ela é aberta pelo QR Code mostrado no sistema local de cartões de avaliação. O link chega
depois do `#` no endereço, parte que o navegador não envia ao servidor, e a página não
envia nem guarda nada (há uma regra de segurança Content-Security-Policy que bloqueia
qualquer conexão externa).

Endereço: https://hei32sabe-ship-it.github.io/gravador-nfc/
