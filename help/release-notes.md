---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;notas de versão
seo-description: 'null'
seo-title: Notas de versão
title: Notas de versão
uuid: 47a5d6f3-c074-4ad5-ad4b-e603049689b
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Notas de versão{#release-notes}

## Notas de versão {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 0.0.817 May 17, 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

## Novos recursos {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Recurso </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Dados de Ocorrência Pós-Processamento </p> </td> 
   <td colname="col2"> <p> Foi adicionada a capacidade de <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local"> exibir valores em ocorrências do Analytics após a execução</a>das regras de processamento. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Versão 0.0.810 6 de março de 2019 {#topic-83bb7ddd68594177be9fd7826b650b80}

## Novos recursos {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Recurso </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Testes dos auditores </p> </td> 
   <td colname="col2"> <p> Adicionados testes <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local"> do</a> Auditor ao Debugger </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>O depurador agora exibe respostas do AAM </p> </td> 
  </tr> 
 </tbody> 
</table>

## Correções de erros {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* Corrigido um problema no qual o rodapé ocultava o conteúdo na parte inferior da página

* O rodapé do depurador foi atualizado
* Corrigido um problema no qual terminologia desatualizada era usada para o Target

## Versão 0.0.809 28 de fevereiro de 2019 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## Novos recursos {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Recurso </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Incorporar funções de código </p> </td> 
   <td colname="col2"> <p> Divida as funções substituir e inserir código incorporado. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Melhorias {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* Corrigida uma possível vulnerabilidade causada por entradas de usuário não aprovadas.

## Correções de erros {#section-556417ff055848c1bf037354dd43cbd0}

* Corrigido um problema no qual os eventos AAM DIL não eram capturados na guia AAM

* Correção de um problema no Inicialização de inserção dinâmica em que a interface do usuário parecia mapear para um código incorporado diferente quando não era
* Correção de um problema no Launch Inserir dinamicamente em que um URL inválido continuava a ser exibido
* Correção de um problema em que o Depurador continuou a substituir códigos incorporados mesmo quando a janela do Depurador era fechada

## Versão 0.0.806 10 de setembro de 2018 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## Novos recursos {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Recurso </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Link do Analytics na guia Ferramentas </p> </td> 
   <td colname="col2"> <p>Mostre nomes amigáveis para evars/props por meio da API do Analytics por meio do logon IMS. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Inserir Dinamicamente Inicialização </p> </td> 
   <td colname="col2"> <p>Na guia Ferramentas, é possível inserir dinamicamente o Launch em qualquer página para testar algo em uma página que não tenha o Launch instalado. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aprimoramentos do Target </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">Adição de tempos de desempenho para solicitações do Target. </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">Capture adobe.target.trackEvent </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Melhorias {#section-56003a12c32f4998bf1cf2a25a518592}

* Aprimorada a exibição da guia Rede para que a altura da tabela não fique muito grande e force o usuário a rolar verticalmente antes de rolar horizontalmente. Anteriormente, as barras de rolagem apareciam na parte inferior da tabela. Como a tabela podia ficar bem grande, os usuários tinham que rolar todos os lados verticalmente para baixo para vê-los.
* Atualização do link para o ObservePoint na guia Ferramentas.

## Correções de erros {#section-d9231f5c77254d0888347e5f569a8b1d}

* Corrigido um problema no qual a guia da Experience Cloud não era atualizada

* Corrigido um problema no qual "Media Otimizer" era exibido na linha Solução da guia Rede, em vez do nome atual da "Advertising Cloud"
* Corrigido um problema que fazia com que o Debugger injetasse _satellite em cada página

## Versão 0.0.803 10 de agosto de 2018 {#topic-d2901fb70ce04a5586f6c7a994fce875}

A versão 0.0.803 não inclui alterações voltadas para o cliente.

## Versão 0.0.802 1 de agosto de 2018 {#topic-b93cd396af5e49dc97cd86264871aeb4}

## Novos recursos {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Recurso </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Link do auditor na guia Ferramentas </p> </td> 
   <td colname="col2"> <p>Foi adicionado um link para o Auditor a partir do Depurador </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Guias recolhidas </p> </td> 
   <td colname="col2"> <p>As guias recolhidas persistem nas guias Resumo e Ferramenta </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Clique para exibir </p> </td> 
   <td colname="col2"> <p> Adição da funcionalidade clicar para exibir em todas as guias </p> </td> 
  </tr> 
 </tbody> 
</table>

## Melhorias {#section-0e7090e3e6a645f085d4553b983ecff8}

* Nome alterado do Media Otimizer para Advertising Cloud
* Soluções removidas da guia Rede se não encontradas

## Correções de erros {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* Corrigido um problema no qual a função "Clique na célula para exibir" não era atualizada
* Corrigido um problema no qual ocorrências de AAM não eram exibidas na guia AAM

## Versão 0.0.798 14 de junho de 2018 {#topic-3b2d44277f2f4c0295d82724c34bf467}

## Novos recursos {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Recurso </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Opção de exportação do Excel </p> </td> 
   <td colname="col2"> <p>Opção de exportação do Excel adicionada à guia Rede. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aparência aprimorada </p> </td> 
   <td colname="col2"> <p>Fonte de extensão do Chrome atualizada para o Adobe Clean. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Funcionalidade de deslizamento do trackpad </p> </td> 
   <td colname="col2"> <p>Desativada a funcionalidade de deslizamento para frente/trás do trackpad. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Indicador de chamada de servidor bruto </p> </td> 
   <td colname="col2"> <p>Foi adicionado um indicador de que a sequência de chamada bruta do servidor foi copiada. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Guia Limpar registros </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">Ocultar soluções no Filtro de soluções se nenhum item de linha para essa solução for encontrado nos registros </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">Ocultar filtro de nível se nenhuma chamada de DTM for encontrada, pois se aplica somente ao DTM </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">Altere os ícones mostrados na coluna Nível para que eles não pareçam clicáveis quando nada acontecer ao clicar </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">Padronizar a formatação de "Mostrar código" em itens de linha do DTM </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Atualizar link de ajuda no rodapé </p> </td> 
   <td colname="col2"> <p>Atualizar link de ajuda no rodapé para <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/" format="https" scope="external"> https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Correções de erros {#section-c292cf7dcb17463bb1928de73bd55121}

* Corrigido um problema no qual o número do crachá não era limpo
* Correção de um problema em que um cliente relatava detalhes de resumo em branco

## Version 0.0.797 May 25, 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

## Novos recursos {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Recurso </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Mbox alternância </p> </td> 
   <td colname="col2"> <p>As alternâncias de mbox foram adicionadas à guia Target </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>As configurações de filtro agora são aderentes </p> </td> 
   <td colname="col2"> <p>As configurações de filtro agora se fixam na parte superior da tela nas guias de rede e registros. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Exibir e copiar valores de rede </p> </td> 
   <td colname="col2"> <p>Você pode exibir detalhes e copiar o valor de qualquer célula na guia rede. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Links de rodapé legais e direitos autorais </p> </td> 
   <td colname="col2"> <p>Adicionados links de rodapé legais e informações de direitos autorais à interface do usuário. </p> </td> 
  </tr> 
 </tbody> 
</table>

