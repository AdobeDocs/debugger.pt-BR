---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;tools;dtm;target
seo-description: 'null'
seo-title: Ferramentas
title: Ferramentas
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: b9147536b8312599dd3144cac31dea9f0f1c3625

---


# Ferramentas {#tools}

Na tela Ferramentas, você pode ativar ou desativar várias ferramentas para a solução instalada. Por exemplo, você pode ativar as instruções de depuração do console do Target ou usar a Biblioteca de preparo do DTM. Essas ferramentas só estarão disponíveis se o Target e o DTM estiverem instalados na página.

![](assets/tools.jpg)

Você pode inserir dinamicamente o Launch ou DTM em qualquer página para testar algo em uma página que não tenha o Launch ou o DTM instalado. Click the **[!UICONTROL Embed Code]** icon, then type your [embed code](https://experiencecloud.adobe.com/resources/help/en_US/dtm/deployment.html) and click **[!UICONTROL Save]**.

![](assets/tools-embedcode.jpg)

## Informações do DTM {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Ferramenta </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> Registro do console do DTM </p> </td> 
   <td colname="col2"> <p>Essa ferramenta expõe as instruções de depuração específicas do DTM para o console do navegador. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Usar biblioteca de preparo </p> </td> 
   <td colname="col2"> <p>Essa ferramenta usa a biblioteca de preparo para obter as informações de depuração do DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Desativar DTM </p> </td> 
   <td colname="col2"> <p>Essa ferramenta bloqueia a verificação das informações do DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Inserir dinamicamente o DTM </p> </td> 
   <td colname="col2"> <p> Essa ferramenta insere o código do DTM na página. Use o editor do Código de incorporação para editar o código inserido. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Informações do Target {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Ferramenta </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Registro do console do Target </p> </td> 
   <td colname="col2"> <p>Esta ferramenta expõe as instruções de depuração específicas do Target para o console do navegador, tudo começando com o prefixo <span class="codeph"> AT:</span>, adicionando um cookie chamado <span class="codeph">mboxDebug=true</span> no navegador. No momento, as instruções do console não aparecem na tela Registros do depurador, mas são visíveis no console de depuração nativo do navegador. </p> <p> Esta ferramenta requer o at.js 0.9.6+. Se você estiver usando uma versão anterior do at.js, poderá adicionar o parâmetro da sequência de consulta <span class="codeph">?mboxDebug=true</span> ao URL para ativar o registro do console. Se você estiver usando o mbox.js, poderá adicionar o parâmetro <span class="codeph">?_AT_Debug=console</span> para ativar o registro do console limitado às atividades do Visual Experience Composer. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Ativar Mbox Traces </p> </td> 
   <td colname="col2"> <p>Esta ferramenta adiciona as informações detalhadas nas respostas do Target, que podem ser exploradas na tela <span class="uicontrol">Target&gt;Mbox Trace</span> do depurador. </p> <p> Você deve fazer logon na Experience Cloud em uma das guias do Chrome para ativar essa ferramenta. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Desativar o Target </p> </td> 
   <td colname="col2"> <p>Esta ferramenta desativa todas as solicitações do Target, adicionando um cookie chamado <span class="codeph">mboxDisable=true</span> no navegador. </p> <p> Esta ferramenta requer o at.js 0.9.6+. Se você estiver usando uma versão mais antiga, poderá adicionar o parâmetro da sequência de consulta <span class="codeph">?mboxDisable=true </span> ao URL para desativar mboxes. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Realce da mbox </p> </td> 
   <td colname="col2"> <p> Esta ferramenta desenha uma caixa vermelha em torno das mboxes herdadas no estilo de quebra automática. </p> </td> 
  </tr> 
 </tbody> 
</table>

O vídeo a seguir explica como usar a extensão do Depurador com o Adobe Target.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=por_br)