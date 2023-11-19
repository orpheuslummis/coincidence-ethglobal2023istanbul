# Coincidence

<img src="./public/logo.png" alt="Coincidence Logo" height="222px"/>

Connect, collaborate, & coincide, privately.

- [Video presentation](https://youtu.be/2S1VGk5AQz0)
- [Slides](https://drive.google.com/file/d/1CSZBckMBVWU30o3MABEz3xYByE-Ba1BP/view?usp=sharing)

Created during ETH Global Istanbul 2023.


## Problem it solves

Most match-making apps focus on dating, limiting other social interactions. They often misuse user data, compromising privacy and safety. Additionally, connecting over shared interests or finding projects can be challenging and time-consuming. This reveals a gap: the need for a platform that enables safe, interest-based connections, free from the typical privacy concerns, and what’s culturally associated with match-making apps.

## How it works

- Create profile
- Add your interests
- Coincide with people sharing your interests
- Chat with your new friends

## How to run

Visit https://app.coincidence.network/.

Use with [Optimism Goerli Chain](https://chainlist.org/chain/420).

To run locally:

```shell
npm install && npm run dev
```

## Challenges during implementation

- EAS: ethers v5 incompatibility with the EAS sdk. All schemas are unique, which is why all second attempts always run into error.
- Implementation of a full PSI protocol was over our time\*complexity budget.
- We had some difficulties with the Typescript build system, pushing us to use Javascript in some places.

## Authors and licensing

- Orpheus (https://github.com/orpheuslummis)
- Giovanni Fulin (https://github.com/aeither)
- Manuela Garcia Toro (https://github.com/AlumnaeGracia)

MIT license.
