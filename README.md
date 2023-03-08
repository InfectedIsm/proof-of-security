# Proof of Security

Journal of my learning progress in blockchain programming and security


#### DAY 35 8-mar-2023
- Spent some time on the C4 Aragon contest
This time I studied the Framework part, I though I got something but I was wrong. I'll try again tomorrow

#### DAY 34 7-mar-2023
- Spent some time on the C4 Aragon contest
I've pretty well understood the DAO and Permission Manager, took some notes.
There's still the Framework part I need to study
The Aragon codebase is pretty big for a start, but I'm learning a lot even if not finding anything for now: 
- learned coding patterns
- learned a lot about DAOs functionalities
- learned that staying focus and sharp is very important during discovery phase

#### DAY 33 6-mar-2023
- Spent some time on the C4 Aragon contest
I've read the documentation and tried to understand the code
____
#### DAY 32 5-mar-2023
- Started C4 Aragon contest 

#### DAY 31 4-mar-2023
- Solved WETH-11 QuillCTF challenge
- Started C4 Ethos contest, then noticed I was first planing to do Aragon with someone. 
I will do Aragon as there's only 2 days left to Ethos, and Aragon seems easier to understand

#### DAY 30 3-mar-2023
Suceeded in the #30daysweb3security challenge!
Thank you to the @Web3SecurityDAO for organizing this! 
- I finally solved Damn Vuln DeFI #12 Climber!
Struggled so much bc of the execute/schedule ids+ manipulating the arrays, to finally get a pretty clean solution!
It would have probably took more time without this insane ressource : https://solodit.xyz/issues/682
By digging existing findings on similar topics, I was able to find the real vulnerability which certainly inspired this challenge
- 2/ I also solved the QuillCTF : Donate!
https://quillctf.super.site/challenges/quillctf-challenges/donate
There's still the WETH11 available to solve
I like the idea of a leaderboard, remind me of CaptureTheEther but with a time limit 

#### DAY 29 2-mar-2023
Still not able to implement correctly Damn Vuln DeFi #12 correctly, but I'm half way
Continued reading Biconomy 2022-03 report

#### DAY 28 1-mar-2023
Bonked my head over Damn Vulnerable DeFi #12, I know I have the solution but issues to implement it.
When its like this, I'm better waiting tomorrow, it usually works better!

#### DAY 27 28-fev-2023
Started to get into the C4 Biconomy audit report, participating in the weekly audit study club from 
@Web3SecurityDAO
While for past report I wasn't reading the project documentation, this time 
@ArtemkaWeb3
 proposed to read the doc day1, good idea!

#### DAY 26 27-fev-2023
- I'm pretty sure I found the solution to Damn Vulnerable DeFi #12 Climber!
Using the audit tags helps a lot, but https://solodit.xyz/dashboard even more🤟
- Posted this thread about a vulnerability I think was fun enough to share it!
https://twitter.com/InfectedCrypto/status/1630334513791287299
 
#### DAY 25 26-fev-2023
- Got 4.5/8 at Secureum race 15 (got same grade for race 14). But I feel more comfortable now with the time limit. Also I could have gotten more, first question I forget there was multiple good answers... I think I can be in the top 32 next time :D
- Started lurking into Damn Vuln Defi #12 : Climber. Taking this as opportunity to get deep into Upgradable OZ contracts

#### DAY 24 25-fev-2023
- Worked on Secureum Race 10 to 14
Tomorrow I'll participate to the RACE 15!

#### DAY 23 : 24-fev-2023
Worked on [Secureum Race](https://ventral.digital/posts/2022/8/29/secureum-bootcamp-epoch-august-race-9) 6 to 9

#### DAY 22 : 23-fev-2023
- Read the last Block Threat Intelligence newsletter (not entirely yet, too many of interesting topics in there)
- From the newsletter, really liked [this finding](https://twitter.com/leekt216/status/1625147853890023426) from @leekt216 on Safe based 4337 wallets

- Completed Secureum Race 5

#### DAY 21 : 22-fev-2023
- Read TimeSwap contest from c4
- Read [an article](https://t.co/XXeYhJ1zTm) about the simple inliner optimizer

#### DAY 20 : 21-fev-2023
#### DAY 19 : 20-fev-2023
Had to rest because of a medical issue

#### DAY 18 : 19-fev-2023

Made [a writeup](https://github.com/InfectedIsm/some-quizz/blob/main/Quizzes/4-%20Secureum%20-%20Pitfall%20%26%20Best%20Practices.md) of the "Pitfalls and Best Practices 101" Quizz from Secureum
I remember few weeks ago when I read it and was a bit lost. This time I rolled over it 🚄
I think that next week I will go over Securem RACEs

#### DAY 17 : 18-fev-2023

Today I studied the writeups from @deliriusz_eth on the 2 bugs he found : [https://twitter.com/deliriusz_eth/status/1626577338019495936](https://twitter.com/deliriusz_eth/status/1626577338019495936)
Thought it would be a great way to apply my fresh foundry and cloned his repo with the poc to study them

#### DAY 16 : 17-fev-2023

Today I continued working the Foundry Book
I really like the UI and all the tools
Will I become a Foundry devout when I'll finish it ?..

#### DAY 15 : 16-fev-2023

- Started the Foundry Book. I know this is the tool to-go for auditing and testing smart contracts. Nearly every POCs are based on Foundry

The Foundry Book : [https://book.getfoundry.sh](https://t.co/1ZylTfE9Au)

I've been using hardhat for a long time, but reading the doc I see why Foundry is prefered. The integrated tools are really powerful : gas tracking, detailed callstack, fuzzing,  forking, evm debugger, ... That's INSANE

- Started a Notion list of findings with tags and associated vulnerability

Notion list of findings: This idea came from [@andyfeili](https://twitter.com/andyfeili) videos and interviews. I was feeling too "passive" while reading the audits. Filling up this database with findings, trying to sort them by type and type of vulnerability will certainly help a lot to learn them better!

#### DAY 14 : 15-fev-2023

Today I studied the last hacks from Block Threat Intelligence 
& Started to read the PoolTogether C4 contest thanks to an initiative on the [@Web3SecurityDAO](https://twitter.com/Web3SecurityDAO)

consisting in reading a report each week (which fits exactly with my todo on day8 !)

#### DAY 13 : 14-fev-2023

I finally found the solution for #11 Backdoor challenge!!
What a relief, what a feeling.
Struggling during multiple sessions, thinking that you got the solution, but finally not...
But after each try, feeling that you're closer than before

I really liked this challenge because I was forced to explore in details how the Gnosis Safe works, function after function, deeper and deeper. Damn Vulnerable Challenge are insanely well written, I can see the gradual progression. [@tinchoabbate](https://twitter.com/tinchoabbate) did an amazing job

If you haven't already started doing CTFs, don't be afraid and jump into it. I like to take my time with CTFs and document myself a lot on related topics during the exercise, to get the most of it in term of knowledge.
I'll probably go to code4rena once I'll finish them!

#### DAY 12 : 13-fev-2023

Small day, just continued worked on the DVChallenge #11 Backdoor
I've found the solution, need to finish coding it
Compared to previous challenges, this one require us to explore a big codebase to find the solution. I really like the gradual step-up!

Aaand, finally while in bed… I found [a great article](https://t.co/tHK3yJd33D) on formal verification applied to solidity code

Formal verification determine whether a given logical formula can be true or false based on a set of rules. We must not forget about these tools

#### DAY 11 : 12-fev-2023

I continued exploring Gnosis src.
Very interesting, they uses a "module" system, where a Safe is first a very simple contract-wallet w/ limited capabilities. But users can dynamically activate modules and execute their code : [https://github.com/safe-global/safe-modules](https://github.com/safe-global/safe-modules)

I also learned about EIP712 (not 721) because it is used by Gnosis.
This standard allows wallets to display data in signing prompts in a structured and readable format

[https://eips.ethereum.org/EIPS/eip-712](https://t.co/oisSIVD0c5)

#### DAY 10 : 11-fev-2023

Today I started the Backdoor #11 challenge [https://damnvulnerabledefi.xyz/challenges/backdoor/…](https://t.co/4J3aFnG09n)

Then I got lost in articles and docs about Gnosis Safe contracts

Found out a lot of protocol make use of these, so it is important for an auditor to get a good grasp on what it is, how it works, what vulnerabilities exists. For example, [here is a list of countermeasure against MEV](https://t.co/d3RP91CI33) on Safes Tx 

Found myself pretty lost for now in this challenge, simply because I still don't understand how to interact with a safe in the first time. The Gnosis Safe documentation is way less helpful than the Uniswap V2 one.
I'll have to read the solidity code then!..

#### DAY 9 : 10-fev-2023

I decided to continue reading articles and docs (links shared in next posts)

- Went over all items of BlockThreat (a web3 sec newsletter) "Hacks" section

[@blockthreat](https://twitter.com/blockthreat) share a weekly [newsletter](https://newsletter.blockthreat.io/p/blockthreat-week-5-2023) about web3 security. A great way to keep yourself informed of latest hacks, vuln, tools, or great articles.
This week, oracle manipulation, reentrancy, business logic issue, ... 
Will assuredly continue to read

- Read the "awesome-oracle-manipulation" repo (0xcacti)

Stumbled over this great repo sharing interesting readings about oracle manipulation :

[https://github.com/0xcacti/awesome-oracle-manipulation…](https://t.co/1N27u94xhX)

Went through most of them, but as always, you click a link, then from this link you click 10 other links... Web3 security is really prone to rabitholing

- Documented myself about oracles

From these links, I really link Euler serie on oracles, they're easy to read. It emphasis on Uniswap pools oracle (TWAP :Time-Weighted Average Prices) and its limits
part 1: [https://eulerlabs.com/blog/prices-and-oracles…](https://t.co/5KT8ebNgKu)

part 2: [https://eulerlabs.com/blog/moving-average-filters](https://t.co/ACkNfUFwNB)

#### DAY 8 : 9-fev-2023

've never been so consistent in my learning, this challenge helped for sure !
Today :

- Read EVM Deep Dives Part 3 on Storage

Before reading part 3, I went back to part 2 to be sure it was fully understood. Part 3 was really cool, love how ingenious is the process to read packed variables, using bitwise and shift operations : )

- Read my first code4rena audit => Papr

I finally read my first code4rena audit ! I tried to chose a pretty recent one : Papr (small codebase). I still have to read the H findings, but I have read and understood the rest !
Will try to implement this as a routine : read least 1 audit a week

What I really liked too is that I did not only learn about security issues, but also how the findings are rated, discussed, and demonstrated.

#### DAY 7 : 8-fev-2023

Today I published [my writeup for the Challenge #7](https://coinsbench.com/damn-vulnerable-defi-challenges-7-compromised-9ada74bc42fe) from Damn Vulnerable DeFi.
I've already completed the #10, but I'm a bit late on my articles, but at the end this is a great way to refresh my memory !

#### DAY 6 : 7-fev-2023

Today :

- I implemented the solution to #10 Free Rider from Damn Vulnerable DeFi, this is a step further from the previous challenges, loved it

I think this challenge goes a step further as the solution require more research and reading outside of the challenge contracts themselves.
Can't wait to discover #11.
But first I need to catch up on my [CTF write-ups](https://medium.com/@infectedf)

- Read through the EVM deep dives post from Noxx substack

Noxx blogposts are incredibly well written, a go-to if you want to understand how solidity is compiled into opcodes, and how the EVM work through this.
I don't know who created the EVM Playground but his work is a gift to us, learners!

[https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy-d6b](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy-d6b)

#### DAY 5 : 6-fev-2023

today i read the Uniswap V2 whitepaper + a great blogpost from [@samczsun](https://twitter.com/samczsun) on oracles price manipulation (i’m sharing it at the end)

Very well written, i prefered reading the whitepaper over the documentation, as all choices are explained, great reading from an auditor standpoint. 100% recommended to read it : [https://docs.uniswap.org/whitepaper.pdf](https://t.co/2q5FgcaMEh)

The note [3] from this whitepaper leads to a great blogpost from samczsun on an oracle price manipulation, but i would like to share it another one from his blog which sumarize this topic + gives hints on how to mitigate these risks : gold!

#### DAY 4 : 5-fev-2023

Went back to #10 free-rider from Damn Vulnerable DeFi this morning, eat, thought about it whil eating, took a train for a 3h travel, and found the solution!

This challenge forced me to dig into UniV2 documentation, I feel way more confident about it now!

#### DAY 3 : 4-fev-2023

Today I spent most of my time on challenge #10 from CTF Damn Vulnerable DeFi : [https://www.damnvulnerabledefi.xyz/](https://www.damnvulnerabledefi.xyz/)

If I can give you an advice : don't give up on these challenges, you will learn a lot if you solve them by yourself. I'm giving you an alpha from [@pashovkrum](https://twitter.com/pashovkrum) if you find something hard, most of your competitor will find it hard too first time. Make the diff and don't giveup

My own advice : don't try to rush everything, do it on your own pace. My style is to follow my curiosity. This can slow you down, but on the long run you will get a lot more depth

#### DAY 2 : 3-fev-2023

Finished my Solidity 201 Quizz writeup !
Will probably start next quizz tomorrow.
This is a great way to practice and learn when you don't have that much time on your schedule !

#### DAY 1 : 2-fev-2023

A challenge started on Discord Web3SecurityDAO, its called #30daysweb3security 

I was already trying to work each and every day on web3 security, but doing it publicly with a group can be very encouraging!

Let's try to run this challenge !
Today I'm continuing writeups of [@Secureum](https://twitter.com/Secureum) quizzes, a great way to test my knowledge and then fixing it in my mind by doing research and writing them !

[InfectedIsm/some-quizz](https://t.co/ivP1CjuDV8)

#### Before DAY 1
- Started with CryptoZombies
- Read Ethereum White Paper
- Read Ethereum Workbook 
- Read Solidity Doc
- Then BuildSpace web3 course
- Solved Lotteries and Math from Capture the Ether. I learned a LOT with these challenges (Remix, Etherscan, and of course Solidity), I highly recommend them
- Eats the Blocks 6-figures training (not the best one, wouldn't recommend it its based on 0.4.2)
- Learned a bit of web deb with Angular and Typescript
- Learned Truffle and Ganache, but didn't like it at all
- Learned Hardhat, was way better
- Wrote writeup to multiple quizzes (Rareskill, Secureum)
- Read hundreds of articles/blogposts
