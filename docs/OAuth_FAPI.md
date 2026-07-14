# OAuth 2.0 & FAPI Security

## Overview

The Open Banking API Gateway uses OAuth 2.0 together with the Financial-grade API (FAPI) security profile to provide secure access to customer financial data.

---

## Authentication Flow

1. Developer registers an application.
2. Client requests authorization.
3. Customer logs in securely.
4. Customer provides consent.
5. Authorization Server issues an Authorization Code.
6. Client exchanges the code for an Access Token.
7. Client accesses protected banking APIs.

---

## Security Features

- OAuth 2.0 Authorization Code Flow
- PKCE (Proof Key for Code Exchange)
- OpenID Connect (OIDC)
- JWT Access Tokens
- Refresh Tokens
- Mutual TLS (mTLS)
- FAPI 1.0 Advanced Security

---

## Access Token

The Access Token contains:

- User ID
- Client ID
- Consent ID
- Scope
- Expiration Time

---

## Scopes

Example API scopes:

- accounts.read
- transactions.read
- payments.write
- consent.read

---

## Benefits

- Strong customer authentication
- Secure API access
- Fine-grained permissions
- Protection against token theft
- Compliance with Open Banking standards
