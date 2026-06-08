# Cadastro de empresa no Rotina Flow

## Resumo
O cadastro de empresa é único e atende os dois módulos principais do Rotina Flow: Simples Fator R e DP/eSocial/DARF.

Existem dois caminhos diferentes de implantação:

1. Empresa nova no sistema, cadastrada manualmente.
2. Empresa já existente no eSocial, implantada por ZIP/XML.

Escolha o caminho conforme a situação real da empresa.

## Vídeo passo a passo
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe src="https://www.youtube.com/embed/COLOCAR_ID_DO_VIDEO_AQUI" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allowfullscreen></iframe>
</div>

## Quando usar
Use antes de começar qualquer rotina mensal de Simples, folha, eSocial, DCTFWeb, DARF, Nibo ou WhatsApp.

## Caminho 1: empresa nova
Use quando a empresa ainda não foi implantada no Rotina Flow e você vai preencher os dados manualmente.

Abra o tutorial: [Como cadastrar empresa nova](cadastrar-empresa-nova.md)

Esse caminho usa a seção **Cadastro de empresa** em **Empresas/Implantação**.

## Caminho 2: empresa já existente no eSocial
Use quando a empresa já possui eventos no eSocial e você tem XML ou ZIP exportado do eSocial.

Abra o tutorial: [Como implantar empresa existente pelo eSocial](implantar-empresa-existente-esocial.md)

Esse caminho usa a seção **Implantação automática pelo ZIP do eSocial** em **Empresas/Implantação**.

## Campos que impactam os módulos
- **CNPJ**: identifica a empresa em todos os módulos.
- **Data de abertura**: usada na apuração fiscal do Simples quando necessário.
- **Pró-labore padrão**: valor base usado pela folha quando o sócio não tem valor próprio.
- **Início no sistema**: primeira competência considerada pelo sistema.
- **Início eSocial pelo SaaS**: primeira competência enviada/calculada pelo Rotina Flow no eSocial.
- **Desativar folha a partir de**: impede cálculo de folha em competências posteriores.
- **Ambiente eSocial**: produção restrita ou produção oficial.
- **Sem folha de pagamento**: remove a empresa do motor automático de folha.
- **Empresa já enviada anteriormente ao eSocial**: indica que o cadastro inicial já existe no eSocial.
- **Organization ID Nibo**: vincula a empresa para entregas e integrações quando aplicável.
- **WhatsApp**: usado para envio de links e documentos ao cliente.

## Erros comuns
- Cadastrar manualmente uma empresa que já deveria ser implantada por XML do eSocial.
- Marcar **Sem folha de pagamento** em empresa que deve calcular pró-labore.
- Escolher produção restrita quando a empresa deve operar em produção oficial.
- Informar competência de início posterior à competência que será processada.
- Não importar S-1010, S-1005, S-1020 ou S-2300 para empresa já existente no eSocial.

## Como resolver
Revise primeiro qual caminho de implantação se aplica. Se a empresa já existe no eSocial, prefira importar o ZIP/XML. Se a empresa é nova ou não tem histórico a importar, faça o cadastro manual e depois complete estabelecimento, lotação e sócio/pró-laborista.

## Observações importantes
O cadastro da empresa não pertence exclusivamente ao Simples nem exclusivamente à folha. Ele é a base comum para os dois módulos.
