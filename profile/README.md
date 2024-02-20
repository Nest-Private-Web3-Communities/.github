## Inspiration

Managing communities has perpetually posed challenges, particularly in achieving complete security and completely custom tailor made solutions. Traditional Web2 solutions face issues of centralization and security, while transitioning to Web3 often triggers privacy concerns due to the public exposure of data. "Nest" steps in to offer a user-friendly interface, drawing inspiration from popular apps like Telegram, Discord, and WhatsApp. It facilitates the creation, management, and participation in communities through a private, fully encrypted, and completely decentralized platform.

## What it does
The platform offers seamless community creation, requiring only a Nest account for identification across all Nest communities, linked to your address. Users have the freedom to create and join communities, each boasting full customization options. From color themes to emojis and reactions, every aspect can be tailored to suit the community's vibe. Additionally, users can establish networks within these communities, akin to Discord's channels within servers. All standard social media functionalities, such as posts, image sharing, comments, and reactions, are seamlessly integrated into the platform. When you create a community, it's a contract which is deployed and owned by you. Nest steps is for user authentication and collaboration amongst communities.

## How it works
![18dc576066560c59226b242492984275](https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/735ee7a5-f09a-47ed-a8af-87c303ecb2a8)

The key exchange protocol is an asynchronous slightly modified version of the Diffie Hellman Key Exchange protocol adapted for multi party exchange. To Learn Further -> [How Nest Encryption Works](https://www.youtube.com/watch?v=WqT1THswinI&t=380s)

## What's next for Nest
- [ ] **Monetization** : We aim to add a financial incentive for all nest community participants by using SocialFi principles. We plan to add a "Award" feature which will function similar to the current "reaction" feature but will be payable and can act as a tip for people who generate valuable content for a community. We also wish to explore further monetization methods and possibilities.

- [ ] **Messaging** : Throughout the demo and the video you might have noticed the "Coming Soon" text indicating that the messaging feature is a Work In Progress, though we were aiming to complete this feature within the hackathon timeline, since we could not it is the next priority which we have, to get those messages working.

- [ ] **Community Aggregation / Collaboration** : This was planned initially but we reckoned it was out of scope for the hackathon timeline. This feature will allow communities to share their content (as a directed graph) with each other and thus communities can fetch content from other communities and new posts within the "sharing" communities will appear in the communities with which the content is being "shared".

- [ ] **Web2 plugins** : We aimed to incorporate chainlink functions to fetch and serialize data from web2 social media platforms like reddit and add relevant data (for eg: from a subreddit) to a Nest community. This will be done as a batch job using Chainlink functions.

## Learnings and Challenges
- The web client is developed using React, viem, Particle Connect, and TailwindCss.
- The smart contracts are written in Solidity
- Developing a mathematical model for key exchange and asynchronous and private encryption was interesting and challenging but eventually accomplished.
- We discovered the enjoyable aspects of mathematics especially in Cryptography & Network security.
- We improved our team Collaboration and Optimization skills

## ScreenShots

### Landing Page
<img width="1120" alt="e7cdfc6a-3f74-498d-80f6-4c1912ef6776" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/033a823c-0d0a-47fc-984a-aefce001bd2e">

### Create Nest account Page
<img width="1120" alt="Screenshot 2024-02-19 201146" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/1f2a077b-bfce-49b9-9b43-0f449cbd0c72">

### Your Communities Page
<img width="1120" alt="Screenshot 2024-02-20 000213" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/e634af42-9305-44f0-b435-d4844772e55a">

### Joining a community
<img width="1120" alt="Screenshot 2024-02-20 000725" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/65339239-ae94-4158-8155-b5ca0acc109c">

### Creating a community with different themes and emotes
<img width="1120" alt="Screenshot 2024-02-19 195121" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/a4d9dd11-2f4f-473b-99bf-6a03fad54c05">
<img width="1120" alt="Screenshot 2024-02-19 194757" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/84b89211-a5bf-48b6-8156-4c3aeae41980">

### Selecting a theme for your community
<img width="1120" alt="Screenshot 2024-02-19 194622" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/f0fc1823-9575-4bc2-8553-3d2514527004">

### Inviting New members to community 
<img width="1120" alt="Screenshot 2024-02-20 020334" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/68b218be-1a67-4b98-a9c6-f51096e352a8">

### Adding new network
<img width="1120" alt="Screenshot 2024-02-20 020515" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/6a5615cd-8df0-4136-99e1-9f7898d80700">

### Community on Nest
<img width="1120" alt="Screenshot 2024-02-20 023951" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/a5f9fcb4-ec86-469f-aacd-8ab425f10edd">

### Your Community Info
<img width="1120" alt="Screenshot 2024-02-20 024005" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/eef51abc-4a0c-4a54-a17b-f9c6a1936821">

### Another Community on Nest
<img width="1120" alt="Screenshot 2024-02-19 230501" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/1f8f66eb-b406-4b52-9ebb-003a2b3c833d">

### Community Info
<img width="1120" alt="Screenshot 2024-02-19 230908" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/7c9e0eed-532a-4871-b6ac-03d582ec58f2">

### Share post with others
<img width="1120" alt="Screenshot 2024-02-19 230511" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/db39c050-7fcc-4006-84ce-eaadbec3289b">

### Another Community on Nest
<img width="1120" alt="Screenshot 2024-02-20 124312" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/b1f09fcf-9ae3-44bd-a194-692f4058e12f">

### Comment on posts
<img width="1120" alt="Screenshot 2024-02-20 124507" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/a372e7f0-c30a-4f15-9dd1-b61779bd6fbe">

### Add a new network
<img width="1120" alt="Screenshot 2024-02-20 123312" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/ba72163f-6115-4b8c-a058-9140eead6c39">

### Another Community on Nest
<img width="1120" alt="Screenshot 2024-02-19 234535" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/aba490a8-23cc-46fd-a861-e39892a0930a">

### Another Community on Nest
<img width="1120" alt="Screenshot 2024-02-20 103701" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/8e4ea103-1098-4846-a4d8-0a333ebc1f95">

### Add Comment to post
<img width="1120" alt="Screenshot 2024-02-20 131353" src="https://github.com/Nest-Private-Web3-Communities/.github/assets/96080203/4c8804f2-5550-4d5f-9c80-dae094283df0">

