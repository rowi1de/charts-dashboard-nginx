# basic-auth-gateway

![Version: 0.6.1](https://img.shields.io/badge/Version-0.6.1-informational?style=flat-square)

Basic auth gateway chart for traefik

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| credentials.password | string | `nil` |  |
| credentials.username | string | `"admin"` |  |
| ingressRoute.certificate.clusterIssuer | string | `"letsencrypt"` |  |
| ingressRoute.certificate.name | string | `nil` |  |
| ingressRoute.domain | string | `"admin.my-domain.com"` |  |
| ingressRoute.entryPointName | string | `"websecure"` |  |
| ingressRoute.upstream.service.name | string | `"traefik-internal"` |  |
| ingressRoute.upstream.service.port | int | `8444` |  |

<img src="https://iits-consulting.de/wp-content/uploads/2021/08/iits-logo-2021-red-square-xl.png"
alt="iits consulting" id="logo" width="200" height="200">
<br>
*This chart is provided by [iits-consulting](https://iits-consulting.de/) - your Cloud-Native Innovation Teams as a Service!*

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)
