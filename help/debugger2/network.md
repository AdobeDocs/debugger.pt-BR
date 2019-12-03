---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;network;information
seo-description: 'null'
seo-title: Informações de rede
title: Informações de rede
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
translation-type: tm+mt
source-git-commit: 2c3d056451c5b7b4bf5603c22bf3bbdbc693491f

---


# Informações de rede {#network-information}

To view Network information, click **[!UICONTROL Network]**.

A tela Rede agrega todas as chamadas da solução da Adobe Experience Cloud feitas na página e exibe da esquerda para a direita. Os parâmetros padrão são identificados automaticamente com nomes familiares e organizados para agrupar parâmetros comuns na mesma função.

![](assets/network.jpg)

Essa tela é útil para comparar pares de valores chave entre ocorrências. Você pode confirmar se os parâmetros usados para integrações, como a ID de visitante da Experience Cloud ou a ID de dados complementares, são consistentes em todas as integrações.

>[!NOTE]
>
>No momento, nem todos os parâmetros transmitidos nas chamadas da solução (por exemplo, variáveis de contexto do Analytics, parâmetros personalizados do Target ou IDs do cliente do serviço da Experience Cloud ID) estão visíveis na tela Rede.

Para filtrar as informações por solução, selecione a solução que deseja exibir na lista da navegação esquerda. O exemplo a seguir é filtrado para mostrar somente o Analytics:

![](assets/network-analytics.jpg)

Para voltar a exibir todas as soluções, clique em **[!UICONTROL Network]**

Clique em um item na exibição Rede para ver uma exibição expandida. Na janela de exibição expandida, é possível copiar as informações mostradas para a Área de transferência.

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

Para limpar a lista, clique em **[!UICONTROL Remove Events]**.

Para baixar um arquivo do Excel que contém as informações nesta tela, clique em **[!UICONTROL Download]**.