---
title: SIP.Message | SIP.js
---
# SIP.Message

`SIP.Message` represents an instant message using the SIP method MESSAGE. By default, the message is treated as plain text. However, any valid content type may be specified.

* TOC
{:toc}

## Construction

The Message constructor is intended for internal use only. Instead, outbound Messages are created through the [`SIP.UA.message`](/api/devel/ua/#messagetarget-body-options) method. Inbound Messages are obtained via the `SIP.UA` [`message`](/api/devel/ua/#message) event callback.

## Instance Attributes

`SIP.Message` inherits its instance attributes from [`SIP.ClientContext`](/api/devel/context/client/) or [`SIP.ServerContext`](/api/devel/context/server/).

## Instance Methods

`SIP.Message` inherits its instance methods from [`SIP.ClientContext`](/api/devel/context/client/) or [`SIP.ServerContext`](/api/devel/context/server/).

## Events

`SIP.Message` inherits its events from [`SIP.ClientContext`](/api/devel/context/client/) or [`SIP.ServerContext`](/api/devel/context/server/).

<!--

### `message(options)` *(Client Only)*

Send this MESSAGE.

#### Parameters

Name                  | Type               | Description
----------------------|--------------------|--------------
`options`             |`Object`            |Optional `Object` with extra parameters (see below).
`options.extraHeaders`|`Array` of `Strings`|Extra SIP headers for the request.

#### Returns

Type | Description
-----|-------------
`SIP.Message`| This Message

-->
