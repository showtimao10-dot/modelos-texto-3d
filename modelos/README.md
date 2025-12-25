# Modelos de Texto 3D (Galeria)

Dentro de `/modelos` ficam os arquivos da galeria.

## Arquivos
- `index.html` — página da galeria
- `modelos.js` — lista de modelos (URLs)
- `EXTRATOR_120.txt` — captura as primeiras 120 imagens em sequência e remove duplicados

## Como preencher o modelos.js
1) Abra: https://beta.designi.com.br/busca?t=efeitos+de+texto  
2) Role até carregar bastante itens  
3) F12 → Console → cole o script do `EXTRATOR_120.txt`  
4) Cole o JSON dentro do `modelos.js` em `window.MODELOS = [...]` e faça commit
