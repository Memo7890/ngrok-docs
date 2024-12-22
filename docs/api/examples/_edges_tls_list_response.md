<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-22T10:06:05Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2qZF0FGMAsUZ593O3c1AGTv5xv4",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qZF0FGMAsUZ593O3c1AGTv5xv4"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2qZEymnVPYzYu9i4EjKOcjD6UMe",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2qZEymnVPYzYu9i4EjKOcjD6UMe"
				},
				"enabled": true
			},
			"created_at": "2024-12-22T10:05:53Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2qZEypNRD8f2p3gBWstA3kVN0UE",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qZEypNRD8f2p3gBWstA3kVN0UE"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
