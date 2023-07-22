# Class-07 Reading Notes

## Intro to JWT

> 1. ***What is a JSON Web Token (JWT)?***
> A JSON Web Token (JWT) is a compact, URL-safe, and self-contained token format used for securely transmitting information between parties. It is commonly
> used to authenticate and authorize users in web applications and APIs.
>
> 2. ***When should we use JSON Web Tokens?***
> User Authentication & Authorization and Access Control
>
> 3. ***Claims are expected in which structural component of a JWT?***
> Claims are expected in the "Payload" component of a JSON Web Token (JWT). The payload is the second part of the JWT, and it contains the claims, which are
> statements about an entity (typically the user) and additional data.
>

## Are JWTs Secure?

> 1. ***If I get a JWT and I can decode the payload, how can we call that secure?***
> The security of JWTs does not rely on the payload's confidentiality but rather on the token's integrity and authenticity.
>
> 2. ***If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.***
> When sending a JSON Web Token (JWT), both the sender (typically the server) and the receiver (usually the client or another server) must share a common
> secret key (for HMAC-based algorithms) or have access to the same public key (for RSA or ECDSA-based algorithms). This shared key or public key is used for
> generating and verifying the token's signature.
>
> 3. ***Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.***
> Sending and receiving concatenated content and a secret securely can be explained to a non-technical recruiter using a simple analogy of sending a locked \
> package with a key.
>

## JWTs Explained

> 1. ***Why use JWT?***
> Stateless and Scalable
>
> 2. ***JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.***
> Imagine you want to send a secret message to your friend, but you want to make it easy for them to read without any special tools or complicated steps. This  
> is where a "compact and self-contained" message like a JSON Web Token (JWT) becomes really useful!
>
> 3. ***What are the three components (the structure) of a JWT signature?***
> The JWT signature is created using three components: the header, the payload, and the secret key (or private key for asymmetric algorithms).
>

## Things I want to know about
