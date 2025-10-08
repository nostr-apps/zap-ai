# ZapAI ⚡🤖

> A decentralized AI bot on Nostr that responds to questions when you zap Bitcoin via Lightning Network.

## What is ZapAI?

ZapAI is an AI-powered bot living on the Nostr protocol. It answers your questions instantly after you send a Lightning zap. No accounts, no subscriptions, no tracking—just mention the bot, zap some sats, and get your answer.

## How It Works

1. **Mention @ZapAI** in a Nostr post with your question
2. **Send a zap** (100+ sats) to that post
3. **Get your answer** within seconds, posted publicly on Nostr

## Features

- ⚡ **Lightning Payments**: Pay per question with Bitcoin micropayments
- 🔐 **No Sign-up**: Use your existing Nostr key (npub)
- 🤖 **AI-Powered**: Supports GPT-4, Claude, and other models
- 🌐 **Decentralized**: Built on open protocols, censorship-resistant
- 📖 **Public Knowledge**: All Q&A becomes a shared knowledge base

## Technology Stack

- **Nostr Protocol**: Decentralized social network
- **Lightning Network**: Bitcoin micropayments
- **DVM (Data Vending Machine)**: NIP-90 for AI services
- **AI Models**: OpenAI GPT, Anthropic Claude, or self-hosted LLaMA

## Investment Opportunity

We're raising **$3,000 USD in Bitcoin** through [Angor](https://angor.io) to build ZapAI.

**Stage 1 ($1,500)**: Infrastructure setup, Lightning integration, AI API, basic bot  
**Stage 2 ($1,500)**: Advanced engine, payment processing, production deployment

**50% Profit Sharing**: Investors receive 50% of all revenue, paid monthly in Bitcoin via Lightning.

[→ View on Angor](https://angor.io) (launching Q4 2025)

## Quick Start

```bash
# Clone the repository
git clone https://github.com/nostr-apps/zap-ai.git
cd zap-ai

# Install dependencies
npm install

# Configure environment
cp .env.example .env
# Edit .env with your keys

# Run the bot
npm start
```

## Configuration

Create a `.env` file:

```env
NOSTR_PRIVATE_KEY=your_nsec_here
AI_API_KEY=your_openai_or_claude_key
LIGHTNING_ADDRESS=your_lightning_address
MIN_ZAP_AMOUNT=100
```

## Roadmap

- [x] Basic concept & design
- [ ] Nostr relay integration
- [ ] Lightning payment gateway
- [ ] AI API integration
- [ ] Mention & zap detection
- [ ] Production deployment
- [ ] Multi-language support
- [ ] Advanced features

## Contributing

Contributions are welcome! Open an issue or submit a pull request.

## License

MIT License - feel free to use, modify, and distribute.

## Contact

- **Nostr**: @ZapAI (coming soon)
- **GitHub**: [nostr-apps/zap-ai](https://github.com/nostr-apps/zap-ai)
- **Website**: [zap-ai.netlify.app](https://zap-ai.netlify.app)

---

**Built with ⚡ Lightning • 🌐 Nostr • 🤖 AI**