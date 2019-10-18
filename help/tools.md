---
description: 'null'
keywords: depurador;extensão do depurador da Experience Cloud;chrome;extension;ferramentas;dtm;target
seo-description: 'null'
seo-title: Ferramentas
title: Ferramentas
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Ferramentas{#tools}

Na tela Ferramentas, você pode ativar ou desativar várias ferramentas para a solução instalada. Por exemplo, você pode ativar as instruções de depuração do console do Target ou usar a Biblioteca de preparo do DTM. Essas ferramentas só estarão disponíveis se o Target e o DTM estiverem instalados na sua página.

![](assets/tools.jpg)

Você pode inserir dinamicamente Launch ou DTM em qualquer página para testar algo em uma página que não tenha Launch ou DTM instalado. Clique no ícone **[!UICONTROL Incorporar código]** , digite o código [](https://experiencecloud.adobe.com/resources/help/en_US/dtm/deployment.html) incorporado e clique em **[!UICONTROL Salvar]**.

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
   <td colname="col2"> <p>Essa ferramenta expõe instruções de depuração específicas do DTM ao console do navegador. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Usar biblioteca de preparo </p> </td> 
   <td colname="col2"> <p>Essa ferramenta usa a biblioteca de preparo para obter informações de depuração do DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Desativar DTM </p> </td> 
   <td colname="col2"> <p>Essa ferramenta impede que as informações do DTM sejam verificadas. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Inserir dinamicamente o DTM </p> </td> 
   <td colname="col2"> <p> Essa ferramenta insere o código do DTM na sua página. Use o editor de código incorporado para editar o código inserido. </p> </td> 
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
   <td colname="col2"> <p><span class="codeph"> Esta ferramenta expõe instruções de depuração específicas do Target ao console do navegador, tudo começando com o </span> AT: , adicionando um cookie chamado <span class="codeph"> mboxDebug=true</span> ao seu navegador. No momento, as instruções do console não aparecem na tela Registros do depurador, mas são visíveis no console de depuração nativo do navegador. </p> <p> Esta ferramenta requer o at.js 0.9.6+. Se você estiver usando uma versão anterior do at.js, poderá adicionar o parâmetro <span class="codeph"> ?mboxDebug=true</span> da string de consulta ao URL para ativar o registro no console. Se você estiver usando o mbox.js, poderá adicionar o parâmetro <span class="codeph"> ?_AT_Debug=console</span> para ativar o log do console limitado às atividades do Visual Experience Composer. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Ativar rastreamentos de mbox </p> </td> 
   <td colname="col2"> <p>Essa ferramenta adiciona informações detalhadas às respostas do Target, que podem ser exploradas na tela <span class="uicontrol"> Target&gt;Rastreamento</span> da mbox do depurador. </p> <p> Você deve ter feito logon na Experience Cloud em uma de suas guias do Chrome para habilitar essa ferramenta. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Desativar o Target </p> </td> 
   <td colname="col2"> <p>Esta ferramenta desativa todas as solicitações do Target adicionando um cookie chamado <span class="codeph"> mboxDisable=true</span> ao seu navegador. </p> <p> Esta ferramenta requer o at.js 0.9.6+. Se você estiver usando uma versão mais antiga, poderá adicionar o parâmetro <span class="codeph"> ?mboxDisable=true </span>query string ao seu URL para desativar mboxes. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Realce da mbox </p> </td> 
   <td colname="col2"> <p> Esta ferramenta desenha uma caixa vermelha em torno de mboxes legadas e de estilo de quebra automática. </p> </td> 
  </tr> 
 </tbody> 
</table>

O vídeo a seguir explica como usar a extensão do Depurador com o Adobe Target.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=por_br)
