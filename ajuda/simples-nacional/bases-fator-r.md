# Bases 12 meses e Fator R

## Objetivo
Garantir que o cálculo do Fator R use as bases corretas de faturamento e folha dos últimos 12 meses.

## Vídeo passo a passo
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe src="https://www.youtube.com/embed/COLOCAR_ID_DO_VIDEO_AQUI" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allowfullscreen></iframe>
</div>

## O que o sistema usa
O Simples Fator R considera:

- Receita da competência.
- Histórico de receita dos últimos 12 meses.
- Folha/prolabore dos últimos 12 meses.
- Regras de anexo e atividade PGDAS.
- Data de abertura para empresas novas, quando aplicável.

## Como alimentar bases
Você pode alimentar bases de três formas:

1. **Notas fiscais**: XML/ZIP/CSV ou Nibo.
2. **Extrato PGDAS-D PDF**: usado para importar histórico 12 meses.
3. **Bases manuais**: usadas para complementar faturamento ou folha que não veio automaticamente.

## Importar histórico PGDAS-D
1. Acesse **Simples Fator R**.
2. Em **Importar histórico 12 meses**, envie o PDF do extrato PGDAS-D.
3. Confira as competências carregadas.
4. Marque as linhas como revisadas.
5. Clique em **Gravar bases**.

## Buscar bases pela Integra Contador
1. Em **Importar histórico 12 meses**, clique em **Folhas / bases históricas**.
2. Selecione empresa e competência da declaração.
3. Clique em **Consultar e conferir**.
4. Revise os valores antes de gravar.

## Lançar base manual
1. Clique em **Bases manuais**.
2. Selecione empresa e competência.
3. Informe faturamento manual e/ou folha manual.
4. Salve.
5. Recalcule a empresa.

## Conferir Fator R
Depois de calcular, abra a etapa **Cálculo** e confira:

- **Fator R** em percentual.
- **RBT12** ou **RBT12p**.
- **Folha 12m**.
- **Anexo III ou V**.
- Valor estimado de folha necessária para mudar ou manter anexo, quando exibido.

## Regra prática
Se o sistema mostrar Anexo V e você esperava Anexo III, confira primeiro folha dos últimos 12 meses e bases manuais antes de alterar atividade ou transmitir PGDAS-D.
