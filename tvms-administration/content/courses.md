# Courses

The overview table gives you common info about courses you have in the TVMS.

Each courses must contain an _icon_, _name, release year_ and _URL_. More required fields must be filled while adding a new course

{% hint style="info" %}
The fact that a course is in the list **does not mean** that it is available to the user, it may contain test courses too. To make it available, you have to create a [bundle ](courses.md#bundles)for a [product](../inventory/inventory.md)
{% endhint %}

<figure><img src="../../.gitbook/assets/Без имени (123).png" alt=""><figcaption></figcaption></figure>

## Add a course <a href="#add-a-course" id="add-a-course"></a>

Click the Add Course button to open a course adding wizard.

{% hint style="info" %}
Read in advance the [Course requirements](https://mwaretv.atlassian.net/wiki/spaces/TM/pages/43745332) to learn **URL** prerequisites and **token** settings
{% endhint %}

Follow the steps to add a course, required field are emphasized:

* Specify general info like _Name_ and _Released_ and others
* Select a _provider_ of a course. Refer to [the instructions](settings.md#providers) to add one
* Add _Tags_ to make it available for search in the application
* If you use _VAST_, put a link
* Select _PPV rules_, read here [how to add one](pay-per-view.md)
* Set a _token_ and _DRM_ (if any), refer [how to add DRM](drm-and-tokens.md)
* Set a _Parental Control_ ON to lock it from kids
* Set _Content placement_ if you want to have any temporary settings for this course
* Add _Description/Translations_ to provide a general info about a course for end users
* Define _teachers_
* Add _lessons URLs_: specify _Lesson Name_, _Lesson Number_, _Lesson Length_, _Descriptions/Translations, Lesson URL and upload a Lesson image of 640x360 pixels_
* Upload a _course poster 340x500 pixels, course widescreen of 640x360 pixels_ and _course background of 1920x1080 pixels_

<details>

<summary>Expand to see how it looks on a real page</summary>

<img src="../../.gitbook/assets/Courses page.png" alt="" data-size="original">

</details>

## Courses details <a href="#courses-details" id="courses-details"></a>

You may also check properties of already added courses by clicking _Details_.

Information is divided in different tabs so you can navigate through and change the values.

Expand to take a look what is inside every tab:

<details>

<summary>First tab contains general info and additional options</summary>

<img src="../../.gitbook/assets/course details.png" alt="" data-size="original">

</details>

<details>

<summary>In Images you can change the artwork</summary>

<img src="../../.gitbook/assets/course details images.png" alt="" data-size="original">

</details>

<details>

<summary>Monetizing allows you to manage advertising and the PPV rules</summary>

<img src="../../.gitbook/assets/course details monetizing.png" alt="" data-size="original">

</details>

<details>

<summary>Security contains content protection settings</summary>

<img src="../../.gitbook/assets/course details security.png" alt="" data-size="original">

</details>

<details>

<summary>Add, change or delete lessons</summary>

<img src="../../.gitbook/assets/course details lessons.png" alt="" data-size="original">

</details>

## Bundles

Each bundle contains categories who in return contain Courses

<figure><img src="../../.gitbook/assets/Без имени (129).png" alt=""><figcaption></figcaption></figure>

## Adding a bundle <a href="#adding-a-bundle" id="adding-a-bundle"></a>

Click Add Bundle and specify its name in the popup window that logically describes a purpose of this bundle, e.g. News/Sports or Standard/Premium. Then, expand it and click Add Category. Specify the required info or leave blank

<figure><img src="../../.gitbook/assets/Без имени (130).png" alt=""><figcaption></figcaption></figure>

Once added, click _Courses_ in Category.

<figure><img src="../../.gitbook/assets/Без имени (131).png" alt=""><figcaption></figcaption></figure>

For your convenience, you have options to **filter** the courses by a provider, tag or name. Drag and drop required courses or all at once by clicking **>>** and **<<**

If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish bundles! You may publish a single one or all at once. If you don’t publish a bundle, content won’t be propagated to the app.
{% endhint %}

## Lists

Specify here any **content** that you want to **promote** on the **Home page** of your **application**.

<figure><img src="../../.gitbook/assets/Без имени (132).png" alt=""><figcaption></figcaption></figure>

Click Add List and specify its self-explainable **name** in the **popup** window. Once it’s added, click _Courses_.

<figure><img src="../../.gitbook/assets/Без имени (133).png" alt=""><figcaption></figcaption></figure>

For your convenience, you have options to **filter** the shorts by a provider, tag or name. If there are more than one bundle, you may **switch to another one** using the dropdown menu in the **upper right** corner.

{% hint style="info" %}
Don’t forget to publish lists! If you don’t publish it, content won’t be propagated to the app.
{% endhint %}
