# QPA — Programa Administrativo (demo independente)

Esta versão é uma demonstração estática para GitHub Pages. Ela usa apenas **dados fictícios embutidos no `index.html`**. Não chama Google Apps Script, não lê planilhas e não se conecta ao WPA Produção.

## Publicar no GitHub Pages

1. Crie o repositório `qpa-programa-administrativo`.
2. Coloque `index.html` na raiz do repositório.
3. Faça commit e push para a branch `main` deste repositório QPA (não é a `main` do WPA).
4. No GitHub, abra **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
6. Aguarde a URL do Pages aparecer na mesma tela.

## Importante

- Esta é somente uma demo visual/funcional com registros fictícios; não é uma integração com dados reais.
- Não publique o endpoint antigo do Apps Script nem altere suas permissões para `Qualquer pessoa` para fazer esta demo funcionar.
- Para integração real, crie uma fonte de dados de demonstração separada e um backend com acesso mínimo; valide a política de acesso antes de conectá-lo.
- O aviso `LF/CRLF` do Git é apenas sobre finais de linha e não impede a execução.
