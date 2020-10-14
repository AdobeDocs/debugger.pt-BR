---
description: Tela Eventos do Depurador Experience Platform
keywords: debugger;experience platform debugger extension;chrome;extension;events;dtm;target
seo-description: Tela Eventos do Depurador Experience Platform
seo-title: Eventos
title: Eventos
translation-type: tm+mt
source-git-commit: 53f027d5a5ae56c7a8e812b10a2649a38df3b31d
workflow-type: tm+mt
source-wordcount: '169'
ht-degree: 89%

---


# Eventos {#events}

>[!IMPORTANT]
>
>O Adobe Experience Platform Debugger está atualmente em beta. A documentação e a funcionalidade estão sujeitas a alterações.

A tela Eventos fornece uma exibição gráfica dos eventos que ocorrem, exibidos em uma linha do tempo.

![](assets/events.jpg)

Para cada evento, um ícone da solução aplicável da é exibido na linha do tempo. Os ícones também mostram as alterações na camada de dados (se ativada). Passe o mouse sobre um ícone para ver um resumo do evento. Clique no evento para obter mais detalhes. É possível clicar com a tecla Shift pressionada ou com a tecla Control pressionada para exibir vários eventos.

![](assets/events-details.jpg)

Clique em um detalhe para obter mais informações.

![](assets/events-details-more.jpg)

## Rastrear alterações na camada de dados

Para ativar na linha do tempo o rastreamento de alterações na camada de dados:

1. Clique no ícone de engrenagem na parte superior direita.
1. Insira o nome da camada de dados.

   ![](assets/event-datalayer.jpg)

1. Clique em **[!UICONTROL Save]**.

Os detalhes de alterações da camada de dados mostram qualquer coisa que foi excluída ou adicionada. Você pode clicar em **{}** para enxergar mais fundo na camada de dados.

## Baixar informações do evento

Clique em **[!UICONTROL Download]** para baixar um arquivo de Excel que mostra informações sobre suas chamadas de página.