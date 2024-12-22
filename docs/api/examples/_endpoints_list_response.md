<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-22T10:05:56Z",
			"hostport": "746af84e0b34.ngrok.paid:443",
			"id": "ep_2qZEz7jvIOYiB80TyIBSLvMGGKm",
			"name": "command_line",
			"principal": {
				"id": "usr_2qZEwocSpttbRFzQ3thpv2OehVm",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://746af84e0b34.ngrok.paid",
			"tunnel": {
				"id": "tn_2qZEz7jvIOYiB80TyIBSLvMGGKm",
				"uri": "https://api.ngrok.com/tunnels/tn_2qZEz7jvIOYiB80TyIBSLvMGGKm"
			},
			"tunnel_session": {
				"id": "ts_2qZEz5THuEtZ9JRTG5ULytP3m7h",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2qZEz5THuEtZ9JRTG5ULytP3m7h"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-22T10:05:56Z",
			"upstream_url": "http://localhost:80",
			"url": "https://746af84e0b34.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-22T10:05:54Z",
			"domain": {
				"id": "rd_2qZEylfOwr4TyLokAMaTgvGAROk",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2qZEylfOwr4TyLokAMaTgvGAROk"
			},
			"edge": {
				"id": "edgtls_2qZEypNRD8f2p3gBWstA3kVN0UE",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2qZEypNRD8f2p3gBWstA3kVN0UE"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2qZEykB5Bf0w51cZVFh6bDg9V0E",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-22T10:05:54Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
