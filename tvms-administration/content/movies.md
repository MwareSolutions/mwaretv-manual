# Movies

The overview table gives you common info about movies you have in the TVMS.

Each movie must contain an _icon_, _name, release year_ and _URL_. More required fields must be filled while adding a new movie

{% hint style="info" %}
The fact that a movie is in the list **does not mean** that it is available to the user, it may contain test movies too. To make it available, you have to create a [bundle ](movies.md#bundles)for a [product](../inventory/inventory.md)
{% endhint %}

<figure><img src="../../.gitbook/assets/Без имени (90).png" alt=""><figcaption></figcaption></figure>



## Adding a movie

Click the Add Movie button to open a movie adding wizard.

{% hint style="info" %}
Read in advance the [Movie requirements ](../../transcoding-and-streaming.md)to learn **URL** prerequisites and **token** settings
{% endhint %}

Follow the steps to add a movie, required field are emphasized:

* Specify general info like _Name_ and _Released, Runtime_ and others
* Select a _provider_ of a movie. Refer to [the instructions](settings.md#providers) to add one
* Add _stream URL_, use **MP4** or **DASH**
* Add _Description/Translations_ to provide a general info about a movie for end users
* Add _Content_ _Tags_ to make it available for search in the application
* Add _Content Genres_ to indicate it and help users better understand the content
* Define _actors_
* Set a _Parental Control_ ON to lock it from kids
* Set _Content placement_ if you want to have any temporary settings for this movie
* Set a _token_ and _DRM_ (if any), refer [how to add DRM](drm-and-tokens.md)
* If you use _VAST_, put a link
* Select _PPV rules_, read here [how to add one](pay-per-view.md)
* Upload a _movie poster 340x500 pixels, movie background of 1920x1080 pixels, movie logo of 300x100 pixels_, make sure it is contrast enough against the background

<details>

<summary>Expand how it looks on a real page</summary>

<img src="../../.gitbook/assets/Movies page.png" alt="" data-size="original">

</details>



## Movies details

You may also check properties of already added movies by clicking _Details_.

Information is divided in different tabs so you can navigate through and change the values.

Expand to take a look what is inside every tab:

<details>

<summary>First tab contains general info and additional options</summary>

<img src="../../.gitbook/assets/Movies details.png" alt="" data-size="original">

</details>

<details>

<summary>In Images you can change the artwork</summary>

<img src="../../.gitbook/assets/movies details images.png" alt="" data-size="original">

</details>

<details>

<summary>In Streams you can change the Streams URL</summary>

<img src="../../.gitbook/assets/movies details streams.png" alt="" data-size="original">

</details>

<details>

<summary>Security contains content protection settings</summary>

<img src="../../.gitbook/assets/movies details security.png" alt="" data-size="original">

</details>

<details>

<summary>Monetizing allows you to manage advertisement and the PPV rules</summary>

<img src="../../.gitbook/assets/movies details monetizing.png" alt="" data-size="original">

</details>



## Bundles

Each bundle contains categories who in return contain movies.

<figure><img src="../../.gitbook/assets/Без имени (97).png" alt=""><figcaption></figcaption></figure>

### Adding a bundle

Click Add Bundle and specify its name in the popup window that logically describes a purpose of this bundle, e.g. Drama/Comedy or Standard/Premium. Then, expand it and click Add Category. Specify the required info or leave blank

<figure><img src="../../.gitbook/assets/Без имени (98).png" alt=""><figcaption></figcaption></figure>

Once added, click _Movies_ in Category.

<figure><img src="../../.gitbook/assets/Без имени (99).png" alt=""><figcaption></figcaption></figure>

For your convenience, you have options to **filter** the movies by a provider, tag or name. If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish bundles! You may publish a single one or all at once. If you don’t publish a bundle, content won’t be propagated to the app.
{% endhint %}



## Lists

Specify here any **content** that you want to **promote** on the **Home page** of your **application**.

<figure><img src="../../.gitbook/assets/Без имени (100).png" alt=""><figcaption></figcaption></figure>

Click Add List and specify its self-explainable **name** in the **popup** window. Once it’s added, click _Movies_.

<figure><img src="../../.gitbook/assets/Без имени (101).png" alt=""><figcaption></figcaption></figure>

In the new window just **drag and drop** required movies. You may move all movies back and forth by clicking **>>** and **<<**

For your convenience, you have options to **filter** the movies by a provider, tag or name. If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish lists! If you don’t publish it, content won’t be propagated to the app.
{% endhint %}



## Search

**TVMS** provides an option of **automated movies import** from an online database. Thus, you’ll get **metadata** and **artwork**.

<figure><img src="../../.gitbook/assets/Без имени (102).png" alt=""><figcaption></figcaption></figure>

**Specify** a _movie name_ in the search field and click Search Movie. **Wait** for a while and check the search results below **in the table**. Find a **required movie** and click _Select_. **Specify** all required information in the **popup window** and click Add Movie in the bottom.

Thus, you have a **complete movie** in a bundle.
