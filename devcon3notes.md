[devcon3](https://github.com/drandreaskrueger/devcon3)notes.md (follow link for twitterphotos)  status: Markdown formatted

# DevCon3 LiveStream

Notes of memorable talks.  

e.g. mentioned URLs & addresses  
e.g. youtube start positions (hours/minutes/seconds in the livestream archives) <-- this is the main usefulness.

Almost ALL of the talks in the DevCon livestream (Main Hall only). Yes, 35 hours of [binge-watching :-) ](https://twitter.com/j32804/status/926900616592490497) .

Beware: These notes contain only an idiosyncratic *subset* of talks. Roughly chronological. There were many more. Find them yourself (and if your favorites are missing, just add'em):
 
* https://ethereumfoundation.org/devcon3/agenda/
* https://www.youtube.com/channel/UCNOfzGXD_C9YMYmnefmPH0g

Purposes of this text:

* other people can already start watching now, even before the talks are edited and published. Thus the youtube URLs with exact HOUR:MINUTES:SECONDS links.  
* myself I will more easily find stuff later. 
* placeholders to perhaps insert more info about each talk  
* keeping the mentioned links somewhere. There is so much happening.  
  

There might be some more info in the chat https://gitter.im/ethereum-unofficial/devcon (please create an official chatroom).

What a pity my body was not in Cancun, but you can be sure - my mind was. Greetings from London.

Good night,  
Andreas Krueger

## Participatory
Not sure when/if I ever find the time to further edit this. So: 

* You just go ahead, and improve this if you want to; perhaps add your own notes, do a pull request, whatever. https://github.com/drandreaskrueger/devcon3  
* Just one wish: Please do not write their email addresses in cleartext, to hide them from spambots (search for (at) and you'll see). Thanks. 


#### News 2 weeks later: correct times, other people's TOCs
About the wrong times: It must have happened, because they had initially cut off the beginning of Swarm's and Fabian's talk; and when they later re-inserted that, everything got shifted. I have now corrected the wrong times, if you still find some, please tell me. Thanks.  

Moreover: There were many more than the 42 talks which I have mentioned here. [Ryan Yosua](http://www.ryanyosua.me/devcon-3-talks/) has gone through the pain of linking them all in his blog. Also, most of the yotube videos now have the beginning times as a comment.   


#### News 10 days later: *Mosaic* and *Markdown*
My [twitterphotos/](twitterphotos/) Mosaic got a lot of retweets, thank you very much.

I finally took the time to transform this .txt into a .md file. Feel free to further improve it.

#### News day 5: **twitter photos**
I have downloaded ~1000 of your beautiful [twitterphotos/](twitterphotos/) - thank you so much; that way we could see a bit more of Cancun too. Love the crocodile pictures. 

#### TODO
* Most urgent TODO: Markdown formatting. DONE.
* making this strictly chronological  
* perhaps invent some scheme that all this can still be parsed afterwards?  

#### News day 4: *a few* times might be wrong now  (CORRECTED)   

Arrrghh. They seem to now have f**ked with their youtube videos, *grrr* sabotageurs. Some time positions like &t=3h20m30s were suddenly wrong.  

I have corrected them now.   
If there are still wrong times, then please you look up the correct times, and please fork this repo and send a pull request. Thanks a lot.

----

########################

N.b.: not strictly chronological yet.  (day 1 is further down)

########################

-----
Day 2
-----

#### Great tool: Puppeth - Péter Szilágyi.
DevCon talk - very worthwhile. 
Tool: Fantastic. Spin up your own ether-like blockchain in 20 minutes. 
geth based.
https://github.com/ethereum/go-ethereum/tree/master/cmd/puppeth
Incl:

* ethstats
* miner
* parity because blockexplorer
* webwallet
* faucet
* dashboard 
* with manuals for enduser how to connect

everything here he has deployed in front of our eyes, just now:
http://devcon.network/

you can watch that talk already: 

* https://www.youtube.com/watch?v=8sXzxkODH-c&t=3m

----------------------------------------------

Some interesting talks of today.

#### 1:00 pm - 1:40 pm Swarm Development Update
My notes:  
Part 4 of the SWARM talk. Encryption, Merkle tree "subdirectories"  
might be inspiring our own solutions ... (ACL) Access Control List for distributed systems...  

* https://www.youtube.com/watch?v=aMs0wAFIu7I&t=0h0m01s

----------------------------------------------

#### 2:00 pm - 2:20 pm The Future of Token Contracts - Jordi Baylina

MiniMe & ERC223 = YogaToken  
EIP672 reverse ENS, EIP165  
Governance, LiquidPledging  
https://ethereumfoundation.org/devcon3/sessions/token-contract-explorations-minime-reconstructing-balances-erc223-and-more/  
giveth.io  

* talk begins here https://www.youtube.com/watch?v=aMs0wAFIu7I&t=1h00m47s popular guy, seemingly  
Summary https://www.youtube.com/watch?v=aMs0wAFIu7I&t=01h17m10s  

--------------

possibly have to add 23 minutes to YT positions? (DONE)

-----------------------------------------------------

#### 2:20 pm - 2:40 pm Designing Future-proof Smart Contract Systems - Jorge Izquierdo (Aragon ICO) 
solidity - concepts & tricks for upgradeable contracts  
wiki.aragon.one  
aragon.chat  

* begins here: https://www.youtube.com/watch?v=aMs0wAFIu7I&t=1h19m00s  not ?v=aMs0wAFIu7I&t=0h55m20s  

----------------------------------

#### etherscan.io 
##### 2:40 pm - 3:00 pm Exploring the Ethereum Blockchain Matt Tan & Wee Chuan Tan

*This talk is about my experience building and using a block explorer for the Ethereum blockchain, which will provide a statistics highlight of the Ethereum blockchain and demographics of the Ethereum user base. The demographics portion will based on analytical data generated over the past years from Etherscan.io, which will assist new/existing developers on building a better user experience by first understanding who their potential target audiences are.*

* https://www.youtube.com/watch?v=aMs0wAFIu7I&t=1h35m15s

1st part: interesting numbers  
2nd part: geth vs parity  
3rd part: google analytics of us users "user persona"  

----------------------------------

#### 3:30 pm - 3:55 pm Panel: USCC – The Underhanded Solidity Coding Contest - Nick Johnson & Martin Swende & João Gabriel Carvalho & Richard Moore

* (?v=aMs0wAFIu7I&t=2h05m55s now wrong, add 25 minutes) https://www.youtube.com/watch?v=aMs0wAFIu7I&t=2h30m43s

tricky solidity/EVM vulnerabilities

all 4 could be hired for smart contract code audits ?

-----------------------------------------------------------

#### 4:40 pm - 5:00 pm The Raiden Network - Augusto Hack & Jannik Luhn & Loredana Cirstea

* https://www.youtube.com/watch?v=aMs0wAFIu7I&t=13523s (not ?v=aMs0wAFIu7I&t=3h20m30s)

how to build applications on top  
API calls, WebUI; Ropsten  
microRaiden on Kovan  
use cases: demo.micro.raiden.network & robocar  
 
brainbot.com  

--------------------------------------------------------

other memorable presentations of today (had made no notes, just going through the agenda https://ethereumfoundation.org/devcon3/agenda/ now):

--------------------------------------------------------

#### 9:00 am - 9:20 am Developers, Developers, Developers – Ethereum for all your networks! Péter Szilágyi
* https://www.youtube.com/watch?v=8sXzxkODH-c&t=0h3m0s


#### 10:25 am - 10:45 am The EVM: Cleaner, Meaner, and Closer to the Metal - Dr. Greg Colvin
* https://www.youtube.com/watch?v=8sXzxkODH-c&t=1h20m22s  
https://www.youtube.com/watch?v=8sXzxkODH-c&t=1h23m02s

#### 5:00 pm - 5:20 pm Towards a Permanent ENS Registrar - Nick Johnson
* https://www.youtube.com/watch?v=aMs0wAFIu7I&t=4h4m50s

SUMMARY OF TALK: https://medium.com/@enslisting.com/ens-talk-at-devcon-3-the-unoffical-summary-66afdb2247d1

---

and of yesterday, Day 1:

#### 9:55 am - 10:20 am Ethereum in 25 Minutes, Version MMXVII - Vitalik Buterin
* https://www.youtube.com/watch?v=Yo9o5nDTAAQ&t=49m35s until  
https://www.youtube.com/watch?v=Yo9o5nDTAAQ&t=1h13m55s 
= less than 25 minutes


#### 1:55 pm - 2:15 pm  Package Management for Smart Contracts - Piper Merriam
He is the Python Web3.py guy  
Far reaching concepts for a package management system.  

* https://www.youtube.com/watch?v=Yo9o5nDTAAQ&t=4h48m42s

--------------------------------------------------

was `?v=Yo9o5nDTAAQ&t=0h20m40s`  s\*\*t, have they swapped out the YT video file now?   Will all hour:minutes:seconds break now?  \*grrrr\* that means a lot of confusion. New beginning time: https://www.youtube.com/watch?v=Yo9o5nDTAAQ&t=4h48m42s   

--------------------------------------------------

EDIT: 
'enslisting.com' wrote a summary of the ENS talk, mentioned above.

Plus:
'Argongroup.com' tried a summary of day 1:
https://medium.com/@argongroup/8-things-we-learned-devcon3-day-1-858681157db1


--------
Day 3
--------

INCOMPLETE! Just some talks that I liked...

----------------------------------------------------------------

#### 9:00 am - 9:20 am Intro to Solidity (2017 edition) Hudson Jameson
good intro for very beginners  
solgraph !  
slides https://hudsonjameson.com/speakingengagements/  

* https://www.youtube.com/watch?v=k42YNyvG8CU&t=00h00m030s

--------------------------------------------------------

#### 9:20 am - 9:40 am  Flexibility in Solidity Dr. Christian Reitwiessner
SMTchecker!  

* https://www.youtube.com/watch?v=k42YNyvG8CU&t=00h17m30s

---------------------------------------------------------

#### 9:40 am - 10:10 am Mist: towards a decentralized, secure architecture - Everton Fraga & Victor Maia
Mist Browser!   
* https://www.youtube.com/watch?v=k42YNyvG8CU&t=00h36m17s   


#### Where is the decentralized Web - Moon project - Victor Maia  
http://moon-browser.org/  !!!  IPSF !   

* https://www.youtube.com/watch?v=k42YNyvG8CU&t=00h56m42s

-------------------------------------------------

#### 10:30 am - 10:50 am DappHubb - Andy Milenius
nixos.org  
seth !!  
Dappsys  
DSAuth !!  
DSToken  
https://dapp.tools/  
https://dapphub.com/  

* https://www.youtube.com/watch?v=k42YNyvG8CU&t=01h31m05s

-----------------------------------------------

#### 10:10 am - 10:30 am Dapp Development using Remix, Mist, and Geth - Yann Levreau & Rob Stupay
remix solidity IDE  !  
now with themes :-)  

* https://www.youtube.com/watch?v=k42YNyvG8CU&t=01h11m21s

---------------------------------------------------------------------

#### 11:10 am - 11:30 am MetaMask: Dissecting the fox - Aaron Davis & Frankie Pangilinan
kyokan.io  
state of the dapps metamask support  
metamascara !  
Mustekala: ethereum & IPFS  
hello (at) metamask (dot) io  

* https://www.youtube.com/watch?v=k42YNyvG8CU&t=02h12m42s

-----------------------------------------

mentioned somewhere:

* https://beakerbrowser.com/
* https://github.com/ssbc/patchwork https://www.scuttlebutt.nz/

---------------------------------------------------------

#### 1:00 pm - 1:20 pm Web3.js 1.0 - Fabian Vogelsteller
http://frozeman.de/blog   @frozeman  
version v1.0 many news  
Promises !  
web3.eth.subscribe !  
myContract.methods.doSomething() --> send, on('change'), etc.  
web3.eth.accounts  
web3.utils  
web3.utils.soliditySha3  
...  

* https://www.youtube.com/watch?v=FPHXbJPVVaA&t=00h00m00s (now NOT stupidly cut off by youtube anymore ;-) )

-----------------------------------------------

#### 1:20 pm - 1:40 pm Missing Links in the Ethereum Stack - Jack Peterson   
Augur  
bounties for tools wishlist https://augur.net/bounties/  
e.g. 2000 REP for portable debugger  

* https://www.youtube.com/watch?v=FPHXbJPVVaA&t=00h18m44s (not ?v=FPHXbJPVVaA&t=00h03m07s)

--------------------------------------

#### 1:40 pm - 2:00 pm EthJS – Precision Ethereum Javascript Architecture for dApps - Nick Dodson
https://github.com/ethjs/ethjs-schema  
complete Ethereum RPC specification as a JSON object !! inputs, outputs ...  
Why EthJS?  
frustration about / criticism of web3.js  

* https://www.youtube.com/watch?v=FPHXbJPVVaA&t=00h42m02s (not ?v=FPHXbJPVVaA&t=00h26m15s)

-------------------------------------------------------

#### 2:00 pm - 2:40 pm - Panel: Development Frameworks
very interesting discussion  
Iuri Matias  
Andy Milenius  
Conor Svensson  
Yann Levreau  
Nick Dodson  
Jack Peterson  
Piper Merriam  
who else?  

* https://www.youtube.com/watch?v=FPHXbJPVVaA&t=01h1m32s (not ?v=FPHXbJPVVaA&t=00h45m27s)

---------------------------------

#### 2:40 pm - 3:00 pm Uport – Usable Key Management for Multiple Identities Across Multiple Chains - Michael Sena & Rouven Heck & Pelle Braendgaard
onboarding, userfriendly  
identity management ACROSS chains  

* https://www.youtube.com/watch?v=FPHXbJPVVaA&t=01h37m39s (not ?v=FPHXbJPVVaA&t=01h21m27s)

---------------------------------

#### MUSIC
* https://www.youtube.com/watch?v=FPHXbJPVVaA&t=01h41m30s until  
https://www.youtube.com/watch?v=FPHXbJPVVaA&t=02h12m03s

-----------------------------------------------

#### 3:30 pm - 3:50 pm - Data is the Missing Link - Tim Nugent & Sam Chadwick
Thomson Reuters  
https://developers.thomsonreuters.com/blockchain-apis/blockone-iq-ethereum  
https://blockoneiq.thomsonreuters.com/  
private chains only !  
SPX, Libor, S&P500  
https://blockoneid.thomsonreuters.com/ address mapping, user id, ...  
permID.org identifiers for entities e.g. industry symbols that get recycled  
data coverage, e.g. electricity & gas prices  
if we need other data sets, we can ask then they'll provide  

not ?v=FPHXbJPVVaA&t=02h12m03s arrgghh this YT channel F**KED UP their videos!!!  &t=02h12m03s becomes now:  

* https://www.youtube.com/watch?v=FPHXbJPVVaA&t=02h29m40s == add 17.5 minutes

-----------------------------------------------------------

#### 2 talks oracle <-> trusted hardware: TownCrier, Oraclize
* https://www.youtube.com/watch?v=FPHXbJPVVaA&t=02h48m54s (not ?v=FPHXbJPVVaA&t=02h31m28s)

##### 3:50 pm - 4:10 pm Secure Decentralized Oracles: Applying Intel SGX and TownCrier to external data, payments and off-chain computation - Sergey Nazarov
https://link.smartcontract.com/whitepaper  

##### 4:10 pm - 4:30 pm Scalable Onchain Verification for Authenticated Data Feeds and Offchain Computations - Thomas Bertani

-------------------------------------------------------------------------

#### 4:50 pm - 5:20 pm Mind the Gap: Application-driven evaluation of Smart Contract languages - Andrew Miller
professor at UIUC  
ETH vs BTC: time & money complexity comparisons  
Lottery mechanism. time lock: Claim-or-refund. Tournament scheme.  
Payment channels. BTC: Timeout must be incremented per participant. ETH global registry.  
Poker: ...  
Even raiden has not used Ethereum perfectly yet?  

* &t=03h30m45s WRONG, NOW: https://www.youtube.com/watch?v=FPHXbJPVVaA&t=03h49m00s

---

##########################################################

### people wrote summaries, please add more

#### Day 1
https://medium.com/@grigano1/devcon3-day-1-in-review-ac0d16f6af7f  
https://davidburela.wordpress.com/2017/11/02/devcon-3-report-day-1-core-systems/  
https://medium.com/@argongroup/8-things-we-learned-devcon3-day-1-858681157db1  
https://medium.com/@brandon.obrien/ethereum-devcon3-summary-day-1-1de50737d40  


#### Day2
https://davidburela.wordpress.com/2017/11/03/devcon-3-report-day-2-core-systems/  
https://medium.com/@grigano1/devcon3-day-2-in-review-eth-all-star-presentations-colvin-not-drinking-kool-aid-raiden-ens-d57b15e2eced  
https://www.ethnews.com/devcon3-day-2-morning-brief-a-big-day-for-wallets  
https://www.ethnews.com/devcon3-day-2-afternoon-recap  
https://medium.com/@brandon.obrien/ethereum-devcon3-summary-day-2-b45832d7d748  

#### Day3
https://www.ethnews.com/devcon3-day-3-recap  
https://medium.com/@brandon.obrien/ethereum-devcon3-summary-day-3-c374c1dd9f48  
https://davidburela.wordpress.com/2017/11/04/devcon-3-report-day-3-dapp-development/  

#### Day4
https://medium.com/@brandon.obrien/ethereum-devcon3-summary-day-4-a5e87829164e  
https://www.ethnews.com/devcon3-day-4-recap  
https://davidburela.wordpress.com/2017/11/06/devcon-3-report-day-4-p2p-tech/  
https://davidburela.wordpress.com/2017/11/06/devcon-3-report-day-4-p2p-tech/  

#### Twitter
https://twitter.com/search?f=tweets&q=%23Devcon3  
https://twitter.com/search?f=tweets&q=%23Devcon  

#############################################################

---


------
Day 4 
------

#### 9:00 am - 9:25 am Whisper: Achieving Darkness - Vlad Gluhovsky

privacy !  
everyone tries decrypting everything  
padding with randoms for short messages  
hide message in padding !  
gitter.im/ethereum/whisper   
gitter handles: Vlad @gluk256 and Guillaume @gballet  

* https://www.youtube.com/watch?v=vXVcuWvR5Z0&t=00h00m20s
  
--------------------------------------------  
  
#### 9:25 am - 9:45 am  Using Whisper and IPFS to improve customer experience in a P2P marketplace - Michael Thuy & Stefaan Ponnet  
  
"gas station" for ERC20 tokens  
github.com/swarmcity  
github.com/ipfsconsortium  
github.com/swarmcity/gasstation-service github.com/swarmcity/sc-gasstationclient github.com/swarmcity/gasstation-demo  

* https://www.youtube.com/watch?v=vXVcuWvR5Z0&t=00h24m07s  
  
---------------------------------------------  
  
#### 9:45 am - 10:00 am The Data Mechanics of Saving the Planet - Gregory Landua & Risto Karjalainen
* https://www.youtube.com/watch?v=vXVcuWvR5Z0&t=00h44m04s  

"completely reversing climate change"  
incentivize carbon sequestration  
www.regen.network  
  
--------------------------------------------------  
  
#### 10:00 am - 10:15 am Decentralised Autonomous Organization: Interal Platform for Climate Initiatives - Anton Galenovich, Ph.D. & Sergei Lonshakov  
* https://www.youtube.com/watch?v=vXVcuWvR5Z0&t=01h00m14s  
  
shift climate agreements onto blockchain  
carbon markets, environmental mitigation assets and liabilities  
http://dapp.ipci.io  
http://ipci.io  
info (at) ipci (dot) io  
http://aira.life  
  
-----------------------------------------------------  
  
#### 10:35 am - 10:50 am Blockchain for Humanitarian Assistance - Houman Haddad  
* https://www.youtube.com/watch?v=vXVcuWvR5Z0&t=01h23m14s  
  
world food programme  
UN agency, using private blockchain for cash transfers  
200,000 transactions, saved 98% on fees  
www.wfp.org  
houman (dot) haddad (at) wfp (dot) org  
video slightly spooky at &t=01h38m38s- ID via iris scan - with centralized database?  
  
-----------------------------------------------  
  
  
#### 10:55 am - 11:10 am IDbox – Cost efficient device for self-sovereign identity - Julien Bouteloup  
* https://www.youtube.com/watch?v=vXVcuWvR5Z0&t=01h44m25s  

London Hackathon early 2017  
now version v2 is ready  
open source 3D printer printed  
multimodal biometric identification - but no central storage  
papua new guinea - 90% no ID  
selling electricity via the IDbox  
ERC 725 / 735 = ERC:Identity  
Identity AIM (like ATM)  
Julien (at) Bouteloup (dot) com  
@bneiluj  
http://www.idbox.io/  
  
--------------------------------------------------  
  
#### 1:20 pm - 1:40 pm Kleros: Building a decentralized court system to arbitrate smart contracts - Clément Lesaege  
* https://www.youtube.com/watch?v=ugbRyZSPfYE&t=20h20m00s  
  
arbitrators, and how to select them  
info (at) kleros (dot) io  
https://github.com/kleros  
  
--------------------------  
  
#### 1:40 pm - 2:00 pm Building a decentralized sharing economy on top of Ethereum - Christoph Jentzsch  
* https://www.youtube.com/watch?v=ugbRyZSPfYE&t=00h40m00s  
  
Artik 7 device  
light client  
bike, microwave, washing machine rental  
appartment rental  
https://mvp.slock.it  
  
--------------------------  
  
#### 2:40 pm - 3:00 pm Dai Stablecoin - Andy Milenius  
* https://www.youtube.com/watch?v=ugbRyZSPfYE&t=01h37m30s  
  
MakerDAO  
dapp.tools  
purple paper haskell reference implementation  
https://makerdao.com  
  
--------------------------  
  
  
#### 3:30 pm - 3:50 pm Designing IoT Frameworks Using Ethereum - Shuang Liang & John Gerryts  
* https://www.youtube.com/watch?v=ugbRyZSPfYE&t=02h30m09s  
  
Toyota Research Institute  
short video with good summary at ... &t=02h45m30s  
trusted-iot.org  
Blockchain-Mobility.org  
info (at) OakenInnovations (dot) com  
OakenInnovations.com  
  
--------------------------  
  
#### 3:50 pm - 4:10 pm  The Energy Blockchain in 20 Minutes - Garrett MacDonald  
* https://www.youtube.com/watch?v=ugbRyZSPfYE&t=02h50m40s  
  
https://netstats.energyweb.org  
https://github.com/energywebfoundation/energyweb-client  
garret (dot) macdonald (at) energyweb (dot) org = @nontipo = @bitcoingarret  
brendan (dot) auroranetwork (dot) com = @auroranetwork  
  
pretty balancing visualisation at ... &t=02h57m20s  
open source  
genesis planned for early 2019  
PoA, 3.5 seconds block time, 2500 transactions/second   
  
----------------------------------  
  
  
  
--------------  
Day 1 addendum  
--------------  
  
some of the talks which I had missed because of (sleeping-in after) a long office day:  
  
  
#### 9:55 am - 10:20 am Ethereum in 25 Minutes, Version MMXVII - Vitalik Buterin  
* https://www.youtube.com/watch?v=Yo9o5nDTAAQ&t=49m35s until   
https://www.youtube.com/watch?v=Yo9o5nDTAAQ&t=1h13m55s   
= less than 25 minutes  
  
---------------------  
  
#### 3:30 pm - 4:00 pm Panel: Casper and Consensus - Elaine Shi & Emin Gun Sirer & Peter Czaban & Vlad Zamfir & Vitalik Buterin  
* https://www.youtube.com/watch?v=Yo9o5nDTAAQ&t=6h24m55s  
  
---------------------  
  
#### 4:00 pm - 4:20 pm Introducing the TrueBit Virtual Machine - Jason Teutsch  
* https://www.youtube.com/watch?v=Yo9o5nDTAAQ&t=6h58m48s
  
doge ethereum bridge, art project  
live on kovan testnet  
truebit.io - reddit medium github twitter facebook  
  
------------------------------  
  
#### 4:40 pm - 5:00 pm ZoKrates – A Toolbox for zkSNARKs on Ethereum - Jacob Eberhardt  
* https://www.youtube.com/watch?v=Yo9o5nDTAAQ&t=7h36m30s  
  
at the moment 1.6 million gas for 1 verification  
trusted setup phase --> breakout session Friday  
https://github.com/JacobEberhardt/ZoKrates  
Jacob (dot) Eberhardt (at) tu-berlin (dot) de  
  
------------------------------  
  
#### 5:00 pm - 5:35 pm A modest proposal for Ethereum 2.0 - Vitalik Buterin  
(not: Designing Maximally Verifying Light Clients and Sharding)  

* https://www.youtube.com/watch?v=Yo9o5nDTAAQ&t=7h55m35s  

https://github.com/ethereum/sharding  
  
  
  
----------------------------------------------------------  

----------------------------------------------------------  

----------------------------------------------------------  

## end
  
home of this file: https://github.com/drandreaskrueger/devcon3/  
  
contributors:   

* https://github.com/drandreaskrueger  
* [add your repo/name here]  
  
  
