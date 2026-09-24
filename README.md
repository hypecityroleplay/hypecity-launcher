# Hype City Roleplay — Launcher

Repositório **privado** oficial do Hype City Roleplay.

Ele mantém o controle de versão do launcher Android e as Releases do APK. O público não precisa acessar este repositório diretamente.

## Arquivos

- `version.json` — fonte oficial da versão atual do APK.
- `COMO_PUBLICAR.md` — instruções para publicar novas versões.
- **Releases** — onde cada APK do launcher será anexado.

## Versão inicial

- Version code: `100`
- Version name: `1.0`
- APK esperado: `HypeCityRoleplay-v1.0.apk`

## Padrão do APK

```
HypeCityRoleplay-v1.0.apk
HypeCityRoleplay-v1.1.apk
HypeCityRoleplay-v1.2.apk
HypeCityRoleplay-v2.0.apk
```

## Site oficial

https://hypecityroleplayvx.netlify.app/

O site não precisa expor o GitHub. Ele usa Netlify Functions para consultar este repositório privado e entregar a versão/download ao usuário.

## Separação de sistemas

Este repositório controla apenas **APK/launcher**.

A DATA Lite/Full do jogo continua separada no sistema próprio de atualização.
