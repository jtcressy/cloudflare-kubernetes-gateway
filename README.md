# Cloudflare Kubernetes Gateway
Cloudflare Kubernetes Gateway is an open-source project that provides an implementation of the [Gateway API](https://gateway-api.sigs.k8s.io/) using [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) and Cloudflare's greater [Edge Network](https://www.cloudflare.com/network-edge/) as the data plane. This project is NOT currently maintained by Cloudflare Inc. but is instead maintained currently by those listed on this github repository. The goal of this project is to implement the core Gateway APIs -- `Gateway`, `GatewayClass`, `HTTPRoute`, `TCPRoute`, `TLSRoute`, and `UDPRoute` -- to configure the [Cloudflare Tunnel Client](https://github.com/cloudflare/cloudflared), [Cloudflare Access](https://www.cloudflare.com/products/zero-trust/access/), and [Cloudflare DNS](https://www.cloudflare.com/dns/) for applications running on Kubernetes. Cloudflare Kubernetes Gateway is currently under development and will soon support a subset of the Gateway API.

> Warning: This project is actively in development (pre-alpha feature state) and should not be deployed in a production environment.
> All APIs, SDKs, designs, and packages are subject to change.

# Run Cloudflare Kubernetes Gateway

TBD
