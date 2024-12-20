# Web-SDK Samples

## Objective

This repository contains code samples for the Adobe Experience Platform Web SDK. The intent is to provide working code that illustrates various implementation strategies and techniques.

## Samples

### Personalization

| Description                                                  | Target                                                | AJO                                                     |
| :----------------------------------------------------------- | :---------------------------------------------------- | :------------------------------------------------------ |
| Client-side Personalization - use [web-sdk](https://experienceleague.adobe.com/docs/experience-platform/edge/home.html?lang=en) to get personalization experiences and display them client side | [View Sample App](target/personalization-client-side) | [View Sample App](ajo/personalization-client-side)      |
| Server-side Personalization - request personalization experiences and render them server side | [View Sample App](target/personalization-server-side) | [View Sample App](ajo/personalization-server-side)      |
| Personalization via Hybrid implementation - fetch personalization experiences server side and render them client side using [web-sdk](https://experienceleague.adobe.com/docs/experience-platform/edge/home.html?lang=en) without additional client-side edge requests | [View Sample App](target/personalization-hybrid)      | [View Sample App](ajo/personalization-hybrid)           |
| Personalization via Hybrid implementation and Single-page app (SPA) - fetch personalization experiences server side and render them in a single-page app (spa) client side using [web-sdk](https://experienceleague.adobe.com/docs/experience-platform/edge/home.html?lang=en) without additional client-side edge requests | [View Sample App](target/personalization-hybrid-spa)  |                                                         |
| Automatic Proposition Interaction Tracking - Illustrates how [web-sdk](https://experienceleague.adobe.com/docs/experience-platform/edge/home.html?lang=en) automatically tracks proposition interacteractions for personalization experiences. |                                                       | [View Sample App](ajo/proposition-interaction-tracking) |
| Top and bottom of page events                                | [View Sample App](target/top-and-bottom)              |                                                         |
| In-app messages                                              |                                                       | [View Sample App](ajo/in-app-messages)                  |
| Content Cards                                                |                                                       | [View Sample App](ajo/content-cards)                    |

### Data Collection

| Description                                                                                                                                                               | AEP                                                            |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| Server side data collection - collect data via [Edge Network Server API](https://experienceleague.adobe.com/en/docs/experience-platform/edge-network-server-api/overview) | [View Sample App](data-collection/data-collection-server-side) |

## Contributing

Check out our [Contribution Guidelines](.github/contributing.md) as well as [Code of Conduct](code_of_conduct.md) prior
to contributing to this repository.
