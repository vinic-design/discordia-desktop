# DiscordIA para computador

Instaladores do aplicativo DiscordIA para **Windows** e **Mac**.

Este repositório guarda **somente os arquivos de instalação** (na aba *Releases*).
Não há código-fonte aqui, e o aplicativo não guarda nenhuma senha ou chave.

## Como baixar

Abra a última versão em **Releases** e baixe o arquivo do seu sistema:

- **Windows 10 ou 11 (64 bits):** `DiscordIA-Setup-<versão>.exe`
- **Mac com chip Apple (M1 ou mais novo):** `DiscordIA-<versão>-arm64.dmg`
- **Mac com chip Intel:** `DiscordIA-<versão>-x64.dmg`

No Mac, abra o `.dmg` e arraste o DiscordIA para a pasta Aplicativos. Na primeira
vez, o Mac pode avisar que o app é de um desenvolvedor não identificado: clique
com o botão direito no app, escolha **Abrir** e confirme.

## Conferir o arquivo (opcional)

Cada versão traz o arquivo `SHA256SUMS.txt`. Para conferir que o download não foi
alterado, compare a soma do arquivo baixado com a do `SHA256SUMS.txt`:

- Mac: `shasum -a 256 <arquivo>`
- Windows (PowerShell): `Get-FileHash <arquivo> -Algorithm SHA256`

## Segurança

Achou algum problema de segurança? Não abra uma discussão pública: avise quem
te convidou para o DiscordIA.
