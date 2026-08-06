# FarmaQuest — Pacote Alfa Seguro 0.1.0

Data do build: **23/07/2026**  
Projeto: **FarmaQuest — PID UFCSPA**  
Engine: **Construct 3**

## Arquivo que deve ser aberto

Abra no Construct 3:

`FarmaQuest_Alpha_0.1.0.c3p`

O arquivo original foi mantido sem alterações em:

`BACKUP_ORIGINAL/FarmaQuest_test_2_ORIGINAL.c3p`

Não substitua o backup. Ele serve como ponto de retorno caso o Construct apresente algum problema ao abrir ou salvar a versão modificada.

## O que esta versão pretende resolver

Esta é uma intervenção pequena e conservadora, destinada a produzir uma primeira versão alfa acompanhável pelos orientadores. Ela não executa ainda a refatoração estrutural ampla dos objetos, layers, cutscenes, personagens ou event sheets.

As alterações principais são:

- identificação visível `ALFA 0.1.0` no menu;
- botão **Continuar** oculto enquanto não existe salvamento funcional;
- layers de debug desativadas na inicialização;
- remoção de uma tela de fade duplicada;
- remoção de um conjunto duplicado de popup na amostragem;
- explicação da quarentena antes da aplicação da etiqueta Q;
- informação explícita de que o lote em quarentena não pode entrar em produção;
- instrução da etiqueta Q adaptada para mouse e toque;
- explicação sobre o código de barras e sua relação com pesagem e rastreabilidade.

## Ordem recomendada

1. Faça uma cópia externa deste pacote.
2. Abra `FarmaQuest_Alpha_0.1.0.c3p` no Construct 3.
3. Aguarde o carregamento completo dos assets.
4. Execute a pré-visualização no navegador.
5. Realize todos os testes descritos em `CHECKLIST_TESTE.md`.
6. Corrija no Construct qualquer deslocamento visual inesperado.
7. Salve uma nova cópia antes da exportação.
8. Exporte para Web/HTML5 e publique somente após o checklist básico passar.

## Limitação da validação

O arquivo foi validado estruturalmente: o ZIP está íntegro, os arquivos JSON foram analisados, os identificadores permanecem únicos e as referências principais foram conferidas. Entretanto, não foi possível executar o editor e o runtime do Construct 3 neste ambiente. A abertura no Construct, a pré-visualização completa e o teste em celular continuam sendo a validação final obrigatória.
