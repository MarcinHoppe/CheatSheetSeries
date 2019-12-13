# OAuth 2.0 Cheat Sheet

## Introduction

OAuth 2.0 is an open standard that allows applications to get access to protected resources and APIs on behalf of users without accessing their credentials. OAuth 2.0 can be used in Web, mobile, and desktop applications and is widely supported by identity providers and API vendors. OAuth 2.0, along with related standards and recommendations, provides a versatile framework for addressing a diverse set of use cases. With this versatility comes complexity that often has security implications. Mistakes can lead to serious vulnerabilities.

This Cheat Sheet provides guidance for application builders on how to deploy OAuth 2.0 and integrate with other participants of the OAuth 2.0 ecosystem in a secure manner.

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
