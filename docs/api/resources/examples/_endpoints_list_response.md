<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-26T10:07:54Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2z2cB8Xlsk4rEUCXks5wF2FDhda",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2z2cB8Xlsk4rEUCXks5wF2FDhda"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2z2cBkdf5eXXDwqAZOZjBgakstV",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-06-26T10:07:54Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2z2cBkdf5eXXDwqAZOZjBgakstV",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-26T10:07:51Z",
      "hostport": "16c5e08886ef.ngrok.paid:443",
      "id": "ep_2z2cBKOJYmGQ0jB6l2hLQ5hDGji",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2z2c8v5eXKTLe9sGtrTHoVXOhHU",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://16c5e08886ef.ngrok.paid",
      "tunnel": {
        "id": "tn_2z2cBKOJYmGQ0jB6l2hLQ5hDGji",
        "uri": "https://api.ngrok.com/tunnels/tn_2z2cBKOJYmGQ0jB6l2hLQ5hDGji"
      },
      "tunnel_session": {
        "id": "ts_2z2cBJun8hP64UjTZpMsu5OMWAX",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2z2cBJun8hP64UjTZpMsu5OMWAX"
      },
      "type": "ephemeral",
      "updated_at": "2025-06-26T10:07:51Z",
      "upstream_url": "http://localhost:80",
      "url": "https://16c5e08886ef.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-26T10:07:49Z",
      "domain": {
        "id": "rd_2z2cB8Xlsk4rEUCXks5wF2FDhda",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2z2cB8Xlsk4rEUCXks5wF2FDhda"
      },
      "edge": {
        "id": "edgtls_2z2cB8loyQKnF9dTFTHKwxkEqT5",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2z2cB8loyQKnF9dTFTHKwxkEqT5"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2z2cB6k5OcClftsIr7TfdMvOtKb",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-06-26T10:07:49Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
