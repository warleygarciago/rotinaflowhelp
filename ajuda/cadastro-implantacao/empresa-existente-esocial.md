# Empresa já existente no eSocial

## Quando usar
Use este procedimento quando a empresa já possui cadastro no eSocial e você tem XML ou ZIP exportado.

Esse é o melhor caminho para evitar divergência de recibos, matrículas, validade e rubricas.

## Vídeo passo a passo
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe src="https://www.youtube.com/embed/COLOCAR_ID_DO_VIDEO_AQUI" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allowfullscreen></iframe>
</div>

## Arquivos recomendados
O ZIP deve conter, sempre que possível:

- **S-1000**: dados da empresa.
- **S-1005**: estabelecimentos.
- **S-1020**: lotações tributárias.
- **S-1010**: rubricas.
- **S-2300**: sócios/pró-laboristas.
- **S-2306**: alterações contratuais relevantes.

O **S-1000** é obrigatório para a implantação automática.

## Passo a passo
1. Acesse **Empresas/Implantação**.
2. Use a seção **Implantação automática pelo ZIP do eSocial**.
3. Em **Competência de início no SaaS**, informe a primeira competência que o Rotina Flow vai controlar.
4. Selecione o arquivo **XML ou ZIP**.
5. Clique em **Implantar empresa pelo ZIP**.
6. Aguarde a mensagem de implantação concluída.
7. Leia o resumo: ele informa se criou empresa nova ou atualizou cadastro existente.
8. Selecione a empresa em **Empresa em trabalho**.
9. Confira estabelecimentos, lotações, sócios/pró-laboristas e rubricas.

## O que o sistema faz
- Se encontrar o CNPJ, atualiza a empresa existente.
- Se não encontrar o CNPJ completo, tenta localizar pela raiz do CNPJ.
- Se não encontrar nada, cria uma nova empresa.
- Marca a empresa como já registrada no eSocial.
- Importa dados técnicos como recibo, validade, códigos e rubricas quando os eventos existem no ZIP.

## Após importar
1. Confira o **Ambiente eSocial**.
2. Confira se a empresa ficou com **Empresa já enviada anteriormente ao eSocial** marcada.
3. Acesse **Rubricas**.
4. Classifique as rubricas usadas na folha, principalmente **Pró-labore**, **INSS** e **IRRF**.
5. Só então calcule a folha em **DP/eSocial/DARF**.

## Erros comuns
- Importar ZIP sem S-1000.
- Importar só S-1000 e esquecer S-1010, S-1005, S-1020 ou S-2300.
- Não classificar rubricas importadas antes do primeiro cálculo.
- Escolher competência de início errada.
- Usar XML de empresa vinculada a outro contador.
