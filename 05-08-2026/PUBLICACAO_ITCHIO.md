# Publicação inicial no itch.io

Este roteiro deve ser usado somente depois de o `CHECKLIST_TESTE.md` estar satisfatório.

## 1. Salvar uma cópia de publicação

Antes de exportar, salve uma cópia com nome semelhante a:

`FarmaQuest_Alpha_0.1.0_PRE_EXPORTACAO.c3p`

Não exporte diretamente sobre o único arquivo de trabalho.

## 2. Exportar pelo Construct 3

No Construct 3:

1. Abra o menu de exportação do projeto.
2. Escolha a opção de exportação para Web/HTML5.
3. Mantenha a estrutura de arquivos em pastas.
4. Conclua a exportação para uma pasta vazia.
5. Confirme que o arquivo `index.html` está na raiz da pasta exportada.
6. Teste o build exportado no navegador antes de enviá-lo.

## 3. Criar o ZIP correto

Entre na pasta exportada, selecione todo o conteúdo e compacte os arquivos.

O ZIP deve apresentar esta estrutura:

```text
index.html
scripts/
images/
icons/
...
```

Evite esta estrutura:

```text
FarmaQuest_Exportado/
    index.html
    scripts/
    ...
```

O `index.html` deve estar na raiz do ZIP enviado.

## 4. Dados sugeridos da página

Título:

`FarmaQuest — Alfa Acadêmica`

Versão:

`0.1.0-alpha`

Descrição curta:

> Protótipo em desenvolvimento de um jogo educacional 2D sobre recebimento, quarentena e amostragem de insumos farmacêuticos.

Aviso de desenvolvimento:

> Versão preliminar destinada ao acompanhamento dos orientadores. Conteúdo, arte, interface e mecânicas ainda estão em revisão.

## 5. Configuração da página

- Defina o projeto como jogo executado no navegador.
- Envie o ZIP da exportação web.
- Use proporção 16:9.
- Teste inicialmente com área próxima de `640 × 360` ou com opção de expansão para tela cheia.
- Marque compatibilidade com mobile somente depois de testar em um celular real.
- Mantenha a página restrita ou não listada durante a avaliação interna, caso não queira divulgação pública imediata.

## 6. Depois da publicação

- Abra a página em uma janela anônima.
- Teste em desktop.
- Teste em celular na horizontal.
- Confirme que o arquivo `dialogo.json` foi carregado.
- Confirme que a versão visível no menu corresponde à página.
- Envie ao professor o link e informe que se trata da versão `0.1.0-alpha`.
