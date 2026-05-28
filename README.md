# Hebraico Bíblico - GitHub Pages

Site estático pronto para publicar no GitHub Pages.

## Como publicar

1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para o repositório.
3. Vá em `Settings → Pages`.
4. Em `Build and deployment`, selecione:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Salve.

O arquivo inicial é `index.html`.

## Tamanho do hebraico

Os blocos hebraicos usam CSS:

```css
pre.hebrew-code {
  font-size: 40pt;
}
```

Você pode alterar para `48pt`, `56pt` etc. em:

```text
assets/css/style.css
```
