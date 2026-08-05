# Relatório de validação estrutural

Arquivo validado:

`FarmaQuest_Alpha_0.1.0.c3p`

## Testes executados

- integridade do arquivo ZIP/C3P;
- teste de CRC de todas as entradas do arquivo;
- leitura de todos os arquivos JSON;
- correspondência entre tipos de objeto listados no projeto e arquivos em `objectTypes`;
- verificação de tipos utilizados pelas instâncias dos layouts;
- verificação de unicidade de UIDs;
- verificação de unicidade de SIDs;
- confirmação de somente uma instância de `spr_FadeTela` em `lyt_Jogo`;
- confirmação de somente um conjunto de popup em `lyt_Amostragem`;
- confirmação de `L99_DEBUG` inativa nos três layouts;
- confirmação da existência do texto de versão no menu;
- confirmação de que o botão Continuar inicia oculto;
- confirmação das duas novas cenas de diálogo;
- confirmação de que todas as cenas chamadas por `f_StartDialogue` existem no JSON;
- confirmação do fluxo:
  - explicação da quarentena;
  - retomada da cutscene da etiqueta Q;
  - abertura da etiqueta;
  - explicação do código de barras.

## Resultado automatizado

```text
VALIDATION_OK
JSON files parsed: 160
Object types: 124
Layout instances: 97
Dialogue scenes: 24
Dialogue calls: 18
```

## Limitação

A validação automatizada não substitui a execução do projeto no Construct 3. Não foi possível, neste ambiente, abrir o editor, compilar o runtime ou confirmar visualmente posições, sobreposições, escala, carregamento no navegador e resposta em dispositivo móvel.

O checklist manual permanece obrigatório antes da publicação.
