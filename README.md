# Qilin.Cloud/API/Order

## Description

The Offer API is used to manage orders. An order consists of at least one order line item, as well as billing address, shipping address and often other details (payment methods and payments, shipping methods and shipments, and so on). An order line item usually refers to an [offer](https://github.com/QilinCloud/API-Offer/) on the channel, but can also be a so-called "free item", i.e. an order line item without reference to a specific offer.

### :bulb: Example

*The customer John Doe, residing at Hauptstraße 1, 12345 Berlin, Germany, would like to order 2 pieces of the offered glass bottle Coca-Cola, 1.0L, at 4.00 US Dollar each to the delivery address: Bahnhofsstraße 14, 53123 Bonn, Germany. He has already paid by credit card on 01.01.2023.. This and similar order data (like shipments, returnings, invoices, refunds, and so on) are managed by the Order API.*


## Useful links to get started

* [Documentation](https://documentation.api.qilin.cloud/order/)
* [Schema](https://documentation.api.qilin.cloud/openapi/order/tag/schema/)
* [OpenAPI Specification](https://github.com/QilinCloud/API-Order/blob/main/openapi-order.yaml)
* [Postman Collection](https://github.com/QilinCloud/API-Order/blob/main/postman_collection-order.json)
* [SDKs](https://github.com/search?q=user%3AQilinCloud+SDK)


## How to provide feedback

Generally, bugs and feature requests for the API or docs should be [Github issue](https://github.com/QilinCloud/API-Order/issues/new). Everything else should be discussed here [API-Order Discussion](https://github.com/QilinCloud/API-Order/discussions).

## Legal

:warning: Note that by submitting your feedback, we have the right to use it.[^1]

[^1]:Legalese-wise, this means it’s considered non-confidential and non-proprietary to you, and you grant Qilin.Cloud a non-exclusive, worldwide, royalty-free, irrevocable, sub-licensable, perpetual license to use and publish those ideas and materials for any purpose, without compensation to you.

## Code Quality

We use a variety of state-of-the-art techniques to ensure that our code meets the highest quality criteria.
If you still notice something wrong, we are happy to have a strong community to solve the problem together with you: [How to provide feedback](https://github.com/QilinCloud/API-Order/#how-to-provide-feedback)

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=marcossoftware_Qilin.Core.Order&metric=alert_status&token=34332e2141d01e981faaccaa27d2d80e7c5d8afb)](https://sonarcloud.io/summary/new_code?id=marcossoftware_Qilin.Core.Order)

[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=marcossoftware_Qilin.Core.Order&metric=vulnerabilities&token=34332e2141d01e981faaccaa27d2d80e7c5d8afb)](https://sonarcloud.io/summary/new_code?id=marcossoftware_Qilin.Core.Order) [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=marcossoftware_Qilin.Core.Order&metric=security_rating&token=34332e2141d01e981faaccaa27d2d80e7c5d8afb)](https://sonarcloud.io/summary/new_code?id=marcossoftware_Qilin.Core.Order) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=marcossoftware_Qilin.Core.Order&metric=coverage&token=34332e2141d01e981faaccaa27d2d80e7c5d8afb)](https://sonarcloud.io/summary/new_code?id=marcossoftware_Qilin.Core.Order) [![Bugs](https://sonarcloud.io/api/project_badges/measure?project=marcossoftware_Qilin.Core.Order&metric=bugs&token=34332e2141d01e981faaccaa27d2d80e7c5d8afb)](https://sonarcloud.io/summary/new_code?id=marcossoftware_Qilin.Core.Order) 
