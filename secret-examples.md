# Secret Examples

All of the following secrets are real examples that no longer work. The regex syntax is below each one.

## API Keys

Mailgun: `key-06b34653fd57060f62e4475450ccf053`
> key-[0-9a-zA-Z]{32}

Mailchimp: `e3a648d99c398572dec8a7650c92d1c0-us16`
> [0-9a-f]{32}-us[0-9]{1,2}

Twitter Key: `UDYE17NI3sbgPTaymkYdCEd76`
> [0-9a-zA-Z]{25}

Twitter Secret: `JzXPbtuH2I26L5ilEziVM18Ecd1EW0t2AIjaJIhtm7jpB4W5R5`
> [0-9a-zA-Z]{50}

Twitter Bearer Token: `AAAAAAAAAAAAAAAAAAAAAAzFFFAAAAAAtA1tI2Lx4kvH7N1kWsfIcNFU2v8%3D895Il1bJ8fCWOLjpswwczyruDRGKDx3TuKBvqxsW8HL8duWRGy`
> A{22}[0-9a-zA-Z].{89}

GitHub Token: `ghp_q6yv2mqrgewsuuvzcvqldsi4detvof4r5bse`
> ghp_[0-9a-z]{36}

Twilio API Key: `SK0189365278abEcF1827FFabEc187FAaC`
> SK[0-9a-fA-F]{32}

AWS API Key: `AKIA01JDFHS8CDS82AAA`
> AKIA[0-9A-Z]{16}

AWS AppSync GraphQL Key: `da2-auzbch18ch4dks9cnvb38sloc8`
> da2-[a-z0-9]{26}

Google Cloud Platform API Key: `AIza1Rt9Ac43c789AVcRgyJawTd4\_1sdfdmR9a`
> AIza[0-9A-Za-z\\-_]{35}

Stripe API Key: `rk_live_WXMzpZg9ueNeYNsKhDmQW6Yj`
> rk_live_[0-9a-zA-Z]{24}

Facebook Access Token: `EAACEdEose0cBA09aaDc8DcU76bVx894Ddq`
> EAACEdEose0cBA[0-9A-Za-z]+

YouTube API Key: AIza1Rt9Ac43c789AVcRgyJawTd4\_1sdfdmR8a
> AIza[0-9A-Za-z\\-_]{35}

## Private Keys

```shell
-----BEGIN RSA PRIVATE KEY-----
Proc-Type: 4,ENCRYPTED
DEK-Info: AES-128-CBC,A3278475D0DA2C97F1B5F500A5B5F2A0

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
-----END RSA PRIVATE KEY-----
```

```shell
-----BEGIN DSA PRIVATE KEY-----
```

```shell
-----BEGIN EC PRIVATE KEY-----
```

```shell
// PGP private key block
-----BEGIN PGP PRIVATE KEY BLOCK-----
```