# Strong authentication
Strong authentication is mandatory. But what is it and what should you choose?
## Strong authentication differs from multifactor authentication
Strong authentication is based on cryptographic mechanisms deemed to be strong, but not necessarily on several authentication factors.
- For example, to connect to your email address and have strong authentication you need to :
  - Your password that only you know.
  - A security key that you own.
  - Activate your biometric security key by touching it.
> Strong authentication means combining these three points: a secret you know, something you possess, something you are or do.
### Strong authentication is based on cryptographic mechanisms deemed to be strong
- Your password (see [kyvern/courses/passwordmanager](https://github.com/kyvernfoundation/kyvern/blob/main/courses/passwordmanager.md)).
  - It says nothing about you.
  - one account, one password.
  - The better the entropy, the stronger your password. Add the most random characters with the highest length and let KeePass remember your password.
    - For your security, we recommend that you do not display your password. That way, nobody knows it, only your KeePass.
  - Never put it anywhere else but where you want to connect.
- Security keys must comply with the FIDO2 standard.
- Something only you can do.
