# Zendesk Hide Fields

The [Zendesk Classic Web Widget](https://developer.zendesk.com/api-reference/widget/introduction/) does not provide a way to hide certain fields in the forms. These fields can be seen [here](https://support.zendesk.com/hc/en-us/articles/4408886739098-About-ticket-fields) but for example `Subject` and `Description`.

## Motivation

One of the most asked questions on the Zendesk Support Center is [how to disable these](https://support.zendesk.com/hc/en-us/articles/4408882841498-How-can-I-disable-the-subject-and-description-fields-from-the-request-form-).

The proposed way is not developer friendly. Instead, this repository proposes to hide the HTML of these fields after the Widget has loaded.

## How it works

Checks if the Web Widget has loaded and if so, removes unwanted fields.

## How to use

Adjust your HTML so that it the `<script>` in `script.html` is included in the `body` tag.

Hope that your Zendesk integration goes smooth :fingers-crossed:
