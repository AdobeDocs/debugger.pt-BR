---
description: O Experience Platform Debugger examina as páginas da Web e ajuda a encontrar problemas na implementação das soluções da Experience Cloud
keywords: depurador, extensão do Experience Platform Debugger, chrome, extensão
seo-description: Documentação técnica da extensão do Chrome e do Firefox do Adobe Experience Platform Debugger - examine as páginas da Web e compreenda os problemas das implementações da solução da Experience Cloud
seo-title: Extensão do Chrome e do Firefox do Adobe Experience Platform Debugger
title: Extensão do Adobe Experience Platform Debugger
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
exl-id: e02bc318-fbff-4a19-980a-d5c0a21ca300
source-git-commit: e3f0fa30fa5caeccc9a01b5d1949722836645da9
workflow-type: tm+mt
source-wordcount: '312'
ht-degree: 97%

---

# (Beta) Adobe Experience Platform Debugger {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>O Adobe Experience Platform Debugger atualmente está na versão beta. A documentação e a funcionalidade estão sujeitas a alterações.

O [Adobe Experience Platform Debugger para Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) e [Firefox](https://addons.mozilla.org/pt-BR/firefox/addon/adobe-experience-platform-dbg/) avalia as páginas da Web e ajuda a encontrar problemas na implementação das soluções da Experience Cloud.

Use o Platform Debugger com outras soluções de ativação da Adobe para obter um fluxo de trabalho como o seguinte:

1. Use o [Launch](https://experienceleague.adobe.com/docs/launch/using/home.html?lang=pt-BR) ou o [DTM](https://docs.adobe.com/content/help/pt-BR/dtm/using/dtm-home.html) para incorporar o código que ativa as soluções da [Adobe Experience Cloud](https://docs.adobe.com/content/help/pt-BR/core-services/interface/experience-cloud.html) nas páginas.

1. Use o [Adobe Experience Platform Auditor](https://docs.adobe.com/content/help/pt-BR/auditor/using/overview.html) para testar as implementações.
1. Use o Adobe Experience Platform Debugger para depurar os problemas encontrados pelo Auditor ou para examinar outras informações sobre as implementações.

As etapas acima não são necessariamente executadas nessa ordem, mas é um processo comum.

Embora seja possível executar o Platform Debugger em qualquer página da Web, todos os dados não públicos estarão disponíveis na extensão somente se você estiver autenticado na Experience Cloud em uma das guias abertas do Chrome.

## Casos de uso {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Use o Platform Debugger para coletar informações que ajudam a entender como as soluções da Experience Cloud são implementadas. Por exemplo:

* **Adobe Experience Platform Launch:** veja qual propriedade, ambiente e build estão implementados em uma página.
* **Target:** veja para quais atividades você está qualificado ou não e por quê.

## Tutorial em vídeo

>[!VIDEO](https://video.tv.adobe.com/v/32156?quality=12&learn=on)
