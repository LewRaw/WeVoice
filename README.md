# WeVoice

Aplicativo para Windows x64 com salas de voz, chat e compartilhamento de tela.

**[Baixar a versão mais recente do WeVoice](https://github.com/LewRaw/WeVoice/releases/latest/download/WeVoice-win-x64.zip)**

Este endereço permanece o mesmo nas próximas atualizações.

## Instalar

1. Baixe `WeVoice-win-x64.zip` pelo link acima.
2. Feche o WeVoice se ele já estiver aberto.
3. Extraia o ZIP completo em uma pasta. Para uma atualização manual, substitua os arquivos da instalação anterior.
4. Abra `WeVoice.App.exe`. Mantenha as DLLs, o modelo e as licenças ao lado do executável.

O runtime .NET já está incluído. Suas configurações pessoais ficam fora da pasta
do pacote, em `%APPDATA%\WeVoice`. O recurso de captura de som por processo
exige Windows build 20348 ou superior.

Para conversar, conecte o aplicativo ao endereço do servidor da sua comunidade.
O download não fornece um servidor público de voz.

A partir de 0.1.4, use **Servidor da comunidade — automático** para receber o
endereço oficial atualizado. O aplicativo verifica a assinatura antes de aceitar
uma mudança. Não é preciso baixar outro EXE quando o administrador troca o túnel.
Desmarque a opção para informar outro servidor manualmente. O modo automático
localiza o servidor, mas não o mantém online quando o equipamento hospedeiro desliga.

## Atualizações pelo aplicativo

A partir da versão 0.1.1, o WeVoice verifica as atualizações ao abrir. Quando houver
uma nova versão, clique em **Atualizar** para baixar, conferir e instalar o pacote.
O aplicativo reinicia após a instalação e preserva sua identidade e configurações.

Atualizações opcionais oferecem **Atualizar** ou **Agora não**. Se sua versão
estiver abaixo da versão mínima permitida, o aviso de atualização obrigatória
oferece somente **Atualizar** ou **Fechar** antes de permitir a entrada no aplicativo.

A assinatura do aviso e os hashes dos arquivos são verificados antes da instalação.
Se uma exigência obrigatória já foi recebida, ela também é lembrada sem conexão.
Sem conexão e sem aviso conhecido, o aplicativo não consegue descobrir uma exigência nova.

Quem usa a versão 0.1.0 precisa baixar e extrair manualmente uma última vez a
versão com o atualizador. Essa versão antiga ainda não consulta as atualizações.

O arquivo `WeVoice-win-x64.zip.sha256`, disponível em cada Release, permite conferir
a integridade do ZIP com `Get-FileHash .\WeVoice-win-x64.zip -Algorithm SHA256`.

## Autoria e licença

WeVoice por **[LewRaw](https://github.com/LewRaw)**.
Copyright (c) 2026 LewRaw. Todos os direitos reservados sobre o código original.

Uso gratuito sob os termos de [LICENSE.txt](LICENSE.txt). Este repositório contém
somente a página de downloads e as condições de uso. O código original do WeVoice
não está publicado. Créditos não concedem permissão para copiar ou reutilizar código.

As bibliotecas de terceiros mantêm suas licenças e créditos próprios, incluídos
no ZIP. Leia `WeVoice-LICENSE.txt` e os arquivos de avisos que acompanham o pacote.

As versões anteriores estão disponíveis em [Releases](https://github.com/LewRaw/WeVoice/releases).
