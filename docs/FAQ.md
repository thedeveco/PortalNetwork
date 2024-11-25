# Portal Network FAQ

Welcome to the Portal Network FAQ! This document addresses common questions about the Portal Network and provides guidance for contributors and users.

---

## General Questions

1. What is the Portal Network?

The Portal Network is an open-source project designed to connect Discord servers focused on technology, development, and innovation. It serves as a database and directory of categorized servers, making it easier for members to explore new communities and access valuable resources.

2. How does the Portal Network work?

**The Portal Network is powered by:**

- A metadata repository that organizes server information.
- A Portal Network bot that provides updates and search functionality.
- An announcements channel in the devEco Discord server that shares updates.

**Communities can subscribe to the network by either:**

- Following the #portal channel in the devEco Discord.
- Inviting the Portal Network bot into their server.

3. Why should my server join the Portal Network?

By joining the Portal Network, your server becomes part of a growing ecosystem of developer communities. Members gain:

- Access to a wider audience and collaborative opportunities.
- Discovery by developers looking for niche or general communities.
- Increased visibility through Portal Network updates and search tools.

---

## For Contributors

4. How can I add my server to the Portal Network?

**Follow these steps:**

- Fork the Portal Network Metadata repository.
- Add your server’s details to the servers.json file in the specified format.
- Submit a pull request (PR) with your changes. For detailed instructions, see the CONTRIBUTING.md file.

5. What information is required to add my server?

**You’ll need the following details:**

- Name: The name of your server.
- Invite Link: A permanent, non-expiring invite link.
- Description: A brief overview of your server.
- Tags: Keywords to help categorize and describe your server.
- Category: The ID of the category from categories.json that best fits your server.
- Member Count: Approximate or latest member count.

6. What if my server doesn’t fit into an existing category?

If your server doesn’t align with the current categories in categories.json, you can:

- Suggest a new category by opening a GitHub issue.
- Provide a justification for how the new category will add value to the Portal Network.

---

## Technical Questions

7. What is the Portal Network bot, and how does it work?

The Portal Network bot is a tool that integrates with Discord servers to:

- Provide updates from the Portal Network.
- Allow members to search for servers by category or tags.
- Notify subscribed servers about new additions or changes.
- To invite the bot, follow the instructions in the Portal Network Bot repository.

8. Can I self-host the Portal Network bot?

Yes! The bot is open source, and you can find self-hosting instructions in the Portal Network Bot repository.

---

## Maintenance and Updates

9. How often is the Portal Network updated?

The network is updated regularly as new servers are added or existing servers provide updated metadata. Subscribing servers will receive updates automatically.

10. How do I report an issue or suggest an improvement?

---

**You can:**

- Open a GitHub issue in the Portal Network Metadata repository.
- Reach out in the #portal channel of the devEco Discord server.

11. What if my server information changes?

If your server details (e.g., description, tags, invite link) need updating, submit a pull request with the updated information. Clearly describe the changes in the PR.

---

## Contact and Support

12. How can I get additional support?

**If you need help or have questions:**

- Check the documentation in this repository.
- Join the devEco Discord server and ask in the #portal channel.
- Submit a GitHub issue for technical concerns.