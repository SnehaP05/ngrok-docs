<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-06-26T10:07:33Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.3nbh4smg4kgwfhsjy.local-ngrok-cname.com",
      "created_at": "2025-06-26T10:07:33Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2z2c96j62VEZKV1s7NDUyZ2LSFj",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2z2c96j62VEZKV1s7NDUyZ2LSFj"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2z2c94UPj6aDChj52Xvf6jOE6At",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2z2c94UPj6aDChj52Xvf6jOE6At"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.3nbh4smg4kgwfhsjy.local-ngrok-cname.com",
      "created_at": "2025-06-26T10:07:33Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2z2c96htka7wGhnzi6MSCYtjpzV",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2z2c96htka7wGhnzi6MSCYtjpzV"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
