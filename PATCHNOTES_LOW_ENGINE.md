# neddlesSY Low Engine 1.8.16 — Rosa, dois cliques e confirmação de buffs

- Busca alvos **somente pela cor rosa**, confirma o cursor de ataque e dá **até dois cliques no mesmo ponto**. Depois faz uma nova leitura e busca outro candidato pela cor. Sem rosa, deixa de explorar posições aleatórias.
- Mantém **250 ms entre cliques de F1**. Em ataque duplo, F2 passa a **duas tentativas**, com intervalo planejado mínimo de 150 ms, dentro do limite de dois cliques por aquisição.
- Mantém o mínimo de **8,5 segundos entre ciclos F2**, contado da última tentativa enviada com sucesso. Cooldowns configurados maiores continuam respeitados com margem de 0,2 s.
- Preserva a tentativa de buff após o tempo de espera e **confere novamente o efeito antes de repetir**. Se a confirmação chegar atrasada, reconhece o lançamento sem enviar outro lote e mantém o timer contado do clique original.
- Para buffs com referência visual, **cooldown sozinho não confirma renovação**. Se o efeito estiver presente, mas a origem da renovação for inconclusiva, continua observando sem inventar um novo timer. O modo “Só timer/CD” permanece disponível.
- Mantém a recuperação de lançamentos que realmente falharam, os intervalos configurados e as antecipações habilitadas. A observação tardia libera o ataque após o timeout.
- Preserva movimentos e cliques sustentados orgânicos, prioridade de poções, buffs, bolha, reposição e morte/Cidade. Interrupções descartam tentativas pendentes.

Feche o macro e atualize pelo canal da sua edição. Preferências e calibração existentes são preservadas.

Atualização exclusiva da Low, com canal e instalador próprios. Continua exigindo mobs rosas e o HUD correspondente.

Validada por testes automatizados, simulações de efeitos atrasados e auditoria do pacote. Instalação e gameplay deste instalador não foram executados na preparação.
