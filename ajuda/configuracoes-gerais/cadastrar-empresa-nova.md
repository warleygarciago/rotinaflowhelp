# Como cadastrar empresa nova

## Resumo
Este tutorial mostra como cadastrar manualmente uma empresa nova em **Empresas/Implantação**. Use quando a empresa ainda não foi montada no Rotina Flow por importação do eSocial.

## Vídeo passo a passo
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe src="https://www.youtube.com/embed/COLOCAR_ID_DO_VIDEO_AQUI" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allowfullscreen></iframe>
</div>

## Quando usar
Use para cliente novo, empresa sem ZIP/XML do eSocial ou empresa que será preparada manualmente antes da primeira rotina mensal.

## Passo a passo
1. Acesse **Empresas/Implantação**.
2. Vá até a seção **Cadastro de empresa**.
3. Informe **Razão social**, **Nome fantasia** se houver e **CNPJ**.
4. Informe a **Data de abertura** quando a empresa será usada no Simples Fator R.
5. Preencha **WhatsApp** se pretende enviar link/documentos ao cliente.
6. Preencha **Organization ID Nibo** se a empresa já estiver vinculada ao Nibo.
7. Informe o **Pró-labore padrão**.
8. Defina **Início no sistema**.
9. Confira **Início eSocial pelo SaaS**. Ao alterar o início no sistema, o sistema também preenche o início eSocial com a mesma competência.
10. Use **Desativar folha a partir de** somente quando a empresa deve parar de processar folha a partir de uma competência.
11. Escolha o **Ambiente eSocial**: produção restrita ou produção oficial.
12. Marque **Sem folha de pagamento** somente se a empresa não deve entrar no cálculo automático de folha.
13. Marque **Empresa já enviada anteriormente ao eSocial** apenas se o cadastro inicial já existe no eSocial.
14. Clique em **Cadastrar empresa**.

## Depois de cadastrar
Para usar no DP/eSocial, selecione a empresa em **Empresa em trabalho** e cadastre ou importe:

- **Estabelecimentos**: S-1005 ou cadastro manual.
- **Lotações tributárias**: S-1020 ou cadastro manual.
- **Sócios / Pró-laboristas**: S-2300 ou cadastro manual.
- **Rubricas**: use a tela **Rubricas** quando houver S-1010 importado.

Para usar no Simples Fator R, confira se a empresa aparece em **Simples Fator R** na competência desejada.

## Erros comuns
- Deixar **Pró-labore padrão** zerado em empresa que terá folha.
- Marcar **Sem folha de pagamento** e depois esperar que a empresa apareça para cálculo de folha.
- Colocar **Início no sistema** depois da competência que será calculada.
- Cadastrar CNPJ errado ou duplicado.
- Esquecer estabelecimento, lotação ou sócio antes de enviar eSocial.

## Como resolver
Edite a empresa na própria tela **Empresas/Implantação**, corrija os campos e salve. Depois selecione a empresa em **Empresa em trabalho** e complete os cadastros dependentes.

## Observações importantes
Empresa nova sem histórico importado pode ter rubricas padrão criadas pelo fluxo de eSocial quando necessário. Empresa já existente no eSocial deve receber os XMLs para preservar códigos, recibos, rubricas e vínculos corretos.
