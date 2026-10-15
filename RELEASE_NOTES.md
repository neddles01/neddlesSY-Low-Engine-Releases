# neddlesSY Low Engine 1.8.11 — Ataque persistente e atualização própria

Esta atualização mantém o método de mobs rosas, sem IA neural, e traz mais
continuidade de ataque após encontrar uma hitbox válida.

- **Ataque persistente:** após confirmar o cursor vermelho, realiza até dez
  cliques com intervalo de 0,25 s, durante 2,25 s entre o primeiro e o último.
  Dispensa a rechecagem do cursor entre esses cliques e busca novamente ao final.
- **Suporte prioritário:** poções, bolha/buffs, morte/Cidade, reposição e stop
  continuam podendo interromper o lote. Mantidos movimento e cliques orgânicos;
  perda de foco, mudança de contexto ou movimento manual também cancelam.
- **F1/F2 revisado:** F2 respeita o cooldown configurado com margem de 0,2 s,
  usa dois slots de tentativa e retorna a F1. Tentativa interrompida não fica
  pendente para outro alvo; comandos enviados não garantem usos da skill.
- **Atualizador próprio Low:** o atalho passa a verificar somente o repositório
  neddlesSY-Low-Engine-Releases. Oferece atualizar e permite continuar local.
  Confere nome/origem/tamanho/SHA-256 antes de abrir o instalador; recusa os
  instaladores da edição com IA. Falha na consulta não impede abrir a Low local.
- **Sem modelo neural:** não inclui ONNX Runtime, pesos de IA ou dependência de
  GPU dedicada. Continua exigindo o cliente com mobs rosas.
- **Dados e licença preservados:** preferências Low, calibração e Keygen
  permanecem como antes; licença online continua obrigatória.

**Para quem usa a Low 1.8.10:** feche o macro e instale manualmente esta 1.8.11
na pasta Low. Essa primeira instalação adiciona o updater; nas próximas versões,
o atalho Low poderá oferecer a atualização. Não é necessário desinstalar.
Nunca instale o pacote normal com IA por cima da Low.

Low e principal têm canais independentes: uma versão maior da principal não
obriga atualizar nem trocar a Low de edição. Os números de versão iguais não
significam pacotes intercambiáveis.

A rotina foi verificada por testes de fonte, extensões e auditoria do pacote.
O instalador final não foi instalado automaticamente; aumento de DPS depende
do teste real do jogo e não é garantido pela contagem de cliques.
