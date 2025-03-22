# DocBlock - Decentralized Whistleblowing Platform

DocBlock is a revolutionary whistleblowing platform built on the Internet Computer Protocol (ICP) that provides unparalleled security, speed, and censorship resistance. Unlike traditional platforms or Tor-based solutions, DocBlock leverages blockchain technology to ensure documents can never be taken down or tampered with.

## Key Features

- **Censorship Resistant**: Documents stored on ICP cannot be taken down by any government or organization
- **Lightning Fast**: Direct content serving through ICP nodes provides superior speed compared to Tor
- **Always Available**: Decentralized infrastructure ensures 100% uptime
- **End-to-End Encryption**: Military-grade encryption protects document contents and whistleblower identities
- **Zero-Knowledge Proofs**: Submit documents without revealing your identity
- **Immutable Records**: Blockchain ensures document integrity and timestamp verification
- **No Special Software**: Works in any modern browser - no Tor or plugins needed

## Why ICP Over Traditional Solutions?

### Advantages Over Tor
- **Speed**: Direct content serving without multiple relay hops
- **Reliability**: No dependence on volunteer-run nodes
- **Accessibility**: Works in any browser without additional software
- **Permanent Storage**: Documents cannot be lost or deleted

### Advantages Over Centralized Platforms
- **Cannot Be Shut Down**: No central servers to raid or take offline
- **No Trust Required**: Zero-knowledge cryptography protects identities
- **Immutable**: Documents cannot be altered or deleted once published
- **Borderless**: Not subject to any single jurisdiction

## Technical Architecture

DocBlock leverages ICP's unique features:
- On-chain storage for permanent document preservation
- Canister smart contracts for access control
- Internet Identity for anonymous authentication
- Chain-key cryptography for security

## Development

1. Local setup:
```bash
dfx start --clean
```

2. Install dependencies:
```bash
npm install -g pnpm
pnpm install
```

3. Deploy canisters:
```bash
dfx deploy
dfx deps deploy
```

Access the frontend at `http://localhost:8000`

## Security Considerations

While DocBlock provides strong security guarantees through ICP:
- Use Tor/VPN when accessing for additional anonymity
- Be cautious with metadata in documents
- Consider document fingerprinting


## Contributing

We welcome contributions that enhance security and usability.

## Disclaimer

This is beta software. Review security implications before using for sensitive data. 
