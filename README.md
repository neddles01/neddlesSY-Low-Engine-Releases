# neddlesSY Low Engine

Repositório exclusivo de distribuição da **Low Engine**, a edição clássica para
Priston Tale com mobs rosas. Não contém o código-fonte nem a versão principal com IA.

## Download

- [Instalador Low Engine 1.8.10 (.exe)](https://github.com/neddles01/neddlesSY-Low-Engine-Releases/releases/download/1.8.10/LowEngine-neddlesSY-v1.8.10-Setup.exe)
- [Última release e arquivos](https://github.com/neddles01/neddlesSY-Low-Engine-Releases/releases/latest)
- [Instruções de instalação](LOW_ENGINE_INSTALL.txt)
- [Patchnotes](PATCHNOTES_LOW_ENGINE.md)
- [SHA-256 do instalador](SHA256_LOW_ENGINE.txt)

## Como usar

1. Prepare uma cópia do cliente Priston com a alteração de mobs rosas.
2. Feche o macro antes de instalar. Use a pasta exclusiva sugerida pelo instalador.
3. Abra o atalho **neddlesSY Low Engine**, não o da versão principal.
4. Confira classe, teclas das skills e calibração antes de iniciar.

A Low usa detecção por cor/cursor, sem ONNX Runtime ou pesos de IA. Mantém
poções, buffs, reposição e morte/Cidade. Não reconhece monstros de textura normal
por IA. A versão principal com IA continua no repositório
[SistemaGEM-Releases](https://github.com/neddles01/SistemaGEM-Releases/releases/latest).

## Sem atualização automática

Não há updater no instalador Low. O atalho abre o launcher diretamente.
Atualizações Low são manuais por outro instalador Low explicitamente identificado.
Não foi usada versão artificialmente alta para evitar atualizações.

A licença Keygen continua obrigatória; ausência de updater não significa modo
offline. Licença e calibração são compartilhadas com a edição normal, enquanto
as preferências Low ficam em `settings-low.json` (ou por instância).

## Separação e integridade

Esta distribuição foi criada em **14/10/2026**, copiando sem recompilar os quatro
assets da release anterior `low-engine-v1.8.10` de `SistemaGEM-Releases`. O EXE é
o mesmo instalador de 160.563.256 bytes, com hash conferido; não há novas mudanças
de ataque, buffs, perfis ou autenticação nesta separação.

O link antigo permanece disponível para não quebrar mensagens enviadas aos clientes.
Para novos compartilhamentos, utilize os links deste repositório.

SHA-256 do instalador:
`05fa4c9ed61e5b4c0e6fabd2a3d878ace6e7dfee2c0962f8f0bb2060e65b65eb`.

Os executáveis ficam em **Releases**, não no histórico Git. Este repositório
versiona somente documentação e metadados de distribuição.
