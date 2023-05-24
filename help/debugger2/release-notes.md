---
title: Notas de versão
description: As notas de versão mais recentes do Adobe Experience Platform Debugger.
keywords: depurador;extensão do Experience Platform Debugger;chrome;extensão;notas de versão
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 4%

---

# Notas de versão

## Versão 1.3.0 - 28 de janeiro de 2022

* Adição do link Sobre para mostrar a versão atual e as notas.
* Adição de um botão para exibir ocorrências pós-processadas para solicitações do Analytics. O botão de alternância está disponível na seção Analytics.
* Correção de um problema de sessão de depuração remota quando a sessão era fechada fora do depurador.
* Correção da notificação de erro que estava visível na guia Transações de borda do SDK da Web.
* Corrigidas as tags Adobe no aviso de descontinuação da página quando o depurador acessava o objeto _satellite.
* Correção de alguns casos em que uma instância do AppMeasurement não era encontrada na página.
* Correção de um problema de conexão de página que ocorria ao abrir a janela do depurador pela primeira vez.

## Versão 1.2.0 - 26 de outubro de 2021

* Mostrar eventos de todas as guias do navegador na exibição de rede. Para ver apenas os eventos da guia atual, selecione o ícone de bloqueio no canto inferior direito do depurador.
* Marca atualizada.

## Versão 1.1.0 - 5 de outubro de 2021

* Visualização de depuração remota - Organize os eventos de depuração remota em um fluxograma visual na seção Adobe Experience Platform Web SDK > Transações de borda.
* Exigir que a organização IMS do SDK da Web da Adobe Experience Platform usada na página corresponda à organização conectada ao iniciar uma nova sessão de depuração remota.
* Mostrar somente as transações de borda da guia conectada. Os logs de rastreamento do Target ainda estão disponíveis na seção Logs > Edge.
* Permitir a substituição da configuração da ID de fluxo de dados separada para cada instância do SDK da Web da Adobe Experience Platform na página. Adicionar alternância habilitada para depuração.
* Correção de um problema em que o token de rastreamento do Adobe Target nem sempre era enviado com sessões de depuração remota para o SDK da Web da Adobe Experience Platform.

## Versão 1.0.0 de 5 de maio de 2021

* Primeira versão principal do Experience Platform Debugger. Destina-se a substituir o Experience Cloud Debugger.
