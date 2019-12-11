# OAuth 2.0 Cheat Sheet

## Introduction

With the growth of micro-services and interconnected applications, authorization requests rose, such as providing a statistics service to access your twitter information in order to analyze your top followers. In order to access your twitter information, OAuth was used to provide authorization to specific details in your account, where authentication was not required (_e.g._ the service doesn't ask for your password).

OAuth is an open standard for access delegation, otherwise known as third-party authorization, where application users grant websites and services access to their information through the use of tokens, instead of credentials (username/password).

## Contents

- [Terminology](#terminology)
   - [Access Tokens](#access-tokens)
   - [Refresh Tokens](#refresh-tokens)
   - [Tokens TTL](#tokens-ttl)
   - [Managing Tokens](#managing-tokens)
   - [Redirect URI](#redirect-uri)
- [Security Protective Measures](#security-protective-measures)
   - [Client Credentials Protection](#client-credentials-protection)
   - [CSRF Protection](#csrf-protection)
   - [Referer Header Leaks Protection](#referer-header-leaks-protection)
   - [Token Logging Protection](#token-logging-protection)
   - [Authorization Server Mix-Up Protection](#authorization-server-mix-up-protection)
   - [PKCE Considerations](#pkce-considerations)
- [Use Cases](#use-cases)
   - [Classic Web Applicaiton](#classic-web-applicaiton)
   - [Single Page Application](#single-page-application)
   - [Mobile Application](#mobile-application)
   - [Backend Service](#backend-service)

## Terminology

Here go explanation of this, that, and the other term...

### Access Tokens

Explain in brief access tokens and implementations best practices

### Refresh Tokens

Explain in brief refresh tokens and implementations best practices

### Tokens TTL

Time to live recommendation and the need for this feature.

### Managing Tokens

Best practices for managing tokens for client and authorization services

### Redirect URI

Implementing redirect URI in a secure and safe manner

## Security Protective Measures

### Client Credentials Protection

Implement `client_id` and `client_secret`

### CSRF Protection

Implement `state` parameter

### Referer Header Leaks Protection

How to avoid leaking the authorization code through the `Referer` Header

### Token Logging Protection

How to protect against logging the tokens in middlewares and server logs

### Authorization Server Mix-Up Protection

How to validate and target the proper authorization server

### PKCE Considerations

// Can be injected in the use cases as well.

## Use Cases

### Classic Web Applicaiton

### Single Page Application

### Mobile Application

### Backend Service
