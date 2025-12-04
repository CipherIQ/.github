![CipherIQ Logo](/images/cipheriq_logo_2x.png)

# Cryptographic Observability for the Quantum Era

CipherIQ is an open source cryptographic observability platform that combines static asset discovery with runtime network monitoring to provide complete visibility into enterprise cryptographic posture. 

As organizations face mandatory post-quantum cryptography (PQC) migration deadlines and the "harvest now, decrypt later" threat, CipherIQ solves the fundamental problem: you cannot migrate what you cannot see.


## Our Tools

**[cbom-generator](https://github.com/CipherIQ/cbom-generator)** - Static cryptographic asset discovery with PQC readiness assessment  
**[cbom-explorer](https://github.com/CipherIQ/cbom-explorer)** - Web-based CBOM visualization and navigation  
**[crypto-tracer](https://github.com/CipherIQ/crypto-tracer)** - eBPF-based runtime cryptographic operation monitoring  
**[pqc-flow](https://github.com/CipherIQ/pqc-flow)** - Passive network traffic analyzer for PQC detection  



## The Complete Picture: Static + Runtime

**Static Analysis** (cbom-generator → cbom-explorer)  
Discover what cryptographic assets exist in firmware, containers, and filesystems

**Runtime Monitoring** (crypto-tracer + pqc-flow)  
Observe what cryptography is actually being used in production

**Detect Drift:** Configuration says TLS 1.3, runtime shows TLS 1.2 fallback


## Use Cases

✅ **IoT/OT Manufacturers:** Generate CBOMs for FDA/UN R155/IEC 62443 compliance  
✅ **Security Teams:** Inventory cryptographic assets across infrastructure  
✅ **Compliance Officers:** Document cryptographic controls with evidence  
✅ **DevSecOps:** Integrate CBOM generation into CI/CD pipelines  


## Commercial Support

**CipherIQ Generator** (Commercial product)  
Production-grade CBOM generation with professional support, Yocto/Buildroot integration, compliance templates, and custom scanner development.

For details contact: sales@cipher.io


##  Community

- **Discussions:** Ask questions, share use cases in repo discussions
- **Contributing:** We welcome PRs! See CONTRIBUTING.md
- **Support:** Community-driven (commercial SLA available)

##  Resources

- **Docs:** [cipheriq.io](https://cipheriq.io)
- **Contact:** team@cipheriq.io

---

**Built for organizations protecting 20-30 year device lifespans**

*GPL 3.0 & Commercial dual-licensed • Quantum-ready • Standards-based*

