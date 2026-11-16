# neddlesSY Low Engine

Versão atual: **1.8.16** — rosa, dois cliques e confirmação de buffs.

[Baixar Low Engine 1.8.16](https://github.com/neddles01/neddlesSY-Low-Engine-Releases/releases/download/1.8.16/LowEngine-neddlesSY-v1.8.16-Setup.exe)

[Patchnotes e arquivos da atualização](https://github.com/neddles01/neddlesSY-Low-Engine-Releases/releases/tag/1.8.16)

Busca somente pelo rosa, confirma o cursor de ataque e envia até dois cliques
no mesmo ponto antes de buscar novamente pela cor. Sem rosa, não explora pontos
aleatórios. F1 mantém 250 ms; F2 usa duas tentativas com intervalo planejado
mínimo de 150 ms. O cooldown mínimo entre ciclos F2 continua
em 8,5 s, contado da última tentativa enviada; recargas configuradas maiores
continuam respeitadas com margem de 0,2 s. Preferências e calibração preservadas.

Buffs preservam a tentativa após o timeout e reveem o efeito antes de repetir.
Confirmação tardia mantém o timer no clique original, sem outro lote. Com
referência visual, cooldown sozinho não confirma renovação. Se o efeito estiver
presente sem prova de origem, continua observando sem inventar um timer novo.
Só timer/CD e recuperação de falhas reais permanecem.

Feche o macro e execute o instalador como administrador sobre a pasta existente
neddlesSY Low Engine, sem desinstalar. Abra pelo atalho Low e confira 1.8.16.
Se o atualizador antigo não oferecer a versão, use o download manual acima.

A Low exige mobs rosas e HUD correspondente: use uma cópia preparada do cliente.
Usa cor/cursor, sem IA neural, ONNX Runtime ou GPU dedicada. Mantém busca
distribuída, movimentos orgânicos e prioridade de poções, buffs, bolha, reposição
e morte/Cidade. A verificação online de licença continua obrigatória.

Canal exclusivo da Low, com validação de nome, origem, tamanho e SHA256.
Instale somente na pasta Low. Confira SHA256_LOW_ENGINE.txt.
As versões anteriores permanecem disponíveis. A edição normal é independente.

Testes automatizados de fonte/módulos compilados e auditoria do pacote aprovados.
Instalação, upgrade e gameplay desta entrega não foram executados nesta preparação.
Este repositório contém somente distribuição, documentação e metadados.
