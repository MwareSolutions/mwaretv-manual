# Preparing Apps for Publishing

First of all, you need to create an app approval product. This would be a special product with Live TV channels only to simplify the app publishing process.

<details>

<summary>Create an app approval product</summary>

1. First thing is to decide which content will you use for the approval product. In most cases, these are 10 most popular channels with legal papers. You can choose them out from the channels list and create their copies. Don't forget to add a note that this is a special copy for the approval product and keep all other properties untouched, **including the channel number**. Once you have these copies, you can combine them in a bundle.
2. Go to Bundles and create a new one, call it "Approval bundle" to not confuse it with other live bundles. Add that approval content, additionally you can create different categories like News, Sports, etc. Don't forget to publish this bundle.
3. Go to Inventory > Subscriptions > click Add Subscription and create an approval one, call it "Approval product", select BASE type, PAID variant, include the bundle you made, 5 maximum allowed devices and significant subscription length about a year or more with zero cost. Don't forget to publish it.
4. Go to Billing, create a test webshop and add this product therein.&#x20;
5. Go to Customer and create customers apple\_approval, google\_approval, etc. Give it a password like 1234.
6. Try to log in with these credentials and make sure it shows the defined content.

</details>

Once your app approval product is ready, you can proceed with completing all the mandatory steps to publish your apps on various stores. To do this, check the articles below:

<details>

<summary>Apple App Store</summary>

If you have not created your Apple Developer account yet, please see the following [article](https://docs.tvms.io/app-publishing/completing-the-prerequisites/registering-developer-accounts#apple-developer-account).

### Creating your app

To add a new app on App Store Connect you need to have an App ID created. The App ID will be created by our development team. Once it is created, you can continue and [create a new app](https://help.apple.com/app-store-connect/#/dev2cd126805) on the App Store Connect. We support iOS and tvOS platforms on the App Store.

### Preparing your app for publishing

After you have created your app on App Store Connect, you can upload its information such as name, description, keywords, graphics, etc. Next, we'll describe only the mandatory steps you need to complete in order to submit your app for review.

You can start with the iOS and/or tvOS app version information. Here you'll need to provide:

* App screenshots
* Description
* Keywords
* Support URL
* Copyright

Also, you'll need to provide App Review information:

* Sign-in information
* Contact information

All these items should be intuitive, but if you have questions, you can click on the hint icon next to each of these items in the App Store Connect to read more. You can find all graphics requirements in our [article here](https://docs.tvms.io/app-publishing/completing-the-prerequisites/store-requirements#app-store).

Next, find the **General** section in the side menu on the left and complete the following:

**App Information**

* Set up Content Rights
* Set Age Rating
* Select the category for your app. Select **Entertainment** as the primary category.

**Pricing and Availability**

* Select the price. Most likely you are going to sell a service, but not the app itself. If so, select **Free**.
* By default, your app will be available in all available regions. If you want to change it, you can do it in the **Availability** section.

**App Privacy**

* Add your Privacy Policy URL

</details>

<details>

<summary>Google Play</summary>

If you have not created your Google Play Developer account yet, please see the following [article](https://docs.tvms.io/app-publishing/completing-the-prerequisites/registering-developer-accounts#google-play-developer-account).

### Creating your app

This [manual](https://support.google.com/googleplay/android-developer/answer/9859152?hl=en\&ref_topic=7072031) describes app creation at Google Play. Just follow the steps and you'll create your app. When creating your app, choose _App_ and _Free_.

### Preparing your app for publishing

After you’ve created your app, you can start setting it up. You need to complete the [initial setup](https://support.google.com/googleplay/android-developer/answer/9859454?hl=en). This setup includes completing the **App content** section and providing store listing details.

**App content**

The **App content** page is where you provide and manage the information Google needs to ensure that your app is safe for its intended users, is compliant with [Google Play Policies](https://play.google.com/about/developer-content-policy/), and satisfies legal requirements. Here you need to complete:

* Privacy policy Provide a URL to your Privacy policy.
* App access Here you need to provide Google Play Review Team with access to your app. To do this, select **All or some functionality is restricted** and add new instructions to log in to the app.
* Ads Select **No, my app does not contain ads**.
* Content rating Here you need to complete the content rating questionnaire to receive official content ratings for your app. Click **Start**, enter your email, select the **Entertainment** category. Complete the questionnaire, click **Save**, then **Next**, and after it click **Submit**.
* Target audience Select the **18 and over** target age group and answer the question.
* News apps Select **No**.

If you need more info about the App content page, please see the following [manual](https://support.google.com/googleplay/android-developer/answer/9859455).

**App categorization and store listing details**

Next, you need to complete store settings and provide store listing details.

* Store settings Open the [Store settings](https://play.google.com/console/developers/app/store-settings) page. Here you need to select the **Entertainment** category for your app and enter your contact details. Optionally you can select one or multiple tags. Save the changes.
* Store listing Open the [Main store listing](https://play.google.com/console/developers/app/main-store-listing) page. Here you need to provide app short description, app full description, and graphics. You can find all graphics requirements on the **Main store listing** page or at our [article here](https://docs.tvms.io/app-publishing/completing-the-prerequisites/store-requirements#google-play)

</details>

<details>

<summary>Amazon Appstore</summary>

This [manual](https://developer.amazon.com/docs/app-submission/publish-app-login-and-add-app.html#log-in-and-add-an-app) describes how to create an app on the Developer Portal. When adding a new app, choose **Android**.

After you’ve created your app, you can start setting it up. You need to complete all the tabs on the Developer Portal before you can submit your app for review to Amazon.

As you navigate from tab to tab, click **Save** to save your information. The information on each tab is not automatically saved when you go to another tab

Please find the [workflow map](https://developer.amazon.com/docs/app-submission/submitting-apps-to-amazon-appstore.html#publishing-overview) in the Amazon Appstore manual. It will guide you through the process. Click on the step you are currently working on and it will provide you with the details.

After you have submitted your app for review, it takes Amazon 1-2 weeks to review and approve your app to go live in the marketplace. You should be receiving an email once your app has gone through Amazon's submission process.

</details>

<details>

<summary>LG Content Store</summary>

If you have not created your LG Developer account yet, please see the following [article](https://docs.tvms.io/app-publishing/completing-the-prerequisites/registering-developer-accounts#lg-developer-account).

### Creating your app

To create an app, go to [LG Seller Lounge](http://seller.lgappstv.com/seller/guide/sellerRegistration.lge), sign in with your LG Developer account, and register a new app.

### Preparing your app for publishing

* **Upload the app for the pre-test** LG .ipk file from Mware is required here.
* **Upload graphics** If you don't have graphics, please see the following [article](https://docs.tvms.io/app-publishing/completing-the-prerequisites/store-requirements).
* **App submission details** Fill in your app submission details for the supported region, content, rating, etc.
* **App test details** Provide info to help app testing.

To find more info, please see **the** **App Management** section (pages 34-61) in the [LG Seller Lounge](http://gfts.lge.com/fts/gftsDownload.lge?biz_code=APP_STORE\&func_code=APP_PAPER\&file_path=/appstore/seller/guide/sellerlounge_user_guide_v11.5.zip) guide. The guide is available as a PDF file.

</details>

<details>

<summary>Samsung Tizen Store</summary>

If you have not created your Samsung Developer account yet, please see the following [article](https://docs.tvms.io/app-publishing/completing-the-prerequisites/registering-developer-accounts#samsung-developer-account).

### Creating your app

The next [manual](https://developer.samsung.com/smarttv/develop/distribute/seller-office/applications/registering-application.html) describes how to create an app on Samsung TV Seller Office. When creating an app, choose the **Tizen** app type.

### Preparing your app for publishing

After you’ve created your app, you can start setting it up. You'll need to provide the following information:

* **App UI Description** file according to [this guide](https://developer.samsung.com/smarttv/develop/distribute/launch-checklist/application-ui-description.html).
* App title and description in each of the supported languages,
* Contact information as an email address for VOC inquiries and notifications
* Test account credentials, vouchers, etc. (with enough credit to fully test the application on all selected platforms)

Also, you'll need to upload graphics that you should already have. If not, please find the graphics requirements in this [article](https://docs.tvms.io/app-publishing/completing-the-prerequisites/store-requirements).

To find more info, please see [Samsung's guide](https://developer.samsung.com/smarttv/develop/distribute/seller-office/applications/entering-application-information.html)

</details>

<details>

<summary>Roku Channel Store</summary>

If you have not created your Roku Developer account yet, please see the following [article](https://docs.tvms.io/app-publishing/completing-the-prerequisites/registering-developer-accounts#roku).

### Pre-publishing checklist

Before submitting a channel for publication, complete the following items:

* Create your Roku Developer account and verify your email address.
* Link a Roku device to your account.
* Fill out complete company info: name, address, phone, etc.
* Prepare the required [assets](https://docs.tvms.io/app-publishing/completing-the-prerequisites/store-requirements#roku-channel-store) for branding your channel.

When all these items are completed and you are ready to launch your Roku app, please contact our team and we'll do the needful.

</details>

