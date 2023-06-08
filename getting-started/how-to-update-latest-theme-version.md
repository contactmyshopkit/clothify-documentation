# How To Update Latest Theme Version

It's essential to update your theme regularly to ensure it remains up-to-date with new features and improved functionality. We'll release new updates on Github and notify you via email. To install the latest theme, follow the same steps as before.

Please keep in mind that the updated theme won't preserve any customizations you made in the previous version. Custom code and built-in apps won't migrate automatically to the new theme. Therefore, you'll have to migrate and re-integrate the apps manually.

### 1. **Move the old theme configuration to the new one**

#### a/ Move the settings\_data.json file

* "Edit code" of the old theme version

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

* Open settings\_data.json file > Copy the whole code on this file.

<figure><img src="../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (65).png" alt=""><figcaption></figcaption></figure>

* Paste it into the same file of the new theme.

<figure><img src="../.gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

#### b/ Move index.json file

You can follow the same steps as you did with settings\_data.json file above. Copy the index.json file of the old theme & paste it into the new theme.

#### c/ Move .json files with a green dot in Templates folder

The green dot indicates that they are changed files. So, you need to copy & paste them into the new theme.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

### 2. Move the **translation file**

If you sell in multi-languages, you need to move the translation file to the new theme.

* Click the Locales folder to open the language file. Copy all language files you have. In this case, I only have vi.json file.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

* Paste it into the new theme: Add a new locale > Paste vi.json.

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>
