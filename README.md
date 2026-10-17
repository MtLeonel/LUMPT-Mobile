# Lumpt Mobile

App Android do **Lumpt**, a plataforma gamificada para aprender programação (Turma 924 IOT, FIRJAN Benfica).

O app empacota a versão web (`www/index.html`, arquivo único que funciona offline) com o [Capacitor](https://capacitorjs.com/).

## Baixar o APK

O APK é gerado automaticamente pelo GitHub Actions a cada push na `main` e fica na branch **`apk`** (arquivo `Lumpt.apk`).
Para gerar de novo manualmente: aba **Actions** > *Gerar APK do Lumpt* > *Run workflow*.

Para instalar: copie o `Lumpt.apk` para o celular Android, abra o arquivo e permita "instalar apps de fontes desconhecidas".
É um APK de teste (debug); publicar na Play Store exige uma versão assinada.

## Gerar localmente

Precisa de Node.js 18+, JDK 17 e Android SDK. Veja o `LEIA-ME.txt`.

O progresso do aluno fica salvo no próprio aparelho. Login, sincronização, comunidade compartilhada e IA real dependem de um backend ainda não conectado.
