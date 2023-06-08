# How to Translate The Theme

The default setting for Shopify stores is to allow the use of only one translation file at a time. While most Shopify themes are in English, some do offer multiple language options. In this article, I'll provide instructions on how to translate online stores into a single language other than English, as well as how to enable multi-language options.

### 1. Single Language

#### **Step 1: Change the default language**

* Settings > Languages > Under Published languages, click "Change default" button.

<figure><img src="../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

* Select the language you want to set as default. For example, I choose Italian > Save.

<figure><img src="../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

#### **Step 2: Update the translation file**

* Go to your current theme, Action > Edit default theme content.

<figure><img src="../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

#### **Step 3: Translate the theme**

You can translate manually for each element. For more information, you can follow this [Translating Themes instruction](https://help.shopify.com/en/manual/online-store/themes/customizing-themes/language/translate-theme) by Shopify.

<figure><img src="../.gitbook/assets/image (83).png" alt=""><figcaption></figcaption></figure>

### 2. Multi-language

In order to [sell products in multiple languages](https://help.shopify.com/en/manual/markets/languages), you must have the following:

* A theme that is capable of supporting sales in multiple languages (Digita is designed to do so).
* Installation of [Shopify's Geolocation app](https://apps.shopify.com/geolocation).
* Installation of [Shopify Translation & Adapt app](https://apps.shopify.com/translate-and-adapt).

#### Step 1: Install the two above-recommended apps

<figure><img src="../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

#### **Step 2: Create a new market which you want to add its language.**

* Settings > Markets > Hit "Add Market" button

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

* Select the market you want to add its language. In this case, I'll go with Germany.

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

#### Step 3: Add Languages

* Settings > Languages > Hit "Add Language" button

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

* Select the language > Next > Assign it to the corresponding Market

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

* Remember to publish the language

<figure><img src="../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

#### Step 4: Translate with the Translate App.

* Next to the language you want to translate, click "Edit" > choose "Translate & Adapt"

<figure><img src="../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

* Scroll down to the "Theme" area > Click "Edit" on the "Default theme content" section

<figure><img src="../.gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure>

* You can manually type your translation on the target language column or use Auto-translate function.

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

#### Step 5: Auto-generate the translation file.

The app will auto-generate the translation file for you. Let's check it if works

* Edit code > Open Locales folder > Check if there's a de.json file.

<figure><img src="../.gitbook/assets/image (100).png" alt=""><figcaption></figcaption></figure>
