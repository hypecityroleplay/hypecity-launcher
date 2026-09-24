# Como publicar uma nova versão

Exemplo: versão **1.1**.

## 1. Gere o APK

O nome esperado será:

```
HypeCityRoleplay-v1.1.apk
```

## 2. Crie uma Release

No GitHub:

- Abra **Releases**
- Clique em **Draft a new release**
- Tag sugerida: `v1.1`
- Título sugerido: `Hype City Roleplay v1.1`
- Anexe `HypeCityRoleplay-v1.1.apk`
- Publique a Release

## 3. Atualize version.json

Exemplo:

```json
{
  "latest_version_code": 101,
  "latest_version_name": "1.1",
  "apk_filename": "HypeCityRoleplay-v1.1.apk",
  "apk_url": "https://github.com/hypecityroleplay/hypecity-launcher/releases/latest/download/HypeCityRoleplay-v1.1.apk",
  "download_page": "SEU_LINK_NETLIFY",
  "notes": "Baixe a versão mais recente do cliente oficial do Hype City.",
  "updated_at": "AAAA-MM-DD"
}
```

## Regra importante

Sempre publique primeiro o APK da nova versão e depois altere o `version.json`.

Assim você evita bloquear usuários apontando para um APK que ainda não foi enviado.
