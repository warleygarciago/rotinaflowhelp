# Como preparar empresa para o Simples Fator R

## Resumo
Este tutorial mostra quais dados do cadastro único da empresa impactam a apuração do Simples Fator R. O cadastro fica em **Empresas/Implantação** e também é usado pela folha, DP e eSocial.

## Vídeo passo a passo
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe src="https://www.youtube.com/embed/COLOCAR_ID_DO_VIDEO_AQUI" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allowfullscreen></iframe>
</div>

## Quando usar
Use antes da primeira apuração do Simples ou quando a empresa não aparece corretamente em **Simples Fator R**.

## Antes de começar
Se a empresa ainda não existe no sistema, escolha um dos procedimentos:

- [Como cadastrar empresa nova](../configuracoes-gerais/cadastrar-empresa-nova.md)
- [Como implantar empresa existente pelo eSocial](../configuracoes-gerais/implantar-empresa-existente-esocial.md)

## Campos importantes para o Simples
- **CNPJ**: usado para localizar documentos, NFS-e e vínculos.
- **Data de abertura**: ajuda o sistema a tratar empresas novas e proporcionalidade quando aplicável.
- **Início no sistema**: define a partir de qual competência a empresa entra na rotina.
- **Organization ID Nibo**: usado quando o fiscal busca organizações/NFS-e pelo Nibo Empresa.
- **Pró-labore padrão** e folhas calculadas: usados indiretamente no Fator R quando a folha entra na base dos últimos 12 meses.
- **Sem folha de pagamento**: pode afetar a disponibilidade de folha para compor Fator R.

## Passo a passo
1. Acesse **Empresas/Implantação**.
2. Procure a empresa em **Empresa em trabalho**.
3. Se precisar alterar dados, clique em **Editar** na empresa.
4. Confira **CNPJ**, **Data de abertura**, **Início no sistema** e **Organization ID Nibo**.
5. Salve as alterações.
6. Acesse **Simples Fator R**.
7. Selecione a competência e busque a empresa.
8. Clique em **Sincronizar Nibo** quando precisar atualizar organizações/NFS-e.
9. Calcule ou recalcule a empresa.

## Erros comuns
- Empresa não aparece porque a competência é anterior ao **Início no sistema**.
- Data de abertura vazia em empresa recém-aberta.
- Organization ID Nibo ausente quando a rotina depende da integração.
- Folha sem cálculo ou base histórica incompleta, afetando o Fator R.

## Como resolver
Corrija o cadastro em **Empresas/Implantação** e volte para **Simples Fator R**. Se o problema for base histórica, use as funções de bases/folhas históricas da tela fiscal antes de transmitir.

## Observações importantes
O Simples não tem um cadastro separado de empresa. Ele usa a mesma empresa cadastrada para DP/eSocial, com dados fiscais e integrações revisados.
