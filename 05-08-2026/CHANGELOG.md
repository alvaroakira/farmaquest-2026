# Changelog — FarmaQuest

## 0.1.0-alpha — 23/07/2026

### Menu e identificação da versão

- Nome interno do projeto alterado de `FarmaQuest_test` para `FarmaQuest_Alpha`.
- Versão interna alterada de `1.0.0` para `0.1.0`.
- Adicionado o objeto de texto `txt_VersaoProjeto`.
- Adicionado no canto inferior direito do menu o texto:
  - `ALFA 0.1.0 | 23/07/2026`
- `btn_ContinuarMVP` e `txt_BtnContinuarMVP` passam a iniciar ocultos.
- O botão Continuar também tem colisão desativada no layout.
- A event sheet do menu reforça a ocultação do botão e de seu texto no início do layout.

### Segurança e limpeza técnica

- `L99_DEBUG` passa a iniciar invisível e não interativa nos três layouts:
  - `lyt_MenuMVP`;
  - `lyt_Jogo`;
  - `lyt_Amostragem`.
- Removida uma das duas instâncias de `spr_FadeTela` em `lyt_Jogo`.
- Mantida a instância cujo comportamento `Fadeout` não destrói o objeto, permitindo reutilização nas transições.
- Removido o conjunto local duplicado de:
  - `popup_Fundo`;
  - `popup_AvatarNPC`;
  - `popup_Texto`;
  - `popup_BotaoOK`.
- Mantido o conjunto em `L90_UI_GLOBAL/lyr_UI_Popup`, que é a layer efetivamente controlada pelas event sheets.

### Quarentena e rastreabilidade

- O fluxo não salta mais diretamente para `CUTSCENE_07_QUARENTENA`.
- Antes de Sofia aplicar a etiqueta Q, é iniciado o diálogo:
  - `Quarentena_01_ExplicacaoEtiqueta`.
- Esse diálogo explica:
  - registro interno do lote;
  - rastreabilidade;
  - condição de quarentena;
  - proibição de uso na produção;
  - encaminhamento a área segregada e de acesso restrito.
- O motor de diálogo recebeu um mapeamento para retomar `CUTSCENE_07_QUARENTENA` após a explicação.
- A instrução foi alterada de:
  - `Clique na etiqueta Q para ver os detalhes.`
- Para:
  - `Clique ou toque na etiqueta Q para consultar os dados do lote.`
- Ao abrir a etiqueta detalhada, passa a ser iniciado o diálogo:
  - `Quarentena_02_CodigoBarras`.
- O novo diálogo explica a relação entre:
  - código de barras;
  - registro interno;
  - confirmação do material na pesagem;
  - movimentação;
  - rastreabilidade.

### Alterações deliberadamente adiadas

Não foram realizadas nesta versão:

- renomeação em massa de objetos, layers ou animações;
- unificação das barricas e pallets em tipos reutilizáveis;
- reconstrução visual da área de quarentena com grade ou barreira física;
- novas artes de An-Lu, Sofia ou Leo paramentados;
- introdução da antecâmara e da paramentação do Leo;
- coleta interativa separada em topo, meio e fundo;
- sistema de salvamento;
- três perfis locais;
- revisão do indicador de pontuação;
- compêndio interno de BPF;
- reconstrução das cutscenes com Timeline ou Tween.

Esses itens permanecem reservados para versões posteriores, evitando ampliar o risco técnico antes da primeira publicação alfa.
