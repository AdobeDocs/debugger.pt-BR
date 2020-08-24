---
description: Execução do Experience Cloud Debugger
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: Execução do Experience Cloud Debugger
seo-title: Tela Resumo
title: Tela Resumo
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: ht
source-git-commit: 1d81f427e2c1a68a182fae8262d0e2ad32a87223
workflow-type: ht
source-wordcount: '1035'
ht-degree: 100%

---


# Tela Resumo {#summary-screen}

Para executar o Experience Cloud Debugger, clique no ícone de extensão na barra de extensão e abra a página que deseja examinar no Chrome.

![](assets/start-icon.jpg)

A tela Resumo do Adobe Experience Cloud Debugger é exibida.

![](assets/summary.jpg)

Essa tela mostra uma miniatura da página, bem como o URL e o título da página. Ela também mostra informações sobre cada solução da Adobe Experience Cloud. As informações mostradas variam de acordo com a solução, mas geralmente incluem informações como biblioteca e versão da solução (por exemplo, &quot;AppMeasurement v2.9&quot;) e identificadores de conta (como a ID do conjunto de relatórios do Analytics, o código de cliente do Target, a ID de parceiro do Audience Manager, etc).

Os números em azul ao lado das guias na parte superior da janela mostram o número de chamadas de servidor efetuadas. Você pode redefinir esses números como zero ao clicar em **[!UICONTROL Clear All Requests]** na respectiva guia.

Por exemplo, a imagem a seguir mostra informações sobre o Adobe Target. Observe que para expor os detalhes da atividade descritos abaixo sem autenticação, você deve implementar o ouvinte de eventos de Depuração no código ou gerenciador de tags e ativar os [tokens de resposta](https://docs.adobe.com/content/help/pt-BR/target/using/administer/response-tokens.html) necessários na interface do usuário do Target.

![](assets/summary-target2.jpg)

## Executar uma auditoria no Auditor {#section-82bc57440406461ebf27a16855b71655}

Você pode usar o Adobe Auditor para executar uma série de auditorias na página. Para executar o Auditor, clique em **[!UICONTROL Auditor]** no menu superior e, em seguida, em **[!UICONTROL Audit Page Now]**. Para abrir o Adobe Auditor, clique em **[!UICONTROL Run Multi-Page Audit Now]**.

## Informações mostradas no Debugger {#section-88a95ba53dca43d9b96a585e75e5f5cf}

O Debugger mostra as seguintes informações para cada solução:

**Informações da página**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Captura de tela da página </p> </td> 
   <td colname="col2"> <p>Miniatura da página </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>URL da página </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Título </p> </td> 
   <td colname="col2"> <p>O nome especificado na tag <span class="codeph">&lt;TITLE&gt;</span> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Conjuntos de relatórios </p> </td> 
   <td colname="col2"> <p>Um <a href="https://docs.adobe.com/content/help/pt-BR/analytics/admin/manage-report-suites/report-suites-admin.html" format="html" scope="external">conjunto de relatórios</a> define o relatório completo e independente de um site escolhido, o conjunto de sites ou o subconjunto de páginas da Web. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versão </p> </td> 
   <td colname="col2"> <p>A versão do <a href="https://docs.adobe.com/content/help/pt-BR/analytics/implementation/js/overview.html" format="html" scope="external"> AppMeasurement</a> definida para a página. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versão do visitante </p> </td> 
   <td colname="col2"> <p>A versão da biblioteca de <a href="https://docs.adobe.com/content/help/pt-BR/analytics/components/metrics/unique-visitors.html" format="html" scope="external">ID de visitante</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nome da página </p> </td> 
   <td colname="col2"> <p>A variável <a href="https://docs.adobe.com/content/help/pt-BR/analytics/implementation/vars/page-vars/page-variables.html" format="html" scope="external">pageName</a> enviada ao Analytics que contém um nome familiar do site. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Módulos </p> </td> 
   <td colname="col2"> <p>Os módulos carregados pelo Adobe Analytics. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Parceiro </p> </td> 
   <td colname="col2"> <p>O <a href="https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/dil-api/dil-instance-methods.html#getpartner" format="html" scope="external">nome do parceiro</a> para a instância DIL. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versão </p> </td> 
   <td colname="col2"> <p>O <a href="https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/api-and-sdk-code/rest-apis/aam-api-dil-methods.html#return-version-dil" format="html" scope="external">número da versão</a> da instância DIL. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>A <a href="https://docs.adobe.com/content/help/pt-BR/audience-manager/user-guide/reference/ids-in-aam.html" format="html" scope="external">ID de usuário exclusiva</a> associada à instância DIL. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nome </p> </td> 
   <td colname="col2"> <p>O nome da <a href="https://docs.adobe.com/content/help/pt-BR/launch/using/reference/admin/companies-and-properties.html" format="https" scope="external">propriedade</a> do Adobe Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versão </p> </td> 
   <td colname="col2"> <p>A versão da <a href="https://developer.adobelaunch.com/extensions/reference/turbine-free-variable/" format="https" scope="external">Turbina</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Data de build </p> </td> 
   <td colname="col2"> <p>A data de build da <a href="https://docs.adobe.com/content/help/pt-BR/launch/using/reference/publish/libraries.html" format="https" scope="external">biblioteca</a> do Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ambiente </p> </td> 
   <td colname="col2"> <p>O <a href="https://docs.adobe.com/content/help/pt-BR/launch/using/reference/publish/environments.html" format="https" scope="external">ambiente</a> usado pela biblioteca do Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Diretório de script </p> </td> 
   <td colname="col2"> <p>O diretório onde o script do Launch está armazenado. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nome da biblioteca </p> </td> 
   <td colname="col2"> <p>O nome da <a href="https://docs.adobe.com/content/help/pt-BR/dtm/using/library-management.html" format="html" scope="external">biblioteca</a> do Adobe DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versão </p> </td> 
   <td colname="col2"> <p>A versão da Turbina. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Data de build </p> </td> 
   <td colname="col2"> <p>A data de build da <a href="https://docs.adobe.com/content/help/pt-BR/dtm/using/library-management.html" format="html" scope="external">biblioteca</a> do Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ambiente </p> </td> 
   <td colname="col2"> <p>O ambiente usado pela biblioteca do DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Diretório de script </p> </td> 
   <td colname="col2"> <p>O diretório onde o script do DTM está armazenado. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Serviço da Adobe Experience Cloud ID**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>ID da organização da Experience Cloud </p> </td> 
   <td colname="col2"> <p>A <a href="https://docs.adobe.com/content/help/pt-BR/id-service/using/home.html" format="https" scope="external"> ID da organização</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versão </p> </td> 
   <td colname="col2"> <p>A versão da biblioteca de <a href="https://docs.adobe.com/content/help/pt-BR/analytics/components/metrics/unique-visitors.html" format="html" scope="external">ID de visitante</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Código do cliente </p> </td> 
   <td colname="col2"> <p>O <a href="https://docs.adobe.com/content/help/pt-BR/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external">Código de cliente</a> do Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versão </p> </td> 
   <td colname="col2"> <p>Sua versão atual do <a href="https://docs.adobe.com/content/help/pt-BR/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external">at.js</a> ou mbox.js </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nome da mBox global </p> </td> 
   <td colname="col2"> <p>A <a href="https://docs.adobe.com/help/pt-BR/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">mbox global</a> se refere à única chamada de servidor feita na parte superior de cada página da Web na implementação do Target </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nome da mbox </p> </td> 
   <td colname="col2"> <p>O nome de uma mbox ao redor de um <a href="https://docs.adobe.com/content/help/pt-BR/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">local</a> na página. Disponível sem autenticação somente se você implementar o ouvinte de eventos de Depuração no código ou gerenciador de tags e ativar os <a href="https://docs.adobe.com/content/help/pt-BR/target/using/administer/response-tokens.html" format="html" scope="external">tokens de resposta</a> necessários na interface do usuário do Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nome da atividade </p> </td> 
   <td colname="col2"> <p>O nome da <a href="https://docs.adobe.com/content/help/pt-BR/target/using/activities/activities.html" format="html" scope="external">campanha ou atividade</a> do Target. Disponível sem autenticação somente se você implementar o ouvinte de eventos de Depuração no código ou gerenciador de tags e ativar os <a href="https://docs.adobe.com/content/help/pt-BR/target/using/administer/response-tokens.html" format="html" scope="external">tokens de resposta</a> necessários na interface do usuário do Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID da atividade </p> </td> 
   <td colname="col2"> <p>A ID da atividade do Target. Disponível sem autenticação somente se você implementar o ouvinte de eventos de Depuração no código ou gerenciador de tags e ativar os <a href="https://docs.adobe.com/content/help/pt-BR/target/using/administer/response-tokens.html" format="html" scope="external">tokens de resposta</a> necessários na interface do usuário do Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nome da fórmula </p> </td> 
   <td colname="col2"> <p>O nome da <a href="https://docs.adobe.com/content/help/pt-BR/target/using/experiences/experiences.html" format="html" scope="external">experiência</a> do Target. Disponível sem autenticação somente se você implementar o ouvinte de eventos de Depuração no código ou gerenciador de tags e ativar os <a href="https://docs.adobe.com/content/help/pt-BR/target/using/administer/response-tokens.html" format="html" scope="external">tokens de resposta</a> necessários na interface do usuário do Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID de receita </p> </td> 
   <td colname="col2"> <p>A ID da fórmula do Target. Disponível sem autenticação somente se você implementar o ouvinte de eventos de Depuração no código ou gerenciador de tags e ativar os <a href="https://docs.adobe.com/content/help/pt-BR/target/using/administer/response-tokens.html" format="html" scope="external">tokens de resposta</a> necessários na interface do usuário do Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Oferta </p> </td> 
   <td colname="col2"> <p>O nome da <a href="https://docs.adobe.com/content/help/pt-BR/target/using/experiences/offers/manage-content.html" format="html" scope="external">oferta</a> do Target. Disponível sem autenticação somente se você implementar o ouvinte de eventos de Depuração no código ou gerenciador de tags e ativar os <a href="https://docs.adobe.com/content/help/pt-BR/target/using/administer/response-tokens.html" format="html" scope="external">tokens de resposta</a> necessários na interface do usuário do Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID da oferta </p> </td> 
   <td colname="col2"> <p>A ID da oferta do Target. Disponível sem autenticação somente se você implementar o ouvinte de eventos de Depuração no código ou gerenciador de tags e ativar os <a href="https://docs.adobe.com/content/help/pt-BR/target/using/administer/response-tokens.html" format="html" scope="external">tokens de resposta</a> necessários na interface do usuário do Target. </p> </td> 
  </tr> 
 </tbody> 
</table>

