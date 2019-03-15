# Go API client for openapi

Moov GL is an HTTP service which represents both a general ledger and chart of accounts for customers. The service is designed to abstract over various core systems and provide a uniform API for developers.

## Overview
This API client was generated by the [OpenAPI Generator](https://openapi-generator.tech) project.  By using the [OpenAPI-spec](https://www.openapis.org/) from a remote server, you can easily generate an API client.

- API version: 1.0.0
- Package version: 1.0.0
- Build package: org.openapitools.codegen.languages.GoClientCodegen
For more information, please visit [https://groups.google.com/forum/#!forum/moov-users](https://groups.google.com/forum/#!forum/moov-users)

## Installation

Install the following dependencies:
```
go get github.com/stretchr/testify/assert
go get golang.org/x/oauth2
go get golang.org/x/net/context
go get github.com/antihax/optional
```

Put the package under your project folder and add the following in import:
```golang
import "./openapi"
```

## Documentation for API Endpoints

All URIs are relative to *http://localhost:8085*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AccountApi* | [**CreateAccount**](docs/AccountApi.md#createaccount) | **Post** /customers/{customer_id}/accounts | Create a new account for a Customer
*AccountApi* | [**GetAccountsByCustomerID**](docs/AccountApi.md#getaccountsbycustomerid) | **Get** /customers/{customer_id}/accounts | Retrieves a list of accounts associated with the customer ID.
*CustomerApi* | [**GetCustomer**](docs/CustomerApi.md#getcustomer) | **Get** /customers/{customer_id} | Retrieves a Customer object associated with the customer ID.


## Documentation For Models

 - [Account](docs/Account.md)
 - [Address](docs/Address.md)
 - [CreateAccount](docs/CreateAccount.md)
 - [Customer](docs/Customer.md)
 - [Error](docs/Error.md)
 - [InlineResponse200](docs/InlineResponse200.md)
 - [Phone](docs/Phone.md)


## Documentation For Authorization
 Endpoints do not require authorization.


## Author


