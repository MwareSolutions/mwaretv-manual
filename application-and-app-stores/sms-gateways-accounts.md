# SMS gateways accounts

## Twilio

* Log in to your Twilio account.
* In the top-right corner click **Admin > Account management**.
* Go to **Keys & credentials** > **API keys & tokens**.
* Click **Create API key**.
* Then give a name for the API key.
* Select the **Region**, then select a key type: **Standard**, **Main**, or **Restricted** (available in the United States Region only). For Restricted keys, you also have to select the **Permissions**.
* Click **Create**.
* Copy the secret key, paste it to the TVMS and better safe it somewhere else in a secure place.
* Check the **Got it!** checkbox and click **Done**.

## Africa's Talking

![](../.gitbook/assets/5zQ9vItQ4wdlAozp3ByLnzrG8mi40pxC2w0YRjBj8ImPKNVVheawn4CQHMK5dAm7tANxE5zF-3NvMc0ufYHAmfnROLu3CAfeTydkQVqzUrFcyhitOqEg9BCRvN5K-WHM59gwOVWE.png)

**Production/Live Users**

1. Log into your account and open the dashboard
2. In the left menu, click **Settings**
3. Click **API Key**
4. Enter a password and click **Generate**
5. Copy the API Key in the TVMS and safe in a secure place.

**Sandbox Users**

1. Log into your account, and click the **Go To Sandbox App** button.
2. In the left menu, click **Settings**
3. Click **API Key**
4. Enter a password and click **Generate**
5. Copy the API Key in the TVMS and safe in a secure place.

{% hint style="info" %}
Wait about 3 minutes before a new API key is activated.
{% endhint %}

## Pindo

Generating an API key for Pindo requires a bit of expertise in Python.

Install from PyPi using [pip](http://www.pip-installer.org/en/latest), a package manager for Python.

If you don't have it, install it:

`$ curl https://raw.github.com/pypa/pip/master/contrib/get-pip.py | python`

`python setup.py install`

Then run:

`pip install pindo-cli`

Refer to the instruction below:

```
Usage: pindo [OPTIONS] COMMAND [ARGS]...

Pindo CLI
	
A simple Command Line Interface that allows you to authenticate with the Pindo API
	
https://www.pindo.io

<...>

Commands:<...>
  token          Request a token for using Pindo API.
```

Generate an API key and paste it to the TVMS.

Refer to the Pindo documentation for more details: [https://github.com/pindoio/pindo-cli](https://github.com/pindoio/pindo-cli)
