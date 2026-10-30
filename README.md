# Mitto — APK para Android

Este repositório disponibiliza o arquivo de instalação Android **mitto-final.apk**, enviado pelo mantenedor do projeto.

## Download

[Baixar mitto-final.apk](https://github.com/mz-dev-cloud/mitto-android/raw/main/mitto-final.apk)

Tamanho: aproximadamente 6,8 MB  
SHA-256: `85a1970ba9975657f3dd114d8df1a89778e29fce88910cd8752bb169b6012958`

## O que é o Mitto

Mitto é um aplicativo de conversas e mensagens. A descrição incluída no próprio app apresenta a proposta como um espaço para conversar em particular, criar grupos e se conectar com outras pessoas.

Entre as funções visíveis no aplicativo estão conversas privadas e em grupo, envio de mensagens e anexos (como fotos, vídeos, áudios e arquivos), gravação de áudio/vídeo, chamadas de voz e vídeo e figurinhas.

## Por que foi criado

Pelo texto e pelas telas do próprio app, o Mitto foi pensado para oferecer um lugar dedicado à comunicação entre pessoas, tanto em conversas individuais quanto em grupos, com mensagens e chamadas no mesmo aplicativo.

## Como foi feito e tecnologias identificadas

A inspeção do APK mostra uma atividade Android nativa (`MainActivity`) que exibe a interface em uma `WebView`. A interface e parte da lógica do cliente estão empacotadas no APK como HTML, CSS e JavaScript. O cliente usa Socket.IO e requisições HTTP para se comunicar com os serviços do Mitto; o código da interface também usa APIs de mídia do navegador para recursos de áudio/vídeo. O pacote inclui componentes Android/Kotlin e Firebase, inclusive um serviço de mensagens Firebase.

Este repositório contém somente o APK pronto para instalação — não o código-fonte completo do app nem o servidor/backend. Portanto, as tecnologias descritas acima foram identificadas nos arquivos internos do APK e não representam documentação completa do sistema.

## Instalação

1. Baixe `mitto-final.apk` pelo link acima em um dispositivo Android.
2. Abra o arquivo baixado e siga as instruções do Android.
3. Se o sistema solicitar, permita a instalação de apps desta fonte nas configurações do dispositivo; você pode desativar essa permissão depois.

Instale APKs somente se confiar na origem. O arquivo foi fornecido pelo mantenedor deste repositório; o GitHub não certifica nem analisa o aplicativo.

## Detalhes do arquivo

- Arquivo: `mitto-final.apk`
- Formato: pacote de instalação Android (APK)
- SHA-256: `85a1970ba9975657f3dd114d8df1a89778e29fce88910cd8752bb169b6012958`

## Aviso

Este repositório serve para distribuir o APK e informações básicas do projeto. Não contém o código-fonte do aplicativo, instruções para compilá-lo, nem garantia de compatibilidade com todos os dispositivos Android.
