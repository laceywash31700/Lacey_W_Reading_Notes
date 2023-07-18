# Class-06 Reading Notes

## Securing Passwords

> 1. ***Explain to a non-technical friend how you would safely hash and store a password.***
>  So when you want to protect a password you don't want to just have your password not encoded with a cryptographic hash algorithm which is just a function
> that takes in the password in its plain text form and pushes out a encoded password that has either the same length or a length that is more than what the .
> input length was.
>
> 2. ***What is Bcrypt?***
> Bcrypt is a algorithm that is a adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and uses a work factor that
> allows you to determine how expensive the hash function will be. it is really slow but strong because it makes brute force attacks take forever to decrypt.
>
> 3. ***Why might you use something like Bcrypt?***
> It is really slow but strong as hell because it makes brute force attacks take forever to decrypt.
>
>

## Basic Auth

> 1. ***What is Basic Authentication?***
> Basic authorization is a method for HTTP clients not to be confused with HTTPS which it is often combined with for more confidentiality. It is a means of
> transferring usernames and passwords when making a request to a server.
>
> 2. ***What properties are necessary in the header of a Basic Auth request?***
> You need a header field that is set up in this format.
> Authorization: Basic <(credentials)>(which can look something like this Q09NUEFOWVhcdXNlcjE6cGFzc3dvcmQxMjM=) this is encoded like so (siteName + '\' +
> username + ':' + password) using a base-64 encoding.
>
> 3. ***How are username:password in Basic Auth encoded?***
> Base64 which is just a binary-to-text encoding in a sequence of 24 bits(for context bits are the most basic units of information in computing basically 1 and
> 0's)
>

## OWASP auth cheat sheet

> 1. ***Define the authentication process to a non-technical recruiter.***
> The authentication process begins with user identification. This typically involves users providing a unique identifier, such as a username or email address,
> to indicate who they are.Once the user is identified, they must provide credentials to prove their identity. The most common credential is a password, which
> is a secret combination of characters known only to the user. Other forms of credentials may include PIN numbers, security tokens, or biometric data like
> fingerprints or facial recognition.The system compares the credentials provided by the user with the stored credentials associated with that user account.
> The stored credentials are usually securely encrypted to protect them from unauthorized access. Depending on the system's security requirements, additional
> authentication methods may be employed to enhance the verification process. These methods can include two-factor authentication (2FA) or multi-factor
> authentication (MFA). With 2FA or MFA, users are required to provide a second form of authentication, such as a unique code sent to their mobile device, to
> further validate their identity.If the provided credentials and any additional authentication methods pass verification, the system grants access to the user.
> there are a few caveats to consider when making a authentications for a system. To name a few you want to make sure the user IDs are case-insensitive and
> to not allow login with sensitive accounts to any front-end user interface this is basically data bases and middleware the back-end.
>
> 2. ***How should your error messaging respond (both HTTP and HTML)? Why?***
> An error message should respond with the HTTP error code associated with the error with a the error message property content showing in the HTML document.
> when you show the error code that is sorta of a give away as to what went wrong and can provide insight as to how to fix it.

## Things I want to know about
