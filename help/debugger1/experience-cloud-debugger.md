---
description: O Debugger examina as páginas da Web e ajuda a encontrar problemas na implementação das soluções da Experience Cloud
keywords: depurador, extensão do experience cloud debugger, chrome, extensão
seo-description: Technical documentation for the Adobe Experience Cloud Debugger Chrome Extension - examine your web pages and understand problems with your Experience Cloud solution mplementations
seo-title: Adobe Experience Cloud Debugger Chrome Extension
title: Extensão do Adobe Experience Cloud Debugger
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
exl-id: 02d88172-3fb1-4111-a80d-e9d46df9ea1e
source-git-commit: bb3891dabd8721fe9e81bffac8e97fd2866b676b
workflow-type: tm+mt
source-wordcount: '270'
ht-degree: 85%

---

# Extensão do Adobe Experience Cloud Debugger{#adobe-experience-cloud-debugger-extension}

>[!IMPORTANT]
>
>Há uma nova versão do Debugger disponível no momento. O novo Adobe Experience Platform Debugger pode ser encontrado [here](https://chrome.google.com/webstore/detail/adobe-experience-platform/bfnnokhpnncpkdmbokanobigaccjkpob).

A [extensão do Adobe Experience Cloud Debugger para Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) avalia as páginas da Web e ajuda a encontrar problemas na implementação das soluções da Experience Cloud.

Use a extensão do Adobe Experience Cloud Debugger com outras soluções de ativação da Adobe para obter um fluxo de trabalho como o seguinte:

1. Use [Adobe Experience Platform Launch](https://experienceleague.adobe.com/docs/launch/using/home.html?lang=pt-BR) para inserir o código que ativa [Adobe Experience Cloud](https://experienceleague.adobe.com/docs/home.html) nas suas páginas.

1. Use o [Adobe Experience Platform Auditor](https://docs.adobe.com/content/help/pt-BR/auditor/using/overview.html) para testar as implementações.
1. Use a extensão do Adobe Experience Cloud Debugger para depurar os problemas encontrados pelo Auditor ou para examinar outras informações sobre as implementações.

As etapas acima não são necessariamente executadas nessa ordem, mas é um processo comum.

Embora seja possível executar o depurador em qualquer página da Web, todos os dados não públicos estarão disponíveis na extensão somente se você estiver autenticado na Experience Cloud em uma das guias abertas do Chrome.

## Casos de uso {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Use o Debugger para coletar informações que ajudam a entender como as soluções da Experience Cloud são implementadas. Por exemplo:

* **Platform Launch:** veja qual propriedade, ambiente e build estão implementados em uma página.
* **Target:** veja para quais atividades você está qualificado ou não e por quê.
