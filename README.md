# Hi, I'm Loïc Sikidi 👋

I'm a passionate developer, curious and always eager to learn new things. My journey has primarily focused on cybersecurity topics (least privilege, authorization/authentication, zero trust, etc.). After more than a decade of developing proprietary code, I challenged myself in 2025 to contribute to open source projects in my spare time, particularly to deepen what I like to call my **obsessions**.

## Current Obsessions

### TPM (Trusted Platform Module) and Remote Attestation

I'm deeply interested in TPM technology and Remote Attestation (see [RFC 9334](https://datatracker.ietf.org/doc/html/rfc9334)). Here are some open source projects I'm currently working on:

- 💊 [TPM Pills](https://tpmpills.com/) - A series of articles and tutorials to learn how to use TPMs and Remote Attestation.
  - I hope to finalize a V1 of the project in 2026!
- 🛡️ [tpm-ca-certificates](https://github.com/loicsikidi/tpm-ca-certificates) - Centralizes Certificate Authority (CA) certificates from different TPM manufacturers to facilitate verification of TPM authenticity.
- 🧿 [tpm-trust](https://github.com/loicsikidi/tpm-trust) - A CLI tool that verifies whether a TPM is genuine, using `tpm-ca-certificates`.
- 🧰 [go-tpm-kit](https://github.com/loicsikidi/go-tpm-kit) - A library providing helpers to facilitate TPM integration in Go.

> [!IMPORTANT]
> My personal work does not represent my employer.

### Transparency Logs

I find transparency logs to be an excellent way to improve security and trust by providing an immutable and verifiable record of events. The ecosystem is very active and more and more tools (e.g., [tessera](https://github.com/transparency-dev/tessera)) are reducing the barrier to entry for using a tlog in projects.

> [!NOTE]
> [tpm-ca-certificates](https://github.com/loicsikidi/tpm-ca-certificates) uses Sigstore to prove the integrity and authenticity of the bundle it generates.

## Technical Goals (2026)

- Find interesting use cases for transparency logs
- Learn to code in Rust and Haskell
  - **Rust:** Some projects I follow are coded in Rust; I want to understand the language to better grasp them and potentially contribute
  - **Haskell:** Deepen functional programming concepts

## Talks

- [Chiffrement @S3NS](https://www.youtube.com/watch?v=FDOX6HHsvQU) at S3NS Submit 2026 (content in 🇫🇷)

## Latest Articles
- [Why I Prefer Structs Over Variadic Functions in Go](https://words.lsikidi.com/posts/002-why-i-prefer-structs-over-variadic-funcs/) (3 days ago)
- [Making Go APIs More Ergonomic with Optional Arguments](https://words.lsikidi.com/posts/001-optional-arg-is-dope/) (3 days ago)
- [Why I&#39;m creating a personal blog](https://words.lsikidi.com/posts/000-my-first-post/) (4 days ago)

## Professional

- I currently work at [S3NS](https://www.s3ns.io/en) where we offer a new GCP (Google Cloud Platform) region in France, aimed at businesses, ensuring their data remains in France and is protected by strict security standards. Check it out!
- I'm open to collaboration or employment opportunities in the cybersecurity field, particularly those involving the **development of innovative solutions** using technologies like TPM, Remote Attestation, Confidential Computing, or transparency logs.

## Contact Me

- Email: loic.sikidi@gmail.com

*PS: I have an aversion to social networks, so my accounts on these platforms have been inactive for years.*
