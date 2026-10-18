# mg.celltech

Site da **mg.celltech**: conserto de celular e criação de sites profissionais no Rio de Janeiro.

- **Celular**: serviços, como funciona, tela original x paralela e orçamento.
- **Sites**: tipos de site, como funciona e orçamento.

Os dois formulários montam a mensagem e abrem o WhatsApp (21 98111-9638) com o pedido pronto. Não há banco de dados: nada é guardado no site.

## Estrutura

```
index.html    página única (HTML, CSS e JS juntos)
favicon.svg   ícone da aba
vercel.json   configuração do Vercel (site estático)
```

## Links diretos

- `/#celular` abre a página de conserto
- `/#site` abre a página de sites

## Publicação

Hospedado no Vercel como site estático. Cada `git push` na branch `main` publica uma nova versão.
