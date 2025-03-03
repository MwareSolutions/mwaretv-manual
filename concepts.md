# Concepts

We are happy to see you as MwareTV customer and hope that the following manual will help you to understand the required steps toward your OTT success.

OTT, or Over-The-Top, service refers to the delivery of **TV**, **movies**, **series**, and other media content via the internet, without requiring users to use a traditional cable or satellite pay-TV service. The term "over-the-top" refers to the fact that these services go "over" the top of traditional distribution platforms.

OTT services are typically accessed through devices connected to the internet, such as _smartphones_, _tablets_, _smart TVs_, _gaming consoles_, and _set-top boxes_ on a subscription basis like Netflix, Hulu, or Amazon Prime Video. It's also possible to offer content on a **pay-per-view** or **ad-supported** model.

{% hint style="info" %}
OTT services can be an ideal up-sell product, offering your customers better value, helping you retain them, and enhancing their overall user experience.
{% endhint %}

OTT technology encompasses the tools, software, and infrastructure required to deliver content online. This includes video hosting platforms, content delivery networks (CDNs), video encoding tools, and interactive streaming features that ensure seamless delivery and a high-quality viewing experience.

These services are monetized through various business models, including paid subscriptions (SVOD), ad-supported streaming (AVOD), transactional purchases (TVOD), or hybrid models combining subscriptions and ads.

Here is how OTT technology looks in action:

1. Broadcasters upload video content to an OTT video hosting platform
2. The video host transmits the data to remote servers via a content delivery network (CDN) - is exactly whait sounds like a network of servers that delivers content.
3. Viewers select the content they want to stream on the user-facing video gallery
4. The video player on the device pulls the video content from the CDN’s server with the internet

However, the apparent simplicity of an OTT solution is deceptive. In essence, it requires a significant amount of resources and time to create a product that truly delivers value to your customers. This will involve meticulous work with content, precise business calculations, creativity in customer acquisition, and numerous technical tasks related to video.



Please read the followings parts to learn more about upcoming actions that are need to be taken.

## What TVMS does?

Take a look at the picture below. It schematically represents the layout of a complete OTT installation and shows all the crucial parts which OTT cannot exist without.&#x20;

TVMS is a middleware system, and it is literally a system in the middle—it serves to connect different standalone modules into one ecosystem, such as content streaming, devices, billing, customer management, and so on. It allows you to manage system entities, build your application, track billing, and work with customers. Without such software, you cannot build a working solution, and that is the crucial role of the middleware.

<figure><img src=".gitbook/assets/изображение (1).png" alt=""><figcaption></figcaption></figure>

At the top, you see the MwareTV Management System section, which contains Content, Apps, Marketing, and other modules. It integrates with a website, allows you to implement content protection in your streaming environment, and manage end users' devices.&#x20;

Of course, it's not an admin panel for encoders, transcoders, DRM, and other third-party tools, but it leverages them to bring everything together.

<figure><img src=".gitbook/assets/изображение (2).png" alt=""><figcaption><p>This is how the TVMS looks</p></figcaption></figure>

## TVMS services

TVMS consists of seven modules that serve their purpose and form the overall service.

1. [Content](tvms-administration/content/): upload content, create bundles, assign EPG, set additional properties
2. [Inventory](tvms-administration/inventory/): create subscription out of bundles and define taxes
3. [Billing](tvms-administration/billing/): manage your webshop life cycle and communications with your customers
4. [Customers](tvms-administration/customers/): manage your customers and check their details
5. [Marketing](tvms-administration/marketing/): manage marketing campaigns, affiliates and coupons
6. [Reports](tvms-administration/reports/): create custom statistics
7. [Apps](tvms-administration/application/): build and mange your brand application

## Content

Content **is a core** of a TV service - you start this business to show content, your users want to watch content, so this is the most important part of your business.&#x20;

### Which content you plan to offer

#### TV

Good content selection **is the key to the success** of your OTT business. This selection must be based on your target audience' needs and preferences. For example, your audience are families with middle-aged parents and kids, so the main focus should be on the **entertainment** and **kids channels.** If the audience consists of older people then it makes sense to add  channels with **nostalgic movies and TV shows.** On weekdays in working hours the main consumers are housewives so the content of **soap operas** and **TV stores** can be an excellent choice to add in your product.

Add **local and regional channels** so that people can receive news about their city and region. Mix them with **nationwide** and **international** content to create a truly valuable product that customers are **unlikely to refuse**.

<figure><img src=".gitbook/assets/изображение (4).png" alt=""><figcaption><p>Just an example of one of multiple possible ways to visualize the TV content in the app</p></figcaption></figure>

**Sports channels** are more expensive to obtain, and it makes sense to upsell them as an additional package. Note that such channels may have a seasonal nature and are broadcast during a certain period, e.g., a couple of months during important tournaments, championships, etc.

If you also provide content with an **adult rating,** you can upsell it as an additional package. Don't forget to set the parental controls to prevent kids' access.

#### Movies and series

Really successful OTT cannot be imagined without movies and series. VOD is rapidly growing every single moment, statistics say its consumption grows every quarter. Look at Netflix, it continues to exemplify the importance of VoD in its strategy, boasting a subscriber base of approximately 300 million by early 2025. Disney has 150 million and Hulu has 50 mln, all these numbers were reached by successful leveraging of VoD content and a way how it is distributed to a consumer.

Like for TV, you must understand the needs of your target audience. Nowadays, the main consumers of VoD are young people, so give them the opportunity to watch the most popular premieres and good old classics of teenage entertainment. Also, older people must have access to good old movies of the classical era.

Of course, family movies are essential for an OTT service because it brings common value for all the ages.

<details>

<summary>Look at the TVMS side</summary>

1. Go to Content to manage it and explore the available options.
2. Open channels to explore them all or add a new one. While adding, fill Name, Number, URL and other mandatory options.
3. Create bundles and add content into them.
4. Upload EPG&#x20;
5. Do the same for Movies, series and other content types
6. Once it's done, publish bundles, so you're ready to create subscription in Inventory.

For additional info [refer to Content.](concepts.md#content)

</details>

### Providers, sources, graphics, metadata

Choosing a content provider can take a lot of time searching and negotiating the terms of mutually beneficial cooperation. Your interaction with the provider will largely determine the OTT business model, so take this with full responsibility.

Technically, providers provide you with content sources (e.g. URLs), branded graphics, and metadata. Also they can provide you with EPG. If there are something that aren't covered by a single provider, you can find it another providers/sources by agreement.

Providers may have requirements regarding broadcast security, broadcast network, and others.

<details>

<summary>Managing providers in TVMS</summary>

TVMS has Providers [page where you can add them ](tvms-administration/content/settings.md#providers)and then track statistics based on providers.

Some providers may have additional [query parameters ](tvms-administration/content/settings.md#parameters)so add it in the settings and then use in channels' details.

</details>

### Content license documents for app stores

Secure your rights to broadcast content. Providers, app stores and other organizations actively combat unauthorized access and piracy by monitoring broadcasting and preventing the publication of such applications and their distribution. These documents will be requested by app stores when publishing your application. In the absence of licenses for content broadcasting, the application will not be published.&#x20;

An application that is suspected of distributing unlicensed content may be blocked in app stores and receive a DMCA letter. In this case, the owner of the application will have to prove the legality of distributing this content using licenses obtained from the provider. Otherwise, the application will remain blocked.

<details>

<summary>Learn more about publishing in App Stores</summary>

We have a [special manual section ](application-and-app-stores/)with detailed explanations

</details>

## Video streaming

Our streaming team is available 24/7, covering all regions. We provide services for content delivery and transcoding by receiving video streams from a provider and making them available to end users.&#x20;

Everything is cloud-based, so there’s no need to build on-premise solutions or worry about external conditions.

### Preferred specification for streaming (depends on support devices)

To enjoy Over-The-Top (OTT) streaming services seamlessly, a reliable internet connection is paramount. The fundamental prerequisite for optimal streaming is a stable broadband connection, typically with a minimum speed of 25 Mbps for high-definition (HD) content. For 4K Ultra HD streaming, this requirement increases to around 50 Mbps or higher. This bandwidth ensures that data can be transmitted quickly enough to prevent buffering and interruptions, which can significantly detract from the viewing experience.&#x20;

In addition to speed, latency and jitter are critical factors that influence the quality of an OTT streaming experience. Latency refers to the time it takes for data to travel from the source to the destination, while jitter measures the variability in packet arrival times. Ideally, latency should be kept below 100 milliseconds for a smooth streaming experience, as higher latency can lead to delays in video playback. Jitter should also be minimized to ensure that data packets arrive in a consistent manner, preventing disruptions in the stream.

{% hint style="info" %}
Please check the [Transcoding and Streaming page](transcoding-and-streaming.md) for more details
{% endhint %}

### Infrastructure for content delivery (streaming)

Most often, the provider already has a broadcast stream. This stream will be added to the CDN (Content Delivery Network) to distribute the load and broadcast zone. Also, you can transcode video and audio streams to match the bandwidth of your clients, both wide and narrow. It is possible to use ABR (Adaptive Bitrate) - this is a video transcoding scenario in which the client's device independently selects the best stream for itself for uninterrupted broadcasting.&#x20;

To protect broadcasting, content protection services like DRM and tokenization are used.&#x20;

You can provide your clients with TV archive (CatchupTV) and recording (DRV) services to improve their user experience and retain them.

<details>

<summary>Learn more about the streaming prerequisites</summary>

We have a [special page for reference](transcoding-and-streaming.md)

</details>

### Why video transcoding matters

Video transcoding is crucial for delivering a seamless viewing experience across various devices and bandwidth conditions. Different devices, such as smartphones, tablets, smart TVs, and computers, have varying screen resolutions, processing power, and supported video formats. Transcoding ensures that video content is optimized for each device by converting it into the appropriate format, resolution, and bitrate. Additionally, users access content on networks with different bandwidth capabilities, ranging from high-speed broadband to slower mobile connections. By transcoding videos into multiple quality levels (e.g., 1080p, 720p, 480p), providers can dynamically adapt streaming quality to match the available bandwidth, preventing buffering and ensuring smooth playback. This adaptability not only enhances user satisfaction but also reduces data usage for viewers on limited plans, making transcoding an essential component of modern video delivery systems.

### Content protection (Token or DRM)

DRM systems enable content providers to control how their media is consumed, ensuring that only authorized users can view or download the content. This is particularly important in an era where piracy and content theft are rampant. By encrypting the media files and requiring specific licenses for playback, DRM helps maintain the integrity of the content and the revenue streams for creators and distributors.

<figure><img src=".gitbook/assets/изображение (5).png" alt=""><figcaption><p>A concept chart how DRM works</p></figcaption></figure>

Tokens are used as secure identifiers that grant access to protected content. When a user attempts to stream a video, the OTT platform generates a token that encapsulates the user's authentication and authorization details. This token is then used to request a decryption key from the DRM server, which allows the user to access the content securely. Tokens can be time-limited and tied to specific user sessions, adding an additional layer of security by ensuring that access is granted only for a defined period.

## Devices

### Which devices will be support by your service

One of the key factors for the success of your OTT business is the ability to launch the application on the maximum number of devices. Basically, these are Android and Apple devices such as set-top boxes, phones, tablets. Also consider the popularity of installing applications through TV vendor stores, such as Samsung and LG. They often have different technical platforms, but MwareTV provides applications for all of these stores. In particular, we support Roku, Amazon, game consoles and many other devices.&#x20;

<figure><img src=".gitbook/assets/изображение (3).png" alt=""><figcaption><p>The most popular platforms are TV set-top boxes, PC and mobile devices</p></figcaption></figure>

You should familiarize yourself with the most popular devices of your target audience. This can be both ready-made statistics on your customers, marketing reports on sales, user feedback. Of course, support for Apple and Android is necessary in any case, since these are the most common platforms in the world.

### Open app stores accounts for each selected devices

Each platform has its own app store and its own terms of participation in them. Differences can be both starting with registration (for example, registration with Apple can take a long time), and in the operation of the application, some stores can often change the terms of their use, require support for certain functions or comply with their design code.&#x20;

For publishing in stores, you better create a special subscription version. It does not necessarily have to include all the content, you can place the most popular there and provide unlimited access for app stores employees.

We describe the account creation process in detail on this page: [preparing-apps-for-publishing.md](application-and-app-stores/preparing-apps-for-publishing.md "mention")

## How to get new user and how to keep them engages

Marketing is they key factor to make your OTT service a success once your OTT service has been launched.

Understand the importance of a comprehensive marketing plan. Modern business consists of different parts, ways and approaches so you have to count them all on the way to successful OTT.

A well-structured marketing plan is crucial as it serves as a roadmap for reaching and engaging target audiences in a competitive landscape. Given the proliferation of streaming services, a comprehensive marketing strategy helps differentiate the brand by clearly defining its unique value proposition and identifying the specific demographics it aims to attract. This plan outlines key tactics for customer acquisition, retention, and engagement, including promotional campaigns, social media outreach, content marketing, and partnerships with influencers or other platforms. Additionally, a marketing plan enables the business to allocate resources effectively, set measurable goals, and track performance metrics, allowing for data-driven adjustments to optimize marketing efforts. By fostering brand awareness and building a loyal subscriber base, a robust marketing plan not only drives initial sign-ups but also enhances long-term profitability and sustainability in the ever-evolving OTT market.

### Paid subscriptions

The most popular way to generate revenue in OTT are paid subscriptions. This concept is clear for business and people: customer pay a fix price for a subscription time, business can easily forecast revenue and manage the prices. Let's consider how it works in details.&#x20;

<figure><img src=".gitbook/assets/изображение (6).png" alt=""><figcaption></figcaption></figure>

#### Base subscriptions

In TVMS, once content is added, you can create different bundles and put content there. Bundle works like a brick in your subscription wall - it contains a certain list of available content. For example, you can create a bundle for News or Kids channels or divide them according to another logic, it's up to your business logic. When you have the bundles ready you can create a subscription. For example, Bronze subscription contains News and Movies bundles; Silver contains additional bundles for Business channels; Platinum subscription contains all amount of available content. Such classical business models is called **BASE** subscriptions in TVMS.

Define subscription length, for example a month, half-year or annual. Set different prices that will cover your expenses like content licensing and streaming infrastructure payments, and generate you a desired revenue. It is essential to analyze the target audience and their willingness to pay, which can vary significantly based on demographics, content preferences, and regional economic conditions. Competitor pricing is another critical consideration; understanding how similar services are priced can help position the offering effectively in the market. Promotional strategies, such as free trials can also help to attract new subscribers and retaining existing ones.

#### Extra subscriptions

You can also upsell additional content on customers' demand, it's called EXTRA subscriptions in TVMS. For example, you may have a special Sport channels with exclusive content. Usually, it costs a lot from providers and for providers so there's no reason to give it for free like other channels.&#x20;

<figure><img src=".gitbook/assets/изображение (8).png" alt=""><figcaption></figcaption></figure>

Thus, create an EXTRA subscription and add it to your webshop. Customers will have a choice to purchase it in addition to their BASE subscription. So, customer obtains more value from your application and you have more revenue.&#x20;

<details>

<summary>Learn how to create subscriptions in TVMS</summary>

Refer to the [Inventory part of the manual ](tvms-administration/inventory/)for step-by-step guide

</details>

### By advertisements

Yet another great opportunity to earn with OTT is advertisement. TVMS provides options to integrate ads in the app like onscreen banners and VAST - Video Ad Serving Template.

Upload advertisement content to TVMS and place it. You may manage its position, length, text. Set publishing period or indefinitely.

You may use one or multiple VAST sources, combine it differently, even appropriate in meaning to a certain TV channel or movie/series. The main benefit of VAST is tracking that allows you and advertiser to analyze ads campaigns according to tags inside VAST.

Good choices for onscreen banners may be your local business or something that people might react while watching TV, like local food delivery, electronic retailers and so on. You can also advertise your another services, if any.

<details>

<summary>Where is it in TVMS?</summary>

Onscreen images can be set in the App Builder, please refer to [the App Builder page.](tvms-administration/application/app-builder/)

VAST ads are managed in the channels' details, [check on the Channel page.](tvms-administration/content/channels.md)

</details>

### Pay per View

Pay per View (PPV) is yet another popular way to monetize an OTT service. In this way, customers pay for a content unit be it a channels, movie or even games. It's useful if you position the service like AppleTV where customers pay for exceptional quality or reduce costs of purchasing and distributing of expensive content that may be e.g. a premiere.

TVMS provides a rent model when customers pays for temporarily access for a set amount of days, month or years. Define a rule and apply it to selected content, then when customers purchase it they are billed.

### Via a webshop

Web shop may be an additional channel of revenue generating. Show website visitors the best you can give them, highlight your app's advantages, attracts with affordable prices.

Take in consideration that some web shops may take a fee for payments processing, as well as payment providers, so include this depreciation in your price.

<figure><img src=".gitbook/assets/image (108).png" alt=""><figcaption></figcaption></figure>

Another important thing is taxes. TVMS allows you to adjust the price calculation by adding tax rates in Inventory, so you will have your final price according to your financial laws.

Likewise with the app, you can put advertisement in your web shop that can be by another advertiser or by your another business.

<details>

<summary>Learn more about the TVMS webshop</summary>

It is explained in details in [the Billing part ](tvms-administration/billing/)of the manual

</details>

### Via an existing billing system

In case, if you already have your customers in another business, like ISP and you consider ways how to give them more value and earn, so that also can be possible.

<figure><img src=".gitbook/assets/изображение (10).png" alt=""><figcaption></figcaption></figure>

Once you've created your OTT service, start promoting it among your current customers. Make product purchasing seamless and profitable for them. Having them in your billing system, you can easily export them in TVMS. Choose between TVMS customer management or your own. In the second case you have integrate your billing with TVMS via APIs we have to synchronize management actions.

### In-app registration

Many modern application support in-app registrations when users download the app and register in-house. It presents both advantages and disadvantages from a business perspective. On the positive side, requiring users to register within the app can significantly enhance user engagement and retention, as it allows for personalized content recommendations and tailored marketing strategies based on user preferences and viewing habits. This data can be invaluable for driving targeted advertising and subscription offers, ultimately increasing revenue potential. Additionally, in-app registration can facilitate smoother payment processing for subscription services, reducing churn rates and fostering a loyal customer base.

However, app stores can take 30% fee for every new subscriber and that can significantly reduce your revenue. Thus, if you decide to use this way, you have to adjust the prices according to app stores policies. In this case, it's wise to offer customers more monetized content in order to cover the fee.

### Free use (no registration needed)

If you decide to not bill your customers and grant them free access, first you have to understand your content policy. Some providers may prohibit free and anonymous access to their content and obviously you don't generate revenue by subscriptions bills.

<figure><img src=".gitbook/assets/изображение (7).png" alt=""><figcaption><p>This chart represents the onboarding workflow for in-app registration</p></figcaption></figure>

Alternatively, you can grant for free most popular content monetizing other instead. Thus, for people that prefers to have unlimited access to nationwide channels and sometimes pay for another content it may be a perfect option. Integrate VAST to cover the expenses and this way may work out.

### Combining different ways of monetizing

Of course, you can use some monetization methods or all of them simultaneously. Let's consider:

1. You sell subscriptions in a web shop that will cover your expenses and give you revenue
2. Upsell EXTRA products with exclusive content
3. You sell ads for onscreen banners to let other business promote in your app
4. You added VAST sources to content, so you have your income by them
5. Set PPV for selected content
6. Provide free access to the app with most popular content and with paid
