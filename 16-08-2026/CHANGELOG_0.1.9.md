# FarmaQuest 0.1.9 — Hotfix de fluxo e interface

## Correções aplicadas

- Corrigido o avanço dos diálogos: o primeiro toque durante a digitação apenas completa a fala; somente um toque posterior avança.
- Reorganizados os eventos de logística da Fase 3 que haviam sido inseridos entre a condição de digitação e o `Else`, quebrando o comportamento anterior.
- Etiqueta Q: o botão X fica oculto e sem colisão enquanto o diálogo do código de barras estiver ativo. Ele só aparece após o término da fala.
- Ao fechar a etiqueta Q, o fluxo só avança se nenhum diálogo estiver ativo.
- Corrigido o flash de retratos ao entrar na Área de Preparação: todos os retratos iniciam ocultos e são exibidos somente pelo sistema de diálogo.
- An-Lu permanece paramentada a partir da quarentena/almoxarifado e durante amostragem, CQ e logística.
- Adicionada versão paramentada do retrato lateral `SPR_AnLu_Apoio`.
- O frasco de amostra ganhou a animação `Rotulado`; ela é ativada ao confirmar o rótulo.
- A pose de Leo segurando o frasco permanece 0,5 s a mais antes do diálogo e é mantida durante a primeira fala da entrega ao CQ.
- Ao abrir o laudo do CQ, todos os retratos são ocultados para não cobrir o botão de confirmação.
- Removida a fala artificial “Fase 2 concluída...”. O retorno ao almoxarifado agora faz uma transição narrativa direta para PCP/OP.
- Corrigido o encadeamento da Fase 3: `Almoxarifado_02_LoteAprovado` agora leva diretamente a `CUTSCENE_FASE3_01_PCP_OP`.

## Versão

Alpha 0.1.9 — 13/08/2026
