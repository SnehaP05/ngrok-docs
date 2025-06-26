<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-06-26T10:07:59Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2z2cCNw8l7UX9hqWsitFIekN9A5",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2z2cCNw8l7UX9hqWsitFIekN9A5"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2z2cB3Zn9lLIBAuaRKIObioZnNv",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2z2cB3Zn9lLIBAuaRKIObioZnNv"
        },
        "enabled": true
      },
      "created_at": "2025-06-26T10:07:49Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2z2cB8loyQKnF9dTFTHKwxkEqT5",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2z2cB8loyQKnF9dTFTHKwxkEqT5"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
