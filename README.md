# Blockchain-In-Music-Industry-Knack-Music-Platform

Created by Romit Chattopadhyay
<br>
Stream: CSE(AIML)
<br>
Enrollment Number: 12020002018032
<br>

## Problem Statement:
Music is known to be effective for mood improvement. It has the power to change one's overall frame of mind. Music also plays a very big role in changing the atmosphere and influencing the ambiance of any place. Seeing how much of a great impact music has on everyone’s lives we need a stable service to fulfill a few requirements that would make listening to music a better experience.
## Motivation:
The music industry has grown exponentially in the past few years with the success of digital music streaming services. However, the major music streaming platforms are centralized, and as a result, the artists lack control over their content. A technology that can improve transparency and provide more control to the artists over the money they make can revolutionize the industry. The direct interaction between consumers and artists would also eliminate the need for intermediaries from the revenue stream.
## Our Solution:
A blockchain-based decentralized music streaming platform to connect music enthusiasts directly to independent music artists. The artists can use this platform to share their music with greater freedom while ensuring ownership and avoiding duplication of their music. People can listen to their favorite songs and support the artists by making micropayments through our custom crypto tokens.
## Architecture:
![Untitled design](https://user-images.githubusercontent.com/53979947/160265658-1ced9b83-712c-40b0-ba4e-d75be6b9ff8c.png)
## Features implemented:
1. Recommendation of music (if a user searches ‘gaye’, results should be used gaye and other songs with ‘Gaye’ in their names) (YouTube music)
2. Identification of music (via smart contracts/NFTs)
3. Streaming the music uploaded by the artist
4. Artist revenue generation
## Technology Stack:
1. React.js
2. Node.js
3. Web3.Storage
4. Solidity
5. Truffle
6. Ganache
7. Metamask
## Setup:
- Install and setup Ganache, Truffle, and Metamask (chrome extension)
- Clone the repository
``` 
git clone https://github.com/RogerThaTOP/Blockchain-In-Music-Industry-Knack-Music-Platform.git
```
- Setup a workspace of knack on Ganache
- Connect Metamask to the Ganache workspace
- Migrate the Contracts
```
truffle migrate
```
- Start the React App
```
npm start
```
