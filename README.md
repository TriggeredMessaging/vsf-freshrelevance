# Fresh Relevance
This module extends installs the [Fresh Relevance](https://www.freshrelevance.com) script. It passes site information,
browsing data to the Fresh Relevance backend. This will allow you to implement cart, browse and post-purchase triggers,
web and live email personalisation (including product recommendations). Data integrations supported with a [wide range
of ESPs, CDPs, Analytics and Review providers](https://www.freshrelevance.com/platform/integrations).


## Installation:

### 1. Clone the repository

Clone the vsf-freshrelevance repository into your VSF installation.
```shell
$ git clone git@github.com:TriggeredMessaging/vsf-freshrelevance.git vue-storefront/src/modules/vsf-freshrelevance
```
### 2. Add the extension config to your local VSF configuration file.
Add the following JSON config snippet into your `config/local.json`:

```json
"freshrelevance": {
  "id": "YOUR FRESH RELEVANCE WEBSITE ID",
}
```
Your Fresh Relevance Website ID can be found in the dropdown in the top right hand corner of your account.


#### Note that a Fresh Relevance account is required - contact us at `hello@freshrelevance.com` to get going.
