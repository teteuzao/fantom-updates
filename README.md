# fantom-updates

Repositorio privado de atualizacao do **Fantom OpenCodeEdition**.

## Arquivos

- `FantomOpenCodeEdition_1.0.0.exe` - build atual (a versao vale pelo nome do arquivo)
- `fantom-version.txt` - manifesto de atualizacao

## Ciclo de release

1. Compilar o exe
2. Subir `FantomOpenCodeEdition_1.0.1.exe` no branch `main`
3. Atualizar `fantom-version.txt`:
   - `version=1.0.1`
   - `exe=` apontando para o arquivo novo
4. Quem abrir a versao antiga recebe a atualizacao obrigatoria

## Acesso

O app le o repo via API do GitHub com um token fine-grained (Contents: Read-only)
colocado em `update-token.txt` ao lado do exe.
