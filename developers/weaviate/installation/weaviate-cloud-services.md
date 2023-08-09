---
title: Weaviate Cloud Services
sidebar_position: 1
image: og/docs/installation.jpg
# tags: ['installation', 'Weaviate Cloud Services']
---
import Badges from '/_includes/badges.mdx';
import WCSApiKeyLocation from '../../wcs/img/wcs-apikey-location.png';

<Badges/>

## Overview

Weaviate Cloud Services (WCS) is a managed SaaS service that requires no maintenance at your end. Accordingly, it may be the easiest way to run Weaviate.

:::tip How to access

Head to [https://console.weaviate.cloud](https://console.weaviate.cloud) to sign up and create your own Weaviate instance.

Note: WCS offers free sandboxes with a 14-day expiry date.

:::

:::info Learn More

You can learn more about WCS from the dedicated [WCS documentation](/developers/wcs/index.mdx).

:::

## Set API in Client

After creating of your instance, click on the <kbd><i class="fa-solid fa-key"></i></kbd> button for the Weaviate API key.

:::note <i class="fa-solid fa-camera-viewfinder"></i> <small>Your WCS cluster details should look like this:</small>
<img src={WCSApiKeyLocation} width="60%" alt="Instance API key location"/>
:::

import ConnectToWeaviateWithKey from '/_includes/code/installation.connect.withkey.mdx'

<ConnectToWeaviateWithKey />

Now you are connected to your Weaviate instance!

## More Resources

import DocsMoreResources from '/_includes/more-resources-docs.md';

<DocsMoreResources />
