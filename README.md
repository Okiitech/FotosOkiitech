# FotosOkiitech

Repositório público que **hospeda as imagens finais dos anúncios da Okiitech**. As planilhas de anúncio usam os links diretos (raw) destas imagens.

## Estrutura

```
<SKU>/
  Originais/        fotos reais, recortes, cenários e desenhos-base (não vão para anúncio)
  Shopee/           <SKU>-01.jpg ... <SKU>-09.jpg
  Amazon/           idem (imagem 01 com fundo branco puro)
  MercadoLivre/     idem
  Magalu/           idem
  SHEIN/            idem
  TikTok/           idem
```

- **SKU** em maiúsculas, com hífens, sem acento: `FAMÍLIA-PRODUTO-VARIAÇÃO` (ex.: `CHV-HOMEONDAS-PRETO`, `CPO-CLAVE-SOL`).
- Famílias: `CHV` chaveiro, `QDR` quadro, `PAN` porta-panelas, `T7/T11` temperos, `CPO` porta-copos orgânico.
- Imagens: `<SKU>-NN.jpg`, NN com dois dígitos (01 = principal). Quadrado 1:1, JPG.
- Variações de palavra (ex.: `CHV-MONSTERA-HOME-AREIA`): imagem principal de cada variação em `<SKU>-VAR-<PALAVRA>.jpg` (PALAVRA em maiúsculas, sem acento), dentro da pasta de cada marketplace. São montagens com a palavra gravada trocada; a peça só é produzida quando vende.
- Cada marketplace tem a sua pasta, mesmo quando a imagem é igual, para poder ajustar sem afetar os outros.
- Não renomear nem mover arquivos já publicados: os links das planilhas dependem do caminho.

## Link direto de uma imagem

```
https://raw.githubusercontent.com/Okiitech/FotosOkiitech/main/<SKU>/<Marketplace>/<SKU>-NN.jpg
```

Exemplo: `https://raw.githubusercontent.com/Okiitech/FotosOkiitech/main/CHV-HOMEONDAS-PRETO/Shopee/CHV-HOMEONDAS-PRETO-01.jpg`

## Regras

- Só entram imagens aprovadas, fiéis ao produto que o cliente recebe.
- O repositório é público: nada de dados de clientes, preços de custo ou documentos.
