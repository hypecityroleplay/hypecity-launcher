# Como publicar uma nova versão do APK

Exemplo: versão **1.1**.

## 1. Compile o launcher

A source será configurada para gerar automaticamente:

```
HypeCityRoleplay-v1.1.apk
```

## 2. Crie uma Release neste repositório privado

- Abra **Releases**
- Clique em **Draft a new release**
- Tag: `v1.1`
- Título: `Hype City Roleplay v1.1`
- Anexe: `HypeCityRoleplay-v1.1.apk`
- Publique a Release

## 3. Atualize version.json

Exemplo:

```json
{
  "latest_version_code": 101,
  "latest_version_name": "1.1",
  "apk_filename": "HypeCityRoleplay-v1.1.apk",
  "download_page": "https://hypecityroleplayvx.netlify.app/",
  "download_endpoint": "https://hypecityroleplayvx.netlify.app/api/download",
  "notes": "Baixe a versão mais recente do cliente oficial do Hype City.",
  "updated_at": "AAAA-MM-DD"
}
```

## Ordem correta

**Primeiro publique a Release com o APK. Depois aumente a versão no version.json.**

Assim o launcher nunca bloqueia usuários apontando para um APK que ainda não foi enviado.

## Segurança

O repositório deve permanecer **Private**.

O token usado pelo Netlify deve ficar somente nas variáveis de ambiente do Netlify e nunca no HTML, JavaScript público ou APK.
