# Hype City Roleplay — Launcher

Repositório oficial usado pelo **Hype City Roleplay** para controlar a versão atual do APK e disponibilizar o download do launcher Android.

## Arquivo principal

O arquivo `version.json` é a fonte oficial de versão usada pelo launcher e pelo site.

Versão inicial configurada:

- Version code: `100`
- Version name: `1.0`
- APK: `HypeCityRoleplay-v1.0.apk`

## Padrão de nome dos APKs

Use sempre:

```
HypeCityRoleplay-v1.0.apk
HypeCityRoleplay-v1.1.apk
HypeCityRoleplay-v1.2.apk
HypeCityRoleplay-v2.0.apk
```

## Download direto

O site usa o endereço de download direto salvo no `version.json`.

Quando existir uma Release publicada com o APK correto, tocar em **Baixar APK** no site inicia o download do arquivo, sem precisar abrir a página do GitHub.

## Atualização do launcher

Quando uma nova versão for lançada:

1. Compile o APK novo.
2. Publique uma nova GitHub Release.
3. Anexe o APK com o nome correspondente à versão.
4. Atualize `version.json` com o novo `latest_version_code`, `latest_version_name`, `apk_filename`, `apk_url` e `updated_at`.
5. O launcher passa a considerar a versão antiga desatualizada.

> A DATA do jogo é mantida separadamente. Este repositório controla somente o APK/launcher.
