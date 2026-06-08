# Como preparar empresa para DP, folha e eSocial

## Resumo
Este tutorial mostra como preparar a empresa para cálculo de pró-labore, folha, eventos eSocial, DCTFWeb e DARF. A preparação começa no cadastro único em **Empresas/Implantação**.

## Vídeo passo a passo
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe src="https://www.youtube.com/embed/COLOCAR_ID_DO_VIDEO_AQUI" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allowfullscreen></iframe>
</div>

## Quando usar
Use antes de calcular a primeira folha de uma empresa ou quando o eSocial mensal não estiver pronto para envio.

## Escolha o procedimento correto
Se a empresa é nova no Rotina Flow, use:

[Como cadastrar empresa nova](../configuracoes-gerais/cadastrar-empresa-nova.md)

Se a empresa já existe no eSocial, use:

[Como implantar empresa existente pelo eSocial](../configuracoes-gerais/implantar-empresa-existente-esocial.md)

## Campos importantes para DP/eSocial
- **Pró-labore padrão**: valor usado quando o sócio não tem valor individual.
- **Início no sistema**: primeira competência do sistema.
- **Início eSocial pelo SaaS**: primeira competência em que o Rotina Flow calcula/envia eSocial.
- **Desativar folha a partir de**: bloqueia cálculo em competências futuras a partir do mês informado.
- **Ambiente eSocial**: produção restrita ou produção oficial.
- **Sem folha de pagamento**: tira a empresa do motor automático de folha.
- **Empresa já enviada anteriormente ao eSocial**: evita tratar empresa importada como cadastro inicial novo.

## Cadastros necessários
Depois de salvar a empresa, selecione-a em **Empresa em trabalho** e confira:

1. **Estabelecimentos**: CNPJ/Inscrição, CNAE, FPAS, terceiros, iniValid e recibo.
2. **Lotações tributárias**: codLotacao, tpLotacao, FPAS, terceiros e vínculo com estabelecimento.
3. **Sócios / Pró-laboristas**: CPF, início TSVE, dados pessoais, endereço, cargo, CBO, valor de pró-labore, matrícula eSocial e recibo.
4. **Rubricas**: na tela **Rubricas**, classifique rubricas importadas de S-1010 para pró-labore, INSS, IRRF ou outra finalidade.

## Passo a passo
1. Acesse **Empresas/Implantação**.
2. Cadastre manualmente ou importe a empresa pelo ZIP/XML do eSocial.
3. Selecione a empresa em **Empresa em trabalho**.
4. Revise estabelecimentos, lotações e sócios/pró-laboristas.
5. Para empresa importada, confira as rubricas na tela **Rubricas**.
6. Acesse **DP/eSocial/DARF**.
7. Escolha a competência.
8. Calcule a folha ou envie o eSocial quando a folha já estiver calculada.

## Erros comuns
- Empresa marcada como **Sem folha de pagamento** e por isso não aparece para cálculo.
- Competência anterior ao **Início eSocial pelo SaaS**.
- Estabelecimento, lotação ou sócio ausente.
- Empresa já existente no eSocial cadastrada manualmente, sem recibos/códigos importados.
- Rubricas importadas sem finalidade definida para o cálculo.
- Ambiente eSocial incorreto.

## Como resolver
Volte em **Empresas/Implantação**, edite a empresa e complete os cadastros. Para empresa já existente, importe o ZIP/XML com S-1000, S-1005, S-1020, S-1010 e S-2300 sempre que possível.

## Observações importantes
Empresas já importadas do eSocial não devem depender de rubricas padrão geradas automaticamente. Confira e classifique as rubricas importadas antes da primeira folha.
