# Testing an app

{% hint style="info" %}
In this section, you can find information on how to install your app for testing and what to test in your app.
{% endhint %}

Whether we have provided you with a brand new app or a new version of your app, you may be interested in testing it before releasing it to your clients. Of course, the Mware team performs all performance and stability tests with every new app, but we believe that you might still be interested in running a test review of the app or a smoke test on your devices.

### How to install your app for testing <a href="#how-to-install-your-app-for-testing" id="how-to-install-your-app-for-testing"></a>

We all know how to install an app from a marketplace. But if your app has not been published yet in a marketplace and you need to install it for a test review, the installation process is different. For details, see the following:

<details>

<summary>How to Install an App for Testing on Android</summary>

Let's take a look at the easiest ways to install your Android app for testing.

### Install from APK

The most straight and simple way is to download an APK file of your app on your Android device and install it.

1. When your app is ready for testing, we'll provide you with a link to download the APK file.
2. You can open this link on your Android device and download the file.
3. Next, tap on the file and follow the steps that your device will provide to complete the installation.

That's it. You have installed your app and are ready [to proceed with testing](https://docs.tvms.io/app-publishing/app-testing#what-to-test).

However, this simple method can have its pitfalls. Downloading and installing an APK means you are installing an app from an unknown source. Nowadays Android has additional layers of security, like [Google Play Protect](https://support.google.com/android/answer/2812853), that may not allow you to install an app from an unknown source. It is up to you whether you'll disable this feature or will keep it enabled, but if you are facing difficulties installing an app from APK or the security policies in your organization deny installing an app from an unknown source, see the second option below.

### Create a testing track on Play Console

If you have not created your Google Play Developer account yet, please see the following [article](https://docs.tvms.io/app-publishing/completing-the-prerequisites/registering-developer-accounts#google-play-developer-account).

The second option is to use [Play Console](https://play.google.com/console/u/0/developers). Using it, you can set up open, closed, or internal test tracks. These tracks allow you to test your app with specific groups or open your test to Google Play users. Each of these testing tracks has its own features, but we recommend you to continue with the **Internal testing track** because it is the fastest one. However, if you want to learn more about all other tracks, see the following [article](https://support.google.com/googleplay/android-developer/answer/9845334).

By default, we provide APK files for app testing, but to launch your app for testing via Play Console, you'll need an **AAB** (Android App Bundle) file. If you are going to continue through the Play Console, please let us know and we'll provide you with the AAB file for testing.

To continue, you should have an app created at Play Console. If it is not, see the following [article](https://docs.tvms.io/app-publishing/working-with-stores/google-play#creating-your-app).

To set up internal testing, complete the following steps.

#### Step 1: Set up test details

You have to create a list of internal testers by email address. An internal test can have up to 100 testers per app.

1. Log in to [Play Console](https://play.google.com/console/u/0/developers) and go to the [**Internal testing**](https://play.google.com/console/developers/app/tracks/internal-testing) page (**Testing** > **Internal testing**).
2. Select the **Testers** tab, then select **Create email list**.
3. Enter a list name. You can use the same list for future tests on updates of your app.
4. Add email addresses separated by commas or click **Upload CSV file**. If you use a .CSV file, put each email address on its own line without any commas. If you upload a .CSV file, it will overwrite any email addresses you've added.
5. Select **Save changes**, then **Create.** You have created an email list of your testers.
6. Next, select the user lists you want to test your release.
7. Copy the shareable link to share the release with testers. Then select **Save changes**.

#### Step 2: Create a release

Once you've set up the details of your app's test, you can prepare and roll out a release.

1. Go to **Testing > Internal testing** and click **Create new release**.
2. Upload your AAB file, then select **Save**.
3. When you've finished preparing your release, select **Review release**.
4. Select **Start rollout to Internal testing**, then select **Rollout**.

#### Step 3: Share your app with testers

Your internal testers won’t be able to find your app by searching it on Google Play. You need to share the app’s Play Store URL with testers so they can download your app. You have copied this URL in the last item at **Step 1**, so this step is pretty easy:

1. Simply share the link with your testers and you are ready [to proceed with testing.](https://docs.tvms.io/app-publishing/app-testing#what-to-test)

After clicking the opt-in link, your testers will get an explanation of what it means to be a tester and a link to opt-in. Each tester needs to opt-in using the link before he can install your app.

#### Step 4: End a test

When you have finished testing your app and are ready to release it to production, it may be useful to end the testing track you have, so the users that were testing won't face any difficulties installing the production version.

To remove users from your app's test:

1. Open Play Console and go to **Testing** > **Internal testing**.
2. Near the top right of the page, select **Pause track**.
3. After ending a test, testers won't receive updates but the app will remain installed on their device

</details>

<details>

<summary>How to install an app for testing on iOS and tvOS</summary>

Let's take a closer look at how you can install your iOS or tvOS app for testing.

### TestFlight

TestFlight is a beta-testing service that is available in your Apple Developer account.

The fastest and the easiest way is to use **Internal Testing** in TestFlight. When your iOS or tvOS app is ready for testing, we'll upload it to your account at App Store Connect and it will appear in TestFlight.

#### Preparations

To start testing, you’ll need to accept an email invitation and have a device that you can use to test. To send you the invitation, you need to provide us with your Apple ID email address. If you don't have an Apple ID, you can [create a new one here](https://appleid.apple.com/account) or you can provide us with your email address and you'll be prompted to register a new Apple ID when you will be accepting the invitation.

In total you'll need to accept 2 invitations:

* The first one is to join your Apple Developer team and have the possibility to become an internal tester. That is why an Apple ID is required.
* The second one is to join TestFlight and test your app.

If you want to complete this preparation step by yourself, see the following [article](https://help.apple.com/app-store-connect/#/dev839fb66e9).

#### Installation

To get started, install TestFlight on the device you’ll use for testing. Then, accept your email invitation to install your app.

**Installing an iOS app via email invitation**

1. [Install TestFlight](https://itunes.apple.com/us/app/testflight/id899247664?mt=8) on the iOS device that you’ll use for testing.
2. Open your invitation email on your iOS device.
3. Tap View in TestFlight or Start Testing; or tap Install or Update for the app you want to test.

**Installing a tvOS App via Email Invitation**

1. [Install TestFlight](https://itunes.apple.com/us/app/testflight/id899247664?mt=8) on Apple TV.
2. Open your invitation email on a mobile device or computer.
3. Click or tap Start Testing. You'll be taken to a web page with a redemption code.
4. Open TestFlight on Apple TV.
5. Go to Redeem and enter the redemption code.

That's it. You have installed your app and are ready [to proceed with testing](https://docs.tvms.io/app-publishing/app-testing#what-to-test).

</details>

<details>

<summary>How to install an app for testing on Firestick</summary>



You need the **Downloader** app to be installed for downloading files from the Internet. Please, follow the steps:

1.

    <figure><img src="../.gitbook/assets/Без имени (43).png" alt=""><figcaption></figcaption></figure>
2.

    <figure><img src="../.gitbook/assets/Без имени.jpeg" alt=""><figcaption></figcaption></figure>
3.

    <figure><img src="../.gitbook/assets/Без имени (1).jpeg" alt=""><figcaption></figcaption></figure>
4.

    <figure><img src="../.gitbook/assets/Без имени (2).jpeg" alt=""><figcaption></figcaption></figure>
5.

    <figure><img src="../.gitbook/assets/Без имени (3).jpeg" alt=""><figcaption></figcaption></figure>
6.

    <figure><img src="../.gitbook/assets/Без имени (4).jpeg" alt=""><figcaption></figcaption></figure>
7.

    <figure><img src="../.gitbook/assets/Без имени (44).png" alt=""><figcaption></figcaption></figure>
8. Select “Open”, then “Allow” then “OK”
9. Then put a link to APK file you want, download and install it

</details>

<details>

<summary>How to install an app for testing on Roku</summary>

## How to Install an App for Testing on Roku

Unfortunately, we can't provide you with the possibility to install your white-labeled Roku app for testing. Instead, you can use our [demo app](https://my.roku.com/account/add/6GMLZDP), which can be added as a private demo channel to your account on Roku. Your white-labeled app will be the same as the demo app, except for logos and icons.

### How to add a demo channel?

The demo app is a non-certified channel that can be used for testing. To download and install our demo channel:

1. Go to [my.roku.com](http://my.roku.com/) on your computer or smartphone.
2. If prompted, sign in to your Roku account.
3. Under Manage account select **Add channel with a code**.
4. Enter our demo channel access code **6GMLZDP** and select **Add Channel**.
5. Acknowledge the warning message that appears.

The channel will not immediately appear in the list of channels on your Roku streaming player or Roku TV™. Your Roku device checks every 24 to 36 hours for any new channels you have added from the website and automatically installs them.

If you would like to download the channel immediately, go to your Roku device and select **Settings** > **System** > **System update** > **Check now.**

Once downloaded, new channels are added to the list of channels under Home on the main screen of your Roku device.

</details>

### What to test

Simulate all of the expected behaviors of your end-users. To make it clearer, here's a quick checklist for efficient app testing.

* Check how your branding is applied. Does the app icon, splash logo, and other images look good or do you want to change some particular image for another?
* Check UI design;
* Check log in;
* Check is your app pointed to correct CRM;
* Check Search;
* Check Channels: Live TV, Zapping, Press and hold;
* Check TV Guide;
* Check CatchupTV;
* Check Recordings;
* Check Movies;
* Check Series;
* Check Music.

All these things are checked by us before providing you with a new app version. However, we recommend you to run these tests on your devices as well to ensure your app looks and functions how you expect, and in the best way possible for your users.
