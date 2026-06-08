# Como implantar empresa existente pelo eSocial

## Resumo
Este tutorial mostra como implantar uma empresa que já existe no eSocial usando XML ou ZIP. O sistema lê os eventos e monta a empresa, estabelecimentos, lotações, rubricas e pró-laboristas.

## Vídeo passo a passo
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe src="https://www.youtube.com/embed/COLOCAR_ID_DO_VIDEO_AQUI" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allowfullscreen></iframe>
</div>

## Quando usar
Use quando a empresa já foi enviada ao eSocial antes de entrar no Rotina Flow.

Este é o caminho recomendado para empresa já existente, porque preserva dados técnicos como recibos, validade, matrícula e códigos de eventos importados.

## O que o ZIP/XML precisa conter
O arquivo deve conter o **S-1000** da empresa. Quando disponíveis, inclua também:

- **S-1005**: estabelecimentos.
- **S-1020**: lotações tributárias.
- **S-1010**: rubricas.
- **S-2300**: sócios/pró-laboristas.
- **S-2306**: alterações de TSVE, quando houver histórico relevante.

## Passo a passo
1. Acesse **Empresas/Implantação**.
2. No topo da tela, use a seção **Implantação automática pelo ZIP do eSocial**.
3. Em **Competência de início no SaaS**, escolha a primeira competência que o Rotina Flow deve controlar.
4. Em **Arquivo XML ou ZIP**, selecione o arquivo exportado do eSocial.
5. Clique em **Implantar empresa pelo ZIP**.
6. Aguarde a mensagem **Implantação por XML concluída com sucesso**.
7. Confira o resumo da importação.
8. Em **Empresa em trabalho**, selecione a empresa importada.
9. Revise **Estabelecimentos**, **Lotações tributárias**, **Sócios / Pró-laboristas** e **Rubricas**.

## Como o sistema trata empresa já cadastrada
Se o CNPJ do XML já existir no Rotina Flow, o sistema atualiza o cadastro existente em vez de criar outro.

Se não encontrar o CNPJ completo, o sistema tenta localizar empresa pelo começo do CNPJ raiz. Se ainda assim não encontrar, cria uma nova empresa.

## Depois da implantação
1. Revise o **Ambiente eSocial** da empresa.
2. Confira se **Empresa já enviada anteriormente ao eSocial** ficou marcada.
3. Verifique se os estabelecimentos e lotações têm **iniValid** e recibos quando vierem do XML.
4. Na tela **Rubricas**, classifique a finalidade das rubricas importadas, principalmente pró-labore, INSS e IRRF.
5. Só depois siga para **DP/eSocial/DARF** para calcular folha ou enviar eventos mensais.

## Erros comuns
- Enviar ZIP/XML sem S-1000.
- Importar XML de empresa vinculada a outro contador.
- Escolher competência de início errada.
- Não importar rubricas S-1010 e depois tentar calcular empresa já existente.
- Importar apenas S-1000 e esquecer S-1005, S-1020 ou S-2300.

## Como resolver
Monte um novo ZIP com os eventos cadastrais necessários e importe novamente. O sistema atualiza a empresa existente quando encontra o mesmo CNPJ.

## Observações importantes
Para empresa já existente no eSocial, não cadastre tudo manualmente se você possui XMLs. A importação reduz rejeições por código, validade, recibo e matrícula divergente.
