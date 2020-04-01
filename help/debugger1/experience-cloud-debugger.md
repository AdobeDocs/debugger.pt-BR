---
description: O Debugger examina as páginas da Web e ajuda a encontrar problemas na implementação das soluções da Experience Cloud
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Documentação técnica da extensão do Chrome do Adobe Experience Cloud Debugger - examine as páginas da Web e compreenda os problemas das implementações da solução da Experience Cloud
seo-title: Extensão do Chrome do Adobe Experience Cloud Debugger
title: Extensão do Adobe Experience Cloud Debugger
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: 9bb030d94db1a1e70ecda3d62caf542d7f750317

---


# Extensão do Adobe Experience Cloud Debugger {#adobe-experience-cloud-debugger-extension}

A [extensão do Adobe Experience Cloud Debugger para Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) avalia as páginas da Web e ajuda a encontrar problemas na implementação das soluções da Experience Cloud.

Use a extensão do Adobe Experience Cloud Debugger com outras soluções de ativação da Adobe para obter um fluxo de trabalho como o seguinte:

1. Use o [Launch](https://docs.adobe.com/content/help/en/launch/using/overview.html) ou o [DTM](https://docs.adobe.com/content/help/en/dtm/using/dtm-home.html) para incorporar o código que ativa as soluções da [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html) nas páginas.

1. Use o [Adobe Cloud Platform Auditor](https://docs.adobe.com/content/help/en/auditor/using/overview.html) para testar as implementações.
1. Use a extensão do Adobe Experience Cloud Debugger para depurar os problemas encontrados pelo Auditor ou para examinar outras informações sobre as implementações.

As etapas acima não são necessariamente executadas nessa ordem, mas é um processo comum.

Embora seja possível executar o depurador em qualquer página da Web, todos os dados não públicos estarão disponíveis na extensão somente se você estiver autenticado na Experience Cloud em uma das guias abertas do Chrome.

## Casos de uso {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Use o Debugger para coletar informações que ajudam a entender como as soluções da Experience Cloud são implementadas. Por exemplo:

* **Experience Platform Launch:** veja a propriedade, o ambiente e o build que são implantados em uma página.
* **Target**: veja para quais atividades você está qualificado ou não e por quê.
