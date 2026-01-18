# AetherisQueue
Aetheris Queue is an automated matchmaking and tournament management system integrated directly into Discord. It is designed to provide an organized, "ranked-like" competitive environment for amateur League of Legends communities. By utilizing a custom MMR (Matchmaking Rating) system, the bot ensures balanced matches for players of all skill levels, facilitating a structured league experience outside of the standard client queues.

Dynamic Matchmaking: Players join a persistent queue via Discord interactions. The bot automatically groups players into teams of five based on their primary/secondary roles and MMR to ensure competitive balance.
Automated Lobby Management: Upon a "Match Pop," the bot will utilize the Tournament API to generate unique tournament codes, allowing players to join pre-configured custom lobbies instantly.
Voice Integration: The system dynamically creates private, team-specific voice channels for each match to facilitate communication and competitive integrity.
Automated Result Reporting: By hooking into the Tournament API Webhooks, the bot will automatically record match winners, update player statistics (Wins/Losses/KDA), and adjust MMR without requiring manual staff intervention or screenshots.
