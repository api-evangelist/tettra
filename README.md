# Tettra

Tettra is an AI-powered knowledge management system that helps teams curate company policies, processes, and knowledge articles into a searchable internal wiki. It features an AI assistant named Kai that integrates directly with Slack and Microsoft Teams to automatically answer repetitive questions from the team knowledge base.

## API

Tettra provides a limited experimental REST API (`https://app.tettra.co/api`) for automating common tasks and building custom integrations. The API supports:

- **Search** pages in the knowledge base
- **Create Pages** from HTML content
- **Suggest a New Page** (page requests for knowledge gaps)
- **Suggest Page Updates** to existing pages
- **Create Questions** within the Q&A workflow

API keys are provisioned through account settings and are only available on the **Scaling** and **Enterprise** plans. The API is marked experimental and may include breaking changes without notice.

## Authentication

All API requests require an `api_key` query parameter. Keys are available via team account settings for eligible plan subscribers.

## Resources

- **Homepage:** https://tettra.com/
- **API Documentation:** https://support.tettra.com/api-overview
- **Pricing:** https://tettra.com/pricing/
- **Changelog:** https://changelog.tettra.co/
- **Status:** https://tettra.statuspage.io/
- **LinkedIn:** https://www.linkedin.com/company/tettra
- **GitHub:** https://github.com/Tettra

## Maintainer

Kin Lane (kin@apievangelist.com)
