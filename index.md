# OpenID Connect

|Implementation |Username      |Display Name|Mail |Group Name|Groups  |Distinguished Name|
|:-------------:|:------------:|:----------:|:---:|:--------:|:------:|:----------------:|
|custom         |N/A           |displayName |mail |cn        |N/A     |dn                |
|activedirectory|sAMAccountName|displayName |mail |cn        |N/A     |distinguishedName |
|freeipa        |uid           |displayName |mail |cn        |memberOf|dn                |

Test [OpenID Connect] and [token lifespan]

[//]: # (Links)

[OpenID Connect]: https://openid.net/connect/
[token lifespan]: https://docs.apigee.com/api-platform/antipatterns/oauth-long-expiration
