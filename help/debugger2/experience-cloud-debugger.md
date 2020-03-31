---
description: O Debugger examina as páginas da Web e ajuda a encontrar problemas na implementação das soluções da Experience Cloud
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Documentação técnica da extensão do Chrome e do Firefox do Adobe Experience Cloud Debugger 2.0 - examine as páginas da Web e compreenda os problemas das implementações da solução da Experience Cloud
seo-title: Adobe Experience Platform Debugger Chrome e Firefox Extension
title: Adobe Experience Platform Debugger Extension
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: dc723f0848c56794e9a1a6eda405de2f4ea6b8fa

---


# (Beta) Adobe Experience Platform Debugger 2.0 {#adobe-experience-platform-debugger}

> [!IMPORTANT]
>
> O Adobe Experience Cloud Debugger 2.0 está atualmente em beta. A documentação e a funcionalidade estão sujeitas a alterações.

The [Adobe Experience Platform Debugger for Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/adobe-experience-platform-dbg/) examines your web pages and helps you find problems with how your Experience Cloud solutions are implemented.

Use o Adobe Experience Platform Debugger com outras soluções de ativação da Adobe para obter um fluxo de trabalho como:

1. Use o [Launch](https://docs.adobe.com/content/help/en/launch/using/overview.html) ou o [DTM](https://docs.adobe.com/content/help/en/dtm/using/dtm-home.html) para incorporar o código que ativa as soluções da [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) nas páginas.

1. Use o [Adobe Cloud Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) para testar as implementações.
1. Use o Adobe Experience Platform Debugger para depurar problemas encontrados pelo Auditor ou para examinar outras informações sobre suas implementações.

As etapas acima não são necessariamente executadas nessa ordem, mas é um processo comum.

Embora seja possível executar o depurador em qualquer página da Web, todos os dados não públicos estarão disponíveis na extensão somente se você estiver autenticado na Experience Cloud em uma das guias abertas do Chrome.

## Casos de uso {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Use o Debugger para coletar informações que ajudam a entender como as soluções da Experience Cloud são implementadas. Por exemplo:

* **Iniciar:** Veja qual propriedade, ambiente e compilação são implantados em uma página.
* **Target**: veja para quais atividades você está qualificado ou não e por quê.
