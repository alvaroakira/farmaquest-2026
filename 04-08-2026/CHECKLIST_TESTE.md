# Checklist de teste — FarmaQuest 0.1.0-alpha

Use uma cópia do `.c3p` durante os testes.

## 1. Abertura do projeto

- [ ] O Construct 3 abre `FarmaQuest_Alpha_0.1.0.c3p` sem informar corrupção.
- [ ] Os três layouts continuam disponíveis.
- [ ] As event sheets continuam vinculadas aos layouts corretos.
- [ ] O arquivo `dialogo.json` aparece nos arquivos do projeto.
- [ ] O Construct não informa objeto ou addon ausente.

## 2. Menu inicial

- [ ] O título `FarmaQuest` aparece normalmente.
- [ ] O texto `ALFA 0.1.0 | 23/07/2026` aparece no canto inferior direito.
- [ ] O texto da versão não fica cortado.
- [ ] O botão **Continuar** não aparece.
- [ ] Não existe área invisível clicável correspondente ao botão Continuar.
- [ ] O campo de nome aceita texto.
- [ ] O jogo inicia com nome preenchido.
- [ ] O jogo inicia com o campo vazio, usando `Estudante` como nome padrão.

## 3. Recebimento e inspeção visual

- [ ] O primeiro diálogo carrega corretamente.
- [ ] O nome do jogador substitui `{PlayerName}`.
- [ ] As três barricas aparecem.
- [ ] Os hotspots da inspeção visual respondem ao toque/clique.
- [ ] A barrica danificada leva à decisão sobre a avaria.
- [ ] As alternativas Segregar e Relevar continuam funcionando.
- [ ] A sequência com Helena e An-Lu continua avançando.

## 4. Inspeção documental

- [ ] A prancheta abre.
- [ ] As abas de documentos respondem.
- [ ] As páginas podem ser consultadas.
- [ ] A decisão correta do primeiro documento permite seguir.
- [ ] A decisão do segundo lote conduz à reprovação documental.
- [ ] Os popups não aparecem duplicados.

## 5. Quarentena

- [ ] Antes de a etiqueta Q aparecer, An-Lu explica o registro interno do lote.
- [ ] O diálogo afirma que o material em quarentena não pode ser usado na produção.
- [ ] O diálogo menciona área segregada e acesso restrito.
- [ ] Após o diálogo, Sofia aparece e a etiqueta Q é aplicada.
- [ ] A instrução exibida é: `Clique ou toque na etiqueta Q para consultar os dados do lote.`
- [ ] A etiqueta Q apresenta movimento/destaque.
- [ ] O toque ou clique na etiqueta abre a imagem detalhada.
- [ ] Ao abrir a etiqueta, inicia o diálogo sobre código de barras.
- [ ] O diálogo menciona confirmação na pesagem e rastreabilidade.
- [ ] A etiqueta detalhada continua visível depois que o diálogo termina.
- [ ] O botão de fechar a etiqueta funciona.
- [ ] O jogo segue para o transporte ao almoxarifado.

## 6. Transições

- [ ] As telas pretas de transição aparecem somente uma vez.
- [ ] Não há sobreposição de duas telas de fade.
- [ ] O fade continua disponível em transições posteriores.
- [ ] A troca para o cenário do almoxarifado ocorre.
- [ ] A transição para `lyt_Amostragem` ocorre.

## 7. Amostragem

- [ ] O layout de amostragem abre.
- [ ] O diálogo de introdução aparece.
- [ ] O painel da capela responde.
- [ ] A escolha de ferramentas funciona.
- [ ] Feedback de ferramenta incorreta aparece apenas uma vez.
- [ ] O botão OK fecha o popup.
- [ ] O popup não fica preso na tela.
- [ ] O calador permite avançar.
- [ ] A etapa de rotulagem aparece.
- [ ] A conclusão da amostragem avança normalmente.

## 8. Desktop e mobile

- [ ] O mouse aciona os eventos baseados em Touch no navegador desktop.
- [ ] O jogo responde ao toque em um celular ou emulação móvel.
- [ ] Os controles principais não ficam pequenos demais.
- [ ] A tela permanece em orientação paisagem.
- [ ] Não há corte importante ao redimensionar o navegador.
- [ ] O campo de nome não desloca a página de maneira inesperada no celular.
- [ ] O áudio, caso seja adicionado depois, não inicia antes da interação do usuário.

## 9. Exportação

- [ ] O Construct conclui a exportação Web/HTML5.
- [ ] Existe um `index.html` na raiz da pasta exportada.
- [ ] O jogo abre localmente pelo método de pré-visualização/servidor recomendado pelo Construct.
- [ ] O ZIP de publicação contém diretamente o `index.html`, e não uma pasta adicional acima dele.
- [ ] A versão publicada exibe `ALFA 0.1.0` no menu.
