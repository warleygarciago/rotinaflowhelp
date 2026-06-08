# Cadastro e implantação de empresa

## Objetivo
Implantar a empresa uma vez, do jeito certo, para que ela funcione nos módulos **DP/eSocial/DARF** e **Simples Fator R**.

O Rotina Flow não tem um cadastro separado para cada módulo. A empresa cadastrada em **Empresas/Implantação** é a base comum para folha, eSocial, Simples, Nibo, WhatsApp e documentos mensais.

## Vídeo passo a passo
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe src="https://www.youtube.com/embed/COLOCAR_ID_DO_VIDEO_AQUI" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allowfullscreen></iframe>
</div>

## Antes de cadastrar, decida o caminho

### Caminho A: empresa nova
Use quando a empresa ainda não tem histórico no Rotina Flow e você vai cadastrar os dados manualmente.

Exemplo: cliente novo, empresa recém-aberta ou empresa sem XML de implantação disponível.

Tutorial: [Empresa nova](empresa-nova.md)

### Caminho B: empresa já existente no eSocial
Use quando a empresa já foi enviada ao eSocial antes de entrar no Rotina Flow.

Exemplo: empresa que já tem S-1000, S-1005, S-1020, S-1010 ou S-2300 no eSocial.

Tutorial: [Empresa já existente no eSocial](empresa-existente-esocial.md)

## O que eu faria como implantação correta
1. Acessaria **Empresas/Implantação**.
2. Verificaria se a empresa já existe no eSocial.
3. Se já existe, importaria primeiro o ZIP/XML do eSocial.
4. Se não existe, cadastraria manualmente a empresa.
5. Conferiria **CNPJ**, **início no sistema**, **ambiente eSocial** e **pró-labore padrão**.
6. Selecionaria a empresa em **Empresa em trabalho**.
7. Conferiria ou cadastraria **Estabelecimentos**.
8. Conferiria ou cadastraria **Lotações tributárias**.
9. Conferiria ou cadastraria **Sócios / Pró-laboristas**.
10. Se houver eSocial importado, revisaria a tela **Rubricas**.
11. Só depois seguiria para a competência mensal.

## Campos que merecem atenção
- **CNPJ**: localiza empresa em notas, folha, eSocial e integrações.
- **Data de abertura**: importante para o Simples em empresas novas.
- **Pró-labore padrão**: usado na folha se o sócio não tiver valor próprio.
- **Início no sistema**: primeira competência em que a empresa entra no Rotina Flow.
- **Início eSocial pelo SaaS**: primeira competência enviada pelo Rotina Flow ao eSocial.
- **Desativar folha a partir de**: remove a empresa da folha a partir da competência informada.
- **Ambiente eSocial**: produção restrita ou produção oficial.
- **Sem folha de pagamento**: empresa não entra no cálculo automático de folha.
- **Empresa já enviada anteriormente ao eSocial**: indica que o cadastro inicial já existe no eSocial.
- **Organization ID Nibo**: vínculo para Nibo e notas fiscais.
- **WhatsApp**: usado para enviar links e documentos ao cliente.

## Resultado esperado
No fim da implantação, a empresa deve aparecer corretamente em **DP/eSocial/DARF** e em **Simples Fator R**, respeitando a competência escolhida.
