# Series

The overview table gives you common info about series you have in the TVMS.

Each series must contain an _image_, _name_ and _URL_. More required fields must be filled while adding a new series.

{% hint style="info" %}
The fact that a series is in the list **does not mean** that it is available to the user, it may contain test series too. To make it available, you have to create a [bundle](series.md#bundles) for a [product](../inventory/inventory.md)
{% endhint %}

<figure><img src="../../.gitbook/assets/Без имени (115).png" alt=""><figcaption></figcaption></figure>

## Adding series

Click the Add Series button to open a series adding wizard.

{% hint style="info" %}
Read in advance the [Series requirements ](../../transcoding-and-streaming.md)to learn **URL** prerequisites and **token** settings
{% endhint %}

{% hint style="warning" %}
According to the TVMS structure, Series is just a collection of Seasons, so now you add only common series info without season and episodes, follow next pages to learn how to add a complete series
{% endhint %}

Follow the steps to add a series, required field are emphasized:

* Specify _Name_ and _IMDB ID_ (if any)
* Select a _provider_ of a series. Refer to [the instructions ](settings.md#providers)to add one
* If you use _VAST_, put a link
* Select _PPV rules_, read here [how to add one](pay-per-view.md)
* Set a _token_ and _DRM_ (if any), refer [how to add DRM](drm-and-tokens.md)
* Set a _Parental Control_ ON to lock it from kids
* Below, you can set a _country-specific age rating_
* Add _Content Tags_ to make it available for search in the application
* Add _Content Genres_ to indicate it and help users better understand the content
* Set _Content placement_ if you want to have any temporary settings for this series
* Upload a _series widescreen 640x360 pixels, series logo of 300x100 pixels_

<details>

<summary>Expand to see how it looks on a real page</summary>

<img src="../../.gitbook/assets/Series page.png" alt="" data-size="original">

</details>

## Seasons

{% hint style="info" %}
All your seasons in the system, you can add as many as you want.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

Seasons are included in series, they define the content filling of series, so one can't watch series without seasons.

### Addind a season

Click the **Add Season** button to open a wizard

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
### Common information

Specify the required fields above: _Name_, _Seasons Number_, _Released_, _Studio_, _Language_.&#x20;

Optionally, set a _star rating_, it will help you users understand content better. \
Select a provider, so you can track the content comsumption on a provider-based condition. \
Give a _description_ so end users will read short annotations about a particular season. \
&#xNAN;_&#x41;ctors_ will be displayed in the app with their fotos, _tags_ will help customers navigate the content. \
&#xNAN;_&#x43;ontent placement_ allows you to manage the availability time of a season.
{% endstep %}

{% step %}
### Adding episodes

Click the **Add Season Episodes** button to open a new popup wizard.



<img src="../../.gitbook/assets/image (8).png" alt="" data-size="original">

Specify _Name_, _Number and Length_. Optionally, give a description. Set an _Episode URL_, that's what an end user will watch in the app. We recommend to use MP4 or DASH.

Additionally, you may define _subtitles_ and _thumbnail_ URLs if any.

Turn _Allow Download_ on to let users save an episode to watch it offline later. Set _Expiration Downloads_ in days to define how long one can store content on a device.

Upload an episode preview picture of 1&#x36;**:9 aspect ratio.**

Click **Add Episode** to save it. Click **Add Season Episodes** to add a next episode.
{% endstep %}

{% step %}
### Artwork

Last, upload artwork for a poster, background and logo. Respect the mentioned aspect ratio, otherwise files will be refused.

<img src="../../.gitbook/assets/image (9).png" alt="" data-size="original">


{% endstep %}

{% step %}
### Adding a season to series

Once a season is added, you have to add to a series. Go back to the series list, find a required series and click the Add Seasons button



<img src="../../.gitbook/assets/image (10).png" alt="" data-size="original">
{% endstep %}
{% endstepper %}

## Bundles

Each bundle contains categories who in return contain Series

<figure><img src="../../.gitbook/assets/Без имени (118).png" alt=""><figcaption></figcaption></figure>

## Adding a bundle <a href="#adding-a-bundle" id="adding-a-bundle"></a>

Click Add Bundle and specify its name in the popup window that logically describes a purpose of this bundle, e.g. News/Sports or Standard/Premium. Then, expand it and click Add Category. Specify the required info or leave blank

<figure><img src="../../.gitbook/assets/Без имени (119).png" alt=""><figcaption></figcaption></figure>

Once added, click _Series_ in Category.

<figure><img src="../../.gitbook/assets/Без имени (120).png" alt=""><figcaption></figcaption></figure>

For your convenience, you have options to **filter** the series by a provider, tag or name. If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish bundles! You may publish a single one or all at once. If you don’t publish a bundle, content won’t be propagated to the app.
{% endhint %}

## Lists

Specify here any **content** that you want to **promote** on the **Home page** of your **application**.

<figure><img src="../../.gitbook/assets/Без имени (121).png" alt=""><figcaption></figcaption></figure>

Click Add List and specify its self-explainable **name** in the **popup** window. Once it’s added, click _Series_.

<figure><img src="../../.gitbook/assets/Без имени (122).png" alt=""><figcaption></figcaption></figure>

In the new window just **drag and drop** required series. You may move all series back and forth by clicking **>>** and **<<**

For your convenience, you have options to **filter** the series by a provider, tag or name. If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish lists! If you don’t publish it, content won’t be propagated to the app.
{% endhint %}

