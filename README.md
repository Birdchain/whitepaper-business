
# Birdchain - Business white paper
## The app that rewards

1. [Abstract](#abstract)
2. [Established business](#established-business)
3. [Birdchain. The app that rewards](#birdchain-the-app-that-rewards)
    1. [Raising value of the Token](#raising-value-of-the-token)
        1. [Streams of the Token](#streams-of-the-token)
        2. [GBI - Global Basic Income](#gbi---global-basic-income)
    2. [Overview](#overview)
        1. [What is A2P messaging and why it is important?](#what-is-A2P-messaging-and-why-it-is-important) 
        2. [Definitions, acronyms, and abbreviations](#definitions-acronyms-and-abbreviations)
        3. [MVP Overview](#mvp-overview)
    3. [Overall Description](#overall-description)
        1. [Product Perspective](#product-perspective) 
        2. [Tokenization](#tokenization)
        3. [Product Functions](#product-functions)
        4. [Constraints](#constraints)
    4. [User Flow](#user-flow)
        1. [Ads Subscriber](#ads-subscriber) 
        2. [Ads Provider](#ads-provider) 
    5. [Specific Requirements](#specific-requirements)
        1. [Netting](#netting) 
        2. [Escrow](#escrow)
        3. [Battery Life](#battery-life)
    6. [Backend Microservices Details and Functional Scheme](#backend-microservices-details-and-functional-scheme)
        1. [Operational Service](#operational-service) 
        2. [OAuth 2.0 Authentication](#oauth-2.0-authentication)
        3. [Proxy Service](#proxy-service)
        4. [Channel Builder](#channel-builder) 
        5. [Cold Storage](#cold-storage)
        6. [Hot Storage](#hot-storage)
        7. [Ethereum Operator](#ethereum-operator) 
        8. [Ethereum Manager](#ethereum-manager)
        9. [Administrative Service](#administrative-service)
        10. [Front End Applications](#front-end-applications) 
        11. [Mobile Applications](#mobile-applications)
    7. [Smart Contracts Details and Functional Scheme](#smart-contracts-details-and-functional-scheme)
        1. [Balance Storage Contract](#balance-storage-contract) 
        2. [Campaign Creation Factory Contract](#campaign-creation-factory-contract)
        3. [Ads Campaign Contract](#ads-campaign-contract)
        4. [Escrow Contract](#escrow-contract) 
        5. [Proxy Contract](#proxy-contract)
        6. [Token Contract](#token-contract)
    8. [Operations on Smart Contracts and Required Toolset](#operations-on-smart-contracts-and-required-toolset)
    9. [Server Setup](#server-setup)
    10. [Prioritization and Release Plan](#prioritization-and-release-plan)
        1. [Prioritization](#prioritization)
        2. [Release Plan](#release-plan)
4. [Token sale](#token-sale)
    1. [Soft and Hard cap's](#soft-and-hard-caps)
    2. [Purpose of the Token](#purpose-of-the-token)
    3. [Fund Allocation](#fund-allocation)
    3. [Are Birdchain tokens Securities?](#are-birdchain-tokens-securities)
    4. [Please Note](#please-note)
5. [Exchanges](#exchanges)
6. [Appendix](#appendix)

# Abstract

A team of the Birdchain is not a start-up. It is part of a parent company, named Vertex. Vertex is a profitable company with a team of experienced professionals, whose professionalism and skills were tested in action. The founding team has successfully co-launched several businesses.

<p align="center">
  <img alt="Vertex" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/BirdChain-Whitepaper-Vertex.png">
</p>
 
Birdchain is a decentralized application (Dapp) similar to instant messenger. The big difference is Birdchain will allow its users to make a monthly passive income. Simultaneously, Birdchain will provide companies with higher quality and better-priced services: A2P SMS distribution, content engagement, personal data marketplace and others. The main goal of the Birdchain app is to create internal economics, where its users can earn, transfer (to exchanges), or spend their BIRD tokens, without leaving the app. Birdchain will be developed exclusively for Android devices. 

All features of the Birdchain create strong BIRD token. It stands out with low initial cost and token flexibility as a unique currency with favourable viability.

The official app presentation is planned at the Mobile World Congress in Barcelona in 2019.

In short:
1) Birdchain is DApp that rewards;
2) The intelligent features system creates internal economics and allows people to earn and spend money on the app;
3) Dapps are the future of the blockchain. Everyone at the moment invests in protocols, rather than actual applications. A comparison: whether to invest in HTML protocol or an Uber app? 

**Join the ICO with the potential of real adaptability!**


# Established business
The team behind Birdchain has been a part of  [the European-based company JSC “Vertex”](https://rekvizitai.vz.lt/en/company/vertex/). In 2009, Vertex started our A2P SMS aggregation business, called [VertexSMS](https://vertexsms.com/?lang=en). Since then, [VertexSMS](https://vertexsms.com/?lang=en) has delivered more than 2.6 billion SMS messages globally for various international brands, including Western Union, SalesForce, TransferGo, and many others.

<p align="center">
  <img alt="Clients" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/BirdChain-Whitepaper-Clients2.jpg">
</p>
 
Vertex is a profitable company. In 2015, Vertex received an award for being the fastest growing ITT company in Lithuania. Vertex continued to grow in 2016. In 2012, Vertex was recognized as one of the fastest growing companies in Latvia.

In early 2015, Vertex was certified in information security management and received an ISO/IEC 27001 certificate. The certificate is adapted to all our businesses held in Vertex headquarters: dating sites, bulk SMS sending systems, and a rent-to-own company. Now, all these procedures are being applied to Birdchain.

The combined per country turnover and EBITDA of Vertex is growing every year. 

|  | Turnover | EBITDA |
| :--- | :--- | :--- |
2017* | 4-5M euro* | 20%* | * Estimations
2016 | 3-4M euro | 19% |
2015 | 3-4M euro | 17% |
2014 | 2-3M euro | 18% |
2013 | 2-3M euro | 17% |
2012 | 2-3M euro | 16% |

Vertex owns several brands and VertexSMS is one of them. Company founders gathered Birdchain team members from other brands, meaning the members of the Birdchain team know each other well and have been working together for years. This decision eliminates possibilities of the team not being able to work together and creates a healthy, creative, and productive working atmosphere.

Birdchain team members are individuals with a set of unique experiences to make Birdchain fly. Most of them have experience working in a global A2P SMS market and share extended know-how about regulations, key players, technologies, and other aspects. Other team members are experts in marketing, business development, law, and software development.

The founding team has successfully co-launched several businesses:

**Social network** with more than 1 000 000 unique users (flirtas.lt, flirts.lv, flirtak.pl, teidi.ee, and others). This business allowed our team to design and test new ways of advertisement. It exposed several unique user experience patterns to us, which led to developing very efficient campaigns. We learned a lot about software and app development in the user communication field. We will adopt this knowledge to the Birdchain app and service.

In 2013, we invested in **advanced microlaser manufacturer** (integratedoptics.com). Today, we manufacture the smallest lasers in the world, and our company is considered one of the most promising Eastern European start-ups. We have more orders for our lasers than we can manufacture.

**Retail**. In 2013, we launched the first in the region rent-to-buy service (bekredito.lt).

Birdchain team is led by [Ernestas Petkevicius](https://www.linkedin.com/in/epetkevicius), [Audrius Vrubliauskas](https://www.linkedin.com/in/outrum), [Aurimas Sabaitis](https://www.linkedin.com/in/sabaitis), [Marius Petrauskas](https://www.linkedin.com/in/mariuspetrauskas), [Joao Martins](https://www.linkedin.com/in/joao-martins-porto), [Arminas Keraitis](https://www.linkedin.com/in/arminas-keraitis-460a4a40), [Tomas Vitkauskas](https://www.linkedin.com/in/tomasvit6/), [Simas Radkevicius](https://www.linkedin.com/in/simonasrad), [Kristina Mataciunaite](https://www.linkedin.com/in/kristina-mataciunaite-41690b149), [Martynas Rackauskas](https://www.linkedin.com/in/martynas-ra%C4%8Dkauskas-b3648a14b), [Aiste Surutkoviciute](https://www.linkedin.com/in/aistesur), and [Zygimantas Vanagas](https://www.linkedin.com/in/zygimantas-vanagas).

<p align="center">
  <img alt="Team" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/Team%202.png">
</p>

### Advisors

**[Anatoly Ressin](https://www.linkedin.com/in/anatolyressin)** 

![Anatoly](https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/200xanatoly.png)

A founder of Fastr, a reading-training application development firm, and AssistUnion, which builds intelligent and performing web-enabled systems. Has been a team member of Civic as a contractor, senior software developer at C.T.Co and #Decent as a core developer. At the moment, he is a CEO of BlockVis, a company involved in organizing blockchain competence and education opportunities and structuring the blockchain market in Latvia and abroad.

**[Andreas Petrow](https://www.linkedin.com/in/andreypetrow)**

![Andreas](https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/200xandreas.png)

7+ years of experience working in financial services & data providing business. He is a leading Relationship Manager within Standard & Poor’s – improving client relations and consulting Asset Managers in Northern Europe. Andrey is developing and cultivating strategic relationships, maintaining and developing existing business at CEO-Level. By helping customers develop their businesses using advanced analytics, standing up financial-data analytical tools, creating and maintaining financial models, and onboarding compelling new datasets – growth is always a top priority. The focus lies on Portfolio Analytics and Quantitative investment approach.

**[Rob Eijgenraam](https://www.linkedin.com/in/robeijgenraam)**

![Rob](https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/200x-rob.png)

Rob Eijgenraam is an online marketing expert, founder of ICO Marketing company CryptoLeads.io, and a co-founder of Purple Minds. He is a speaker about cryptocurrency marketing and an organizer of crypto educational events. His passion for Bitcoin and Blockchain comes from a belief in open systems and a permissionless society and market place.

**[Paulius Petretis](https://www.linkedin.com/in/sauga)**

![Paulius](https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/200xpaulius.png)

Paulius Petretis is a Data Privacy and Information Security expert, guest speaker at various conferences and seminars, Trainer at exclusive training courses. Paulius manages VORAS Consulting which offers consultancy services including data privacy and information security management, social engineering and IT service management. Certification in CISSP-ISSMP, CISM, CGEIT, CRISC, CISA, PMP, CIW-SA!

**[David A. Cohen](https://www.linkedin.com/in/davidallencohen)**

![David](https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/200xdavid.png)

David A. Cohen is internationally renowned for his pioneering work in the Decentralized Software industry and recently in the Digital Currency and Blockchain industry.  David is working on next generation blockchain architectures such as Hashgraph, and is currently advisor to Hashgraph. David is a former IOTA Foundation member.  He is also working with FarmaTrust, WePower, Wireline.io, and other blockchain companies.  He is Founder of Dcntral.ai, a blockchain-based cybersecurity software company.

He was the founder and CEO of Infotility where he pioneered the “Grid Edge” unlocking multi-billion-dollar software markets and creating the industries first artificial intelligence-based software platform - GridAgents™.

David is a thought leader and has spoken at many venues such as MIT, TEDx, Consensus, Blockchain 100X and Singularity University.  He is an expert on Blockchain, Artificial Intelligence, Cybersecurity, and Edge Computing.

# Birdchain. The app that rewards
Birdchain is a decentralized app that will help people to make a passive income, while offering cheaper and better services to businesses. All the features and the demand for them are based on our work experience, insights, and knowledge.

The first version for commercial consumption will be complete in 6 months. After the ICO, it will receive money transfers and will be capable of earning income for the app holder. Our contributors can test the version first. We will consider their feedback and will improve our app and tune it in line with the recommendation for the perfect launching.

The first version of the application will hold an interface, enabling communication with friends and family, and a possibility to sell unused SMS and an opportunity to amass cryptocurrency from SMS messages. We will start with this feature because it has the highest potential of money earning initially. We have specialized in SMS delivery business for nearly ten years and hold a deep understanding of market specifics and SMS transmission technologies. Also, this will allow users to earn money from the first day.

The next step will be taking on the other features described in this WP, which will allow people to earn money: Content Engagement, Personal Data Marketplace, and 3rd party in-app mini games.

All methods of money earning will be based on the volunteering principle. App users can personally choose the means and amount of possible earnings.

We will officially present the app at the Mobile World Congress in Barcelona in 2019.

# Raising value of the token
Our goal is to create a strong token that would be useful for our contributors and could circulate in the world easily. We believe circulation and spread of the token is the key to its value. The more people and companies that use our token, the more it would be used, the stronger it will be. Here are key points that make BIRD token stand out:
1. **Low initial cost**. During the ICO, the BIRD will be sold at the lowest price to create a higher incentive for contributors.
2. **Token flexibility**. When the BIRD value and demand increases, it can be fragmented into 18 decimals to serve market needs. 
3. **Unique currency**. Exclusively, BIRD tokens are used for purchasing Birdchain A2P service and rewarding Birdchain app users, ensuring the BIRD token has a real demand. 
4. **Favorable viability**. To have a sustainable business, it needs only 100 000 app installs. Each phone can sell about 100 SMS per day on a conservative approach.
5. **High desirability**. Providing the possibility of an income to its users, the Birdchain App is highly appealing to the public. The more users that install the app, the more SMS flux it creates, meaning a faster BIRD rotation, demand, and appreciation.
6. New features and higher **BIRD circulation**. We will drive demand and circulation of BIRDs with new Birdchain features and services.
7. **Embracing the competition**. Our A2P SMS service will be appealing to all companies that look for lower SMS price and high-quality service.
8. Detailed **financial forecast**. Check it out here: [Finances](#finances)

## GBI - Global Basic Income
The main goal of Birdchain is to disrupt the A2P SMS market with blockchain technology to make it better, faster, more transparent, and fair-priced. However, we believe that, soon it will become obvious that Birdchain is much more than just a (r)evolutionary idea.

Birdchain will be the first (in the history of the world!) non-governmental initiative to create Global Basic Income.

Depending on a country and market activity, Birdchain app users should be able to earn up to 150 USD per month. This means Birdchain could create basic passive income for its users globally.

We see this feature as a huge marketing opportunity and a chance to stand out in the global market of messaging apps. However, Birdchain guarantees no revenue to Birdchain token holders or Birdchain app users.

# Overview
Architecture, performance management, and capacity planning of applications depends on the ability to model these distributed applications at design time as well as during normal operations. This paper specifies overall description and some details on the functional requirements of performance and architecture modeling of the Birdchain Network. These specifications include the need to model transactions consisting of multiple, nested, synchronous and concurrent client-server interactions using tractable techniques and best practice. Example of application model with a centralized backend is presented based on the past experience and as a result of the current research. Suggestions for future work concludes the paper.

Design planning of application architecture and performance becomes more demanding as the client / server paradigm is used in commercial enterprise applications now scales with the ability to decentralize the dataflow and implement cryptographically secured payment gateways based on battle tested blockchain technologies. Modelling of the distributed applications with a centralized core node is crucial for every new service before the development starts. This paper motivates the need for modeling capabilities for these applications, and specifies the functional requirements of performance modeling of commercial distributed-client / centralized-server applications based on available technology solutions and required centralized servers and databases.

## What is A2P messaging and why it is important?

An Application To Person (A2P) SMS is sent from an application — typically a web app — to a mobile subscriber. There are several types of the most popular A2P SMS:
* SMS notifications;
* SMS-based two-factor authentications;
* Automatic booking confirmations;
* One-time passwords;
* Loyalty programs and marketing messages.

Transactional SMS service is mostly used by social networks and companies to provide services of e-commerce and online retail, travel and transportation, financial services and payments, and gaming. Because of their effectiveness, promotional messages are sent by companies operating in almost all markets.

Some examples of a transactional SMSs:
* G-123456 is your verification code.
* Hair Salon appointment reminder: haircut tomorrow at 10:30AM with Charles. If you have questions, please call 0161 55.

<p align="center">
  <img alt="SMS stats" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/07.png">
</p>

You may wonder:
> Why do Facebook, Microsoft, Google, Apple and many other high-tech companies want to send SMS? Why would anyone want to use technology from the ‘80s?

Here is why:
* SMS is platform-independent;
* SMS is network-independent;
* SMS is geographically independent;
* SMS is non-proprietary;
* SMS is app-independent (no need to have an app to communicate);
* SMS requires no data subscription (roaming scenarios for example);
* SMS is by far the most standardized messaging technology.

<p align="center">
  <img alt="Phone users" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/06.png">
</p>

A2P SMS market is expected to grow by around 5% per year and reach $84 billion by 2024. The reasons for A2P growth:
* SMS is the most effective and the cheapest way to reach customers. 98 percent of people read an SMS within three minutes from receiving it, and SMS has the highest engagement rate compared to emails and OTT apps. 

| User Count    | SMS Cost | Email Cost | AdWords Remarketing* | Facebook  | 
| :---          | :---:    | :---:      | :---:                | :---:     |
| CPM**         | 30$      | 15$        | 30$                  | 52.5$     | 
| True View     | 98%      | 22%        | 80%                  | 60%       | 
| Real CPM***   | 31$      | 66$        | 37$                  | 87.5$     | 

* An increase in two-factor authentication and security via SMS. Today, personal data is transferred over the web more often than ever before. Seeking to add a security layer, two-factor authentication has become the go-to method for companies that aim to protect their users. Sending an SMS as an authentication has become very popular because customers usually have a mobile device on them at almost any moment.
* A 2-way authentication has a staggering 99.9% reachability rate across all mobile users, as long as the number provided is correct. It does not require an internet connection. Mobile bandwidth is enough to receive a two-factor authentication or marketing message. 
* No need to install additional apps. SMS messages can be received and read on any mobile phone in any network, almost anywhere in the world.

**In the ideal world**, when a business wants to conduct an SMS marketing campaign, it must contact aggregators. Aggregators are companies that mediate between businesses that WANT to send SMS and operators that CAN send them.  

<p align="center">
  <img alt="Ideal SMS path" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/IdeaWorld.png">
</p>

**In the real world**, it is not that straightforward.
![Real-world path](https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/09.png?raw=true)

As an independent aggregator, we see market flaws as opportunities for Birdchain. Birdchain makes the path of SMS sending as straight as possible.
![Path of the Birdchain](https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/10.png?raw=true)

**The problems:**
1. People have unlimited SMS plans which they do not use;
2. Companies overpay for the A2P SMS service and are constantly looking for opportunities to decrease the price.

**The solution:**
1. People can automatically sell their unused SMS to businesses via Birdchain instant messaging app. Companies get an up to 6 times cheaper service. People get paid for every single SMS sold.

![A2P SMS market growth](https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/04.png?raw=true)

## Definitions, acronyms, and abbreviations

* **Provider** - Ads content provider.
* **Receiver** - Ads content receiver.
* **Android & iOS Mobile Applications** - Application for mobile devices that acts as a messaging channels and Ethereum wallet. 
* **Web Portal** - Browser interface for senders to provide a way to start ads campaign, escrow funds for it and to monitor the campaign status.
* **Administration Application** - Application that provides a possibility for the administrative staff to avoid illegal campaigns. Also it provides a statistical information on users activities. Should be available from browser.
* **Birdchain network** - A set of microservices and different kind of databases to provide the core of the network and various caches to the final network clients - mobile applications, smart contracts and web portals. Birdchain network contains all required data inside to be fully functional and completely separated from any infrastructural components and administrational user interfaces.
* **Ethereum Smart Contracts** - Backend services provided inside the Ethereum ledger. All of them are custom services created by Birdchain developers to give a possibility to get rewards and exchange tokens and provide escrows.

## MVP Overview
he Birdchain MVP is a messenger application with the ability to share ads content between content providers and content receivers. The client side application is divided into two parts. 

* Mobile applications - iOS and Android apps - used by ads viewers
* Browser front end application - used by content providers
* Backend microservices - different services to provide viewers-to-providers communications and various infrastructural services like push notifications, ethereum services etc.

# Overall Description
This section will give an overview of the whole system. The system will be explained in its context to show how it interacts with other systems and introduce the basic functionality of it. It will also describe what type of users that will use the system and what functionality is available for each type. At last, the constraints and assumptions for the system will be presented.

## Product perspective
This system will consist of three parts: mobile applications - Android and iOS, one web portal for ads providers and a backend server - various microservices - with a database(s) and caches.

While the web portal will be used for managing user specific information on profile and payment details and administrative access for selected users. Mobile applications has minimum amount of information provided to Birdchain and super-fast sign up consisted from only one step - user phone number should be provided.

Backend server will contain current Birdchain network state including analytics, statistical information, administrative actions and various caches.

## Tokenization
BIRD token is an initial Birdchain token created with a purpose to provide an initial coin offering and to use the token into an application as a supply commodity. This is a plain Ethereum ERC20 token with the ability to use onto crypto exchanges and can be stored into any Ethereum wallet.

In Birdchain environment users can exchange token into obligations with Birdchain itself  to spread ads into receiver channels - all existing users of mobile applications.

## Product Functions
Mobile application is a gate to Birdchain network. It acts as a messenger where user can subscribe to channels, every channel is a filtered topic of ads available in the network. Filtering by the content and by the location gives a possibility not just to earn by reviewing ads content but, but also to be subscribed to a useful content stream. 

Ads content is a rich media with images and sound attached, all text is represented via HTML markup. User can view ads and get a reward. Also user can share it within Birdchain network or outside of Birdchain to Facebook, Twitter etc. Naturally every sharing should be paid to the user in BIRD token. 

*E.x. I’m a crypto evangelist and I’m interested in earning some BIRD tokens by viewing ads or sharing it, but also my interests are about new computer hardware prices on the market and in visiting blockchain related events. That’s why I have a separate channel in Birdchain messenger with all related ads beside all other. Probably I have a lot of blockchain related friends and I will be happy to share just posted crypto event ads with them.

<p align="center">
  <img alt="Mobile App" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/Mobile%20App%20Mocks.png">
</p>

Once user gets his BIRD token via viewing or sharing ads, the wallet inside the application can help to exchange BIRD into ETH and to withdraw it to any other Ethereum address. Based on the requirement of EIP20 token standard, user’s wallet is pretty straightforward and well known to all Ethereum users around the globe.

Thinking of future it’s natural to add a possibility to all users create its own ads right from the mobile application. That’s how a plain user can spend its BIRD tokens. This idea is well suited for a small business owners and public persons.

## Constraints
Since the interface is the same and is available on all phones - iOS and Android - there is no constraint in messenger usage. Since application doesn’t fetch new data offline, it is crucial that there is an Internet connection for the application to function.

Both the web portal and mobile application should not be constrained by the capacity of the database. Meaning all content should be fetched when app is online and stored inside the database for the future offline review. 

# User Flow
There are two types of the user - ads subscribers and ads producers. Both of the acting as a separate entities. But we specify that ads subscriber will be available to make actions belonging to ads producers in future releases.

## Ads Subscriber

<p align="center">
  <img alt="User Flow. Ads Subscriber" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/User%20Flow.%20Ads%20Subscriber.png">
</p>

Subscriber user flow starts from the sign up into the network. The only required field for sign up is a phone number. Birdchain will verify the phone number with SMS in future releases. Other options like email, gender, should be added optionally and have to be used for more targeted ads suggestion. 

Next app should ask a user for a passcode or fingerprint if available. It’s necessary to save valuable user information inside crypto secured storages - Keychain on iOS, Android Keystore System on Android.

Next user should select preferences for precisely targeted ads. Backend should provide ads content based on user preferences, his profile information.

Backend should create new public address for ETH and BIRD tokens. Both balances are available in settings for the work with them. User can withdraw BIRD or exchange BIRD into ETH and then withdraw ETH. User should be able to recover his account or create a new one with a mnemonic phrase. Note: mnemonic phrase never stored inside the application, this is a security reason and user should be warned.

Once all information has been entered, app started a socket connection with the server. Socket connection is only available when messenger feed is on screen. Otherwise connection will drain phone battery. Ads coming into the feed in the same fashion messages come into plain messenger applications.

User can preview ads, for every preview user get a reward on his BIRD balance. User can respond to the ads, response will be available to ads provider. User can share ads within his social accounts - Facebook, Twitter, etc. For every ads sharing user should get a reward.
User can withdraw received tokens or change them into Ethereum token in a wallet section of the application.

Settings section should provide user with all required inputs to change feed preferences, to filter incoming push notifications, to view a help information, terms of services and privacy policy of the application, to change user profile information, link social networking accounts. In future releases it should be possible to create several accounts and link them under the on super user. 

2-factors authentication nowadays is a must and should be provided to the user later. When available, all user information should be changed using it. For example to use a combination of pin code and a code sent to another user’s device.

## Ads Provider

<p align="center">
  <img alt="User Flow. Ads Provider" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/User%20Flow.%20Ads%20Provider.png">
</p>

Ads provider is a user who is willing to show ads in a selected region for users in a selected targeting scope. Provider should pay to Birdchain system with BIRD tokens or ETH tokens in order to submit a campaign. Campaign should fit into Birdchain’s Terms of Services.
First step to become a birdchain ads provider is to sign up on browser application and provide a user related information like email, password, first and last name etc. On sign up Birdchain shows a mnemonic phrase or uses a mnemonic phrase provided by the user to identify and link Ethereum address to specified account. In case when user doesn’t have a mnemonic phrase and accepts a new one, Birdchain should ask user to write it into a safe place in order to restore the account later.

After user have successfully signed in, he can start new campaign creation process. To begin a new campaign user should provide campaign details including transaction volume of the campaign. User should escrow BIRD tokens to his account, from this tokens receivers will get their reward for ads viewing or sharing. **There is no real transactions inside Birdchain network, but netting is used. Ethereum transactions happen only on withdrawal from Birdchain to external address.** This is how Birdchain can make transactions a way faster than in Ethereum ledger and avoid issues of paying the gas for every transaction inside the network.

All campaign ads should be provided as a rich media content consisted from HTML, image or even video and audio content.
Once the balance is less than one viewing fee, campaign stops. User can load more money to his address and proceed with the campaign, or to finish a campaign successfully.

User can withdraw BIRD or ETH tokens left after the finish of the campaign or after campaign has been stopped. In case user have been restored his account, all amount available in Birdchain is also available in his external wallets.

Additionally Birdchain can provide various cryptocurrencies as exchange functionality. Unfortunately there is no direct possibilities to exchange EIP20 tokens into other types of crypto beside connection to the external exchange API like Kraken or manually by system administrator.

# Specific Requirements
## Netting
There are 3 types of token transactions inside the system:
* User escrow BIRD token in order to create a new campaign. This transaction requires ETH token to be converted inside BIRD and BIRD token is escrowed inside correspondent smart contract. As the other options ETH escrowed without exchanging it into BIRD. And as the third option Birdchain can escrow the amount user wants to use in Birdchain network and assign virtual BIRD tokens which will be used inside the system. Every payment to the developer is a netting operation where there is no transactions happen inside Ethereum ledger but all calculations lay inside of Birdchain backend. Either way should be chosen but the third one will drastically reduce the amount of gas spent on transactions. In such a case transactional gas will be used only when user escrow the amount and withdraw the spend or the reward.
* The second type is a payment to ads viewers and sharers. In order to reduce the amount of gas we propose to change Ethereum transactions onto netting operations between providers and viewers.
* The third one is a withdraw operation. For viewers it happens when they have collected enough BIRD tokens to withdraw or exchange into ETH token. For providers it happens when there is a spend after campaign has been finished, or campaign has been cancelled and provider wants to get his money back.

## Escrow

Ads provider should be able to begin the campaign and in order to make ads viewers sure their actions will be paid, provider escrow the required amount to the corresponded smart contract on the full length of the campaign.

## Battery Life

Battery lifetime is critical when we use sockets in mobile applications. It’s very easy to drain the battery and force user to uninstall the application. Birdchain app should use socket connections only in the case of foreground mode with ads feed visible on the screen. All other communication should be provided as a plain REST queries. Also app should use push notifications to receive all valuable information requested by the user (all notification options are in Settings part of the app).

# Functional Requirements

This section provides all details on user interaction with the system. All user stories and possible use cases provided below with the reference to interface mockups.

## Backend Microservices Details and Functional Scheme

Here we provide backend decomposition and microservices overview. Core microservices included into Birdchain Network solution are:

<p align="center">
  <img alt="Microservices" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/Microservices%20Scheme%20v.2.png">
</p>

### Operational Service

**Warning: operational service should be architectured with a mind that it contains three different microservices - authentication, mobile messaging channels, campaign logic. This microservices should act separately and have to be splitted into three in future releases.

Operational Service represents the core logic of the entire backend. *This is an obvious component and should be done in the first milestone.* It handles all campaign and mobile communication infrastructure tasks:
* New campaign creation
* Campaign cancellation
* Campaign finalization
* Queries Ethereum network to deploy new campaign instance smart contracts
* Listens to Ethereum events
* Handles Ethereum exceptions and react on them
* Contains internal data storage with all current campaign states
* Update Birdchain database with completed, failed and cancelled campaigns
* Handles mobile messaging channels.

Operational Service consists of next components:
* **Task Manager** - contains all business logic of the Operational Service. Reacts on incoming messages from other microservices, handles internal data storage and changes a current state appropriately to users actions. Operational Service can update database. Task Manager send tasks to Campaign Creation Service. Task Manager has a direct connection with future Network Administrators Service in order to monitor the status of all ongoing operations and suspend, cancel and resume all tasks on any emergency. 
* **Campaign Manager** - serves to send new campaign creational requests to Ethereum Smart Contracts. Interoperate with Ethereum Manager Service; listens to Ethereum Manager on a successful campaign event.
Query Broker - a queue manager to avoid concurrent requests overloading. It can be any of battle-tested brokers - RabbitMQ, ZeroMQ, SQS etc.
* **Hot Storage** - plain in-memory key-value storage. All microservice state should stored in it and taken from it on the request. Because we use Elixir in a stack, it’s natural to use ETS (Erlang Terms Storage).
* **Cold Storage** - disk-based key-value storage. It should be used on process / service restarts to save data from Hot Storage and on data restore to Hot Storage. Elixir and Erlang stack provides DETS for it.
* **Repository API** - is a microservice that handles all incoming connections to Hot Storage. It manages communication between microservice and Hot Storage, it saves Hot Storage state to Cold Storage on a request or regularly within some discrete time. 

Operational Service always starts with initial state and contains current state that describes all available temporary data that helps to communicate between internal services.

Operational Service has next communication interfaces:
* **Instance API** - handles all communications between microservices inside Birdchain Backend. Instance API never talks to users and to any third party services outside Birdchain Network.
* **Management API** - handles all communication between entire microservice and Administrative Service(not described on the scheme above). Serves for microservice configuration and monitoring during its work. Task Manager is a single instance that uses this interface.
* **Ethereum Proxy** - handles all requests to Ethereum Smart Contracts and listens to all specified events from Ethereum network. Campaign Creation Service is a single instance that uses this interface.

### OAuth 2.0 Authentication

Birdchain authentication built on top of OAuth 2.0 protocol. We decide to use OAuth as a battle-tested technology available and well known for all platforms. More details on OAuth protocol can be found on the link below:
[OAuth Specification](https://oauth.net/2/)

### Proxy Service

Proxy Service represents a set of small microservices used primarily to handle incoming connections:
* **Router** - should be used to navigate incoming queries to corresponded microservices, each microservice has its own API. There is quite many APIs exposed to receive incoming connections that’s why one routing point becomes very useful.
* **Logger** - it’s a good practice to log everything is coming and going out, collect statistical information and Birdchain should do this at one point instead of on every API endpoint.
* **Rate limiter** - rate limiter should be used to guard possible attach vector related to DDoS attack.
* **Load balancer** - we have to use load balancers on every cluster of hardware servers in the network to be sure we can spawn new instances on warnings related to the lack of resources.
* **TLS terminator** - we propose to terminate HTTPS traffic before Birdchain network. We define all servers as private and there is no possibility for the man-in-the-middle attack or any other chances to take out valuable user information.

Proxy Service should be used for all incoming connections from client side applications excluding direct Ethereum connections.

### Channel Builder

Every user communicates with Birdchain network with its own ads channel. We propose to link user’s mobile application with a socket connection when user is online - than we can send ads like in all other messaging apps - immediately on ads appear. 

Channel builder represents a cluster of nodes linked to each other with a process registry. Every node runs thousands of processes that contain every user’s state - ads feed. Every user is always connected to such a process while he’s online and application is in a foreground mode. On application turned into background or stopped modes channel should persist for a short time and self-destroy saving its state into cold storage. On new user session new channel should be created restoring its state from the cold storage.

The best choice for such functionality is a Phoenix framework built on top of Erlang Virtual Machine. EVM is designed to handle millions of concurrent connections and mainly used in messengers and telecoms.

For interprocess communication it’s a good option to use Process Groups 2 (PG2) library from Erlang environment. 

### Cold Storage

To provide the best consistency of the data and fastest response, we propose to use relational PostgreSQL database for the cold storage. Beside it’s a battle tested database with marvelous amount of great features and extensions, there is a great support of it in Elixir community and it has libraries which are great in usage.

Database should be splitted into schemas according to microservices to provide multi-tenancy and future distribution and sharding - key features of the scale process.

### Hot Storage

As a hot storage for every microservice we propose to use Erlang native key-value in-memory storage ETS (Erlang Terms Storage) and its companion DETS as a filesystem backup of ETS. It has a native Erlang-Elixir support and provides super fast turnaround on reads and writes.

### Ethereum operator

Ethereum Operator is a transaction processing microservice. It sends requests to Ethereum ledger via Parity full Ethereum node laid inside the microservice. Also it listends events from it. 

Ethereum Operator microservice contains the next components:
* **Parity Node** - full Ethereum client node.
* **Sender Server** - sends requests to Ethereum Smart Contracts. 
* **Listener Server** - listens to Ethereum events and transfer them outside.

Ethereum Operator has next communication interfaces:
* **Parity Node**  - incoming and outgoing Ethereum connections;
* **Instance API** - access to Ethereum from outside of the microservice;
* **Event Generator** - event transferring gate. Microservices should connect via the socket to Event Generator and receive all incoming events. 

### Ethereum Manager

Ethereum Manager is a microservice contains specifications and their implementation in order to work with Ethereum Smart Contracts created specifically for Birdchain Network. Ethereum manager from the one side listens to Ethereum Operator for specified Ethereum Events, and from the other side sends requests via Ethereum Operator to Ethereum ledger.

Ethereum Manager microservice contains the next components:
* **Deque Manager & Contract Listener** - the service created with the reason to listen to events coming from Ethereum Operator and to enqueue them into the hot storage. Also it deque events from the hot storage sending them correspondent Birdchain microservices.
* **Contract Caller** - listens to incoming requests from Birdchain Network and pass them to Ethereum Operator. Listens for the OK response from Ethereum Operator.

Ethereum Manager has next communication interfaces:
* **Instance API** - access to Ethereum Manager inside Birdchain Network.
* **Socket Provider** - socket connections pool available in order to listen to incoming events.

### Administrative Service

Birdchain network should be monitored by administrative staff to avoid various illegal content. It should be done automatically by various filters and manually by accepting new campaigns and monitoring of their status. Also Administrative Service should contain all required tools to watch the health of servers and databases, receive information from Logger and statistical information from all other services. Administrator Service should use automatic tools to filter and cancel various malicious and illegal content sent by ads providers.

Administrative Service is an Elixir application running on a single node and providing REST API for administrative front end application. Administrative Service is communicating via REST with all other services, including database health checks and database content check. 

### Front End Applications

Front End Applications are ReactJS browser apps linked via REST API to Birdchain API. On the first stage of the development only ads providers will use browser front end to create new ads, get ads statistics and transfer their funds.

There are two different front end applications in the network:
* Ads provider application
* Administrator application

Both applications linked to their own API endpoints via REST protocol. For the local cache in browser we assume the usage of Redux and Local Storage. Same as mobile applications browser apps will use OAuth 2.0 protocol to establish stateless sessions with the server. In order to update information reactively we propose to use socket connections in future releases.

Design mockups should be provided before starting to build any of them, we’re following a convention - design first. In order to provide the best user experience Birdchain should have its own set of user interface React components library. All of them will be used in container components. 

Administrator Application should contain features required for monitoring and handling all cold storages available in Birdchain. Every storage should have its own component and interface to manage user’s data.

Administrative Application should have an interface to confirm new campaigns. Campaign should be confirmed only in a case when there is enough BIRD or ETH token sent to Escrow Contract.

Administrative Application should have all statistical information from microservices on user load, ip locations and others.

### Mobile Applications

There are two types of mobile applications - for Android devices and for iOS devices. We propose to use reactive architecture and Model-View-View-Model architecture for both of them in order to provide real time updates fetched via socket connection and plain HTTP REST endpoints. Socket connection should be used for ads stream only in order to save user’s battery lifetime.

iOS technology stack should be based on top of Swift programming language and contain next technologies: 
* ReactiveX (RxSwift) for the reactive architecture
* Core Data (SQLite3) for the local cache and permanent storage
* Core Location to determine user’s location for a better ads targeting
* Alamofire for plain HTTP requests
* Facebook’s Socket Rocket for socket connections.

Android technology stack should be based on top of Kotlin programming language and contain next technologies:
* Architecture Components to provide MVVM architecture into Android environment
* Room for the local cache and permanent storage
* Volley for HTTP requests
* Socket.io for socket connections.

## Smart Contracts Details and Functional Scheme

Birdchain network uses Ethereum ledger to provide users with a default payment gate based on ETH and BIRD tokens done on ERC20 (EIP20) standard. Birdchain is linked with Ethereum ledger via Operational Service and User Wallets. Smart contracts development should be provided by Solidity developer and fully tested manually and by providing automated unit testing use cases. It’s a requirement for any contract deployed into a blockchain ledger to be sure that even stochastic bugs are not presented in a code. Once contract has been deployed, there is no possibility to change or update it. It’s possible only to deploy a new contract with a new address and all state variables are empty. Such upgrades is a usual case of issues related to the next balance airdrops, balance lost or funds locks. Smart contract development should be done only by a highly skilled developer with obvious code review.

<p align="center">
  <img alt="Smart Contract" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/Ethereum%20Smart%20Contracts%20Functional%20Scheme%20rev.2.png?raw=true">
</p>

### Balance Storage Contract

Balance storage contract is a business model and its solidity realization that handles all current balances inside Birdchain network. Usually it’s a simple mapper between addresses and values linked to addresses. All balance related operations - transactions and getters should be settled into the contract too.

### Campaign Creation Factory Contract

Campaign creation factory is a contract which handles all required actions to deploy a new campaign contract instances into Ethereum network escrow contract instances. Every campaign has two separate smart contracts for handling all of transactions.

### Ads Campaign Contract

All campaign related functionality including related information data structures and various getters. Campaign contract is a parent contract for the Escrow contract and is able to act on user’s behalf and destroy both Escrow contract and itself.

### Escrow Contract

All escrow related functionality including withdraw, balance storage and various getters. Escrow contract is a mapper between campaign address and deposited tokens. 

### Proxy Contract

Proxy contract acts as a middleware between all Birdchain contracts and incoming requests. Proxy contract is a safety action in order to not to change initial addresses for backend and frontend queries to Ethereum. Once Birdchain dev team decide to upgrade the contract, there is no possibility to left initial contract address and simply swap the contract on a newer version. This is why we have a mapping between addresses available for the public and internal Birdchain contracts addresses.

### Token Contract

Token contract is a standard EIP20 (ERC20) contract created by Birdchain for the ICO with a BIRD symbol. Birdchain network will use BIRD for all transactions, BIRD is available in any Ethereum wallet.

## Operations on Smart Contracts and required toolset

The decision to use standardized ERC20 token gives a possibility to work with plain Ethereum wallets and with a toolset created for Ethereum. It’s straightforward to start using Web3JS library just from the browser using Metamask app (available on Chrome and Firefox) to directly communicate with Ethereum ledger and send transactions. 

Various Ethereum browsers like Mist and Parity are also available to communicate with Ethereum, they have all required toolset from the scratch, including Ethereum wallet and a full Ethereum node.

Android applications can communicate with Ethereum directly using Web3J library, it’s similar to Web3JS but is created on top of Java.
Development toolset should include Truffle framework, all contracts should be unit tested using JS testing environment - Mocha and Chai. All testing use cases and user stories for acceptance tests have to be described before smart contracts development started.

# Server Setup

In this section we describe rough setup of the server environment. This environment includes microservice clusters of nodes, required load balancing and various endpoints.

**TBD**

# Prioritization and Release Plan

## Prioritization

| Requirement ID | Title                                | Requirement Type |
|:--------------:|:-------------------------------------|:-----------------|
|                | Android Messaging Application        | Function         |
|                | iOS Messaging Application            | Function         |
|                | Ads Provider Web Portal              | Function         |
|                | Operational Service                  | Function         |
|                | Ethereum Smart Contracts             | Function         |
|                | System Availability                  | Quality          |
|                | Communication Security               | Quality          |
|                | System reliability and response time | Quality          |

## Release Plan	
The requirements were divided into three releases based on the prioritization and their dependencies. The three different releases were assembled so that each would work as a fully functional application.
			
In the first release the requirements that build up the foundation of the application were included, together with the most highly prioritized requirements and their dependencies.

# Token sale
Token sale will be implemented in several steps:
* Closed pre-sale (2018.01.01-2018.01.18)
* Open pre-sale (starting 2018.01.18)
* Main ICO event (2018.03.01-2018.05.31)

## Soft and Hard cap's

Soft cap of the ICO - **1,500 ETH**
Hard cap of the ICO - **10,500 ETH**

## Token distribution

* Maximum coin supply **580,263,158**
* Total ICO distribution **441,000,000**
* Team and founders **52,223,684**
* Involving corporate contributors and other expenses **87,039,474**

## Purpose of the Token
Birdchain token is NOT AN ASSET NOR A SECURITY. It is a utility token. Birdchain tokens do not represent or confer any ownership right or stake, share, security, or equivalent rights, or any right to receive dividends, other payments, intellectual property rights, or any other form of participation in or relating to the project described in this white paper and/or in Birdchain or any of its affiliates.
 
The Birdchain token holders are only entitled to use the A2P SMS distribution service as described in this document, if successfully developed, or to resell the tokens.

The BIRD token will be based on Ethereum, a blockchain-based computing platform. Ethereum allows smart contracts, distributed computer programs that can facilitate online contractual agreements in a cryptographically secure manner.

Smart contracts enable the existence of Birdchain token as a truly transparent and decentralized service. This technology also ensures Birdchain eliminates the need for intermediaries and having a central authority you must trust. Through smart contracts, the complex process of choosing peers, tracking delivery, and facilitating bidding/payment can be described in the contract, while running on the distributed Ethereum network and taking advantage of the blockchain features.

BIRDs are distributed and kept on the main Ethereum network. To optimize the transaction cost and performance, all micro transactions are processed off-chain, and only the final stakes are returned to the Ethereum network. We believe in the idea of keeping tokens on Ethereum and see it as a bank platform that is excellent for entering exchange markets.

![Token flow](https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/BC-node2.png?raw=true)

## Fund allocation
![Birdchain Finances](https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/FinancialForecast.png?raw=true)
![Birdchain Finances 2020](https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/FinancialForecastSummary.png)

## Are Birdchain tokens Securities?
**No**, Birdchain tokens are not and are not intended to be securities, financial instruments, or investment products of any kind.

For example, for the purposes of financial regulation in the European Union, a “security” is often defined with a reference to “transferable security” within the meaning of the EU Directive on markets in financial instruments (MiFID). According to MiFID, “transferable securities” means those classes of securities negotiable on the capital market, with an exception of instruments of payment, such as:
1. shares in companies and other securities equivalent to shares in companies, partnerships or other entities, and depositary receipts regarding shares;
2. bonds or other forms of securitized debt, including depositary receipts regarding such securities;
3. any other securities giving the right to acquire or sell any such transferable securities or giving rise to a cash settlement determined by reference to transferable securities, currencies, interest rates or yields, commodities or other indices or measures.
  
BIRD does not qualify as “transferable security” for the above purposes.

BIRD, as a utility token, will only provide opportunity to access Birdchain services. The aim of the BIRD is to make it possible to exchange SMSs between the people wishing to access them and the people wishing to dispose extra SMSs.

The BIRD has a specific utility use case. It serves a crucial role in settlement-making with a potentially very large number of mobile phones on the Birdchain network by allowing a fast and open blockchain-based transaction protocol that would not be possible using fiat currency. If the BIRD was not based on blockchain technology, it would be similar to purchasing a ticket or any other document that proves the person may use a particular service.

## Please Note
In this white paper, references to “Birdchain”, “we”, “us” or “our” are to [Birdchain OÜ](https://www.e-krediidiinfo.ee/14362929-BIRDCHAIN%20O%C3%9C?lang=en), a company incorporated under the laws of Estonia with registry code 14362929, and references to “BIRD” or “Birdchain token” are to blockchain tokens created by Birdchain in connection with the project described in this white paper. Sometimes, the term “Birdchain” has been used to refer to the service proposed to be developed by us.         
 
We will announce the date of BIRD sale and all related details on our official website: www.birdchain.io. The rights and obligations of the holders of BIRDS and Birdchain as the issuer will be governed by the terms and conditions of the Birdchain token, which will be available on the same website, and the Estonian law. Please carefully follow the instructions stated on the website to avoid being scammed. Birdchain tokens are not securities or any other form of investment in any jurisdiction. The sale of tokens should not be considered offering of securities or as investment advice, solicitation, or an endorsement of any kind. Any persons deciding to acquire Birdchain token must do this at its own risk and discretion following a thorough analysis of the risks associated.

Nothing in this whitepaper or in any other materials put forth by Birdchain or any other third person acting on behalf of Birdchain should be considered a guarantee that the proposed business ideas will be a success nor are there any guarantees the tokens could be sold. Specifically, no promises on the value of the token are made.
 
All forward looking statements presented in the whitepaper or in any other materials put forth by Birdchain or any other third person acting on behalf of Birdchain are subject to risks and uncertainty and the outcomes might differ from the forward looking statements made. Birdchain does not take any responsibility for updating any forward looking statements made, should any uncertainties materialize.
 
Any citizens and residents of and persons in Canada, or the United States of America (USA), Puerto Rico and the Virgin Islands, and any other USA possessions, or any countries where the sale of Birdchain tokens would constitute a public offering of securities or the sale of tokens would be restricted are prohibited from participating in the sales process of Birdchain tokens and from receiving the tokens. Representatives and individuals acting in the interests of legal entities registered in the referred jurisdictions are prohibited from participating in the sales process of Birdchain tokens and from receiving the tokens. Each potential acquirer of a Birdchain token must ensure itself that the acquisition, possession, and use of the Birdchain tokens comply with all applicable laws and regulations, including any requirements for the sale and acquisition of tokens applicable in the relevant jurisdiction.
 
Birdchain does not make and hereby disclaims, any representation, warranty, or undertaking in any form to any entity or person, including any representation, warranty, or undertaking in relation to the accuracy and completeness of any information set out in this whitepaper. Birdchain reserves the right to amend the white paper until the ICO starts.

# Exchanges
We believe it is better to get listed in one major exchange than in a couple of small ones. It will be easier for both: our contributors and companies that will use our tokens to purchase Birdchain services. We will focus on getting BIRD token listed on some well-known exchanges. Our calculations are that token will be listed within a month after our ICO.

<p align="center">
  <img alt="Roadmap" src="https://github.com/Birdchain/whitepaper-business/blob/master/WP%20images/roadmap.png">
</p>

# Appendix
* “How off-chain trading will work” by Martin Koeppelmann 
* “Ethereum Lightning Network and Beyond” by Robert McCone 
* “State Channels” by Jeff Coleman 
* “Raiden: Scaling Out With Off-chain State Networks” by Heiko Hees 
* “Epicenter Bitcoin: State Networks” by Jeff Coleman 
* “Universal Payment Channels” by Jehan Tremback 
* “Scalability via State Channels” by Martin Koeppelmann 
* “Ethereum: Platform Review” (page 30) by Vitalik Buterin 
* “Sparky: A Lightning Network in Two Pages of Solidity” by Dennis Peterson 
* “An Introduction to State Channels in Depth” by Ameen Soleimani 
* “State Channels Wiki” by Jeff Coleman 
* “Gamble Channels: Fast Verifiable Off-Chain Gambling” by Denis Peterson 
* “Toy State Channels” Jeff Coleman 
* “Raiden Network” by Brainbot 
* “Machinomy” by Sergey Ukustov 
* http://plasma.io/plasma.pdf
* https://iota.org/IOTA_Whitepaper.pdf
* And many MANY others.
