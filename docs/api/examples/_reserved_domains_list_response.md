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
					"started_at": "2024-12-22T10:05:37Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.29w9ehtubfk8cfslm.local-ngrok-cname.com",
			"created_at": "2024-12-22T10:05:37Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2qZEwnd5RIaTs9fxRyIX7DZeQNz",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2qZEwnd5RIaTs9fxRyIX7DZeQNz"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2qZEwhnpkY4uN0fo8fP01i5hoq5",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2qZEwhnpkY4uN0fo8fP01i5hoq5"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.29w9ehtubfk8cfslm.local-ngrok-cname.com",
			"created_at": "2024-12-22T10:05:37Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2qZEwk2TZmXk1FqamJtfIDipkO4",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2qZEwk2TZmXk1FqamJtfIDipkO4"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
