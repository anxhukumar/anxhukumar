# Hi 👋

I am a Backend Developer specialized in Go. I initially worked with JavaScript but later chose Go — I found it to be straightforward, simple, and yet powerful enough to build serious systems. I have a bachelor's degree in Business Administration, though somewhere during college I developed a deep interest in programming and have stuck to it ever since.

This is my current tech stack:

- **Languages:** Go, Python
- **Database:** SQL
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
