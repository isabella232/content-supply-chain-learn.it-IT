---
title: Tutorial sulla gestione delle risorse
description: Per le aziende che hanno difficoltà a collegare e tenere traccia dei propri requisiti di contenuto attraverso il processo di pianificazione, fino alla produzione e al completamento dei contenuti. La mancanza di processi efficaci, pianificazione, approvazioni e coerenza dei dati tra i progetti sta privando la catena di fornitura dei contenuti di questa azienda sia della produttività che dell'efficienza.
solution: Experience Cloud, Experience Manager Assets
feature-set: Experience Manager, Experience Manager Assets
feature: Asset Management, Asset Processing
topic: Content Management, Collaboration, Artificial Intelligence
role: Admin, User, Leader, Developer
level: Beginner
last-substantial-update: 2024-03-06T00:00:00Z
jira: KT-15076
source-git-commit: f3082975a674a13152aa92c06302e67e9f4715b6
workflow-type: tm+mt
source-wordcount: '1075'
ht-degree: 3%

---


# Tutorial sulla gestione delle risorse

Accesso semplificato e riutilizzo di milioni di risorse da un&#39;unica soluzione basata su cloud, garantendo al contempo la coerenza del marchio.  Questi tutorial si concentrano sull’utilizzo di Adobe Experience Manager Assets.


>[!TIP]
>
>Il nostro team di Adobi esperti dei prodotti ha assemblato una raccolta di tutorial sull’integrazione per i casi d’uso principali della supply chain dei contenuti. Se utilizzi più di una soluzione, scopri il modo migliore per integrarle.  Consulta la sezione [Tutorial sull’integrazione della supply chain dei contenuti](https://experienceleague.adobe.com/docs/integrations-learn/experience-cloud/solution-categories/content-supply-chain.html?lang=en).

## Corsi consigliati
<div class="columns is-multiline">
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets - Assets View] Bulk Import - Feature Video" tabIndex="0">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html" title="[AEM Assets - Vista risorse] Importazione in blocco - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3426857?format=jpeg" alt="[AEM Assets - Vista risorse] Importazione in blocco - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html" title="[AEM Assets - Vista risorse] Importazione in blocco - Video sulle funzioni">[AEM Assets - Vista risorse] Importazione in blocco - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Scopri come importare numerosi file in AEM Assets utilizzando la funzione di importazione in blocco, con il Dropbox che funge da provider di archiviazione cloud di esempio per un processo di integrazione chiaro e facile da seguire.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Asset Essentials][Workfront] Assets Essentials and Workfront integration - Catalog" tabIndex="1">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" title="Assets Essentials [Asset Essentials][Workfront] e integrazione con Workfront - Catalogo" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3422184?format=jpeg" alt="Assets Essentials [Asset Essentials][Workfront] e integrazione con Workfront - Catalogo">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" title="Assets Essentials [Asset Essentials][Workfront] e integrazione con Workfront - Catalogo">Assets Essentials [Asset Essentials][Workfront] e integrazione con Workfront - Catalogo</a>
          </p>
          <p class="is-size-6">Scopri come integrare Workfront e gli Assets Essentials.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Adobe Express integration - Feature Video" tabIndex="2">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" title="Integrazione di Adobi Express [AEM Assets] - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3425193?format=jpeg" alt="Integrazione di Adobi Express [AEM Assets] - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" title="Integrazione di Adobi Express [AEM Assets] - Video sulle funzioni">Integrazione di Adobi Express [AEM Assets] - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Scopri come ottimizzare le catene di fornitura dei contenuti con AEM Assets e Adobi Express, migliorando la produttività e l’accessibilità per tutti i membri del gruppo.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Adobe Express] Empower marketing teams to create multi-channel content - Feature video" tabIndex="3">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" title="[Adobe Express] Consentire ai team di marketing di creare contenuti multicanale - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3424446?format=jpeg" alt="[Adobe Express] Consentire ai team di marketing di creare contenuti multicanale - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" title="[Adobe Express] Consentire ai team di marketing di creare contenuti multicanale - Video sulle funzioni">[Adobe Express] Consentire ai team di marketing di creare contenuti multicanale - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Scopri come i team di marketing degli eventi possono creare contenuti univoci per attrarre gli spettatori per gli eventi online. In questo flusso di lavoro, un addetto al marketing B2B avvia un nuovo progetto in Adobi Express utilizzando un modello dal proprio brand kit e dalle proprie librerie. L’addetto al marketing B2B crea varianti per diversi canali social e web e condivide i contenuti sui social media e sulle piattaforme di hosting video.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Workfront Enhanced Integration Basics - Feature Video" tabIndex="4">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html" title="[AEM Assets] Nozioni di base sull&apos;integrazione avanzata di Workfront - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/337575?format=jpeg" alt="[AEM Assets] Nozioni di base sull&apos;integrazione avanzata di Workfront - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html" title="[AEM Assets] Nozioni di base sull&apos;integrazione avanzata di Workfront - Video sulle funzioni">[AEM Assets] Nozioni di base sull'integrazione avanzata di Workfront - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Scopri le nozioni di base dell’integrazione avanzata di Adobe Workfront e Experience Manager Assets, tra cui come collegare risorse e cartelle, definire mappature di metadati, inviare risorse all’AEM, creare versioni delle risorse e pubblicare automaticamente le risorse.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] AEM and Adobe Asset Link Creative Workflow - Value Video" tabIndex="5">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" title="Flusso di lavoro creativo per [AEM Assets] AEM e Adobe Asset Link - Video sul valore" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/335927?format=jpeg" alt="Flusso di lavoro creativo per [AEM Assets] AEM e Adobe Asset Link - Video sul valore">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" title="Flusso di lavoro creativo per [AEM Assets] AEM e Adobe Asset Link - Video sul valore">Flusso di lavoro creativo per [AEM Assets] AEM e Adobe Asset Link - Video sul valore</a>
          </p>
          <p class="is-size-6">Video che mostra il flusso di lavoro creativo di un utente che utilizza AAL e AAM</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AJO] Create content with the Email Designer - Feature Video" tabIndex="6">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" title="[AJO] Creare contenuti con E-mail Designer - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/334150?format=jpeg" alt="[AJO] Creare contenuti con E-mail Designer - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" title="[AJO] Creare contenuti con E-mail Designer - Video sulle funzioni">[AJO] Creare contenuti con E-mail Designer - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Scopri come creare e-mail da zero. Scopri come utilizzare le risorse della libreria di AEM Assets Essentials, modificare la progettazione delle e-mail responsive e creare e-mail dai modelli.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Asset Essentials] Getting started with Assets Essentials - Feature Video" tabIndex="7">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html?lang=it" title="[Asset Essentials] Guida introduttiva agli Assets Essentials - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/336005?format=jpeg" alt="[Asset Essentials] Guida introduttiva agli Assets Essentials - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html?lang=it" title="[Asset Essentials] Guida introduttiva agli Assets Essentials - Video sulle funzioni">[Asset Essentials] Guida introduttiva agli Assets Essentials - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Scopri come Assets Essentials offre un’interfaccia utente intuitiva e facile da usare, rendendo le risorse e le informazioni correlate facili da trovare e ricordare.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html?lang=it" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Content Automation - Value video" tabIndex="8">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" title="[AEM Assets] Automazione dei contenuti - Video sul valore" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/333197?format=jpeg" alt="[AEM Assets] Automazione dei contenuti - Video sul valore">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" title="[AEM Assets] Automazione dei contenuti - Video sul valore">[AEM Assets] Automazione dei contenuti - Video sul valore</a>
          </p>
          <p class="is-size-6">Panoramica delle funzionalità di Photoshop e Lightroom applicate con Adobe Experience Manager Assets Content Automation.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Metadata profiles - Feature Video" tabIndex="9">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/configuring/metadata-profiles" title="[Assets] Profili metadati - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/33974?format=jpeg" alt="[Assets] Profili metadati - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/configuring/metadata-profiles" title="[Assets] Profili metadati - Video sulle funzioni">[Assets] Profili metadati - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">I profili metadati consentono l’applicazione automatica di metadati predefiniti alle risorse all’interno delle cartelle di risorse, contribuendo a ridurre il carico di gestione dei metadati per gli utenti AEM e aumentando la coerenza dei metadati.</p>
        </div>
        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/configuring/metadata-profiles" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Navigation - Feature Video" tabIndex="10">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" title="Navigazione [Assets] - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32046?format=jpeg" alt="Navigazione [Assets] - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" title="Navigazione [Assets] - Video sulle funzioni">Navigazione [Assets] - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Scopri le nozioni di base per navigare in AEM Assets.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Comments and Annotations - Feature Video" tabIndex="11">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" title="[Assets] Commenti e annotazioni - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32049?format=jpeg" alt="[Assets] Commenti e annotazioni - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" title="[Assets] Commenti e annotazioni - Video sulle funzioni">[Assets] Commenti e annotazioni - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Scopri come utilizzare commenti e annotazioni in AEM per comunicare e collaborare alle risorse.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Search - Feature Video" tabIndex="12">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" title="Ricerca di [Assets] - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32054?format=jpeg" alt="Ricerca di [Assets] - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" title="Ricerca di [Assets] - Video sulle funzioni">Ricerca di [Assets] - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Scopri come utilizzare AEM Omnisearch per individuare rapidamente le risorse.</p>
        </div>
        <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Download - Feature Video" tabIndex="13">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" title="Download di [Assets] - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/35090?format=jpeg" alt="Download di [Assets] - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" title="Download di [Assets] - Video sulle funzioni">Download di [Assets] - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Scopri come scaricare le risorse e i relativi rendering nel computer locale per utilizzarle e condividerle.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] AEM Desktop App 2.0 - Feature Video" tabIndex="14">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html" title="[Assets] App desktop AEM 2.0 - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/28868?format=jpeg" alt="[Assets] App desktop AEM 2.0 - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html" title="[Assets] App desktop AEM 2.0 - Video sulle funzioni">[Assets] App desktop AEM 2.0 - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Utilizza l’app desktop AEM per semplificare l’accesso a qualsiasi risorsa gestita nell’AEM sul desktop, per qualsiasi applicazione e formato di file.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] DM Smart Image Crop - Feature Video " tabIndex="15">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html?lang=it" title="[Assets] Ritaglio immagine avanzato DM - Video sulle funzioni " tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/21519?format=jpeg" alt="[Assets] Ritaglio immagine avanzato DM - Video sulle funzioni ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html?lang=it" title="[Assets] Ritaglio immagine avanzato DM - Video sulle funzioni ">[Assets] Ritaglio immagine avanzato DM - Video sulle funzioni </a>
          </p>
          <p class="is-size-6">Il ritaglio avanzato utilizza Adobe Sensei per eliminare le attività di ritaglio dei contenuti che richiedono tempo e denaro per una progettazione reattiva.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html?lang=it" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Asset Source File Translation - Feature Video" tabIndex="16">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" title="[Assets] Traduzione file sorgente risorsa - Video sulle funzioni" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/18331?format=jpeg" alt="[Assets] Traduzione file sorgente risorsa - Video sulle funzioni">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" title="[Assets] Traduzione file sorgente risorsa - Video sulle funzioni">[Assets] Traduzione file sorgente risorsa - Video sulle funzioni</a>
          </p>
          <p class="is-size-6">Adobe Experience Manager (AEM) Assets consente di identificare le risorse che condividono attributi comuni e di contrassegnarle come correlate utilizzando la nuova funzione Risorse correlate.</p>
        </div>
        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">Ulteriori informazioni</span>
        </a>
      </div>
    </div>
  </div>
</div>

## Risorse aggiuntive

* [Eventi Experience League](https://experienceleague.adobe.com/events/)
* [Adobe sulla catena di fornitura dei contenuti](https://business.adobe.com/resources/webinars/adobe-on-the-content-supply-chain.html)
