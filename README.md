# Hi 👋

I’m a Backend Engineer specializing in Go, distributed integrations, and high-concurrency architectures. Coming from a fast-paced startup environment, I love the challenge of taking backend features from early-stage POCs directly through to live client production. My core focus is on building reliable, resilient pipelines and optimizing execution speed to solve real operational bottlenecks.

This is my current tech stack:

- **Languages:** Go, Python
- **APIs & RPC:** gRPC, Protocol Buffers (Protobuf), REST
- **Databases & Tooling:** SQL, sqlc (Type-safe SQL), goose (Migrations)
- **Containerization:** Docker
- **CI/CD:** GitHub Actions
- **Cloud:** AWS (EC2, S3, CloudFront, SES)
- **Message Broker:** RabbitMQ
- **Security:** Encryption, Token Authorization, Rate Limiting
- **Environment:** Linux, Git

---

Here is a project I have built:

### 🔐 Hashdrop — Zero-Trust File Storage & Sharing

A CLI tool with a fully deployed backend. It allows users to upload files with client-side encryption — each file gets its own unique encryption key. The keys are stored by default in an encrypted local vault on the client's machine, with the option to self-manage them entirely.

Uploads go directly to S3 via a presigned URL that the server generates only after validating the request. Encryption, upload, download, and decryption all happen in chunks on the fly — nothing is loaded entirely into memory. The server is also built with clear measures against common attack vectors.

👉 [Documentation](https://hashdrop.dev)
