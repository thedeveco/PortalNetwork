# Welcome to the Portal Network

Welcome to the Portal Network Metadata repository! This is the foundational hub for the Portal Network, an open-source initiative designed to connect developer-focused Discord communities and provide a wealth of resources, knowledge, and collaboration opportunities.

# What is the Portal Network?

The Portal Network is a curated database of Discord servers that are united by a shared vision: openness, collaboration, and innovation. By joining the Portal Network, communities unlock access to a diverse ecosystem of technologies, tools, and expertise that help members explore, learn, and grow.

# Why Join the Portal Network?

- **Explore**: Discover new technologies, communities, and resources.
- **Connect**: Collaborate with technologists, developers, and innovators worldwide.
- **Grow**: Expand your network and accelerate knowledge sharing and innovation.
- **Empower**: Provide your members with opportunities and tools to thrive in the tech ecosystem.

# How It Works

- **Metadata Repository**: This repository contains all the information (metadata) about the Discord servers in the network, categorized and tagged for easy exploration.
- **Portal Bot**: A Discord bot that fetches metadata from this repository and delivers it to subscribed servers.
- **Announcements Channel**: Updates are also shared in the #portal channel within the devEco Discord server.

# How to Join the Portal Network

1) **Add your Server to the Repository**
- Fork this repository
- Add your server's metadata to the `servers.json` file in the following format:

```json
{
  "name": "Your Server Name",
  "invite": "https://discord.gg/yourinvitecode",
  "description": "A brief description of your community.",
  "tags": ["technology", "AI", "IoT"],
  "category": "Technology",
  "member_count": 1200
}
```

- Submit a pull request (PR) with your changes.

2) **Follow the Guidelines**
- Servers must align with the Portal Network’s vision of collaboration and openness.
- Ensure your metadata is accurate and up-to-date.
- Respect all contribution guidelines and the code of conduct.

# Respository Structure 

```bash
/README.md           # Explanation of the Portal Network and metadata repository
/metadata/           
  - categories.json  # List of server categories
  - servers.json     # Metadata for each server
/docs/               
  - CONTRIBUTING.md  # Contribution guidelines
  - FAQ.md           # Frequently Asked Questions
  - CODE_OF_CONDUCT.md # Community guidelines
```

# Contributing

We welcome contributions to improve the Portal Network! Please read the CONTRIBUTING.md file for detailed guidelines.

# License

This repository is licensed under the MIT License.