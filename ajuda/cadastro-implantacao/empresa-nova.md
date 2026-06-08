# Empresa nova

## Quando usar
Use este procedimento quando a empresa ainda não foi implantada no Rotina Flow e não há ZIP/XML do eSocial para importar.

## Vídeo passo a passo
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe src="https://www.youtube.com/embed/COLOCAR_ID_DO_VIDEO_AQUI" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allowfullscreen></iframe>
</div>

## Passo a passo
1. Acesse **Empresas/Implantação**.
2. Na seção **Cadastro de empresa**, informe **Razão social**, **Nome fantasia** e **CNPJ**.
3. Informe a **Data de abertura**.
4. Informe o **WhatsApp** do cliente, se pretende enviar links pelo sistema.
5. Informe o **Organization ID Nibo**, se a empresa já estiver vinculada ao Nibo.
6. Informe o **Pró-labore padrão**.
7. Defina **Início no sistema** como a primeira competência que será controlada pelo Rotina Flow.
8. Confira **Início eSocial pelo SaaS**. Normalmente deve ser igual ao início no sistema.
9. Use **Desativar folha a partir de** somente se a empresa não deve mais calcular folha a partir de certo mês.
10. Escolha o **Ambiente eSocial** correto.
11. Marque **Sem folha de pagamento** apenas se ela nunca deve entrar no cálculo de folha.
12. Deixe **Empresa já enviada anteriormente ao eSocial** desmarcado se ela ainda não tem cadastro inicial no eSocial.
13. Clique em **Cadastrar empresa**.

## Depois de salvar a empresa
1. Em **Empresa em trabalho**, selecione a empresa.
2. Cadastre o **Estabelecimento** com CNPJ/inscrição, CNAE, FPAS e terceiros.
3. Cadastre a **Lotação tributária** com codLotacao, tpLotacao, FPAS e terceiros.
4. Cadastre o **Sócio / Pró-laborista** com CPF, início TSVE, endereço, cargo, CBO e valor do pró-labore.
5. Se a empresa vai transmitir cadastro inicial, clique em **Enviar cadastros** quando tudo estiver conferido.

## Conferência mínima
Antes de calcular folha, confirme:

- Empresa não está marcada como **Sem folha de pagamento**.
- Competência de trabalho não é anterior ao **Início no sistema**.
- Existe pelo menos um sócio/pró-laborista ativo.
- Existe estabelecimento e lotação tributária.
- Certificado eSocial está configurado em **Perfil/Certificado**.

## Erros comuns
- Cadastrar empresa nova como se já tivesse eSocial anterior.
- Esquecer sócio/pró-laborista e tentar calcular folha.
- Usar produção restrita quando o correto é produção oficial.
- Informar início no sistema posterior à competência atual.
