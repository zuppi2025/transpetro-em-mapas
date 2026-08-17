# TI em Mapas — Página de vendas

Página estática de vendas do produto TI em Mapas.

## Execução local

A página pode ser servida por qualquer servidor HTTP estático. Por exemplo:

```bash
python3 -m http.server 5173
```

Depois, abra `http://localhost:5173`.

## Publicação

Este projeto não contém banco de dados, credenciais ou estado de sessão. Os links de checkout, o Meta Pixel e os eventos de checkout estão configurados no `index.html` e no bundle da página.
