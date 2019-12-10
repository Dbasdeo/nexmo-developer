---
title: Send a Link Button
meta_title: Send a link button on WhatsApp using the Messages API
---

# Send a Link Button

## Example

Ensure the following variables are set to your required values using any convenient method:

Key | Description
-- | --
`WHATSAPP_NUMBER` | The WhatsApp number that has been allocated to you by Nexmo.
`TO_NUMBER` | The phone number you are sending the message to.
`HEADER_IMAGE_URL` | The URL of the image to display in the template message header.

> **NOTE:** Don't use a leading `+` or `00` when entering a phone number, start with the country code, for example, 447700900000.

```code_snippets
source: '_examples/messages/whatsapp/send-button-link'
application:
  type: messages
  name: 'Send a link button to WhatsApp'
```

## Try it out

When you run the code a WhatsApp message containing a link button is sent to the recipient. In this example the button is a link to package tracking information.

## Further information

* [Custom objects](/messages/concepts/custom-objects)

## WhatsApp documentation

* [WhatsApp Messages](https://developers.facebook.com/docs/whatsapp/api/messages)
