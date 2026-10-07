# Finanças

Aplicativo pessoal de controle financeiro. Funciona offline, e os dados ficam salvos só no iPhone.

## Arquivos
- `index.html`: o aplicativo inteiro
- `manifest.webmanifest`: nome e ícone usados quando o app é instalado no iPhone
- `sw.js`: guarda o app no celular para funcionar sem internet
- `icons/`: ícones do app

## Publicar uma nova versão
1. Envie os arquivos atualizados para este repositório (Add file › Upload files).
2. Em `sw.js`, aumente a versão (`financas-v1` → `financas-v2`).
3. No iPhone, abra o app duas vezes. Na segunda abertura, a versão nova já aparece.

Os seus dados não são apagados quando o app é atualizado.
