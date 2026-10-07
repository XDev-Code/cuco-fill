# CUCo Fill — updates (só app, sem source)

Este repo serve **só para a função de update** da app.

- `version.json` → lido pela app em `UPDATE_URL`
- Releases → têm o `app-debug.apk` que a app abre quando há versão nova

A app compara `versionCode` do `version.json` com o `versionCode` instalado.
Se `version.json` for maior, mostra a caixa de update com `notes` e botão para `apkUrl`.
