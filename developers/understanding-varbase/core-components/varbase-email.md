# Varbase Email

Adds HTML email templates for Drupal.

## Varbase Email Module

{% hint style="info" %}
Varbase emailing features are bundled through the **Varbase Email** module.\
GitHub: [https://github.com/Vardot/varbase\_email](https://github.com/Vardot/varbase\_email)\
Drupal.org: [https://www.drupal.org/project/varbase\_email](https://www.drupal.org/project/varbase\_email)

After building a project using the `varbase-project` template, you can see the code of the **Varbase Email** module in:
{% endhint %}

```
project_directory
|-- docroot
    |-- modules
        |-- contrib
            |-- varbase_email
```

Brings in the following core and contributed modules to your site:

| Module                                                                       | Purpose                                 |
| ---------------------------------------------------------------------------- | --------------------------------------- |
| ****[**Symfony Mailer**](https://www.drupal.org/project/symfony\_mailer)**** | Integrate Symfony Mailer into Drupal.   |
| ****[**Swift Mailer**](https://drupal.org/project/swiftmailer)****           | Installs Swift Mailer as a mail system. |

{% content-ref url="../../configuring-a-varbase-site/configuring-varbase-mailer-settings/switch-configs-from-swift-mailer-to-symfony-mailer.md" %}
[switch-configs-from-swift-mailer-to-symfony-mailer.md](../../configuring-a-varbase-site/configuring-varbase-mailer-settings/switch-configs-from-swift-mailer-to-symfony-mailer.md)
{% endcontent-ref %}

{% content-ref url="../../configuring-a-varbase-site/configuring-varbase-mailer-settings/configure-symfony-mailer.md" %}
[configure-symfony-mailer.md](../../configuring-a-varbase-site/configuring-varbase-mailer-settings/configure-symfony-mailer.md)
{% endcontent-ref %}

{% content-ref url="../../configuring-a-varbase-site/configuring-varbase-mailer-settings/configure-swift-mailer.md" %}
[configure-swift-mailer.md](../../configuring-a-varbase-site/configuring-varbase-mailer-settings/configure-swift-mailer.md)
{% endcontent-ref %}
