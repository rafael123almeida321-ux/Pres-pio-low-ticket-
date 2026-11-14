# Presépio Noite a Noite · landing page

Página estática (HTML + imagens), pronta para a Vercel.

## Antes de anunciar
Abra `index.html` e preencha o bloco `CONFIG` no fim do arquivo:
- `checkoutUrl`: link do checkout da Cakto (já preenchido)
- `pixelId`: ID do Pixel da Meta (opcional)
- `seller`: nome, CPF/CNPJ e e-mail de suporte

Enquanto esses campos estiverem vazios, a página mostra um aviso de revisão no topo e os botões levam para a seção da oferta.

## Deploy na Vercel
Importe este repositório na Vercel. Framework: "Other". Sem comando de build e sem pasta de saída (raiz).

## Preço de lançamento
`CONFIG.lancamento` mostra "Preço de lançamento até 30/11. Depois, R$ 37,99." O aviso some sozinho depois da data.
Use só se o preço da Cakto subir de verdade para R$ 37,99 depois dessa data.
