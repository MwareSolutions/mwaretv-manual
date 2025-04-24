# Channels

## Overview

The overview table provides you common info about channels you have in the TVMS.

Each channel must contain a _number_, _icon_, _name_ and _URL_. Additionally, you can add _notes_ to a channel for any additional info that may be useful.

{% hint style="info" %}
Please note that the presence of a channel in the list does not necessarily mean that it is available to the user; it may also include test channels. To make a channel **available**, you need to create a [**bundle** ](https://mwaretv.atlassian.net/wiki/spaces/TM/pages/46071839)for a [**product**](https://mwaretv.atlassian.net/wiki/spaces/TM/pages/46563550).
{% endhint %}

<figure><img src="../../.gitbook/assets/Без имени.png" alt=""><figcaption><p>Channels overview</p></figcaption></figure>

### Add a channel

Click the Add Channel button to open a channel adding wizard.

Read in advance the [LiveTV channels requirements](https://mwaretv.atlassian.net/wiki/pages/createpage.action?spaceKey=TM\&title=LiveTV%20Channels\&linkCreation=true\&fromPageId=45645827) to learn **URL** prerequisites and **token** settings

Follow the steps to add a channel, the required field are emphasized:

* Specify general info like _Name_ and _Number_
* Select a channel provider. Refer to [the instructions](https://mwaretv.atlassian.net/wiki/spaces/TM/pages/46170384) on how to add one
* Add _stream URLs_, pay attention that **iOS/tvOS/KaiOS use .m3u8 only**, other platforms use **.mpd**
* If you provide a TV archive service, fill in _InteractiveTV fields,_ make sure you already have [transcoders](https://mwaretv.atlassian.net/wiki/spaces/TM/pages/46170185)
* Turn on Parental Control to restrict access for children.
* Below, you can set a _country-specific age rating_
* Add _Content Tags_ to make it available for search in the application
* Add _Content Genres_ to indicate it and help users better understand the content
* Set _Content placement_ if you want to have any temporary settings for this channel
* Set a _token_ and _DRM_ (if any), refer [how to add DRM](https://mwaretv.atlassian.net/wiki/spaces/TM/pages/45645893)
* Select an _EPG source_ and channel, make sure that [EPG is already added](https://mwaretv.atlassian.net/wiki/spaces/TM/pages/45580299)
* If you use _VAST_, put a link
* Select PPV rules, read here [how to add one](https://mwaretv.atlassian.net/wiki/spaces/TM/pages/46170145)
* Upload a _channel icon_ of **1:1 aspect ratio**, make sure it is contrast enough against the background

<details>

<summary>Expand to see how it looks on a real page</summary>

![](<../../.gitbook/assets/Без имени (4).png>)

</details>

### Channels details

You may also check properties of already added channels by clicking _Details_.

Information is divided in different tabs so you can navigate through and change the values.

Expand to take a look what is inside every tab:

<details>

<summary>First tab contains general info and additional options</summary>

<img src="../../.gitbook/assets/Channels details.png" alt="" data-size="original">

</details>

<details>

<summary>In Images you may change the artwork</summary>

<img src="../../.gitbook/assets/Channels details Images.png" alt="" data-size="original">

</details>

<details>

<summary>In the third tab you may adjust InteractiveTV and streams URLs settings</summary>

<img src="../../.gitbook/assets/Channels details Streams.png" alt="" data-size="original">

</details>

<details>

<summary>Security contains content protection settings</summary>

<img src="../../.gitbook/assets/Channels details Security.png" alt="" data-size="original">

</details>

<details>

<summary>Monetizing allows you to manage advertising and PPV rules</summary>

<img src="../../.gitbook/assets/Channels details Monetizing.png" alt="" data-size="original">

</details>

<details>

<summary>Guide settings let you manage EPG for a certain channel</summary>

<img src="../../.gitbook/assets/Channels details Guide.png" alt="" data-size="original">

</details>

## Bundles

Each bundle contains categories who in return contain your Channels. When publishing your Bundles the mapped Guide data is also published.

<figure><img src="../../.gitbook/assets/Без имени (50).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
During the deployment setup you have chosen the timezone on which the task scheduler should run on, this means each night your TV Guide gets refreshed and published together with your bundles.
{% endhint %}



### Adding a bundle

Click Add Bundle and specify its name in the popup window that logically describes a purpose of this bundle, e.g. News/Sports or Standard/Premium

<figure><img src="../../.gitbook/assets/Без имени (51).png" alt=""><figcaption></figcaption></figure>

When it’s added, expand it and click _Channels_

<figure><img src="../../.gitbook/assets/Без имени (52).png" alt=""><figcaption></figcaption></figure>

In the new window just **drag and drop** required channels. You may move all channels back and forth by clicking **>>** and **<<**

<figure><img src="../../.gitbook/assets/Без имени (53).png" alt=""><figcaption></figcaption></figure>

For your convenience, you have options to **filter** the channels by a provider, tag or name. If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish bundles! You may publish a single one or all at once. If you don’t publish a bundle, content won’t be propagated to the app.
{% endhint %}



## Lists

Specify here any **content** that you want to **promote** on the **Home page** of your **application**.

<figure><img src="../../.gitbook/assets/Без имени (54).png" alt=""><figcaption></figcaption></figure>

Click Add List and specify its self-explainable **name** in the **popup** window. Once it’s added, click _Channels_.

<figure><img src="../../.gitbook/assets/Без имени (55).png" alt=""><figcaption></figcaption></figure>

In the new window just **drag and drop** required channels. You may move all channels back and forth by clicking **>>** and **<<**

For your convenience, you have options to **filter** the channels by a provider, tag or name. If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish lists! If you don’t publish it, content won’t be propagated to the app.
{% endhint %}



## Settings

On this page, specify a number of available **CatchupTV days**. It must be **equal** to the video server settings.

<figure><img src="../../.gitbook/assets/Без имени (56).png" alt=""><figcaption></figcaption></figure>



## Transcoders

To manage the InteractiveTV or CatchupTV settings, you need to add a transcoder, so click the Add Transcoder button

<figure><img src="../../.gitbook/assets/Без имени (57).png" alt=""><figcaption></figcaption></figure>

Specify **required information** and click the Add Transcoder button.

Once added, you may click _Test_ to be sure if the TVMS **can connect** to a transcoder. Then, you can select it in the _Channel details_ to manage the InteractiveTV or CatchupTV settings.

Click _Edit_ to **change** the settings.



## Import

[Download a channels example Excel to get you started](https://cloudtv.akamaized.net/donotremove/tvms/examples/Excels/Channels_.xlsx)

{% hint style="info" %}
We only accept **Excel .xlsx** files for importing
{% endhint %}

It is possible to import images, this is done by providing **a working URL** to the image asset. With importing images it is very important to respect **the aspect ratio 1:1** and the maximum image sizes. Images that have a correct image ratio but the sizes are too big our import tool will **automatically resize** them.

{% hint style="warning" %}
If you have empty columns (columns that hold no value) will cause issues, remove them
{% endhint %}
