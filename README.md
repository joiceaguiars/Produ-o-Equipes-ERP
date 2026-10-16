# Produção das Equipes

Aplicação web estática para controle de produção das equipes.

## Publicar pelo GitHub e Vercel

1. Crie um repositório no GitHub, por exemplo `producao-equipes`.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. No Vercel, escolha **Add New → Project** e importe o repositório do GitHub.
4. Para este projeto HTML estático, não é necessário framework nem comando de build. Se o Vercel pedir configurações, selecione **Other** e deixe o Build Command vazio; o Output Directory pode ficar como `.` (raiz do projeto).
5. Clique em **Deploy**. O Vercel fornecerá um endereço HTTPS.

## Observações

- O arquivo `index.html` é a página inicial do site.
- Antes de usar em produção, teste os recursos de salvar/exportar e a persistência dos dados no iPhone e no computador.
- A publicação do HTML não cria automaticamente uma base de dados compartilhada entre dispositivos. Se o sistema salva dados apenas no armazenamento local do navegador, cada dispositivo poderá ter dados separados.
