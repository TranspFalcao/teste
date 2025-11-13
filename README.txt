# Instruções para publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Suba os seguintes arquivos no repositório:
   - index.html (renomeie o arquivo index_github_excel.html para index.html)
   - Impostos a pagar.xls
3. Ative o GitHub Pages:
   - Vá em Settings → Pages → Source → selecione a branch principal (main) e salve.
4. Edite o arquivo index.html:
   - Substitua a URL no código JavaScript:
     const excelUrl = 'https://SEU_USUARIO.github.io/SEU_REPOSITORIO/Impostos%20a%20pagar.xls';
   - Coloque a URL real do seu repositório.
5. Acesse a URL do GitHub Pages e verifique se os dados aparecem automaticamente.

Observação:
- Sempre que atualizar o arquivo Excel no repositório, o site será atualizado automaticamente.
