# bedrock-locator

Minecraft: Bedrock Edition tool for locate player on the server

# About

**bedrock-locator** is tool focused for locate player on Minecraft: Bedrock Edition Server using [PrismarineJS/bedrock-protocol](https://github.dev/PrismarineJS/bedrock-protocol).

# Issues

Here are some issues I found:

- Minecraft: Bedrock Edition with versions below 1.21.80 does not work
- If the player is in a different dimension than the client, it will not work
- It is possible that only BSD or Vanilla Servers are supported

# How to use
Installation:

1. Clone this repository
  ```bash
  git clone https://github.com/MrVenumX/bedrock-locator
  ```

2. Navigate to `bedrock-locator`
  ```bash
  cd bedrock-locator
  ```

3. Install required dependencies
  ```bash
  npm install
  ```

Usage: 
  ```bash
  npx bedrock-locator --server-host 127.0.0.1 --server-port 19132
  ```

# Information

I have found that sneaking or moving a few blocks can trigger `player_location`.

For more Information you can see [PrismarineJS - Bedrock 1.21.80](https://prismarinejs.github.io/minecraft-data/?v=bedrock_1.21.93&d=protocol#packet_player_location)
