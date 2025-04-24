# Cams

The overview table gives you common info about cams you have in the TVMS.

Each cam must contain a _number_, _icon_, _name_ and _URL_. Additionally, you can add _notes_ to a cam for any additional info that may be useful.

{% hint style="info" %}
The fact that a cam is in the list **does not mean** that it is available to the user, it may contain test cams too. To make it available, you have to create a [bundle](cams.md#bundles) for a [product](../inventory/inventory.md)
{% endhint %}

<figure><img src="../../.gitbook/assets/Без имени (75).png" alt=""><figcaption></figcaption></figure>

## Adding a Cam

Click the Add Cam button to open a cam adding wizard.

Follow the steps to add a cam, required field are emphasized:

* Specify general info like _Name_ and _Number_
* Select a _provider_ of a cam. Refer to [the instructions ](settings.md#providers)to add one
* If you provide a TV archive service, fill in _InteractiveTV fields,_ make sure you already have [transcoders](cams.md#transcoders)
* Add _stream URLs_, pay attention that **iOS/tvOS/KaiOS use .m3u8 only**, other platforms use **.mpd**
* Set a _Parental Control_ ON to lock it from kids
* Below, you can set a _country-specific age rating_
* Add _Content Tags_ to make it available for search in the application
* Add _Content Genres_ to indicate it and help users better understand the content
* Set _Content placement_ if you want to have any temporary settings for this cam
* Set a _token_ and _DRM_ (if any), refer [how to add DRM](drm-and-tokens.md)
* If you use _VAST_, put a link
* Select PPV rules, read here [how to add one](pay-per-view.md)
* Upload a _cam icon_ of **1:1 aspect ratio**, make sure it is contrast enough against the background, _Cam tile_ must be **16:9**

<details>

<summary>Expand to see how it looks on a real page</summary>

<img src="../../.gitbook/assets/Cams page.png" alt="" data-size="original">

</details>



## Cams details

You may also check properties of already added cams by clicking _Details_.

Information is divided in different tabs so you can navigate through and change the values.

Expand pictures to take a look what is inside every tab:

<details>

<summary>First tab contains general info and additional options</summary>

<img src="../../.gitbook/assets/Cam details.png" alt="" data-size="original">

</details>

<details>

<summary>In Images you can change the artwork</summary>

<img src="../../.gitbook/assets/Cam details Images.png" alt="" data-size="original">

</details>

<details>

<summary>In the third tab you can adjust Interactive TV and Stream URLs settings</summary>

<img src="../../.gitbook/assets/Cam details Streams.png" alt="" data-size="original">

</details>

<details>

<summary>Security contains content protection options</summary>

<img src="../../.gitbook/assets/Cam details Security.png" alt="" data-size="original">

</details>

<details>

<summary>Multiscreen</summary>

<img src="../../.gitbook/assets/Cam details multiscreen.png" alt="" data-size="original">

</details>

<details>

<summary>Monetizing allows you to manage the PPV rules</summary>

<img src="../../.gitbook/assets/Cam details Monetizing.png" alt="" data-size="original">

</details>



## Bundles

Each bundle contains categories who in return contain your Cams.

<figure><img src="../../.gitbook/assets/Без имени (83).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Bundles are an easy way to bundle content to be used in your products. Each package contains categories who in return contain content items.
{% endhint %}



### Adding a bundle <a href="#adding-a-bundle" id="adding-a-bundle"></a>

Click Add Bundle and specify its name in the popup window that logically describes a purpose of this bundle, e.g. Beach/City or Standard/Premium. Then, expand it and click Add Category. Specify the required info or leave blank.

<figure><img src="../../.gitbook/assets/Без имени (84).png" alt=""><figcaption></figcaption></figure>

Once added, click _Cams_ in Category.

<figure><img src="../../.gitbook/assets/Без имени (85).png" alt=""><figcaption></figcaption></figure>

For your convenience, you have options to **filter** the cam by a provider, tag or name. If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish bundles! You may publish a single one or all at once. If you don’t publish a bundle, content won’t be propagated to the app.
{% endhint %}



## Lists

Specify here any **content** that you want to **promote** on the **Home page** of your **application**.

<figure><img src="../../.gitbook/assets/Без имени (86).png" alt=""><figcaption></figcaption></figure>

Click Add List and specify its self-explainable **name** in the **popup** window. Once it’s added, click _Cams_.

<figure><img src="../../.gitbook/assets/Без имени (87).png" alt=""><figcaption></figcaption></figure>

In the new window just **drag and drop** required radios. You may move all cams back and forth by clicking **>>** and **<<**

For your convenience, you have options to **filter** the cams by a provider, tag or name. If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish lists! If you don’t publish it, content won’t be propagated to the app.
{% endhint %}



## Settings

On this page, specify a number of available **CatchupTV days**. It must be **equal** to the video server settings.

<figure><img src="../../.gitbook/assets/Без имени (88).png" alt=""><figcaption></figcaption></figure>



## Transcoders

To manage the InteractiveTV or CatchupTV settings, you need to add a transcoder, so click the Add Transcoder button

<figure><img src="../../.gitbook/assets/Без имени (89).png" alt=""><figcaption></figcaption></figure>

Specify **required information** and click the Add Transcoder button.

Once added, you may click _Test_ to be sure if the TVMS **can connect** to a transcoder. Then, you can select it in the _Cam details_ to manage the InteractiveTV or CatchupTV settings.

Click _Edit_ to **change** the settings.

