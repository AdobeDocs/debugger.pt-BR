---
title: Referência do teste de consistência de tag
description: Saiba como o recurso do auditor testa a consistência de tags no Adobe Experience Platform Debugger.
exl-id: 642b0c49-a7c7-4142-8189-67f00ed50015
source-git-commit: f18828bcaa0d244bd5b117fd8bf1c1cdba4d4b52
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 43%

---

# Referência do teste de consistência da tag

Esta referência fornece mais informações sobre como o recurso de auditor no Adobe Experience Platform Debugger testa a consistência de tags.

>[!NOTE]
>
>Para obter mais informações sobre testes do auditor no Platform Debugger, consulte a [visão geral dos recursos do auditor](./overview.md).

Os testes de consistência de tags procuram inconsistências em todas as páginas digitalizadas. Esses são valores ou configurações que devem ser os mesmos em todas as páginas do site para garantir uma coleta de dados precisa.

| Teste | Peso | Critérios | Recomendação |
| --- | --- | --- | --- |
| Adobe Analytics - Versão de código consistente | 5 | Mais de uma versão do código do Analytics foi encontrada. | Substitua todas as instâncias do Analytics pela versão atual.<br><br>[Informações adicionais](https://experienceleague.adobe.com/docs/analytics/implementation/home.html?lang=pt-BR) |

{style="table-layout:auto"}
