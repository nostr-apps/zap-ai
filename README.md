# ZapAI 

> An AI bot on Nostr that responds to your questions when you pay with Bitcoin Lightning.

## What is ZapAI?

ZapAI is an AI-powered bot that lives on the Nostr protocol. Ask it anything, send a Lightning payment, and get your answer instantly. No accounts, no subscriptions, no tracking. Just you, your question, and Bitcoin.

## How It Works

1. **Mention @ZapAI** in a Nostr post with your question
2. **Send a Lightning zap** (100+ sats) to that post
3. **Get your answer** within seconds, posted publicly on Nostr

Simple as that.

## Why ZapAI?

- ⚡ **Pay Per Question**: No monthly fees. Pay only when you ask, using Bitcoin Lightning micropayments.
- 🔐 **No Sign-up Required**: Use your existing Nostr identity. No email, no password, no KYC.
- 🤖 **Powered by AI**: We use modern AI models like GPT-4 and Claude to give you accurate answers.
- 🌐 **Built on Open Protocols**: Runs on Nostr, an open and censorship-resistant network.
- 📖 **Public Knowledge Base**: Every question and answer becomes part of a shared knowledge library.

## Technology Stack

### Core Components

- **Nostr Protocol**: Open social network protocol for publishing questions and answers
- **Lightning Network**: Bitcoin payment layer for instant micropayments
- **DVM (Data Vending Machine)**: NIP-90 standard for AI services on Nostr
- **AI Models**: OpenAI GPT, Anthropic Claude, or self-hosted models like LLaMA

### Infrastructure

- **Bot Identity**: Unique Nostr key (npub/nsec) for the bot
- **DVM Server**: Monitors mentions, verifies zaps, processes questions, and publishes responses
- **Lightning Backend**: Payment processor (LND, Core Lightning, BTCPay, LNbits, or Alby)
- **AI Backend**: Integration with AI APIs or self-hosted models

## Contributing

We welcome contributions! Whether it's code, documentation, or ideas, feel free to:

- Open an issue to report bugs or suggest features
- Submit a pull request with improvements
- Join discussions on Nostr

## License

MIT License. You are free to use, modify, and distribute this project.

## Contact

- **Website**: [zap-ai.netlify.app](https://zap-ai.netlify.app)
- **GitHub**: [nostr-apps/zap-ai](https://github.com/nostr-apps/zap-ai)
- **Nostr**: @ZapAI (launching soon)

---

**Built with ⚡ Lightning • 🌐 Nostr • 🤖 AI**

*An open source project creating fair and sustainable AI services on Bitcoin.*
