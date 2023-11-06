# dns-filter
A Rust based DNS Filter, based on `hickory-dns`.

DnsFilter 主要由 `hickory-dns` 承载，同等一部分 CoreDNS 的能力，借鉴插件式方案。
1. 内置 nacos-sdk-rust -> nacos-server
2. 内置 kube-rs/k8s-openapi -> k8s-apiserver


# License
[Apache License Version 2.0](LICENSE)

# Acknowledgement
- Inspired by DNS-F from Alibaba, CoreDNS
- A Rust based DNS server you known Trust-DNS [hickory-dns](https://github.com/hickory-dns/hickory-dns.git)
