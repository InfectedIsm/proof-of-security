# Proof of Security

Journal of my learning progress in blockchain programming and security. Don't forget to check also my ["before day 1 section!"](#Before-DAY-1)

#### DAY 64 07-mar-2023
> Started the Rubicon C4 Contest

#### DAY 63 05-mar-2023
> - read the [Blockthreat intelligence](https://newsletter.blockthreat.io/p/blockthreat-week-13-2023)
> - Spent 1h30 on the QuillCTF challenge [SlotPuzzle](https://quillctf.super.site/challenges/quillctf-challenges/slot-puzzle), still cannot solve it...  
> 

#### DAY 62 04-mar-2023
> - Spend 2h on the QuillCTF challenge [SlotPuzzle](https://quillctf.super.site/challenges/quillctf-challenges/slot-puzzle) 
> I was able to uncipher the procedure to calculate the slot using the [solidity doc](https://docs.soliditylang.org/en/v0.8.17/internals/layout_in_storage.html#mappings-and-dynamic-arrays), but still I haven't solved it. The dev behind is really evil

#### DAY 61 03-mar-2023
> - Read articles from [Week in Ethereum](https://weekinethereumnews.com/) section 'Security'

#### DAY 60 02-mar-2023
#### DAY 59 01-mar-2023
#### DAY 58 31-mar-2023
Was AFK for a few days!

#### DAY 57 30-mar-2023
> I found my first medium, some gas and QA ! Really happy with that! Now I will have to wait ~1month to get the results :'(

#### DAY 56 29-mar-2023
> Continued the Assymetry C4 contest

#### DAY 55 28-mar-2023
> Continued the Assymetry C4 contest. This time I have decided I will focus on gas/QA/Low issues, and try to find as many as possible.
> I think this is a great way to train my focus and audit muscle. Also, I will have things to write down to train reporting.

#### DAY 54 27-mar-2023
> Read EIP-712 & EIP-2612 (the latter being an extension of EIP-712, but for ERC-20 tokens to add a permit functionnality)
> Started the Assymetry C4 contest

#### DAY 53 26-mar-2023
> - Read EVM Deep Dives: The Path to Shadowy Super Coder [Part 3](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy-3ea?s=r) and [Part 4](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy-5a5?s=r)

#### DAY 52 25-mar-2023
> - Spend some time on the QuillCTF challenge [SlotPuzzle](https://quillctf.super.site/challenges/quillctf-challenges/slot-puzzle) but did not manage to solve it for now

#### DAY 51 24-mar-2023
> Read this very interesting article about [Encrypted Mempools](https://joncharbonneau.substack.com/p/encrypted-mempools). Talks about privacy and protection against MEV.

#### DAY 50 23-mar-2023
> - Read the whole EIP-4337, I feel like this will break a lot of contract logic based on `address.code.length` to differentiate between contracts and EOA. Because after EIP-4337, there every address will have a logic behind it.
> - Started studying Chainlink protocol, for now just reading the doc, but I will go through the codebase soon. I've always been interested in oracles, and I think this is a good way to learn more about them.


#### DAY 49 22-mar-2023
> - Read the Biconomy report. I understand that before focusing on fiding medium issues, I should at least be able to find most of the gas and QA/Low issues pretty easily while going through a codebase. I'm not there yet, but I will work in this direction.
> I'm pretty sure this will lead to better understanding of the code, better methodology, and then give me more time and energy to focus on higher issues.
> - I also read the [Blockthreat intelligence](https://newsletter.blockthreat.io/p/blockthreat-week-11-2023) as usual. A lot of interesting articles and hack walkthrough. 

#### DAY 48 21-mar-2023
> - Read the Looksrare report and started exploring some degen DeFi project (also reading their code published on etherscan)
> - Also read the EIP-1155 in detail. I remember few weeks ago being unable to read it properly, or any other EIP for that matter. I'm glad I'm getting better at it.

#### DAY 47 20-mar-2023
>- Last day of the Canto Identity C4 contest. Did not have so much time to spend on it, but submited a report with some gas and a low issue! I have the feeling that I'm more comfortable exploring a code base.

#### DAY 46 19-mar-2023
>- Continued the Canto Identity C4 contest

#### DAY 45 18-mar-2023
>- Started the Canto Identity C4 contest

#### DAY 44 17-mar-2023
>- Finished reading the report of the Frax contest, it was really interesting. I'm really impressed by the medium findings, which require for the researcher to get deep into the code maths (easy maths, but still it requires some time)

#### DAY 43 16-mar-2023
>- Studying the Frax contest (aug-2022). I've heard a lot about this stablecoin, that's a good way to learn more about it, and train my auditing skills at the same time!

#### DAY 42 15-mar-2023
>- Submited my first report for the Neo Tokyo C4 contest!
>I must admit this is not a great report, I did not had enough time to write it because of my planning today. But I'm happy to have submitted something, I've discovered the tools, the process a bit, and a barrier has been broken. For sure the next one will be better :)`
>- Started learning regex, I'm sure this is a very important tool to find some specific patterns, and thus better catch some vulnerabilities.

#### DAY 41 14-mar-2023
>- Continued exploring Neo Tokyo codebase. While Aragon was a way more complex project, it was easier to understand and follow.
>Project really need to be well documented and well organized, because this can make an audit way more time-efficient and effective.
>- Read Secureum Security Pitfalls & Best Practices 101/201 while exploring the codebase

#### DAY 40 13-mar-2023
>- Started (a bit late) the Neo Tokyo C4 Contest

#### DAY 38 11-mar-2023 & DAY 39 12-mar-2023
>- Days off ! 

#### DAY 37 10-mar-2023
>- Continued reading the [Blockthreat Intelligence newsletter](https://newsletter.blockthreat.io/p/blockthreat-week-9-2023)
	>- [Smart Contract Obfuscation Techniques](https://degatchi.com/articles/smart-contract-obfuscation) was really interesting. The guy  built a more optimized custom function selector, with custom bytecode (and more)
	>- [The interview of Zhuo and Brian](https://medium.com/code4rena/demystifying-exploitable-bugs-in-smart-contracts-with-zhuo-and-brian-f8649d4c427f) who wrote this very important paper about the state of smart contract vulnerabilities was also very interesting (and their advices about auditing)

#### DAY 36 9-mar-2023
>- Read the [Blockthreat Intelligence newsletter](https://newsletter.blockthreat.io/p/blockthreat-week-9-2023)
	>- Really liked this article about the inflation attack related to ERC-4626 vaults: https://mixbytes.io/blog/overview-of-the-inflation-attack
>- Did not have time to study the C4 Aragon contest, same for tomorrow :`( But I'm really eager to read the report when it will come out!

#### DAY 35 8-mar-2023
>- Spent some time on the C4 Aragon contest
This time I studied the Framework part, I though I got something but I was wrong. I'll try again tomorrow

#### DAY 34 7-mar-2023
>- Spent some time on the C4 Aragon contest
I've pretty well understood the DAO and Permission Manager, took some notes.
There's still the Framework part I need to study
The Aragon codebase is pretty big for a start, but I'm learning a lot even if not finding anything for now: 
>- learned coding patterns
>- learned a lot about DAOs functionalities
>- learned that staying focus and sharp is very important during discovery phase

#### DAY 33 6-mar-2023
>- Spent some time on the C4 Aragon contest
I've read the documentation and tried to understand the code

#### DAY 32 5-mar-2023
>- Started C4 Aragon contest 

#### DAY 31 4-mar-2023
>- Solved WETH-11 QuillCTF challenge
>- Started C4 Ethos contest, then noticed I was first planing to do Aragon with someone. 
I will do Aragon as there's only 2 days left to Ethos, and Aragon seems easier to understand

#### DAY 30 3-mar-2023
>- Suceeded in the #30daysweb3security challenge!
Thank you to the @Web3SecurityDAO for organizing this! 
>- I finally solved Damn Vuln DeFI #12 Climber!
Struggled so much bc of the execute/schedule ids+ manipulating the arrays, to finally get a pretty clean solution!
It would have probably took more time without this insane ressource : https://solodit.xyz/issues/682
By digging existing findings on similar topics, I was able to find the real vulnerability which certainly inspired this challenge
>- 2/ I also solved the QuillCTF : Donate!
https://quillctf.super.site/challenges/quillctf-challenges/donate
There's still the WETH11 available to solve
I like the idea of a leaderboard, remind me of CaptureTheEther but with a time limit 

#### DAY 29 2-mar-2023
>- Still not able to implement correctly Damn Vuln DeFi #12 correctly, but I'm half way
Continued reading Biconomy 2022-03 report

#### DAY 28 1-mar-2023
>- Bonked my head over Damn Vulnerable DeFi #12, I know I have the solution but issues to implement it.
When its like this, I'm better waiting tomorrow, it usually works better!

#### DAY 27 28-fev-2023
>- Started to get into the C4 Biconomy audit report, participating in the weekly audit study club from @Web3SecurityDAO
> While for past report I wasn't reading the project documentation, this time @ArtemkaWeb3 proposed to read the doc day1, good idea!

#### DAY 26 27-fev-2023
>- I'm pretty sure I found the solution to Damn Vulnerable DeFi #12 Climber!
>Using the audit tags helps a lot, but https://solodit.xyz/dashboard even more🤟
>- Posted this thread about a vulnerability I think was fun enough to share it!
>https://twitter.com/InfectedCrypto/status/1630334513791287299
 
#### DAY 25 26-fev-2023
>- Got 4.5/8 at Secureum race 15 (got same grade for race 14). But I feel more comfortable now with the time limit. Also I could have gotten more, first question I forget there was multiple good answers... I think I can be in the top 32 next time :D
>- Started lurking into Damn Vuln Defi #12 : Climber. Taking this as opportunity to get deep into Upgradable OZ contracts

#### DAY 24 25-fev-2023
>- Worked on Secureum Race 10 to 14
>Tomorrow I'll participate to the RACE 15!

#### DAY 23 : 24-fev-2023
>- Worked on [Secureum Race](https://ventral.digital/posts/2022/8/29/secureum-bootcamp-epoch-august-race-9) 6 to 9

#### DAY 22 : 23-fev-2023
>- Read the last Block Threat Intelligence newsletter (not entirely yet, too many of interesting topics in there)
>- From the newsletter, really liked [this finding](https://twitter.com/leekt216/status/1625147853890023426) from @leekt216 on Safe based 4337 wallets

>- Completed Secureum Race 5

#### DAY 21 : 22-fev-2023
>- Read TimeSwap contest from c4
>- Read [an article](https://t.co/XXeYhJ1zTm) about the simple inliner optimizer

#### DAY 20 : 21-fev-2023
#### DAY 19 : 20-fev-2023
>Had to rest because of a medical issue

#### DAY 18 : 19-fev-2023

>Made [a writeup](https://github.com/InfectedIsm/some-quizz/blob/main/Quizzes/4-%20Secureum%20-%20Pitfall%20%26%20Best%20Practices.md) of the "Pitfalls and Best Practices 101" Quizz from Secureum
>I remember few weeks ago when I read it and was a bit lost. This time I rolled over it 🚄
>I think that next week I will go over Securem RACEs

#### DAY 17 : 18-fev-2023

>Today I studied the writeups from @deliriusz_eth on the 2 bugs he found : [https://twitter.com/deliriusz_eth/status/1626577338019495936](https://twitter.com/deliriusz_eth/status/1626577338019495936)
>Thought it would be a great way to apply my fresh foundry and cloned his repo with the poc to study them

#### DAY 16 : 17-fev-2023

>Today I continued working the Foundry Book
>I really like the UI and all the tools
>Will I become a Foundry devout when I'll finish it ?..

#### DAY 15 : 16-fev-2023

>- Started the Foundry Book. I know this is the tool to-go for auditing and testing smart contracts. Nearly every POCs are based on Foundry
>
>The Foundry Book : [https://book.getfoundry.sh](https://t.co/1ZylTfE9Au)
>
>I've been using hardhat for a long time, but reading the doc I see why Foundry is prefered. The integrated tools are really powerful : gas tracking, detailed callstack, fuzzing,  forking, evm debugger, ... That's INSANE
>
>- Started a Notion list of findings with tags and associated vulnerability
>
>Notion list of findings: This idea came from [@andyfeili](https://twitter.com/andyfeili) videos and interviews. I was feeling too "passive" while reading the audits. Filling up this database with findings, trying to sort them by type and type of vulnerability will certainly help a lot to learn them better!

#### DAY 14 : 15-fev-2023

>Today I studied the last hacks from Block Threat Intelligence 
& Started to read the PoolTogether C4 contest thanks to an initiative on the [@Web3SecurityDAO](https://twitter.com/Web3SecurityDAO)
>
>consisting in reading a report each week (which fits exactly with my todo on day8 !)

#### DAY 13 : 14-fev-2023

>I finally found the solution for #11 Backdoor challenge!!
What a relief, what a feeling.
Struggling during multiple sessions, thinking that you got the solution, but finally not...
But after each try, feeling that you're closer than before
>
>I really liked this challenge because I was forced to explore in details how the Gnosis Safe works, function after function, deeper and deeper. Damn Vulnerable Challenge are insanely well written, I can see the gradual progression. [@tinchoabbate](https://twitter.com/tinchoabbate) did an amazing job

>If you haven't already started doing CTFs, don't be afraid and jump into it. I like to take my time with CTFs and document myself a lot on related topics during the exercise, to get the most of it in term of knowledge.
>I'll probably go to code4rena once I'll finish them!

#### DAY 12 : 13-fev-2023

>Small day, just continued worked on the DVChallenge #11 Backdoor
I've found the solution, need to finish coding it
Compared to previous challenges, this one require us to explore a big codebase to find the solution. I really like the gradual step-up!
>
>Aaand, finally while in bed… I found [a great article](https://t.co/tHK3yJd33D) on formal verification applied to solidity code
>
>Formal verification determine whether a given logical formula can be true or false based on a set of rules. We must not forget about these tools

#### DAY 11 : 12-fev-2023

>I continued exploring Gnosis src.
>Very interesting, they uses a "module" system, where a Safe is first a very simple contract-wallet w/ limited capabilities. But users can dynamically activate modules and execute their code : [https://github.com/safe-global/safe-modules](https://github.com/safe-global/safe-modules)
>
>I also learned about EIP712 (not 721) because it is used by Gnosis.
>This standard allows wallets to display data in signing prompts in a structured and readable format
>
>[https://eips.ethereum.org/EIPS/eip-712](https://t.co/oisSIVD0c5)

#### DAY 10 : 11-fev-2023

>Today I started the Backdoor #11 challenge [https://damnvulnerabledefi.xyz/challenges/backdoor/…](https://t.co/4J3aFnG09n)
>
>Then I got lost in articles and docs about Gnosis Safe contracts
>
>Found out a lot of protocol make use of these, so it is important for an auditor to get a good >grasp on what it is, how it works, what vulnerabilities exists. For example, [here is a list of >countermeasure against MEV](https://t.co/d3RP91CI33) on Safes Tx 
>
>Found myself pretty lost for now in this challenge, simply because I still don't understand how >to interact with a safe in the first time. The Gnosis Safe documentation is way less helpful than >the Uniswap V2 one.
>I'll have to read the solidity code then!..

#### DAY 9 : 10-fev-2023

>I decided to continue reading articles and docs (links shared in next posts)
>
>- Went over all items of BlockThreat (a web3 sec newsletter) "Hacks" section
>
>[@blockthreat](https://twitter.com/blockthreat) share a weekly [newsletter](https://newsletter.>blockthreat.io/p/blockthreat-week-5-2023) about web3 security. A great way to keep yourself >informed of latest hacks, vuln, tools, or great articles.
>This week, oracle manipulation, reentrancy, business logic issue, ... 
>Will assuredly continue to read
>
>- Read the "awesome-oracle-manipulation" repo (0xcacti)
>
>Stumbled over this great repo sharing interesting readings about oracle manipulation :
>
>[https://github.com/0xcacti/awesome-oracle-manipulation…](https://t.co/1N27u94xhX)
>
>Went through most of them, but as always, you click a link, then from this link you click 10 >other links... Web3 security is really prone to rabitholing
>
>- Documented myself about oracles
>
>From these links, I really link Euler serie on oracles, they're easy to read. It emphasis on >Uniswap pools oracle (TWAP :Time-Weighted Average Prices) and its limits
>part 1: [https://eulerlabs.com/blog/prices-and-oracles…](https://t.co/5KT8ebNgKu)
>
>part 2: [https://eulerlabs.com/blog/moving-average-filters](https://t.co/ACkNfUFwNB)
>
#### DAY 8 : 9-fev-2023

>I've never been so consistent in my learning, this challenge helped for sure !
>Today :
>
>- Read EVM Deep Dives Part 3 on Storage
>
>Before reading part 3, I went back to part 2 to be sure it was fully understood. Part 3 was >really cool, love how ingenious is the process to read packed variables, using bitwise and shift >operations : )
>
>- Read my first code4rena audit => Papr
>
>I finally read my first code4rena audit ! I tried to chose a pretty recent one : Papr (small >codebase). I still have to read the H findings, but I have read and understood the rest !
>Will try to implement this as a routine : read least 1 audit a week
>
>What I really liked too is that I did not only learn about security issues, but also how the >findings are rated, discussed, and demonstrated.

#### DAY 7 : 8-fev-2023

>Today I published [my writeup for the Challenge #7](https://coinsbench.com/>damn-vulnerable-defi-challenges-7-compromised-9ada74bc42fe) from Damn Vulnerable DeFi.
>I've already completed the #10, but I'm a bit late on my articles, but at the end this is a great >way to refresh my memory !

#### DAY 6 : 7-fev-2023

>Today :
>
>- I implemented the solution to #10 Free Rider from Damn Vulnerable DeFi, this is a step further from the previous challenges, loved it
>
>I think this challenge goes a step further as the solution require more research and reading outside of the challenge contracts themselves.
>Can't wait to discover #11.
>But first I need to catch up on my [CTF write-ups](https://medium.com/@infectedf)
>
>- Read through the EVM deep dives post from Noxx substack
>
>Noxx blogposts are incredibly well written, a go-to if you want to understand how solidity is compiled into opcodes, and how the EVM work through this.
>I don't know who created the EVM Playground but his work is a gift to us, learners!

[https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy-d6b](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy-d6b)

#### DAY 5 : 6-fev-2023

>today i read the Uniswap V2 whitepaper + a great blogpost from [@samczsun](https://twitter.com/samczsun) on oracles price manipulation (i’m sharing it at the end)
>
>Very well written, i prefered reading the whitepaper over the documentation, as all choices are explained, great reading from an auditor standpoint. 100% recommended to read it : [https://docs.uniswap.org/whitepaper.pdf](https://t.co/2q5FgcaMEh)
>
>The note [3] from this whitepaper leads to a great blogpost from samczsun on an oracle price manipulation, but i would like to share it another one from his blog which sumarize this topic + gives hints on how to mitigate these risks : gold!

#### DAY 4 : 5-fev-2023

>Went back to #10 free-rider from Damn Vulnerable DeFi this morning, eat, thought about it whil eating, took a train for a 3h travel, and found the solution!
>This challenge forced me to dig into UniV2 documentation, I feel way more confident about it now!

#### DAY 3 : 4-fev-2023

>Today I spent most of my time on challenge #10 from CTF Damn Vulnerable DeFi : [https://www.damnvulnerabledefi.xyz/](https://www.damnvulnerabledefi.xyz/)
>If I can give you an advice : don't give up on these challenges, you will learn a lot if you solve them by yourself. I'm giving you an alpha from [@pashovkrum](https://twitter.com/pashovkrum) if you find something hard, most of your competitor will find it hard too first time. Make the diff and don't giveup
>My own advice : don't try to rush everything, do it on your own pace. My style is to follow my curiosity. This can slow you down, but on the long run you will get a lot more depth

#### DAY 2 : 3-fev-2023

>Finished my Solidity 201 Quizz writeup !
Will probably start next quizz tomorrow.
This is a great way to practice and learn when you don't have that much time on your schedule !

#### DAY 1 : 2-fev-2023

>A challenge started on Discord Web3SecurityDAO, its called #30daysweb3security 
>I was already trying to work each and every day on web3 security, but doing it publicly with a group can be very encouraging!
>Let's try to run this challenge !
>Today I'm continuing writeups of [@Secureum](https://twitter.com/Secureum) quizzes, a great way to test my knowledge and then fixing it in my mind by doing research and writing them !

[InfectedIsm/some-quizz](https://t.co/ivP1CjuDV8)

#### Before DAY 1
>- Started with CryptoZombies
>- Read Ethereum White Paper
>- Read Ethereum Workbook 
>- Read Solidity Doc
>- Then BuildSpace web3 course
>- Solved Lotteries and Math from Capture the Ether. I learned a LOT with these challenges (Remix, >Etherscan, and of course Solidity), I highly recommend them
>- Eats the Blocks 6-figures training (not the best one, wouldn't recommend it its based on 0.4.2)
>- Learned a bit of web deb with Angular and Typescript
>- Learned Truffle and Ganache, but didn't like it at all
>- Learned Hardhat, was way better
>- Wrote writeup to multiple quizzes (Rareskill, Secureum)
>- Read hundreds of articles/blogposts
