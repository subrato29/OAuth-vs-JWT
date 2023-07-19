# OAuth vs JWT

## What is authentication?

```
Authentication is the process of verifying the identity of a user or a client.
It usually involves providing some credentials, such as a username and password, or a token, that prove who you are.
Authentication ensures that only authorized parties can access protected resources, such as APIs, databases, or web pages.

```

## What is authorization?

```
Authorization is the process of granting or denying access to specific resources based on the authenticated identity.
It usually involves checking some permissions, roles, or scopes, that define what you can do with the resources.
Authorization ensures that only authorized actions can be performed on protected resources, such as reading, writing, or deleting data.

```

## What Is OAuth?

```
Open Authorization (OAuth) is an open standard for token-based authentication over public networks.
OAuth allows third-party services such as Facebook and Google to use end-user account information without exposing
the user’s account credentials to a third party.

It acts as an intermediary on behalf of end users, providing access tokens to third-party services authorized to share
certain account information. The process of obtaining a token is called the authorization flow.

```

## What Is JWT (JSON Web Tokens)?

```
JWT is an open standard for creating and exchanging JSON-based tokens that contain some
claims, or information, about the user or the client.

JWT can be used for authentication, by signing the tokens with a secret key or a
public/private key pair, and verifying their integrity and validity.

JWT can also be used for authorization, by encoding some permissions, roles, or scopes, in the tokens,
and checking them against the resources

```

