---
title: Guia Rede
description: Saiba como usar a guia Rede no Adobe Experience Platform Debugger.
keywords: depurador;extensão do Experience Platform Debugger;chrome;extensão;rede;informações
seo-description: Experience Platform Debugger Network screen
seo-title: Network Tab
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
exl-id: ed0579ef-ec26-43df-9453-a395c105038a
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '215'
ht-degree: 59%

---

# Guia Rede

A variável **Rede** A guia agrega todas as chamadas da solução do Adobe Experience Cloud feitas na página e as exibe da esquerda para a direita. Os parâmetros padrão são identificados automaticamente com nomes familiares e organizados para agrupar parâmetros comuns na mesma função.

![](assets/network.jpg)

Essa tela é útil para comparar pares de valores importantes entre ocorrências. É possível confirmar se os parâmetros usados para integrações, como a ID de visitante da Experience Cloud ou a ID de dados complementares, são consistentes em todas as integrações.

>[!NOTE]
>
>No momento, nem todos os parâmetros transmitidos nas chamadas da solução (por exemplo, variáveis de contexto do Analytics, parâmetros personalizados do Target ou IDs do cliente do serviço da Experience Cloud ID) estão visíveis na tela Rede.

Para alterar as informações por solução, selecione a solução que deseja exibir na lista da navegação à esquerda. O exemplo a seguir for filtrado para mostrar somente o Analytics:

![](assets/network-analytics.jpg)

Para voltar a exibir todas as soluções, selecione **[!UICONTROL Network]**

Selecione em um item na exibição Rede para ter uma exibição expandida. Na janela de exibição expandida, é possível copiar as informações mostradas para a Área de transferência.

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

Para limpar a lista, selecione **[!UICONTROL Remove Events]**.

Para baixar um arquivo do Excel que contém as informações nesta tela, selecione **[!UICONTROL Download]**.
