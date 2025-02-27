# Radio

The overview table gives you common info about radio you have in the TVMS.

Each channel must contain a _number_, _icon_, _name_ and _URL_. Additionally, you can add _notes_ to a channel for any additional info that may be useful.

{% hint style="info" %}
The fact that a channel is in the list **does not mean** that it is available to the user, it may contain test channels too. To make it available, you have to create a [bundle ](radio.md#bundles)for a [product](../inventory/inventory.md)
{% endhint %}

<figure><img src="../../.gitbook/assets/Без имени (58).png" alt=""><figcaption></figcaption></figure>

## Add a radio <a href="#add-a-radio" id="add-a-radio"></a>

Click the Add Radio button to open a radio adding wizard.

Follow the steps to add a channel, required field are emphasized:

* Specify general info like _Name_ and _Number_
* Select a _provider_ of a radio. Refer to [the instructions ](settings.md#providers)to add one
* Add _stream URLs_, pay attention that **iOS/tvOS/KaiOS use .m3u8 only**, other platforms use **.mpd**
* Add tags to identify its genres and make available in the app search
* Set _Content placement_ if you want to have any temporary settings for this channel
* Set a _token_ and _DRM_ (if any), refer [how to add DRM](drm-and-tokens.md)
* Select an _EPG source_ and channel, make sure that [EPG is already added](guide.md)
* Select PPV rules, read here [how to add one](pay-per-view.md)
* Upload a _channel icon_ of **1:1 aspect ratio**, make sure it is contrast enough against the background

<details>

<summary>Expand to see how it looks on a real page</summary>

<img src="../../.gitbook/assets/Radio page.png" alt="" data-size="original">

</details>

## Channels details <a href="#channels-details" id="channels-details"></a>

You may also check properties of already added channels by clicking _Details_.

Information is divided in different tabs so you can navigate through and change the values.

Expand pictures to take a look what is inside every tab:

<details>

<summary>First tab contains general info and additional options</summary>

<img src="../../.gitbook/assets/Radio details.png" alt="" data-size="original">

</details>

<details>

<summary>In Images you can change the artwork</summary>

<img src="../../.gitbook/assets/Radio page Images.png" alt="" data-size="original">

</details>

<details>

<summary>In the third tab you can change the streams URLs</summary>

<img src="../../.gitbook/assets/Radio details streams.png" alt="" data-size="original">

</details>

<details>

<summary>Security contains content protection settings</summary>

<img src="../../.gitbook/assets/Radio details security.png" alt="" data-size="original">

</details>

<details>

<summary>Monetizing allow you to manage the PPV rules</summary>

<img src="../../.gitbook/assets/Radio details Monetizing.png" alt="" data-size="original">

</details>

<details>

<summary>Guide settings let you manage EPG for a certain radio</summary>

<img src="../../.gitbook/assets/Radio details Guide settings.png" alt="" data-size="original">

</details>

<details>

<summary>Guide imported shows you actual EPG data</summary>

<img src="../../.gitbook/assets/Radio details Guide importer.png" alt="" data-size="original">

</details>



## Bundles

Each bundle contains categories who in return contain Radio Stations. When publishing your Bundles the mapped TV Guide data is also published.

<figure><img src="../../.gitbook/assets/Без имени (67).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
During the deployment setup you have chosen the timezone on which the task scheduler should run on, this means each night your TV Guide gets refreshed and published together with your bundles.
{% endhint %}



### Adding a bundle

Click Add Bundle and specify its name in the popup window that logically describes a purpose of this bundle, e.g. News/Sports or Standard/Premium. Then, expand it and click Add Category. Specify the required info or leave blank

<figure><img src="../../.gitbook/assets/Без имени (68).png" alt=""><figcaption></figcaption></figure>

Once added, click _Radios_ in Category.

<figure><img src="../../.gitbook/assets/Без имени (69).png" alt=""><figcaption></figcaption></figure>

For your convenience, you have options to **filter** the radio by a provider, tag or name. If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish bundles! You may publish a single one or all at once. If you don’t publish a bundle, content won’t be propagated to the app.
{% endhint %}



## Lists

Specify here any **content** that you want to **promote** on the **Home page** of your **application**.

<figure><img src="../../.gitbook/assets/Без имени (70).png" alt=""><figcaption></figcaption></figure>

Click Add List and specify its self-explainable **name** in the **popup** window. Once it’s added, click _Radios_.

<figure><img src="../../.gitbook/assets/Без имени (71).png" alt=""><figcaption></figcaption></figure>

In the new window just **drag and drop** required radios. You may move all radios back and forth by clicking **>>** and **<<**

For your convenience, you have options to **filter** the radios by a provider, tag or name. If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish lists! If you don’t publish it, content won’t be propagated to the app.
{% endhint %}



## Import

[Download a radio example Excel to get you started](https://cloudtv.akamaized.net/donotremove/tvms/examples/Excels/Radio_.xlsx)

{% hint style="info" %}
We only accept **Excel .xlsx** files for importing
{% endhint %}

It is possible to import images, this is done by providing **a working URL** to the image asset. With importing images it is very important to respect **the aspect ratio 1:1** and the maximum image sizes. Images that have a correct image ratio but the sizes are too big our import tool will **automatically resize** them.

{% hint style="warning" %}
If you have empty columns (columns that hold no value) will cause issues, remove them
{% endhint %}
