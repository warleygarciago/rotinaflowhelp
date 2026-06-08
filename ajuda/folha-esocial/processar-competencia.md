# Processar competência de folha, DP e eSocial

## Objetivo
Calcular a folha, enviar eventos mensais ao eSocial, gerar DARF DCTFWeb e preparar a entrega ao cliente.

## Vídeo passo a passo
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe src="https://www.youtube.com/embed/COLOCAR_ID_DO_VIDEO_AQUI" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allowfullscreen></iframe>
</div>

## Antes de começar
Confira:

- Empresa implantada em **Empresas/Implantação**.
- Certificado enviado em **Perfil/Certificado**.
- Estabelecimento, lotação e sócio/pró-laborista cadastrados.
- Rubricas classificadas, quando a empresa veio de XML do eSocial.
- Alterações contratuais e afastamentos lançados antes do cálculo.

## Passo a passo
1. Acesse **DP/eSocial/DARF**.
2. Escolha a **Competência**.
3. Escolha uma empresa específica ou deixe **Todas**.
4. Clique em **Calcular folha**.
5. Aguarde o processamento.
6. Expanda a empresa e confira a etapa **Folha**.
7. Revise valores de bruto, INSS, IRRF, líquido e holerites.
8. Se estiver correto, clique em **Enviar eSocial das calculadas** ou **Enviar eSocial** dentro da empresa.
9. Aguarde o eSocial fechar a competência com **S-1299 aceito**.
10. Depois de fechado, clique em **Gerar DARF pendentes** ou **Gerar DARF** na empresa.
11. Quando o DARF estiver gerado, siga para entrega ao Nibo ou WhatsApp.

## O que o sistema envia no eSocial mensal
O fluxo mensal pode envolver:

- **S-1200**: remuneração.
- **S-1210**: pagamento.
- **S-1299**: fechamento da competência.

Se precisar corrigir uma competência já fechada, o sistema também possui ações de reabertura e exclusão:

- **S-1298**: reabrir competência.
- **S-3000**: excluir remuneração ou pagamento.

## Status que você deve observar
- **Folha calculada**: folha pronta para conferência.
- **eSocial processando**: eventos enviados ou aguardando retorno.
- **Competência fechada**: S-1299 aceito.
- **DARF gerado**: PDF, valor, vencimento, PIX ou código disponíveis.
- **Enviado ao Nibo**: documentos entregues para conferência.

## Erros comuns
- Empresa não aparece porque está fora da competência de início.
- Empresa marcada como **Sem folha de pagamento**.
- Sócio/pró-laborista ausente.
- Rubrica importada sem finalidade definida.
- Certificado não configurado.
- Enviar eSocial antes de revisar a folha.

## Como corrigir
Volte em **Empresas/Implantação** ou **Rubricas**, ajuste o cadastro e recalcule a folha antes de enviar novamente.
