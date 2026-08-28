# Norte

IDE agêntica local-first, com Agile Board embutido, chat agêntico (Claude Code) e IA embarcada.

Este repositório **não tem código-fonte** — é só o canal de distribuição dos instaladores prontos.
Cada [release](../../releases) publicada aqui traz o `.deb` do Linux daquela versão, com as notas
do que mudou.

## Instalação (Linux, `.deb`)

1. Baixe o `.deb` mais recente na [página de Releases](../../releases/latest).
2. Instale:
   ```bash
   sudo dpkg -i norte_*.deb
   ```
3. Se faltar alguma dependência, resolva com:
   ```bash
   sudo apt-get install -f
   ```

Depois de instalado, o Norte abre pelo menu de aplicativos do sistema ou pelo comando `norte`.

## Atualizando

Não há atualização automática por enquanto — repita os passos acima com o `.deb` da versão mais
nova quando uma sair.

## Changelog

A própria [página de Releases](../../releases) é o changelog: cada tag/versão traz as notas do que
mudou desde a anterior.
