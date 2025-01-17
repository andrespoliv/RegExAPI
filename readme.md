| Domain         	| Platform/API          	| Key Type           	| Target Regular Expression                                                   	| Source                                                                           	|
|---|---|---|---|---|
|Social Media   	|Twitter               	|Access Token       	|[1-9][ 0-9]+-[0-9a-zA-Z]{40}|                                                                                  	|
|Social Media   	|Twitter|Username|"/(^|[^@\w])@(\w{1|15})\b/"|https://stackoverflow.com/a/13398311|
|Social Media   	|Facebook              	|Access Token       	|EAACEdEose0cBA[0-9A-Za-z]+||
|Social Media   	|Facebook              	|OAuth 2.0|[A-Za-z0-9]{125} (counting letters [2])| https://developers.facebook.com/docs/facebook-login/access-tokens/|
|Social Media   	|Instagram             	|OAuth 2.0|[0-9a-fA-F]{7}\.[0-9a-fA-F]{32}| https://www.instagram.com/developer/authentication/                              	|
|Social Media   	|Instagram|Username|"(?:@)([A-Za-z0-9_](?:(?:[A-Za-z0-9_]|(?:\.(?!\.))){0|28}(?:[A-Za-z0-9_]))?)"|https://blog.jstassen.com/2016/03/code-regex-for-instagram-username-and-hashtags/|
|Social Media   	|Instagram|Hashtag|"(?:#)([A-Za-z0-9_](?:(?:[A-Za-z0-9_]|(?:\.(?!\.))){0|28}(?:[A-Za-z0-9_]))?)"|https://blog.jstassen.com/2016/03/code-regex-for-instagram-username-and-hashtags/|
|Social Media   	|Google|API Key            	|AIza[0-9A-Za-z-_]{35}|                                                                                  	|
|Social Media   	|Google|OAuth 2.0|random opaque key up to 256 bytes|https://developers.google.com/identity/protocols/OAuth2|
|Social Media   	|LinkedIn              	|OAuth 2.0| undocumented/random opaque string                                           	|https://developer.linkedin.com/docs/v2/oauth2-client-credentials-flow#|
|Social Media   	|GitHub                	|OAuth 2.0|[A-Za-z0-9_]{255}| https://developer.github.com/apps/building-oauth-apps/authorizing-oauth-apps/    	|
|Social Media   	|Gmail                 	|OAuth 2.0|[0-9(+-[0-9A-Za-z_]{32}\.apps\.qooqleusercontent\.com|                                                                                  	|
|Social Media   	|Foursquare            	|Client Key         	|"[0-9a-zA-Z_][5|31]"|                                                                                  	|
|Social Media   	|Foursquare            	|Secret Key         	|R_[0-9a-f]{32}|                                                                                  	|
|Finance        	|Picatic               	|API Key            	|sk_live_[0-9a-z]{32}|                                                                                  	|
|Finance        	|Stripe                	|Standard API Key   	|sk_live_(0-9a-zA-Z]{24}|                                                                                  	|
|Finance        	|Stripe                	|Restricted API Key 	|sk_live_(0-9a-zA-Z]{24}|                                                                                  	|
|Finance        	|Square|Access Token       	|sqOatp-[0-9A-Za-z\-_]{22}|                                                                                  	|
|Finance        	|Square|OAuth Secret       	|q0csp-[ 0-9A-Za-z\-_]{43}|                                                                                  	|
|Finance        	|Paypal / Braintree    	|Access Token       	|"access_token\|production\$[0-9a-z]{161[0-9a|]{32}"|                                                                                  	|
|Finance        	|Amazon Marketing Services|Auth Token         	|"amzn\.mws\.[0-9a-f]{8}-[0-9a-f]{4}-10-9a-f1{4}-[0-9a|]{4}-[0-9a-f]{12}"|                                                                                  	|
|Communications 	|Twilio                	|API Key            	|55[0-9a-fA-F]{32}|                                                                                  	|
|Communications 	|MailGun               	|API Key            	|key-[0-9a-zA-Z]{32}|                                                                                  	|
|Communications 	|MailChimp             	|API Key            	|"[0-9a-f]{32}-us[0-9]{1|2}"|                                                                                  	|
|Communications 	|Slack                 	|API Key            	|xox[baprs]-[0-9]{12}-[0-9]{12}-[0-9a-zA-Z]{24}|                                                                                  	|
|Communications 	|Slack                 	|Access Token            	|T[a-zA-Z0-9_]{8}/B[a-zA-Z0-9_]{8}/[a-zA-Z0-9_]{24}|https://hooks.slack.com/services/T[a-zA-Z0-9_]{8}/B[a-zA-Z0-9_]{8}/[a-zA-Z0-9_]{24}|
|Cloud          	|Amazon Web Services   	|Access Key ID      	|AKIA[0-9A-Z]{16}|                                                                                  	|
|Cloud          	|Amazon Web Services   	|Secret Key         	|[0-9a-zA-Z/+]{40}|                                                                                  	|
|Cloud          	|Google Cloud Platform|OAuth 2.0|[0-9a-fA-F]{8}-[0-9a-fA-F]{4}-[0-9a-fA-F]{12}|                                                                                  	|
|Cloud          	|Google Cloud Platform|API Key|[A-Za-z0-9_]{21}--[A-Za-z0-9_]{8}|                                                                                  	|
|Cloud          	|Heroku                	|API Key|[0-9a-fA-F]{8}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{12}|https://devcenter.heroku.com/articles/platform-api-quickstart                    	|
|Cloud          	|Heroku                	|OAuth 2.0|[0-9a-fA-F]{8}-[0-9a-fA-F]{4}-[0-9a-fA-F]{12}|                                                                                  	|