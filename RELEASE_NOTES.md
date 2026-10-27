# neddlesSY Low Engine 1.8.12 — Busca mais ativa e alternância de alvos

- **Busca mais distribuída:** após cada rajada, a rotina favorece outras regiões
  da área de combate, incluindo o lado oposto, reduzindo a insistência no mesmo ponto.
- **Melhor distribuição em grupos de mobs:** amplia os pontos de busca quando
  vários monstros rosas ficam sobrepostos, situação observada em Lost 2.
- **Novas tentativas quando a hitbox não responde:** a presença de rosa deixa de
  impedir a exploração de outros pontos quando os contatos testados não ativam
  o cursor vermelho. A confirmação continua sendo exigida antes da rajada.
- **Movimento orgânico:** mantém a duração variável e usa o controlador legado
  de movimento relativo, com chegada conferida e limites da janela.
- **Ataque e suporte preservados:** mantém até dez cliques a cada 0,25 s após
  confirmar o contato, F1/F2 e cooldown, além da prioridade de poções, bolha,
  buffs, reposição, morte/Cidade e parada.
- **Diagnóstico ampliado:** os logs distinguem busca, confirmação de contato e rajada.

A Low continua exigindo o cliente com mobs rosas e o HUD correspondente.
Não usa IA neural, ONNX Runtime nem GPU dedicada. O canal de atualização é
exclusivo da Low e não instala a edição principal com IA.

Testes automáticos de fonte, módulos compilados e auditoria do pacote aprovados.
O comportamento real em Lost 2 e em outros mapas será acompanhado pelos testes
e logs dos usuários; não há ganho de DPS garantido por contagem de cliques.

**Para atualizar:** quem usa a Low 1.8.11 pode abrir o atalho neddlesSY Low Engine
e aceitar a atualização, ou usar o instalador oficial abaixo. Quem ainda usa a
Low 1.8.10 deve instalar manualmente para receber o atualizador próprio.
Feche o macro antes de instalar e mantenha a pasta exclusiva neddlesSY Low Engine.
Não precisa desinstalar nem trocar os perfis para atualizar.
