# Alfa Prime Club para Android

Aplicativo do programa de fidelidade Alfa Prime: pontos, benefícios, veículos e atendimento do posto.

## Instalar

[Baixar a versão mais recente do APK](https://github.com/Balanca02/alfaprime-android/releases/latest/download/Alfa-Prime-Club.apk)

Android 7.0 ou superior. Abra o arquivo baixado e confirme a instalação no Android. O Android pode solicitar autorização para instalar aplicativos pelo navegador utilizado no download.

## Como funciona

O aplicativo conecta ao endereço HTTPS [Alfa Prime Club](https://alfaprime.lemartcrm.com/). Requer internet e o serviço do posto online. O primeiro acesso cria a senha; os próximos acessos usam CPF e senha.

As melhorias publicadas na versão web aparecem ao abrir o aplicativo novamente, sem precisar reinstalar o APK. Alterações locais só chegam aos clientes depois de compilar e publicar a versão web no servidor usado pelo endereço acima.

O aplicativo consulta este repositório automaticamente, no máximo uma vez a cada seis horas, quando é aberto ou retorna ao primeiro plano. O botão **Atualizações** permite verificar na hora. Quando houver um APK mais novo, o aplicativo oferece o download; a instalação depende da confirmação do usuário no Android. Não instala arquivos silenciosamente.

## Distribuição

Este repositório contém somente a distribuição do aplicativo e informações públicas. Não contém banco de clientes, credenciais, chave de assinatura nem o código privado do sistema. Os arquivos `SHA256SUMS.txt` e `release.json`, em cada release, identificam o APK publicado.

Pacote Android: `br.com.alfaprime.club`. Publicações de APK usam tags `android-<versionCode>` e o arquivo estável `Alfa-Prime-Club.apk`.

Esta distribuição inicial utiliza o ambiente de demonstração do posto. A entrega real de confirmação por WhatsApp/SMS depende da configuração do operador.
