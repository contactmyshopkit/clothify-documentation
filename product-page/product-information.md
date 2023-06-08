---
description: >-
  Product Information is the area that displays information about a product such
  as price, badge, product size.
---

# Product Information

### Content > Badge

The Product Badge is one of the best way to enhance customer understanding of key product features and highlight promotion.

The theme provides 2 badges:

1. New: The New badge is displayed if the product has been published within the recent 10 days from today's date.
2. Sale: The Sale badge is displayed if the product is currently on sale.

To disable this feature, simply uncheck Content > Enable.

<figure><img src="../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>

### Content > Title

This product displays the Title of the product.

<figure><img src="../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

### Content > Availability

This block displays the quantity of the product that is currently available in your stock.

### Content > Type&#x20;

This block displays the product type.

<figure><img src="../.gitbook/assets/image (101).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure>

### Content > Collapse

Content > Collapse is a block that toggles the collapse feature of two kind of blocks:

1. Rich Text
2. **Ask to question**&#x20;

#### Collapse -> Rich Text

<figure><img src="../.gitbook/assets/Screenshot 2023-04-20 at 15.34.42.png" alt=""><figcaption></figcaption></figure>

Click on Collapse -> Rich Text to open this block setting. There are 3 settings there:

1. Collapse Icon
2. Collapse Title
3. Collapse Content

Note: The Content will be displayed on all product pages. You can use this feature to display information such as refund policy, shipping policy, etc.

### Adding Metafields to Products through Rich Text Field

Metafield is a useful feature that allows you to add extra information to a product.

To learn more about Metafield, please read [this article](https://help.shopify.com/en/manual/custom-data/metafields).

In this example, I'll show you how to add a Downloadable to the collapse.

#### **Step 1: Click on Settings -> Custom Data -> Products**

{% embed url="https://youtu.be/g2hs8uT3XvE" %}

#### **Step 2: Click Add definition button and create a metafield**

1. Field type: File
2. Validations: Accept all file types

<figure><img src="../.gitbook/assets/Screenshot 2023-04-20 at 16.35.26.png" alt=""><figcaption></figcaption></figure>

#### **Step 3: Navigate to Products -> Click on any product -> You will see Metafields -> Upload a pdf file to this field**

<figure><img src="../.gitbook/assets/Screenshot 2023-04-20 at 16.37.29.png" alt=""><figcaption></figcaption></figure>

#### Step 4: Adding the Downloadable metafield to product page

{% embed url="https://youtu.be/g2hs8uT3XvE" %}

The below is the code snippet that I used in the video:

```liquid
{% raw %}
{% unless product.metafields.custom.veda_product_meta_field.value.url == null %}
<a target="_blank" 
    href="{{ product.metafields.custom.veda_product_meta_field.value.url}}">
    Downloadable
</a>
{% endunless %}
{% endraw %}
```

The **custom.veda\_product\_meta\_field** is namespace and key of the metafield\


<figure><img src="../.gitbook/assets/Screenshot 2023-04-20 at 16.49.40.png" alt=""><figcaption></figcaption></figure>

### Ask to question block

The Ask to question is a block that displays a contact form. Customers can use this form to ask questions related to the product.

<figure><img src="../.gitbook/assets/Screenshot 2023-04-20 at 15.30.32.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2023-04-20 at 15.33.15.png" alt=""><figcaption></figcaption></figure>

