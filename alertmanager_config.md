###

# global

| format                      | default value | description   |
| :----------                 | ------------- | ------------- |
| resolve_timeout: \<duration> | 5m            | ResolveTimeout is the time after which an alert is declared resolved <br> if it has not been updated.|

SMTP

| format                      | default value | description   |
| :----------                 | ------------- | ------------- |
| smtp_from: \<tmpl_string>   |     | The default SMTP From header field.|
| smtp_smarthost: \<string>   |     | The default SMTP smarthost used for sending emails, including port number. <br> Port number usually is 25, or 587 for SMTP over TLS (sometimes referred to as STARTTLS). <br> Example: smtp.example.org:587 |
| smtp_hello: \<string>       | "localhost"   | The default hostname to identify to the SMTP server. |
| smtp_auth_username: \<string>  |            | |
| smtp_auth_password: \<secret>  |            | SMTP Auth using LOGIN and PLAIN. |
| smtp_auth_identity: \<string>  |            | SMTP Auth using PLAIN. |
| smtp_auth_secret: \<secret> |               | SMTP Auth using CRAM-MD5. |
| smtp_require_tls: <bool>    | true          | The default SMTP TLS requirement. |

Slack

| format                      | default value | description   |
| :----------                 | ------------- | ------------- |
| slack_api_url: \<secret>    | | |
| victorops_api_key: \<secret> | | |
| victorops_api_url: \<string> | "https://alert.victorops.com/integrations/generic/20131114/alert/" | |
| pagerduty_url: \<string>    | "https://events.pagerduty.com/v2/enqueue" | |
| opsgenie_api_key: \<secret> | | | 
| opsgenie_api_url: \<string> | "https://api.opsgenie.com/" | |
| hipchat_api_url: \<string>  | "https://api.hipchat.com/" | |
| hipchat_auth_token: \<secret> | | |
| wechat_api_url: \<string>  | "https://qyapi.weixin.qq.com/cgi-bin/" | | 
| wechat_api_secret: \<secret>  | | |
| wechat_api_corp_id: \<string> | | |

HTTP cofiguration

| format                      | default value | description   |
| :----------                 | ------------- | ------------- |
| http_config: \<http_config> | | |

# templates

| format                      | default value | description   |
| :----------                 | ------------- | ------------- |
| - <filepath> ...            |               | Files from which custom notification template definitions are read. <br> The last component may use a wildcard matcher, e.g. 'templates/*.tmpl'. |

# route


| format                      | default value | description   |
| :----------                 | ------------- | ------------- |








# link

https://prometheus.io/docs/alerting/configuration/
