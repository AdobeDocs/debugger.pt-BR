---
description: O Experience Platform Debugger examina as páginas da Web e ajuda a encontrar problemas na implementação das soluções da Experience Cloud
keywords: debugger;experience Platform Debugger extension;chrome;extension
seo-description: Documentação técnica da extensão do Chrome e do Firefox do Adobe Experience Platform Debugger  - examine as páginas da Web e compreenda os problemas das implementações da solução da Experience Cloud
seo-title: Extensão do Chrome e do Firefox do Adobe Experience Platform Debugger
title: Extensão do Adobe Experience Platform Debugger
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 62%

---


# (Beta) Adobe Experience Platform Debugger {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>O Adobe Experience Platform Debugger atualmente está na versão beta. A documentação e a funcionalidade estão sujeitas a alterações.

[O Adobe Experience Platform Debugger para Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) e [Firefox](https://addons.mozilla.org/pt-BR/firefox/addon/adobe-experience-platform-dbg/) examina suas páginas da Web e ajuda a encontrar problemas com a implementação das soluções para Experience Cloud.

Use o Platform Debugger com outras soluções de ativação de Adobe para um fluxo de trabalho como o seguinte:

1. Use o [Launch](https://docs.adobe.com/content/help/pt-BR/launch/using/overview.html) ou o [DTM](https://docs.adobe.com/content/help/pt-BR/dtm/using/dtm-home.html) para incorporar o código que ativa as soluções da [Adobe Experience Cloud](https://docs.adobe.com/content/help/pt-BR/core-services/interface/experience-cloud.html) nas páginas.

1. Use [Adobe Experience Platform Auditor](https://docs.adobe.com/content/help/pt-BR/auditor/using/overview.html) to test your implementations.
1. Use o Adobe Experience Platform Debugger para depurar os problemas encontrados pelo Auditor ou para examinar outras informações sobre as implementações.

As etapas acima não são necessariamente executadas nessa ordem, mas é um processo comum.

Embora seja possível executar o Platform Debugger em qualquer página da Web, todos os dados não públicos só estarão disponíveis na extensão se você estiver autenticado no Experience Cloud em uma de suas guias abertas do Chrome.

## Casos de uso {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Use o Platform Debugger para coletar informações que ajudam você a entender como suas soluções de Experience Cloud são implementadas. Por exemplo:

* **Adobe Experience Platform Launch:** Veja qual propriedade, ambiente e compilação são implantados em uma página.
* **Target:** veja para quais atividades você está qualificado ou não e por quê.

## Tutorial em vídeo

>[!VIDEO](https://video.tv.adobe.com/v/32156?quality=12&learn=on)