<pre>
  DEF: 1
  Title: The Social Smart Contract
  Author: @DemocracyEarth.
  Comments-Summary: No comments yet.
  Status: Active
  Type: Paper
  Created: 2017-07-14
  License: MIT
  Replaces: 0
</pre>

=The Social Smart Contract.=
An Initial Rights Offering from [http://democracy.earth Democracy Earth Foundation].

==i. Abstract.==

In a world that has succeeded in the globalization of financial assets while keeping political rights enclosed to territories, we need to build new models of democratic governance that enable humanity to collaborate and address pressing global issues. Democracy Earth Foundation is building free, open source software for incorruptible blockchain-based voting within institutions of all sizes, from the most local involving two people to the most global involving all of us. Uneven distribution of opportunity around the globe due to the perpetual confrontation between national governments has led to accelerated climate change, rising inequality, terrorism and forced migrations.  Democracy Earth Foundation considers that the technology stack that includes Bitcoin as programmable money without Central Banks, and Ethereum enabling smart contracts without the need of Judiciary Courts, requires a new layer that signals incorruptible votes beyond the territorial boundaries of Nation-States. This transnational network will act in accordance with the personal sovereignty of its members and protect their human rights with encryption. In our Initial Rights Offering we offer a token called ''vote'' that will grant participation rights to every human with decision making as its main function. Our proposal introduces cryptographically induced equality: as long as any person is able to validate his or her self-sovereign identity, they will receive a corresponding share of ''votes'' that is equal to the share of every active participant in the network. We define a ''Proof of Identity'' process that avoids central authority by introducing the concept of ''attention mining'' which incentivizes participants to strengthen the trust of ''votes'' by performing simple tests aimed at detecting replicants. Finally ''votes'' get dripped to valid participants under a ''Universal Basic Income'' mechanism with a goal of finding a proper equilibrium in the historical tension between money and politics. We seek nothing less than true democratic governance for the Internet age, one of the foundational building blocks of an achievable global peace and prosperity arising from an arc of technological innovations that will change what it means to be human on Earth.

==ii. Contents.==

This text is structured in three parts, each aiming to satisfy a different readership target (and all of whom may reside within the same persona.)

* [[#Manifesto|Manifesto]]: For idealists. Diagnoses global political context and argues for a paradigm change.

* [[#Paper|Paper]]: For builders. Describes the building blocks for a system that can be implemented by anyone, anywhere.

* [[#Execution|Execution]]: For pragmatists. Specifies how to execute these ideas for impact.

We do not intend this text to remain fixed. It is published under an open source license and we welcome contributions from anyone, as our goal is for this document to be a living roadmap for planetary governance. Democracy as the ability to trust each other to the greatest possible extent is a defining force shaping the trajectory of history. Our mission echoes urgently across the globe,  encompassing all of humanity: the need to make of our home a place of peaceful coexistence. The [http://democracy.earth Democracy Earth Foundation] has performed [[#Background|extensive research]] on voting systems, cyberpolitics and blockchain networks; we stand at the forefront of a public conversation regarding the internet as a planetary jurisdiction.

Following [https://twitter.com/lsukernik/status/892101885771034628 the example of Satoshi Nakamoto], prior to sharing our ideas in written form we have undertaken to write code first, in order to properly understand what can be done. To this end, more than [https://github.com/DemocracyEarth/sovereign 30,000 lines of code have been written since October 2015], which in turn has driven our research and the ideas presented herein. This is our proposal.

<div id="Background"></div>

==iii. Background.==

We pioneered digital democracy having authored some of the most prominent open source democracy software [https://github.com/search?utf8=%E2%9C%93&q=topic%3Ademocracy&type=Repositories as ranked by the GitHub community] including the original design of [https://www.youtube.com/watch?v=qNCgfd7dNb0 DemocracyOS], a simple direct democracy project we created in 2012. We founded the first digital political party in the Americas, the [http://partidodelared.org Partido de la Red] (Peers Party) that ran for its first election in the city of  [http://www.wired.co.uk/article/e-voting Buenos Aires in 2013]. In 2014 we shared our experience in [https://www.ted.com/talks/pia_mancini_how_to_upgrade_democracy_for_the_internet_era TED] reaching over 1.2 million viewers. During 2015 and 2016, Silicon Valley's [http://ycombinator.com Y Combinator] and [http://ffwd.org Fast Forward] funded our efforts to start the [http://democracy.earth Democracy Earth Foundation], a non-profit organization committed to the mission of borderless governance.

Our experience combining both the political and technological challenges of democracy led us to think and design around the notion of how we could build a political party using smart contracts, or rather a lightweight form of governance anyone can implement at a low cost. We began the development of [http://sovereign.software Sovereign], a '''''blockchain liquid democracy''''' that enables direct voting on issues or the ability to delegate voting power on specific topics to peers over a secure network without central authority. By operating with tokens signaled on a blockchain all votes become censorship resistant and immediate audit rights can be granted to every voter without needing to provide access to servers or private infrastructure, thus making the system open and transparent for all. Our work is driven by open source software development practices and cooperates with key projects aiming to secure identity in decentralized environments including efforts from [https://blockstack.org/blockstack_usenix16.pdf Blockstack], [http://civic.com Civic] and [https://whitepaper.uport.me/uPort_whitepaper_DRAFT20170221.pdf Consensys] among others.

[[File:/images/sovereign.png|Sovereign.]]

[https://github.com/DemocracyEarth/sovereign Sovereign's codebase] delivers an adaptive mobile and desktop application to voters and organizations standardizing incorruptible decision-making in a blockchain based democracy. Our aim is to continue paving the road of implementations that enable [https://www.usenix.org/legacy/event/sec08/tech/full_papers/adida/adida.pdf cryptographic open-audit voting] and integrate our software with blockchains able to guarantee the sovereign rights of users.

----

<div id="Manifesto"></div>

==1. Manifesto.==

<blockquote>
  Democracy is always a work in progress, it’s never an absolute idea or it would otherwise be a totalitarian ideology just like all the rest of them.
</blockquote>
'''[https://en.wikipedia.org/wiki/Jos%C3%A9_Mujica José Mujica]''', President of Uruguay (2010–2015).

Current democratic systems governing societies under the territorial domain of Nation-States have grown stagnant in terms of participation and are leading towards increased polarization. Constituencies are provided with tailor-made media that satisfies their own endogamic beliefs, pulling society apart as discourse and factual debate are replaced with a [https://www.wikiwand.com/en/Post-truth_politics post-truth] mindset. This is a consequence of the drastic expansion in communication channels that shrank attention spans rendering thoughtful analysis expendable. Centralized 20th century information distribution created uniform narratives, realities and identities. The Internet has fractured them. Instances of political participation in the so-called modern democracies are not apt for information abundant contexts and have remained without change since their inception.

[[File:/images/bipartisan-votes-us-congress.png|Bipartisan votes in the U.S. House of Representatives since 1981, source: The Rise of Partisanship (2015).]]

Engagement through the traditional channels is weaker among younger generations, [http://www.economist.com/news/essays/21596796-democracy-was-most-successful-political-idea-20th-century-why-has-it-run-trouble-and-what-can-be-do often not going out to vote and unlikely to engage in party politics]. Meanwhile online activism is increasing with social media becoming the dominant arena for political clashes. This includes Facebook and Twitter (where gossip dissemination is predominant with ''fake news'', ''bots'' and ''trolling'' among other campaign optimizations) and emergent echo chambers like [http://www.4chan.org/ 4chan.org] where anonymity led to political incorrectness or [https://gab.ai/ gab.ai] consolidating the ''alt-right'' community in the USA. Needless to say: endogamy only makes polarization stronger, and our tribalized societies have shown a tendency to continue relativizing truth [https://www.nytimes.com/2017/06/01/climate/trump-paris-climate-agreement.html risking the preservation of resources] and the survival of future generations.

Democratic processes seen during high-stakes elections are often prone to fraudulent behavior with [https://en.wikipedia.org/wiki/Gerrymandering ''gerrymandering''] becoming commonplace and a strong link between what the [https://www.ineteconomics.org/uploads/papers/WP_48_Ferguson_et_al.pdf major political parties spend and the percentage of votes they win]. In developing nations exploits are literal having ballot boxes burnt by large parties to suffocate the chances of smaller competitors. 

This document proposes a solution that will tackle both the political and technical issues currently weakening the prospects of democracy in the world by offering an alternative that can be adopted directly by citizens and implemented using peer to peer networks. As the internet becomes the dominant force in modern politics we see an indispensable need to develop digital technology for voting that can be securely deployed in any geographical location and for communities of any size.

With internet growth [http://www.bbc.com/news/technology-32884867 reaching over 3 billion lives] (far surpassing major religions and Nation-States) and the development of encrypted networks known as blockchains permitting incorruptible transactions with permissionless audits, there’s no reason stopping mankind from building a borderless commons that can help shape the next evolutionary leap for democratic governance at any scale. Even in regions where internet penetration is below 50%, the digital gap is not based on socio-economic factors but it is rather a generational divide. According to Rick Falkvinge, founder of the [https://en.wikipedia.org/wiki/Pirate_Party Pirate Party]: “Politics moves at glacial speeds: nothing seems to happen until suddenly a strenuous noise gets everyone's attention. It is slow because it often takes one generation to die for the next one to take over. And today we live in a world that has the ''offline generation'' in charge and the ''online generation'' growing up”.

New forms of governance must acknowledge the networked commons connecting humanity and progressively weaken the legacy of national frontiers and its inherent inability to address pressing global issues such as climate change, rising inequality, terrorism, automation and forced migrations. Uneven distribution of opportunity around the globe due to the perpetual confrontation between national governments led to the rise of these issues in the global agenda. We believe the technology stack that includes [http://bitcoin.com/bitcoin.pdf Bitcoin] as programmable money without Central Banks and [http://ethdocs.org/en/latest/index.html Ethereum] enabling smart contracts without the need of Judiciary Courts requires a new layer that signals incorruptible votes beyond the boundaries of Nation-States. This transnational network will act in accordance to the personal sovereignty of its members and protect their human rights with encryption.

===1.1 Legacy.===

We can consider elections implemented by states, provinces and city municipalities as democracies where we are reduced to being passive recipients of a monologue. Citizens are called in-between substantially long periods of time, during elections, to provide a basic input: essentially accept or reject players in the same system. This is the bandwidth of the legacy system that is our so-called ''modern democracies''. Under these systems less than one percent of the population is able to vote on legislation or execute budgets while the rest are legally forced to outsource their full citizenship rights to a representing minority that eventually figures out how to perpetuate itself.

The technology behind ''representative democracies'' can be grouped in two sets:

* '''Analogue elections''': usually paper ballots and ballot boxes with authorities responsible for counting votes and reporting fraudulent behavior. Even though these systems are stable in developed nations, they suffer from severe lack of participation. Barriers are implemented with requirements such as the need to register to vote through an excessively bureaucratic process that ends up blocking a majority of disenfranchised voters. Authorities also gerrymander districts by exploiting survey data in anticipation of electoral outcomes. Even though these systems are easier to audit, this also means that they’re easier to corrupt: in developing nations ''analogue elections'' get subverted by mobs representing large parties that burn or 'disappear' ballot boxes, threatening auditors from smaller competitors and letting violence overrun the process in key districts. In our experience with the [http://partidodelared.org Partido de la Red] running for the City Congress of Buenos Aires in the 2013 elections we found out that no effort mattered more than having sufficient party auditors to cover every district in the city or otherwise votes would get stolen. The larger an election’s territory is, the less likely an analogue system can guarantee a fair process. Further,  high implementation costs end up limiting elections to a handful of days per year (if any), rendering democracy an exception rather than the norm regarding how governments actually get elected.

[[File:/images/nation-state-voter-turnout.png|Territorial voting.]]

* '''Electronic voting''': proposals that deliver solutions based on electronic voting machines aim to secure the process through a digital interface yet with the same logic of few elections per year, with the net effect of new technology serving the same purpose of legitimizing professional politicians as old voting technology. Machines can effectively help avoid [https://en.wikipedia.org/wiki/Clientelism clientelist] techniques used to corrupt an election but open a whole new surface of attack by exposing ballots to the risk of undetected hacks and foreign intervention. Experts on this field ([https://www.ndi.org/e-voting-guide/examples/constitutionality-of-electronic-voting-germany including the Supreme Court of Germany]) recommend using electronic voting machines that leave a paper trail [https://www.amazon.com/Voting-Wars-Florida-Election-Meltdown/dp/0300198248 or any alternative medium] for vote proof. Another approach to secure and transparent voting systems are efforts to make voting machines [https://www.nytimes.com/2017/08/03/opinion/open-source-software-hacker-voting.html open source and auditable by the public]. Technology can also be introduced directly by citizens using smartphone apps to perform ''parallel vote tabulation'' to report partial tallies across different polling stations as a safeguard against official reports. By their very nature, computing systems keep logs and cannot guarantee vote secrecy. For this reason any logging of a digital voting system should be public by default and trustless, operating with a distributed ledger syncing the outputs of a shared network. In short: a blockchain.

Traditional analog and electronic elections are strictly for long-term, representative democracies with elective periods ranging from 4 to 6 years. But the underlying dynamic of these systems is that officials are pre-elected from the top-down and presented for citizens to legitimize with their vote. The argument that citizens lack the knowledge and preparation to fulfill political responsibility and don’t have enough time in their daily lives to engage in public affairs is weak on merit: more often than not public servants require input from experts on specific fields to draft legislation. As well, thanks to the Internet, mobile phones, social media and satellites, we observably live in a world full of citizens routinely engaging in debate on political issues (albeit lacking any chances of genuine impact.)

===1.2 Geopolitics.===

A consequence of the US Presidential Election of 2016 is that the [https://www.theguardian.com/us-news/2016/dec/16/qa-russian-hackers-vladimir-putin-donald-trump-us-presidential-election fear of foreign intervention] has become a leading threat to the security of electoral processes. But although voting machines are an extremely vulnerable target, ([https://blog.horner.tj/post/hacking-voting-machines-def-con-25 defcon 25 had a large selection of voting machines, all of them were exploited]) foreign attacks have a simpler method than hijacking voting machines because directly manipulating votes potentially can be traced, is very expensive, and difficult to execute on a scale large enough to satisfy an attacker. A more efficient approach is [https://en.wikipedia.org/wiki/2016_Dyn_cyberattack instilling public fear by collapsing internet infrastructure days prior to an election] in a way that can help push favoritism on a candidate that is perceived stronger than the other one. This kind of cyberattack able to trigger a shift in voter perception is nearly impossible to trace as political subversion and reveals the inherent conflict that a digital commons has with territorial democracies.

[[File:/images/hacked-america.png|Impact of DNS cyberattack (October 21, 2016) & Presidential Election (November 6, 2016).]]

This happened two weeks before the US 2016 election when a botnet coordinated through a large number of Internet of Things (IoT) devices executed a [https://en.wikipedia.org/wiki/Denial-of-service_attack#Distributed_DoS Distributed Denial of Service (DDoS) attack] that affected Domain Name System (DNS) provider Dyn Inc. bringing down major websites in the US including Amazon, Paypal, New York Times and Wall Street Journal among many others.

===1.3 Land vs. Cloud.===

<blockquote>
In the near future, electrons and light flow freely, and corporate computer networks eclipse the stars. Despite great advances in computerization, countries and race are not yet obsolete…
</blockquote>
[http://www.imdb.com/title/tt0113568/ '''''Ghost in the shell'''''], graphic novel (1995).

The 21st century is witnessing a growing conflict between ''The Land'': governments that monopolize the law on territorial jurisdictions by restricting the free movement of physical goods and bodies; and ''The Cloud'': global corporations that monopolize access to user data able to track and target ideas via personalized advertising. In this world freedom is an illusion: our bodies belong to governments, our minds to corporations. Notorious battles from this conflict include the [https://en.wikipedia.org/wiki/FBI%E2%80%93Apple_encryption_dispute ''Apple versus FBI''] case requesting the jailbreak of an encrypted phone; or the historical dispute between [https://www.washingtonpost.com/news/the-switch/wp/2017/03/06/trumps-new-travel-ban-raises-the-same-silicon-valley-objections/?utm_term=.0854c54536d6 Silicon Valley’s cosmopolitanism seeking flexible visas and Washington D. C.’s nationalism raising migration barriers]. As this scenario unfolds, encryption plays a role of growing significance to protect the human rights of digital citizens as it can help them break apart from the ''cloud versus land'' trap.

[[File:/images/the-land.png|The land: monopolies on force.]]

The origins of modern cryptography go back to World War II when Alan Turing built the first proto-computers to decrypt Nazi messages. Since then encryption has been legislated in the USA in the same manner kept for traditional weapons: it is included in the ''Munitions List'' of the [https://www.pmddtc.state.gov/regulations_laws/itar.html International Traffic in Arms Regulations] and related software and hardware must deal with export restrictions. And even though encryption is often considered a right protected under the First Amendment arguing that “code is speech”, its defensive nature indicates that it must also be protected under the umbrella of the Second Amendment since it holds the same reasoning behind the “right to bear arms”: In an era where [http://twitter.com/Snowden whistleblowers] are revealing how the ''Deep State'' spies on citizens anywhere around the globe, encrypted information is the only realistic guarantee that anyone has to be protected from government abuses (and the corporations that back them).

[[File:/images/the-cloud.png|The cloud: monopolies on data.]]

Secrecy is a fundamental property of free and fair elections as it is a mechanism that helps avoid coercion from those in power and prevents the risk of elections being bought and sold for money. Privacy is the best guarantee a conscious free mind has to think for itself. But on the modern internet: privacy is illusory when using Facebook, Google or any web based service. Even though Internet monopolies pretend being the gatekeepers of online privacy, theoretically Facebook can still impersonate any of its 2 Billion registered users if they ever wanted to. Google and Facebook hold the largest identity databases in the world surpassing the governments of India and China, while [https://twitter.com/AdrianChen/status/832452637320556544 97% of their reported revenue comes from advertising] severely conditioning the kind of experience that users get with their technology. It is in their interest to gather as much information as possible to profile people in order to stay competitive in the attention market and both companies filter information fed to users with [https://medium.com/@piamancini/future-scenarios-for-algorithmic-accountability-and-governance-17cd436d22a0 algorithms accountable] to anyone but their own board. None of their services are really free: personal sovereignty is given away in the same way the natives in the American continent got distracted watching their own ''selfies'' in shiny mirrors 500 years ago while the European conquistadors swept their entire way of life at a whim. Uncensored, free and sovereign debates on the future of humanity are being eaten by useless ''likes'' that only help perpetuate these corporate entities. ''Fake news exploits'' (as they were used during the U.S. elections) or critical content spreading like wildfire (as it happened during the ''Arab Spring'') demonstrates that any effort to stop international influence on national politics is futile as societies spend most of their time online. The Internet is incompatible with Nation-States.

===1.4 Intelligence.===

<blockquote>
  I can’t let you do that, Dave.
</blockquote>
'''HAL 9000''' on ''2001: A Space Odyssey'' (1968).

The best civic tech is tech that gets used every day. Already, Facebook, Twitter and other social media platforms have become by proxy the main interface citizens use to influence everyday politics. But the unseen consequences of giving personal data away through centralized web services can be many and with relevant implications for the future of humanity. The information architecture of how personal data is stored, shared and monetized is fundamental to understand sovereignty in the 21st century.

A looming threat is the use of unrestricted Artificial Intelligence (AI) that gets fueled by user generated content without any kind of public supervision. That was evident in a former Blackwater employee’s revelation to us on how data gets weaponized: from an office in Dubai he was able to drive and get the live feed of a drone flying over Syria or Pakistan, but surprisingly the decision whether to kill the target wasn’t made by the human operator (or a supervising authority) but by an AI that called the shots over the Internet “at least 90% of the time“. This AI was provided by a Silicon Valley company often 'credited' with providing intelligence services to the CIA and with having found Osama Bin Laden in 2011.

The issue on AI deciding on the fate of human lives opens up ethical and moral questions. Eventually not even human researchers are able to properly understand how an AI is behaving, becoming a threat if it is a key component of military grade technology. According to author Yuval Noah Harari: “intelligence is breaking apart from living organisms and it won’t be monopolized by carbon beings for long.” Consciousness is the new political frontier being drawn. A line between machines and humans. In other words: understanding whether we are using the machines or the machines are using us. How we structure human organizations —and govern the code running them— defines who is in charge. As the capacity of silicon intelligence matches Moore’s Law growth rates, humanity as a whole must ask itself how it is going to govern the reins of this unprecedented power.

===1.5 Decentralization.===

<blockquote>
  Sovereign is he who decides on the exception.
</blockquote>
[https://wikipedia.org/wiki/Carl_Schmitt '''Carl Schmitt'''], political theorist (1888-1985).

The achilles heel of data hungry, attention farming internet monopolies is their need of a centralized information architecture. They rose as the ''superhubs'' in what used to be the promise of a web shaped network by implementing the winning solutions to the leading online use cases. But the consequence has been a privatized ecosystem: closed code, walled gardens and centralization of power in a few hands paving the way for a full [https://youtu.be/IrSn3zx2GbM?t=10m34s surveillance society] on what could otherwise be a borderless commons. When Sir Tim Berners-Lee, creator of the ''world wide web'' protocols, pointed out the intrinsic risks on today’s internet he requested the need to draft a [https://www.ted.com/talks/tim_berners_lee_a_magna_carta_for_the_web Magna Carta for the Web]: “Unless we have an open, neutral internet we can rely on without worrying about what's happening at the back door, we can't have open government, good democracy, connected communities and diversity of culture. It's not naive to think we can have that, but it is naive to think we can just sit back and get it.“

Centralization is the single point of failure in elections and is incompatible with democracy. In our experience implementing centralized digital voting for decisions of Partido de la Red, we detected that if an election is high-stakes (all or most members have a biased interest in the outcome), the likelihood of the system being corrupted increases. The biggest risk lies in those who are responsible for controlling servers and database integrity. We have found out on [https://asamblea.partidodelared.org/topic/58eaf4739b96a611009bc3fc internal elections] held in early 2017 discrepancies between information reported by database auditors and the logs voters kept in their local machines: manipulation in vote emission data, aribitrary modification of poll closing date, erased records and sudden ban of registered accounts where proven and denounced leading to a generalized perception of fraud in the whole process. Centralized digital democracies without any consideration for cryptographic security are toys useful for playful purposes but can be dangerous when implemented in real scenarios under fraudulent hands.

Meanwhile, traditional elections have a technique known as ''adversarial counting'' when the outcome is close to a tie. Authorities of all involved parties participate in a manual vote count. But when an election happens within a large population, ''adversarial counting'' reduces the cost to subvert it by having an attacker only needing to bribe a few authorities from a competing party to secure a result. Any kind of system that requires trust from participants ultimately runs the risk of having its whole structure collapsing if any authority is fraudulent.

[[File:/images/blockchain-permissionless-audit-voting.png|Blockchain democracies enable permissionless audits.]]

Decentralization is a requirement of democratic elections. Without it there will always be room for corruption. Blockchains enable trustless systems by eroding the need of human authority and increasing the defenses of vote integrity with a shared resource that has scorekeeping as its main function. This permits unprecedented designs for electoral systems. '''With a blockchain-based democracy votes become censorship resistant and every single voter can audit an election without requiring any kind of access rights to infrastructure.''' By storing vote data in a blockchain rather than in private servers or ballot boxes, audit costs become abstracted and are turned into a guaranteed right for every participant. Voters are not just mere spectators but also sovereign gatekeepers of the whole process. This kind of transparency cannot be delivered by traditional electoral systems, analog or electronic.

===1.6 Sovereignty.===

On today's internet, voting has still emerged as the main interaction. Every time users ''like'', ''upvote'', ''heart'', ''link'' or ''retweet'' content they are signaling a preference that serves a feedback loop generating better recommendations for them. But the action won’t go any further: it’s a  ''fake vote'' that lacks institutional implications. ''Likes'' in social media operate as worthless tokens that can be inflated with a single click even though they set the price of advertising dollars. Network effects turned this interaction into a metric that highlights the influence of a specific idea within a crowd, often being a tool for those in power to survey society’s needs. But the financial and political benefits of these transactions are entirely kept by the [https://www.nytimes.com/2016/10/16/technology/peter-thiel-donald-j-trump.html network owners].

[[File:/images/web-voting.png|Web voting.]]

Sovereign technology able to operate in peer to peer networks, validating identity, preserving anonymity, encrypting data, decentralizing infrastructure, with free (''as in freedom'') open source code can completely disrupt the described landscape.

Throughout history only three kinds of sovereigns prevailed: the ''sovereign tribe'' where a crowd follows a leader; the ''sovereign king'' loyal only to God; and the ''sovereign republic'' with continental lands governed under one law. Blockchains operating in cyberspace are giving rise to a fourth kind: the ''networked individual''. It’s not a far fetched possibility: conquering [https://www.amazon.com/Sovereign-Individual-Mastering-Transition-Information/dp/0684832720 personal sovereignty] is already a reality for those who run their finances with bitcoin and other crypto holdings. As investor [http://twitter.com/naval Naval Ravikant] puts it: “You can cross an international border carrying a billion dollars in bitcoin entirely in your head.” This kind of sovereign act is unprecedented even for contemporaneous Heads of State.

The widespread adoption of blockchains is giving rise to a model that initially grew under the shadows of established institutions but eventually will render them obsolete. Blockchains are automated bureaucracies that offer significant financial benefits in terms of transaction costs while abstracting the need of intermediaries. They enable systems of free association that help break the political and financial coercion that governments and banks impose by restricting the right to vote or limiting access to capital. A technologically advanced society can flourish beyond territorial domains anywhere there is an internet connection with digital citizens becoming part of a new kind of diaspora.

----

With this diagnosis, on [[#Paper|Section 2]] we map the basic building blocks for a decentralized liquid democracy. Once the tools are defined, [[#Execution|Section 3]] proposes an implementation that focus on making the system secure and inclusive.

<div id="Paper"></div>

==2. Paper.==

<blockquote>
  It is the technology that we do not control the one that is used to control us.
</blockquote>
[https://twitter.com/earlkman '''Emiliano Kargieman'''], space hacker (1975).

A foundational principle of democracy is the right to be heard. Today most of the world’s population is not heard: having a voice is an accident of birth. Individual and collective voices are politically and economically silenced by ‘illiquidity’ - the marginalized are given no instruments to broadcast or amplify their voice. Modern democracy is the birthchild of the ''Printing Press Era'': printed constitutional systems dependent on wet ink contracts and the speed of the postal service. Representative democracies are an accident of the information technologies of the 18th century.

[[File:/images/liquid.png|Direct democracy vs. Liquid Democracy.]]

A liquid democracy is based on a dynamic representation model that works with a bottom-up approach: citizens are able to freely elect within their social graph (friends, colleagues, family) who they want to have as representatives on a specific set of topics. It is the most flexible form of democratic governance that can be constructed with digital technology, operating as a hybrid that enables direct or delegated voting at any time. There are few precedents of trustworthy bottom-up environments that led to authoritative content, [https://www.wikipedia.org/ Wikipedia] being a pioneering case. But if history is any guide, the last time civilization faced [https://en.wikipedia.org/wiki/Age_of_Enlightenment a paradigm shift regarding encyclopedic enlightment] it was precisely on the epoch preceding the rise of modern democracies.

This paper details the implementation of a liquid democracy using [http://github.com/DemocracyEarth/sovereign Sovereign], our democratic governance application that operates with blockchain tokens using a basic set of smart contracts. Simplicity in the design and language used to express this design matters for the purpose of a genuinely democratic device. No technology will ever be able to satisfy democratic aspirations if it can only be understood by an elite. As cryptographer [https://en.wikipedia.org/wiki/Ralph_Merkle Ralph Merkle] stated:

<blockquote>
  We do not call upon ordinary untrained citizens to perform surgery, fly airplanes, design computers, or carry out the other myriad tasks needed to keep society functioning, what makes governance different? The problem is readily understood: if we give governance to “experts” they will make decisions in their own best interests, not in the best interests of us all.
</blockquote>

===2.1 Token.===

An ideal voting system must be able to satisfy in the greatest possible extent these conditions:

* '''Secrecy''': voter must be able to cast vote in secret.

* '''Verifiability''': voter must be able to verify tallied vote.

* '''Integrity''': system must be able to verify correct vote tally.

Additionally, due to the risk that coercion through physical violence or threats in contexts prone to political violence, an option able to protect coerced voters must be introduced:

* '''Resistance''': voter must be able to override own vote if necessary.

In the work led by researchers Hosp & Vora, an [https://pdfs.semanticscholar.org/24d5/5c866a7317dae11d37518b312ee460bc33d3.pdf Information Theory approach was taken to model voting systems] leading to the conclusion that a natural tension exists with a system aiming for ''perfect integrity'', ''perfect ballot secrecy'' and ''perfect tally verifiability''. All three cannot be simultaneously achieved when an adversary is computationally unbounded, able to brute force a system if unlimited time or memory are available. For this reason we consider indispensable to implement digital democracies using blockchains. With network effects already in place, blockchains are able to verify transaction integrity and prevent token double-spending. Bitcoin’s [https://en.wikipedia.org/wiki/Proof-of-work_system ''proof of work''] model achieves this by rewarding computational capacity verifying transaction blocks (what is often referred as ''mining''), leading to a network “300 times more powerful than Google’s resources” according to pioneer [http://twitter.com/balajis Balaji Srinivasan]. For this reason, our design is based on tokens within a blockchain network operating as ''political cryptocurrency''.

What differentiates a vote from money (or in broader terms: a ''political economy'' from a ''financial economy'') is that political currency is designed to guarantee participating rights under fair conditions to all members within an organization. Rights aim to satisfy overall legitimacy in the governance of an institution. While money is the language of self-interest, votes express the shared views of a community. Political currency is not strictly meant for trade but for social choice.

{| class="wikitable"
|-
! scope="col"| Feature
! scope="col"| Coins
! scope="col"| Votes
|-
! scope="row"| Utility
| Trade.
| Governance.
|-
! scope="row"| Mining
| Computation (e.g. Proof of Work).
| Attention (e.g. Proof of Identity).
|-
! scope="row"| Liquidity
| Scarce.
| Guaranteed.
|-
! scope="row"| Signal
| Self interest.
| Social choice.
|-
! scope="row"| Value
| Space (material goods).
| Time (information).
|}

====2.1.1 Implementation.====

Considering that value [https://en.wikipedia.org/wiki/Dogecoin can be driven by memetic capacity], the Democracy Earth token granting voting rights will be branded with the single most important message any democracy can convey: ''vote''.

The ''vote'' token can be implemented using smart contract code across a variety of blockchains that permit [https://en.wikipedia.org/wiki/Turing_completeness Turing Complete] scripts, including Bitcoin. Our design is blockchain agnostic in recognition of a computer science field still in its infancy where significant innovations remain to be invented. Nonetheless we are working on implementing the ''vote'' token under these smart contract environments:

* '''Ethereum''': Using a set of [https://github.com/ethereum/solidity solidity] smart contracts under the [https://theethereum.wiki/w/index.php/ERC20_Token_Standard Ethereum ERC20 token standard].

** '''Rootstock''': We are taking the necessary steps to make solidity code compatible with [http://www.rsk.co/ Rootstock's smart contract interpreter for the Bitcoin blockchain].

* '''Lightning''': With the activation of [https://en.bitcoin.it/wiki/Segregated_Witness segregated witness] in the Bitcoin protocol that enables routing of payment channels with the [http://lightning.network Lightning Network protocol], liquid democracy delegations can be mapped using satoshi-level transactions carrying an attached ''vote'' identifier. Blockchain settlement cost must be covered by the implementing organization.

Also, multi-chain implementations are encouraged in the spirit of seeking greater experimentation and collaboration regarding these technologies.

===2.2 Voting.===

The ''vote'' token aims to be a standard for digital democracy able to interoperate with other tokens, setting a common language for the governance of blockchain based organizations. Within the context of liquid democracies, a range of voting transactions is permitted with ''votes'':

* '''Direct Vote''': Selfish voter Alice is allowed to use her tokens to vote directly on issues as in a direct democracy.

* '''Basic Delegation''': Alice may delegate ''votes'' to Bob. As long as Bob has access to those tokens he can use them to vote on Alice's behalf.

* '''Tag Limited Delegation''': Alice may delegate ''votes'' to Charlie under the specified condition that he can only use these tokens on issues carrying a specific tag. If the delegation specifies that delegated ''votes'' can only be used on decisions with the ''#environment'' tag, then Charlie won't be able to use these anywhere else but on those specific issues. This leads to a representation model not based on territory but on knowledge.

* '''Transitive Delegation''': If Bob received ''votes'' from Alice, he can then delegate these to Frank. This generates a chain of delegations that helps empower specific players within a community. If Alice does not desire to have third parties receiving the votes she delegated to Bob, she can turn off the transitive setting on the delegation contract. Circular delegations (e.g. Alice receiving the tokens she sent Bob from Frank) are prohibited since the original allocation of ''votes'' from an organization to its members carries a signature indicating who is the sovereign owner of the ''votes''.

* '''Overriding Vote''': If Bob already used the delegated ''votes'' he received from Alice but she has a different opinion on a given issue, as the sovereign owner of her votes Alice can always override Bob's decision. Voters always have the final word on any given decision with their original ''votes''.

* '''Public Vote''': Often referred as the ''golden rule'' of liquid democracies, all delegators have the right to know how their delegate has voted on any given issue with their ''votes''. In the same way congressmen votes are public, on liquid democracies competing delegates on any given tag have an incentive to build a public reputation based on their voting record in order to attract more delegations.

* '''Secret Vote''': A method able to guarantee ''vote'' transactions untraceable to the voter. This is indispensable in contexts of public elections held within large populations that have a high risk of coercion. Even if perfect secrecy on ''vote'' transaction is achieved, user's can still be fingerprinted with exposed meta-data. For this reason, research on integration with blockchains designed for anonymous transactions with a proven track record is encouraged. This might include a mining fee to settle the ''vote'' transaction that can be either subsidized by the implementing organization or directly paid by voters. We recommend research and integration of secret ''votes'' with these blockchains:

** [https://z.cash ZCash]: implements shielded transactions using [https://en.wikipedia.org/wiki/Zero-knowledge_proof zero-knowledge proofs]

** [https://getmonero.org Monero]: uses [https://en.wikipedia.org/wiki/Ring_signature ring signatures with stealth addresses].

===2.3 User Experience.===

User Experience (UX) is a critical aspect of a decentralized architecture and becomes even more important as the redundant layers of centralized architectures condense to the user. In a centralized internet architecture, the user does not own the interface or experience. In a decentralized internet architecture, the user interface (UI) should be based on the user's perspective. In this sense, transactions get done under three distinct views:

* '''Self''': Using a public identity related to an individual.

* '''Organization''': In representation of an organization that extended representation rights to individuals (e.g. workplace, club, political party, etc).

* '''Anonymous''': Without any connection to a public identity.

This undertanding of ''SELF / ORG / ANON'' shape-shifting requirement highly influenced our interface and token design. At any given time a Sovereign user can adopt any of this modes to interact with decentralized organizations.

====2.3.1 Liquid.====

Sovereign aims to make liquid voting immediate and simple. Any friction in the process must be avoided and the delegation widget should be constantly exposed on the interface while browsing issues or looking at member profiles. For this purpose, Sovereign uses a ''liquid bar'' that permits transacting ''votes'' with a single gesture either on mobile and desktop devices.

[[File:/images/liquid-mobile-ux.png|Sovereign mobile interface displaying decision, ballot and liquid voting.]]

The ''liquid bar'' allows these actions:

* '''See available ''votes''''': Since in a liquid democracy a user can have 1 or more delegated ''votes'', having a constant reminder of the balance helps the user understand his or her current power within the system. If some of the ''votes'' were delegated with strict conditions (e.g. a ''Tag Limited Delegation''), this means that a user won't have the same amount of ''votes'' available to spend on every issue.

* '''See cast ''votes''''': A percentage value with the amount of ''votes'' currently cast on other decisions or delegated to other members of the community is shown. The user can tap or click at any time on that value to view a complete list of the issues where he or she is currently having a ''vote'' and decide whether to keep them there or make a strategic change.

* '''Slide to ''vote''''': The user can use his thumb (or mouse click) to slide the ''liquid bar'' handle and upon the release of it he or she will be prompted a confirmation request whether to ''vote'' or not.

* '''Tap to ''vote''''': If the user does not want to allocate more than 1 vote, he or she can simply tap on the ''liquid bar'' handle once and will be prompted to confirm a single ''vote'' transaction.

* '''Remove ''votes''''': At any time, as long as the poll is still open, the user may remove his or her ''votes'' from a decision by simply sliding the ''liquid bar'' handle back to the initial position.

We see this interaction as a step forward from the ''like'' pattern found in social media. ''Likes'' limits voting to mindless clicks and can be inflated at will. Since ''votes'' operate as a scarce resource in the system, they cannot be generated at will and always require a minimum of tactical thinking regarding how a user's interaction will influence a specific decision. ''votes'' have real implications to the user as a stakeholder of a decentralized organization while ''Likes'' only serve their controlling corporations.

====2.3.2 Delegations.====

A ''liquid bar'' also displays the ''vote'' delegation relation a user has with any other member of an organization. Delegations go both ways:

* '''Sent''': A user must be able to delegate any of his available ''votes'' while checking the current delegated amount (if any).

* '''Received''': A user must be able to understand how many ''votes'' were received from someone else.

Every time a member profile is displayed on Sovereign, the current delegation status between the user and the member is shown.

[[File:/images/delegation-relation-votes.png|View of vote delegation relation with another member.]]

====2.3.3 Agora.====

Sovereign also has a debating component codenamed ''Agora''. Debating is likely as important as voting on any democracy. Agoras display ''threaded conversations'', a successful design pioneered by [http://reddit.com Reddit] and [http://news.ycombinator.com Hacker News]. We consider this UX pattern as the best way to engage in thoughtful conversations online as they have the most valued comments bubble up, helping sort the information for a debate using the collective intelligence of the community.

But unlike web based applications, Sovereign does not allow testimonial interactions: instead of permitting infinite ''upvotes'' or ''downvotes'', if the user agrees with a comment from someone else in the platform, it will trigger an instantaneous delegation of a single ''vote''. Hence Agoras permit:

* '''Upvote''': Send a single ''vote'' delegation from the user to the commenter.

* '''Downvote''': If a user disagrees with someone's comment, a ''downvote'' can either retrieve a ''vote'' from the commenter back to the user if there was a previous delegation. Or if no delegation relation exists among them, then a ''downvote'' will act as a penalty sending a ''vote'' from the commenter back to the funds of the organization implementing the Sovereign instance. The criteria for this kind of penalty can be set in the ''constitutional smart contract'' of the implementing organization.

This will make delegations more frequent across the platform. Debates constantly exposed to the risk of ''vote'' transactions means that they are subject to real political impact. This mechanism can help reward good arguments and punish the influence of trolling without requiring the need to develop moderating authorities in the system.

=== 2.4 Pilot ===

<blockquote>
  Blockchain could disrupt voting, just as it has currency, and could apply to any democratic government.
</blockquote>
[https://www.oecd.org/gov/innovative-government/embracing-innovation-in-government-colombia.pdf '''The Organization for Economic Cooperation and Development'''], Embracing innovation in government: global trends (2016).

In October 2016, following a shocking, almost universally unexpected No to peace in the Colombian referendum that put at risk years of negotiation between the government & the marxist narco-guerrillas, Democracy Earth piloted the Sovereign liquid democracy platform in a [http://plebiscitodigital.co/ digital plebiscite] enacting a symbolic vote among the diaspora of ~6 million expatriate citizens. Instead of giving a voter the binary option, the pilot enabled people to vote separately on seven separate sub-themes of the proposed treaty, as well as to delegate their votes to more knowledgeable voters, with results revealing important nuances in voter preferences not captured in the referendum, including the [https://words.democracy.earth/a-digital-referendum-for-colombias-diaspora-aeef071ec014 deal breaker that emerged]: an overwhelming “No” among pilot participants to one particular statement of the treaty regarding political participation of the FARC.

[[File:/images/colombia-use-case.png|Colombia use case data..]]

The pilot study had the [https://www.oecd.org/gov/innovative-government/embracing-innovation-in-government-colombia.pdf additional impact] of increasing the media and political profile of blockchain-enabled, decentralized liquid democracy in Colombia; a blockchain-savvy political party has sprung up, the Partido de la Red Colombia party (“The Net Party”), while the Colombian government’s Centre for Digital Public Innovation (CDPI) investigating the technology as well.

===2.5 Smart Contracts.===

When Claude Shannon wrote his [http://math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf foundational 1948 paper on Information Theory], he was able to demonstrate how circuits can perform logic functions by expressing a binary state of 1 and 0 (<code>true</code> or <code>false</code> states). Since then, digital technology shaped the dynamics of all kinds of information systems. With this in mind we focused on building an efficient design for a governance machine able to operate with blockchains that keeps its human operators as sovereign rulers by means of the vote. In the same way bits move in computers signalling a <code>true</code> or <code>false</code> state, ''votes'' signal a boolean value for institutional decisions to be recorded under smart contracts.

''vote'' tokens operate within the institutional boundaries created by this set of contracts: <code>Organizations</code>, <code>Members</code>, <code>Issues</code>, <code>Ballots</code> and <code>Budgets</code>. These are the building blocks that help create a governance circuit that can scale to operate liquid democracies within communities of any size.

[[File:/images/vote-liquid-democracy-smart-contracts.png|VOTE Liquid Democracy smart contracts..]]

====2.5.1 <code>Organizations</code>====

The entity or institution implementing a Sovereign instance is referred as an <code>Organization</code>. This entity acts as a governing authority definining who are the <code>Members</code> allowed to participate in its decisions and granting them ''vote'' tokens. Since <code>Organizations</code> can live in a decentralized network, the requirements to make an entity able to operate with ''votes'' are similar to those found while setting up a website:

* <code>Domain</code>: Every organization must have its own domain name (e.g. ''democracy.earth'' on the Hypertext Transfer Protocol or HTTP). Some may even have a namespace running as a Top Level Domain or TLD (e.g. ''.earth''). This reference code for an <code>Organization</code> within an open network, whether its the legacy web as in HTTP or new emergent networks for decentralized domains such as [https://blockstack.org Blockstack], is crucial to help build a semantic layer that effectively describes <code>Issues</code> without the risk of having voters manipulating tags in a closed system (referred on Section 2.5.4 as ''squatting''). Domain names help describe an <code>Issue</code> as well as restricting the scope of a delegation contract.

* <code>Constitution</code>: Every organization has a ''Constitution'' that defines its foundational rules in the form of a smart contract. The ''constitutional smart contract'' describes how <code>Members</code>, <code>Issues</code> and ''votes'' connect within the system.

=====2.5.1.1 <code>Constitution</code>=====

The ''constitutional smart contract'' determines how ''votes'' will be allocated to members among other governance decisions. Allocation conditions are a prerogative of the organization depending on its goals: in some cases it can be aligned with financial rights (e.g. the shareholders of a corporation getting one ''vote'' per share); in other cases can be assigned based on an egalitarian distribution to all members (e.g. tax payers within a jurisdiction each getting a same amount of ''votes'').

The basic settings to be found on a constitution are:

* '''Decentralized ID''' (or URL): An identifier that helps refer to the <code>Organization</code> anywhere on the network and that it is connected to its <code>Domain</code>.

* '''Bio''': A basic description of the organization including its name, website, address, jurisdiction (if applicable).

* '''Funding''': The amount of ''vote'' tokens this organization will manage and how these will be allocated to every member and grant access to <code>Budgets</code>.

* '''Membership''': Requirements to become a valid member within organization. This criteria defines the voter registry that guarantees a fair electoral process of a democracy and can be scrutinized by its members.

** '''Open''': Anyone can freely join an organization.
** '''Voted''': Existing members must vote on applicant members. A percentage criteria must be set for approval.
** '''Fee''': The organization requires a payment for membership approval.

* '''Content''': Defines who is allowed to post <code>Issues</code> on the organization.

** '''Open''': Anyone (whether its a member or not) can post. Only members get the right to vote.
** '''Members''': Only approved members have the right to post.
** '''Special Members''': Members that meet certain criteria (e.g. a minimum of delegated ''votes'' or ''votes'' received under a specific tag) have the right to post.
** '''Anonymous''': Defines whether anonymous content is allowed to be posted.

* '''Moderation''': Describes the rules that help define a code of conduct among members of an organization.

** '''Ban''': An amount of ''downvotes'' required to ban a member from participating in the organization and the penalty attached to it (e.g. a period of time)
** '''Expulsion''': If an organization is based on ''Voted Membership Approval'', a member can receive negative votes from other members signalling that such identity has been corrupted or is no longer part of the organization. This criteria can be established as a minimum percentage required.

* '''Voting''': The allowed <code>Ballots</code> to be used for the decisions to be made by the organization and specific settings such as ''quadratic voting''.

* '''Reform''': The requirements to change any of the rules set on a ''Constitution'' (e.g. a special majority).

Templates defining common practices for specific kinds of organizations are encouraged to simplify organizational setup. This will be aided and abetted through work with the Democracy Earth Foundation partnership with [https://aragon.one/ Aragon], who is working on a digital jurisdiction that will make decentralized organizations efficient. Sovereign will include templates for corporations, political parties, trade unions, clubs and coops among others; whatever form the organization takes, Aragon's decentralized network ensures that a company will always work, even in the face of malicious tampering by hostile third parties or abusive governments.

====2.5.2 <code>Members</code>====

Every Organization has members that get the right to vote on the decisions of the organization. Membership criteria is defined in the ''constitutional smart contract'' and is key for the trust on any democratic environment. Among the most common ways to subvert an election is the manipulation of voter registry. Securing this aspect with cryptographic means as well as an approval protocol is critical. Once a member is approved within an organization, he or she gets a specific amount of ''votes'' to be used for its governance.

All <code>Organizations</code> who take the responsibility to approve or disapprove <code>Members</code>, contribute with this task to the ''Proof of Identity'' process described on Section 3.3.

Compatibility with decentralized identity protocols is encouraged for the purpose of guaranteeing decentralized governance. The [https://opencreds.github.io/did-spec/ specification of DIDs (decentralized identifiers analogous to the web's URIs)], proposed by the [https://www.w3.org/ W3C] enabling self-sovereign verifiable digital identity is recommended.

====2.5.3 <code>Issues</code>====

An organization consists of a collection of ''issues'' each describing a decision to be made by the members. Membership properties described in the ''constitutional smart contract'' define member's voting and posting rights. An issue in its most basic form has these properties:

* <code>Description</code>: Text of the decision to be made.
* <code>Tags</code>: Categories that describe the decision within the organization. This helps members navigate across issues, define areas or teams within an organization and limit the scope of a delegation of ''votes''. If the implementation is done with blockchain environments that are used to manage a fixed taxonomy (like [http://blockstack.org Blockstack]), a common distributed language for tags based on decentralized domains helps making the democratic environment more fair as it avoids members trying to control naming conventions for their own benefit. For this reason, within an open network <code>Tags</code> that describe <code>Issues</code> or are used to constraint delegations, are pointers to other <code>Organizations</code>. This is detailed in the ''Proof of Identity'' process.
* <code>Signatures</code>: Members that are authoring the proposal. It can remain anonymous if an organization's governance rules allows it.
* <code>Ballot</code>: The presented options for voters to participate on this decision.
* <code>Budget</code>: An optional element that may include locked funds in a cryptocurrency address that can trigger an action if a decision is voted in support.
* <code>Timespan</code>: For the final tally, an open poll must also set its scope in time and define the kind of decision being made. There are two types of decisions:
** <code>Tactical</code> (limited in time): These are contracts that receive ''votes'' until a closing date is met, where a given block height within the blockchain implementing the ''vote'' smart contracts can be set as the end line for the electoral process. Once all transactions have been tallied and a final result is recorded, all tokens get returned to the corresponding voters and can be used again on future decisions.
** <code>Strategical</code> (unlimited in time): Never-ending open polls that are perpetually registering the consensus of a decision state. ''votes'' can be retrieved by voters at any given time if they feel the need to discontinue their voice in support or rejection of a decision. But as long as the token is assigned to signal a preference on a contract ballot without closing date, it is part of the strategical decision. A common use for strategical decisions can be the members voting for approval of other members within the community of an organization.

====2.5.4 <code>Ballot</code>====

An issue can be implemented with any possible ballot design according to the specifications defined in the ''constitutional smart contract'' of the organization. The building blocks for a ballot are its <code>Interface</code>, <code>Options</code> and <code>Criteria</code>.

=====2.5.4.1 <code>Interface</code>=====

By default Sovereign provides the most commonly used choice mechanisms for ballot interaction. Further innovation on ballot interfaces is encouraged.

* <code>SingleChoice</code>: One selectable option.
* <code>MultipleChoice</code>: One or more selectable options.
* [https://en.wikipedia.org/wiki/Cardinal_voting <code>Cardinal</code>]: A given score per option with a pre-defined range of value.
* [https://en.wikipedia.org/wiki/Ranked_voting <code>Ranked</code>]: Sortable options as ranked preferences. [https://en.wikipedia.org/wiki/Arrow%27s_impossibility_theorem Arrow's impossibility theorem] must be taken into consideration for any innovation regarding ranked ballots. This theorem states that rank-based electoral systems are not able to satisfy fairness on three key aspects at the same time:
** '''Unrestricted domain''': all preferences of all voters are allowed.
** '''Non-dictatoship''': no single voter possesses the power to always determine social preference.
** '''Pareto Efficiency''': if every voter prefers an option to another, then so must the resulting societal preference order.

=====2.5.4.2 <code>Options</code>=====

In order to enable the information processing of ''votes'', ballots carry boolean values expressed in their options. This lets ''vote'' transactions signal a ''decision state'' that will act as a force modeling the institutional choices for the implementing organization. This makes all decentralized organizations also into programmable institutions. Options can then be:

* <code>True</code>: It will signal a <code>true</code> boolean value if selected (often described with 'Yes' or 'Positive' label strings).
* <code>False</code>: Signals a <code>false</code> state (e.g. can display 'No' or 'Negative' labels).
* <code>Linked</code>: The option is connected to another decision within the organization.
* <code>Candidate</code>: A member or list of <code>Members</code> from the organization. This helps elect authorities within the organization or it can be used for membership approvals.

=====2.5.4.3 <code>Criteria</code>=====

Finally, counting methods for the final or ongoing result of a decision within an organization.

* <code>Plurality</code>: Simple majority wins decision.
* <code>Majority</code> A minimum percentage is required for winning decision.
* [https://en.wikipedia.org/wiki/D%27Hondt_method <code>DHont</code>]: Widely used by Nation-State elections based on member lists.
* [https://en.wikipedia.org/wiki/Schulze_method <code>Schulze</code>]: Commonly used by open source communities and Pirate Parties using ranked choice ballots.
* [http://ilpubs.stanford.edu:8090/422/1/1999-66.pdf <code>PageRank</code>]: Counts votes weighting voter reputation in a graph.

====2.5.5 <code>Budget</code>====

Every <code>Organization</code> can have 1 or more cryptocurrency addresses to fund its efforts. Sovereign permits to fund an <code>Organization</code> with Bitcoin and in its <code>Constitution</code> define a criteria on how these assets get distributed among <code>Members</code>:

* '''Percentage for ''Proof of Identity''''': Applicant <code>Members</code> can submit their ''Proof of Identity'' evidence to get membership approval to an <code>Organization</code>. If ''votes'' approve the new member, it strengthens the reputation of a self-sovereign identity in the open network by rewarding him or her a fixed amount of Bitcoin to permit hashing the ''Proof of Identity'' on a blockchain. Some <code>Organizations</code> may allow a bigger reward than others, effectively creating a Reputation score that can protect the network against ''Sybils'' or false identities. This process is detailed on [[#Executive|Section 3]].

* '''Percentage for <code>Issues</code>''': <code>Members</code> seeking to use resources from the <code>Organization</code> can request them by attaching a <code>Budget</code> to an <code>Issue</code>. A <code>Member</code> can request to used funds from a pool specifically reserved for this. If the final tally of a decision reaches a certain value (<code>true</code> or <code>false</code>), it can then enforce the final decision by unlocking coins or triggering a transaction sending the requested assets to a specific address.

===2.6 Security.===

With Sovereign we are aiming to provide a lightweight governance framework that permits all stakeholders of an organization to participate and enforce decisions through the use of cryptography. But it is important to state that we are not aiming for a democratic system based on mob-rule or [https://en.wikipedia.org/wiki/Majoritarianism ''majoritarism'']. History offers sufficient examples on how a blind majority can end up failing the aspirations of a republic often putting demagogues in power.

[[File:/images/ideal-democracy.png|Ideal democracy.]]

Our main goal is to deliver a system able to guarantee the greatest amount of legitimacy while empowering the most knowledgeable voices in any community. The difference between fact and promise is simple: while the art of politics consists in sustaining the fiction that breeds trust on established institutions (e.g. politicians during campaigns), cryptographic proof of events delivers a more reliable method for trusted governance. The incorruptible nature of blockchain transactions provides an incentive for people not to lie, hence organizations storing votes and decisions in them get driven by facts rather than promises. Corruption can be fought at its root as we develop a new sense of citizenship based on digital networks.

Still, liquid democracies can be gamed in different ways with outcomes dominated by the unintended consequences of two dynamics representing extreme ends of the participation spectrum:

* '''Lack of delegationg''' leading to a ''polyopoly'': extreme fragmentation of voting power.
* '''Abundance of delegations''' leading to a ''monopoly'': extreme concentration of voting power.

Each outcome impacts one of the two axes measuring the quality of democratic governance. The incentives on the ''vote'' political economy are designed to keep a stable equilibrium aiming to guarantee the highest level of legitimacy and fact-based decision making.

To become a trusted environment for decentralized governance under large communities (cities, nations or global scale), Sovereign must be protected against different kinds of attackers: ''Mobs'', ''Corporations'', ''Sybils'', ''Fakes'' and ''Big Brother''.

====2.6.1 Polyopoly.====
<blockquote>
  a.k.a. ''Mobs''
</blockquote>

Among the most notable research projects on the field is [http://www.tdcommons.org/cgi/viewcontent.cgi?article=1092&context=dpubs_series Google Votes]. This was an internal implementation made for Google employees led by engineer Steve Hardt where he created a liquid democracy plug-in to be used on the internal version of Google+. The project had the following numbers in terms of impact:

* 15,000 participants.

* 371 decisions.

* '''3.6% of delegated votes''' in total.

The small percentage in delegations means that Google Votes operated more as a direct democracy than a liquid democracy. Delegations occured mostly among those users who actively campaigned to attract them (e.g. vegans in a team hoping to gather power to choose office snacks). The risk of few delegations is that it opens the democracy to the known risks of mob rule. Although this might keep legitimacy high, the quality of the decisions being made by an organization becomes more political than factual. Knowledgeable voices able to address specific problems within a community become disempowered.

To increase delegation frequency, these happen every time self-sovereigns get validated. On the ''Proof of Identity'' process (see Section 3), users are able to natively generate their own ''votes'' as long as their individuality gets endorsed by other identities. Also since the ''vote'' token operates in a blockchain, delegations don't need to necessarily happen within the Sovereign application: messaging applications, tweets and e-mails can be sent with vote addresses or QR codes attached to them making the vote token able to be broadcasted across multiple networks.

====2.6.2 Monopoly.====
<blockquote>
  a.k.a. ''Corporations''
</blockquote>

When the German Pirate Party implemented [https://en.wikipedia.org/wiki/LiquidFeedback Liquid Feedback], a pioneering liquid democracy software developed in 2009, it reached a participation level of ~550 affiliates that led to [http://www.spiegel.de/international/germany/liquid-democracy-web-platform-makes-professor-most-powerful-pirate-a-818683.html a linguist professor becoming the most influential member of the party]. Martin Haase was in charge of translating all uploaded propositions in the system to a neutral language in order to avoid any ideological bias, making him grasp 167 delegations from other members.

The consequences of having a monopolizing leader in a liquid democracy environment goes against the spirit of an ecosystem that aims to incentivize more participation. In liquid democracies ''celebrities'' can become extremely influential being able to attract most of the delegated votes. An attacker willing to subvert an election can promote a TV star wearing a QR code to get a sudden influx of delegations from fans and viewers, instantly becoming a monopolizing force. Monopolies are a threat to liquid democracies since they can disincentivize less fortunate voters to participate, hijacking the legitimacy of the decisions being made.

=====2.6.2.1. Quadratic Voting.=====

A key setting of a liquid democracy system is to permit [http://ericposner.com/quadratic-voting/ quadratic voting] for delegations. The cost for Alice to delegate votes to Bob increases exponentially the more votes get delegated. With quadratic delegations Alice can only delegate Bob 1, 2, 4, 8, 16 or even 128 or 512 ''votes'' but no value in between. This makes any delegation tax the delegator by reducing the opportunity cost of delegating to another member. This method prevents the rise of monopolies within the market dynamics of liquid democracies, always making the participation of all members relevant. If some organizations desire a more vertical chain of command (e.g. corporations), quadratic voting can still be disabled in the ''constitutional smart contract'' of a Sovereign implementation.

====2.6.3 Sybil Attack.====
<blockquote>
  a.k.a. ''Identity Theft''
</blockquote>

Whoever has the ability to control the registry of voters of any given election can directly influence the end result. A classical example is registering defunct members of society to vote in an election. On decentralized networks this is commonly referred as a [https://en.wikipedia.org/wiki/Sybil_attack sybil attack] (a name taken from an [https://www.youtube.com/watch?v=8kPIDt3yu1M homonymous 1976 film] based on a character that suffers a multiple personality syndrome). Sybil nodes are those that identify themselves as independent actors in the network while they all are under the control of a single operator. In decentralized environments sybil attacks are the most common threat and for this reason we consider indispensable that for ''votes'' to be granted they must get validated through a protocol (social and algorithmic) that works as ''Proof of Identity''.

====2.6.4 Fake news.====
<blockquote>
  a.k.a. ''Gossip''
</blockquote>

It is no coincidence that the battlefield of modern democracies is disputed in the media. News organizations have unprecedented capacity to shape voter perception. Across different jurisdictions worldwide, governments wage an internal war between the State and the largest local media conglomerate. This is the playbook behind Donald Trump and his fight against the CNN & New York Times tandem; or the reason Vladimir Putin invested significant resources to create Russia Today in order to have a way of presenting alternative facts. Controlling the message tends to matter more than truth itself. Free media and independent journalism are a fundamental requirement for stable democracies. But if evidence of institutional facts are hard to prove, the room for manipulation is greater than the room for truth to prevail. Traditional institutions are secretive and lack transparency even if they are public offices. Blockchains enable a way of storing institutional facts that guarantees transparency in organizations. In this sense, ''fake news'' can be fought with a new institutional model able to store ''Hard Promises''.

=====2.6.4.1 Hard Promises=====

Corporations and public institutions are prone to corruption because decisions often happen in secrecy behind closed doors while accounting happens over time. Effectively, organizations are ''decision laundering'' by disconnecting accountability from the decisions. The lack of an incorruptible timeline storing financial and political decisions enables such inaccountability. The [https://en.wikipedia.org/wiki/Leviathan_(book) ''Leviathan'' State] is an inefficient machine: although it proclaims itself as the sovereign ruler for any given population by means of force, whoever is in charge of running its bureaucracy can still be corrupted making the whole house of cards fall apart. This distance between fact and accounting is the source of gossip.

The building blocks of institutions consist on facts that define agreements. But the kind of facts agreements contain are of a very specific type: Institutions are not built with objective facts that are scientific, measurable and independent from human judgment; but rather inter-subjective facts that build the social world within a community setting the relations of property and rights. For example, the notion that every red can of soda belongs to the Coca Cola Corporation is not objective but an inter-subjective fact agreed upon all members of society acknowledging the intellectual property rights that a company has over its product. In this way, institutional reality helps scale economic relations and reduce the information required for organizations to transact.

The bureaucracies that protect these agreements depend on promises, i.e. “all money kept in banks will be there tomorrow”. But as [https://twitter.com/aantonop/ Andreas Antonopoulos] states: “We’re used to systems of soft promises and reversible transactions.” If the government (or any other kind of central authority) wanted to confiscate private funds stored in a bank, nobody can stop them from breaking that promise. This has been the experience of Greek, Argentine, Venezuelan or Puerto Rican citizens with their own defaulting governments in the past decade. Blockchain based organizations on the other hand offer an alternative of ''hard promises'': agreements stored in smart contracts strictly protected by cryptography that no single third party can corrupt. Rather than regulating human behaviour post-facto as government law does, blockchains guarantee transparency by default incentivizing honest behaviour since every participant is aware that institutional events will be available for open scrutiny.

====2.6.5 Squatting.====
<blockquote>
  a.k.a. ''Big brother''
</blockquote>

A liquid democracy operates across domains. Setting up an <code>Organization</code> within a network of delegatable ''votes'' is analogous to spinning up a server on the web. Domain squatting is the practice of occupying abandoned or unused web addresses in expectation of a profit. This has led to a billion dollar market having the most commonly used words (identifiers) as the best kind of digital real estate, e.g. [http://sex.com Sex.com] [https://en.wikipedia.org/wiki/Sex.com#Highest_price_paid_for_domain being the highest price paid domain].

On a large scale, liquid democracy's game eventually grows around the <code>Tags</code> being used to describe delegations and issues. In a closed system, the most used <code>Tags</code> point to a reduced universe of relevant voters leading the delegations related to them. Reduced voter participation increases the prediction ability of a democracy, reducing the moments open up for collective decision-making. Democracy thrives as long as participation is incentivized. To prevent this exploit, financial and political interests must be aligned. ''Tag squatting'' can be prevented if the taxonomy used to make liquid delegations and issue descriptions operates in an open network: <code>Tags</code> refer to <code>Organizations</code> that are registered under a decentralized domain name system, considering that every <code>Organization</code> needs a domain name. [Blockstack.org Blockstack's blockchain] specializes on decentralized domain names currently managing over 70,000 Dentralized IDs (DIDs). These are obtained via a ''Proof of Burn'' process where users burn Bitcoin in exchange for Blockstack tokens that permit registering a new namespace.

Words define political ideas. The social narrative built by the art of politics consists of deciding semantic intention. Power defines the theatrical impressions that imprint our memories each time we say ''left'', ''right'', ''free'' or ''equal''. Language is a legacy code that enables large scale human collaboration and its virtues cannot be dennied.

----

All of these strategies attack the core of how a decentralized organization institutionalizes itself. In other words: define the risks on how Democracy Earth allocates ''votes'' to its members on the blockchain as a decentralized entity. For this reason, we detail on [[#Execution|Section 3]] a rollout plan for ''votes'' that raises strong defenses against these kind of attacks and paves the way for a global democracy.

<div id="Execution"></div>

==3. Execution.==

[[File:/images/humans.png|Humans on Earth.]]

A pressing fact that goes to the core of what is behind the political and economical challenges of the 21st century is the rise in population growth: [https://esa.un.org/unpd/wpp/ United Nations estimates that by the year 2100 the world will surpass 10,000,000,000 sapiens]. In other words: the planet’s [https://en.wikipedia.org/wiki/Carrying_capacity carrying capacity] will be reached by the end of this century.

Clues on the risks of running out of resources can be found in the cultural legacy of islands. A far away land such as [https://en.wikipedia.org/wiki/History_of_Easter_Island Easter Island] was during most of its history a closed system lacking any contact with the rest of the world. Its population had no means for survival other than its own resources, constantly facing the dangers of famine, epidemics and civil war. Even though these menaces seem far off under a globalized economy, the sudden rise in human population during the past century is the driving force behind increasing CO2 levels in the atmosphere and the collapse of public infrastructure unable to deal with massive migrations. Refugees are escaping wars that seek to secure energy resources for a future that is coming at us fast as the pace of technological innovation accelerates. Though some have already put escape plans into place, including private efforts to reach Mars in the upcoming decades (resembling the biblical story of Noah's Ark), the urgent call to safeguard humanity as a whole must be both amplified and answered.

Distribution of opportunity and intelligent collaboration accross the globe cannot be achieved peacefully unless every voice gets heard, without exceptions. Global governance is the next logical step in a world already connected over the Internet. Blockchains lead towards the possibility of liquid governance laying out the foundations for a democracy of peers. Permission from established Nation-States is not required: citizens anywhere in the world can embrace this change using sovereign networks.

===3.1 Rights vs. Debt.===
<blockquote>
   “What is justice?” the philosopher asked.
   “Pay your debts and don’t lie” Kefalos (capital), a wealthy arms manufacturer, replied.
</blockquote>
'''Plato''', ''Republic''. Philosopher (428-348 BC).

Although politics and economics are often perceived as different realms, history teaches that money means power and power means votes. In order to effectively promote democracy it is essential to address both.

The association of debt, morality and wars remains at the root of the economic mental models of society. Coins were first created by the great empires to finance wars by enabling the purchase of provisions for soldiers in distant regions and rewarding them for victory. Soldiers could loot silver and gold from conquered cities and then exchange it afterwards as the emperors minted coins with the precious metals in order to create markets. Eventually empires would also ask for a share of those coins to be given back as a tax that was directed at the maintenance of the army. The moral narrative was that citizens were ''indebted'' to the emperor for their security, for being alive. Debt evolved to justify any form of coercion sustaining the power hierarchies in countries anywhere. Lack of liquidity is the most tangible and immediate barrier to freedom under which the majority of humanity finds themselves.

The ''vote'' token will be distributed as a '''Right''' opposing the historical association of '''Debt''' and morals, generating a new breeding ground for transactions that are not based on the possibility of coercion. It aims to bring equivalence to transacting entities, restoring balance and fairness as the new moral standard. Democracy Earth's core motivation is enabling freedom and personal sovereignty, a possibility that can only be reached if individuals are able to say 'no' and choose an alternative order uncoerced and free. This cannot be achieved with induced scarcity as it is often found on most crypto assets, but rather through a guaranteed access to ''votes'' to every member of society turning governance rights into a liquid instrument.

For this reason, [http://democracy.earth Democracy Earth Foundation] will generate an ''Initial Rights Offering'' of ''vote'' tokens designed to reach everyone on Earth under a process that will offer two mechanisms: crypto funding for anyone willing to allocate resources that strengthen the development of a global democracy with the ''vote'' token; and a rights mechanism as a native way of getting ''vote'' tokens by anyone able to ''mine'' his or her corresponding share of ''votes'' through a ''Proof of Identity'' process.

====3.1.1 Initial Rights Offering.====

Identity is foundational to personal sovereignty and the kernel of all voting systems. Votes (on any system) are valid if and only if membership is verified within an organization, no democracy can run on corrupted identities. Today’s standard identity systems are based on central authorities forcing users to share private information risking identity theft if they get hacked. Precedents include [https://gov.uk United Kingdom's Gov.UK] and [https://uidai.gov.in/ India’s Aadhaar], both which have been plagued by reports of improper security practices that included leaks compromising the privacy of millions.

For identities to be self-sovereign, they cannot be owned or controlled by governments, organizations or corporations that ultimately have as a priority the extraction of value from their users. Our approach with [http://sovereign.software Sovereign] is that it is organization-centric as a technology, but an organization can become decentralized if its identity verification process lacks the need of authority. Ultimately, any process dependent on decentralized identity is part of a global commons since the principle of a self-sovereign identitiy renders any ''Big brother'' irrelevant. Therefore, the key to sustain the value of the ''vote'' token as a means for a borderless democracy is to effectively validate all participating identities through a decentralized process that can create, update or revoke keys. This is how Democracy Earth Foundation will grant access to ''votes'' as a human right.

[[File:/images/identity-blockchain.png|Self-sovereign Identity.]]

Anyone able to demonstrate his or her own identity under a decentralized protocol referred as ''Proof of Identity'' (POI) can operate with a corresponding share of ''votes''. This mechansim will trigger an allocation throughout time in the claimed public address of the identity which is accessible through a self-hosted wallet connected to the content and data used for the POI. If sufficient ''votes'' validate the evidence used for the ''Proof of Identity'', the wallet will unfreeze a corresponding amount of ''votes'' following the rules of a ''Universal Basic Income'' dynamic that allocates tokens throughout time that uses the Bitcoin blockchain as a universal clock.

===3.2 Proof of Identity.===

A self-sovereign identity must be voluntarily generated by a user claiming it. For this purpose the user must broadcast a proof of his or her identity that strictly satisfies a criteria that can be met by human judgment and able to avoid an artificial intelligence from interfering with the process. Hence, the proof shall be in a format that requires a large amount of cerebral bandwidth: video. A satisfactory proof shall meet all of these properties,

* '''Incorruptible''': The video file must be protected against any modifications once it has been used as a source for proof.
* '''Singular''': The proof shall validate a single identity without allowing duplicated participants in the network (''replicants'').
* '''Reputable''': Any <code>Organization</code> validating a POI attaches its reputation to the proven identity with its signature.

Even though any digital governance system can benefit from the trust already present in existing networks that validate identities (i.e. Nation-States), a decentralized protocol for validating identities serves the political purpose of personal sovereignty. The benefits of this public record in a networked commons can eventually be used by governments or private organizations in different ways (e.g. verifying age or nationality). Here we propose a new method for validating identites without the need of a single ''Big Brother''.

A ''Proof of Identity'' expires after a given period of time in order to prevent sybil attacks and ensure that only living users are participating in the network. To maintain the validity of the public-private key pair we suggest a period of 1 year is sufficient to generate a new proof updating the previous one. In the same way that physical identities are checked by comparing picture to person, users will need to re-create their ''Proof of Identity'' and broadcast it for verification in order to authenticate their legitimacy. This year period can be referred colloquially as the ''blockbirth'' of an individual and, if desired, celebrated on a yearly basis in the same way nations celebrate their independence day. As newborn babies are registered under this global jurisdiction, ''blockbirths'' get synced with birth dates and will be able to incorruptibly atest for age as well gradually reducing the work of authenticators over time.

====3.2.1 Demo.====

[[File:/images/roma-siri-blockchain-baby.png|Roma Siri's blockchain birth certificate.]]

There is a precedent that helps to illustrate how a ''Proof of Identity'' works. [https://youtu.be/Irc-VMuUs3c?t=55m20s According to NYU professor David Yermack], newborn Roma Siri became the first baby to have a blockchain valid birth certificate on November 7, 2015. The process, even though symbolic at the time, consisted of [https://www.dropbox.com/s/tsi4xo4k6j1jsa6/Blockchain%20Birth%20Certificate%20of%20Roma%20Siri%20-%20Daughter%20of%20Santiago%20Siri%20%28father%29%20and%20Pia%20Mancini%20%28mother%29.MOV?dl=0 a video showing baby Roma that described her vital signs and included witnesses of her birth]. Once the video was filmed, a cryptographic hash of the digital file was generated and encoded into a Bitcoin transaction. This means that regardless where the video is stored, the permanent record of its hash on the Bitcoin blockchain can verify that the file's data was not corrupted and that it existed at the time the proof was generated. With this incorruptible evidence, Roma became a blockchain-certified global citizen.

This demo serves as an example for the steps that need to be followed for a decentralized ''Proof of Identity'':

# '''Film proof''' using any available smartphone or camera.
# '''Hash proof''' on a blockchain to guarantee incorruptibility of evidence.
# '''Validate proof''' through a voting process among peers (''Attention Mining'').

====3.2.2 Video Proof.====

A proof can be done with any recording application as long as it satisfies the requirements of the protocol. An extension no longer than 3 minutes is recommended for the video. In it the user must follow a series of scripted steps in order to help validators judge with their attention:

# '''Face''': Under frontal light, film frontal expression (as when taking a ''selfie'') and each side of the head without wearing eyeglasses, hats, makeup or masks of any kind.

# '''Names''': Say out loud the following indicators:
## Full given name (language-based identity).
## Full surname (blood-based identity, additionally it can state information regarding mother and father).
## Nationality (territorial-based identity, it can include place of residence or tax paying jurisdiction).
## Alternatively the user can use a nickname if it is a more common pointer to his self.

# '''Biometrics''' (Optional): Say out loud or demonstrate in a reliable way any of these indicators. This can be useful for specific use cases such as birth certificates.
## Birthday (day, month and year).
## Height (inches or centimeters).
## Weight (pounds or kilograms).
## Gender (male, female, etc).

# '''Witnesses''' (Optional): Previously validated identities can act as witnesses for this identity. They can be physically on location and appear in the video stating their full names and public keys to endorse a new identity.
## The witnesses can get granted the rights to revoke, update or cancel this proof (e.g. in case of loss of private keys or biological death).
## Twins. Those who have a twin brother or sister must specify this to prevent being flagged as a ''replicant'' during the verification process.
## Certifications. Even though this would be falling back to central authority, legacy reputation from state-issued documents can help make a video proof easier to trust. This might include a birth certificate, driver's license or a national ID as long as it doesn't hold any sensitive information (e.g. using a Social Security Number in the US).

# '''Declaration''': To guarantee that the person generating his or her identity proof is aware of the rights he will receive upon having his membership approved on the network and is not being coerced by an unseen attacker, it is mandatory to make a declaration of self-sovereignty that also includes an oath regarding the stated facts: <blockquote>I, (Personal Name), declare that I'm making this video in accordance to my personal sovereignty as a citizen of Earth and all the statements made are true. I will be the sole user of all the ''votes'' allocated on behalf of this proof and I'm acting without any threat or coercion against my free will.</blockquote>

# '''Public Key''': An address where ''votes'' will be allocated if identity is validated. This will be the [https://github.com/WebOfTrustInfo/ID2020DesignWorkshop/blob/master/topics-and-advance-readings/DID-Whitepaper.md Decentralized Identifier (DID)] pointing to this user. If this identity eventually is voted as corrupted or the user (or any listed witness) revoke it, then the allocated ''votes'' will get invalidated for future use.

# '''Timestamp''': Current block height of the blockchain used for hashing this video to prevent any videos unrelated to the moment in time the POI is being generated to be used as proof. A manual timestamp can simply film the screen of a blockchain explorer application displaying the last block number and the hash corresponding to it. Since this might be complex for most users, apps designed to generate this proof can automatically add this content to the video. This information once the proof is hashed with a blockchain transaction will certify the video was not modified in any possible way by a third party after it was broadcasted to the network.

Even though this process can be more complex than the average sign-up form found on most applications, it is important to state that it is also a political act declaring independence from authorities of any kind. This video is the personal manifesto anyone can make to break free from coercion and a step taken towards a borderless democracy.

====3.2.3 Hashing.====

Once the digital file with the self-sovereign proof has been generated, a [https://en.wikipedia.org/wiki/Cryptographic_hash_function cryptographic hash function] applied to it is calculated. Following the steps of the implementation made by Manuel Araoz and Esteban Ordano with [https://proofofexistence.com ProofofExistence.com], a standard [https://en.wikipedia.org/wiki/SHA-2 SHA-256] digest is recommended. Once the hash has been generated, it can be encoded in a Bitcoin transaction using an [https://en.bitcoin.it/wiki/OP_RETURN OP_RETURN] script that also includes a marker that helps track identity-related proofs. We suggest using 'IDPROOF' (0x494450524f4f46) for this particular use case.

Considering that an average bitcoin transaction consists of 226 bytes with a mining fee as of August 2017 at 27,120 satoshis, the cost for hashing a proof directly on the blockchain is at ~$1 per proof. This can be relatively expensive for a majority of people, hence we recommend scaling this process by enabling a [https://github.com/aantonop/chainpoint Chainpoint] implementation able to store up to 10,000 proofs per transaction by putting the hashed data on a [https://en.wikipedia.org/wiki/Merkle_tree Merkle Tree] and encoding the Merkle root in the OP_RETURN script instead. This will also significantly reduce the memory requirements of the Bitcoin blockchain, a public resource that must not be abused. Alternatively, virtualchains that run on top of the Bitcoin blockchain that have a focus on identity and namespaces such as [http://blockstack.org Blockstack] can be used to satisfy this use case and the management of the private-public key pair.

Any proof that goes through this process in a digital context is guaranteed to not be corrupted in any way. The digital files being used as proof can be stored anywhere, copied without restrictions or even kept in secret without sharing it with anyone. As long as there is a transaction in the blockchain that can validate the encoded hash with the data of the digital file, then the evidence is valid. The Bitcoin blockchain offers the strongest resistance to corruption since it has the largest amount of hashing power in the world protecting its infrastructure. With this mechanism in place, the Bitcoin blockchain can operate as a decentralized index of self-sovereign identities. Leveraging this capacity will only make the bureaucracy of a borderless democracy stronger than any other government on Earth.

====3.2.4 Attention Mining.====
<blockquote>
  In the blockchain nobody knows you are an AI.
</blockquote>
'''Satoshi Nakamoto'''.

[[File:/images/proof-of-identity.png|Proof of Identity.]]

In computer-space identities are nothing but pointers: algorithms lack any awareness about the patterns they are trained to recognize. Identities strictly belong to the human realm (i.e. only a person can recognize another person). So rather than harnessing ''distributed computing power'' to verify transactions as it happens with most cryptocurrencies, ''votes'' use ''distributed attention power'' to verify self-generated identity proofs. This attention is brought in by human participants that act as validators.

A well known precedent of attention mining are CAPTCHA tests often found in the login of high-traffic websites. CAPTCHA is an acronym for ''Completetly Automated Public Turing test to tell Computers and Humans Apart''. These consist of simple vision excercises that can be completed by a human more easily than by a computer. A field [https://www.cs.cmu.edu/~biglou/reCAPTCHA_Science.pdf pioneered by researcher Louis Von Ahn], he used this technique to help build datasets able to train machine learning algorithms to read words printed on paper. As a Google engineer Von Ahn created a simple test distributed across all login pages that displayed two words obtained from scanned pictures. A user would write both words in a text input field to prove he is human and not a machine. The system already knew the meaning of the first word (hence validating the user is human) but it got trained with the second input as it uses this information in the dataset for character recognition algorithms. This simple excercise has been extended to train all kinds of pattern recognition systems and it contributed to the security of websites preventing bots (and botnets) from intruding.

Attention can also validate human identities on a decentralized network, analogous to [https://bitcoin.com/bitcoin.pdf Bitcoin's Proof of Work algorithm (POW)] used by mining nodes to timestamp peer to peer transactions. In Bitcoin, each miner generates its own blockchain-compatible proof hash for a new block of transactions and broadcasts it to the network. If 51% of the nodes in the network accept the verified block, it gets chained to the blockchain and the miner starts working on the next transaction block using the accepted block as the previous hash. This technique permits monetary transactions without central banks. In a democracy without central governments instead of verifying encrypted blocks, human attention serves the purpose of voting on self-generated identities in order to grant them ''votes'' which can eventually be used for new verifications.

Most of the research concerning how to prevent sybil attacks (identity forgery on peer to peer networks) revolves around requiring entities to perform a task that a sybil attacker would not be able to perform. Attention mining requires validators to observe certain aspects of ''Proof of Identity'' videos that only a person can recognize. In order to have a mechanism that prevents bots, the system can generate modified videos to induce attackers to error. These distortions can be created through cropping certain sections out of a video, mixing it with others or distorting voices to work as a video version of a CAPTCHA test aimed to securely distinguish between real human validators and botnets.

====3.2.5 Little Brothers.====
<blockquote>
  Who watches the watchmen?
</blockquote>
[https://en.wikipedia.org/wiki/Watchmen '''''Watchmen'''''], graphic novel (1987).

Self-sovereign identities can be valued on two key aspects that help define their right to participate in the network:

* '''Reputation''': A social indicator that a given identity is to be trusted.
* '''Singularity''': An individual indicator that certifies an identity is uniquely tied to a single person.

Anyone on the network can participate to verify new self-sovereigns in order to secure a global democracy against the threat of a ''Big Brother''. This task is effectively performed whenever an <code>Organization</code> decides to approve a new <code>Member</code>. By harnessing distributed attention across multiple <code>Organizations</code> instead of an all-observing central power, validators are in effect an army of [http://groups.csail.mit.edu/mac/classes/6.805/articles/crypto/cypherpunks/little-brother.txt little brothers] who can collaboratively score a self-sovereign identity in the network. ''Little brothers'' can outperform centralized identity providers in terms of accuracy as they are constantly incentivized to maintain legitimacy within the network in order to keep ''votes'' as a valuable asset: the success of the network on detecting ''replicants'' (duplicated identities) determines the scarcity of the ''vote'' token. The legitimacy of any democracy is based on the maintenance of a proper voter registry.

=====3.2.5.1 Reputation.=====

The interest on effectively validating a ''Proof of Identity'' is among <code>Organizations</code> that must deal with applicant identities willing to become <code>Members</code> able to use their ''votes'' for the decisions related to the entity. Those who within an <code>Organizantion</code> have the rights to approve new memberships end up contributing with the reputation an <code>Organization</code> has to the applicant identity if approved.

The allocation of reputation from an <code>Organization</code> to an approved <code>Member</code> that applied with its POI is done by simply signing the approved POI to certify that an identity is a valid <code>Member</code>. The memberships connected to an identity in the network can be interpreted by future validators on other <code>Organizations</code> in any desired way. <code>Organizations</code> in the network can be as small as a family or as large as a multi-national corporation, but ultimately they are <code>domains</code> in a network that can resemble <code>Tags</code> describing the attributes of an identity. Some <code>Organizations</code> may exist for very specific verifications, e.g. an <code>Organization</code> under a ''legal.age'' domain that only verifies if a POI belongs to someone older than 18 years making any approved <code>Member</code> of such entity carry a valid ''legal.age'' signature on its POI.

The reputation of an <code>Organization</code> can be measured on how often they end up allowing [https://en.wikipedia.org/wiki/Replicant ''replicants''] as <code>Members</code>. In other words: <code>Organizations</code> that fail on the ''Singularity score'' used to value the individuality of participants in the network, end up being less trustworthy than those able to effectively include sovereign individuals.

=====3.2.5.2 Replicants.=====

While governments need to verify the family tree of a potential new citizen and traditional corporations need to rely on [https://en.wikipedia.org/wiki/Know_your_customer ''Know Your Customer''] practices (KYC) to draw a line between their clients and the rest of the world; a global democracy has no such concern for establishing a difference between ''us and them''. The goal of Democracy Earth Foundation is to scale the right to use ''votes'' to every single human: we are all ''us'' (or ''them''). Hence, the overall challenge for a successful decentralized ''Proof of Identity'' dynamic is to simply focus on using the available attention in the network to check for ''replicants'' that are requesting a share of ''votes''.

''Replicants'' are identities that get ''voted'' as duplicates, illegitimately claiming more ''votes'' than they deserve. Fake POIs are likely to happen using modern techniques of 3D rendering aiming to trick the human eye (e.g. beating the [https://en.wikipedia.org/wiki/Uncanny_valley uncanny valley] of perception), but it is a safe assumption to consider that [http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Taigman_DeepFace_Closing_the_2014_CVPR_paper.pdf humans are able to recognize faces with 98% of accuracy] while [http://www.washington.edu/news/2016/06/23/how-well-do-facial-recognition-algorithms-cope-with-a-million-strangers/ the capacity of algorithmical systems decrease when scaled]. Considering that the frontier being drawn is between humans and artificial intelligences is that we use the term ''replicant'' which was coined for the 1982 film ''Blade Runner'' referring to androids capable of simulating being real people.

=====3.2.5.3 Singularity Score.=====

To certify an identity is valid, verifiers are exposed to two simultaneous POI videos that can be chosen at random from all the indexed and hashed videos found on the blockchain. A face-matching algorithm that seeks similarities among facial expressions can be used to optimize the test. Validators must use ''votes'' to agree whether these POI videos belong to a same person or not, being the ongoing result of this decision a ''Singularity score'' for the identity.

The validation process is the same as in every Sovereign voting dynamic: Validators can approve by casting a ''vote'' that includes a <code>Ballot</code> with a <code>true</code> checked <code>Option</code> on it. Otherwise they must cast a ''vote'' in rejection with a <code>false</code> checked <code>Option</code>. All POI related decisions are <code>Strategical</code>: without a closing date where allocated ''votes'' impact in real time. At any time a validator can override the ''vote'' value if it has found evidence that modifies previous judgement. Also ''votes'' validating a POI can be removed if the identity already has input from sufficient validators which makes allocation of additional ''votes'' redundant. As with any Sovereign decision, the end result of a POI related vote will end up on either a <code>true</code> or <code>false</code> value. Anyone who ends up being voted as a ''replicant'' will see his or her granted ''votes'' useless.

The <code>Criteria</code> used for the ''Singularity score'' is also subject for voting by every validated POI participating in the network. Democracies are always a work in progress, perpetually self-correcting with a feedback loop that defines how the observers get observed. The threshold that establishes the sovereign right to ''vote'' must constantly adapt to the exponential growth of computing capacity that can risk subverting the network. By being backed with a decentralized identity index using an incorruptible blockchain that gets maintained with distributed attention (i.e. an open face book), the ''vote'' token becomes a trusted device for a digital democracy to emerge anywhere. Allocating attention to secure the network not only brings consciousness to a system otherwise blind to artificial Intelligence, but also allows participants to own their identities without being coerced by a centralized power that could monetize from it without consent. Conscious attention must always be put in the service of strengthening a global democracy because it is only in the realm of human consciousness that we can define what it means to be human.

===3.3 Universal Basic Income.===
<blockquote>
  Now is the time to make real the promise of democracy.
</blockquote>
'''Martin Luther King Jr.''', Minister and activist (1929-1968).

The ability to develop a reliable self-sovereign identity validation process not only guarantees the legitimate value for ''votes'' to express social choice but also establishes the bedrock for the infrastructure required to make a ''Universal Basic Income'' (UBI) mechanism that can reach everyone on Earth. The symbiotic relationship of UBI and democracy has been well substantiated. According to research presented at Basic Income Earth Network (Munich September 2012), the implementation of basic income [http://basicincome.org/bien/pdf/munich2012/Choi.pdf can greatly contribute to realizing the principles of democracy as well as the establishment of its substantial foundation]. Therefore in order to consolidate the political and financial logic able to establish a borderless democracy, once a ''Proof of Identity'' is validated by peers the distribution mechanism triggered for ''votes'' will be based on time as a UBI.

Time is a valuable and limited asset, therefore tradable. One cannot buy, rent or hire more time: it has an inelastic supply no matter how high the demand. [https://books.google.com/books?id=sjlVAAAAcAAJ&pg=PA5&lpg=PA5&dq=what+is+money+man%27s+birthright+time&source=bl&ots=uxfZPDT94J&sig=gWf_LpHeEA-g6ukveZ1-mQI3FE4&hl=es&sa=X&ved=0ahUKEwjgyuHR2ejVAhUK7iYKHUX0AzgQ6AEILjAB#v=onepage&q=what%20is%20money%20man's%20birthright%20time&f=false Time is the only standard of value by which to test all the labour, either manual or mental, done by men and women]. And by tokenizing time and using it as the basis for allocating ''votes'', it liquidates a possession that every member of a global democracy possesses on equal terms. Liquidity is a requirement for any democracy that aims to avoid coercion: voices must be able to be heard in order to count and by granting ''votes'' as a UBI we are tapping on delivering a human right that can effectively empower individuals that will have to face the coming challenges of automation. ''Votes'' granted throughout time as a right avoids the [https://en.wikipedia.org/wiki/Tragedy_of_the_commons ''tragedy of the commons''] while it sets the foundations for a governance model that goes beyond debt and Nation-States.

A self-sovereign then, is able to obtain ''votes'' in three different ways:

* '''Delegation''': Any <code>Member</code> within an <code>Organization</code> operating as a liquid democracy can get delegated ''votes''.
* '''Grant''': <code>Organizations</code> may grant ''votes'' to new participants on its own terms. Participants can create or fund <code>Organizations</code> using their own ''votes''.
* '''Drip''': Once a ''Proof of Identity'' becomes valid, ''votes'' begin to drip on the user's wallet throughout time.

====3.3.1 Dripping.====

The rate at which 1 ''vote'' gets dripped to a verified identity is syncronized with the Bitcoin blockchain. By using Bitcoin's synchronization mechanism as a clock, an incorruptible consensus sets the rythm for the whole network. Bitcoin chains a new block to the blockchain every 10 minutes, which means,

  1 hour = 6 blocks

Assuming that earnable time across the globe is based on 8 hour work days,

  8 hours per day x 5 days per week x 52 weeks per year = 2,080 hours per year

Or in block time,

  2,080 hours = 12,480 blocks

And considering that established consensus on [https://medium.com/economicsecproj/how-to-reform-welfare-and-taxes-to-provide-every-american-citizen-with-a-basic-income-bc67d3f4c2b8 an ideal basic income rate averages around 10% of an individual's earnings] we can define that,

  10% earnings Annual Basic Income = 208 hours per year = 1,248 blocks

Which means that of the ~52,560 blocks that register a full year of activity on Bitcoin's blockchain, a total of 1,248 blocks should be accounted for rewarding a UBI per year. To sync ''vote'' dripping with Bitcoin as a UBI mechanism based on 10% earnings for every working hour, 1 full unit of a ''vote'' token should then drip every ~42 hours (or ~252 blocks). For the purpose of guaranteeing a feasible divisibility of the ''vote'' token so it can be dripped every few seconds (while it also becomes easier for human and machine interpretation), we set the dripping rate at,

  1 vote = 250 blocks

So every valid POI gets granted a total of:

  210 votes per year

[[File:/images/proof-of-identity-dripping.png|Dripping mechanism for mined votes.]]

Therefore by taking into account the following variables:

* T = Present block height (i.e. current Time).
* r = A constant for ''vote'' allocation rate, set at 1 vote every 250 blocks in time.
* Pᵢ = The ''Proof of Identity'' block containing its corresponding hash for a given identity (i).
* Sᵢ = ''Singularity score'' expressed as a <code>true</code> or <code>false</code> state for a given identity (i).
* Vᵢ = Total quantity of ''votes'' for a given identity (i).

Then the ''votes'' a self-sovereign identity is allowed to use in the system can be calculated on any node running a smart contract with the formula:

[[File:/images/ubi-vote-formula.png|Vᵢ = ((T - Pᵢ) / r) * Sᵢ]]

As long as the ''Proof of Identity'' has been validated by the community and a smart contract is synced with an active blockchain node, then the value of Vᵢ will either be a number that defines the total amount of ''votes'' a self-sovereign has as a right to use on a hosted wallet or, if the POI is rejected (i.e. Sᵢ = <code>false</code>), then the participant's available votes becomes zero.

====3.3.2 Equality====

The described dripping dynamic ends up benefitting early-adopters as it is often the case with financial-oriented cryptocurrencies. Bitcoin for instance is often described as ''cryptographically induced scarcity'' as it is an instrument able to measure wealth in terms of economical resources due to the fixed scarcity of its token. But with the ''vote'' token we are building a network of a different nature that aims to be complementary to financial cryptocurrencies by having governance as a goal. By issuing ''votes'' as a right that can be granted to anyone as long as his or her singular identity is proven, the ''vote'' operates as political clout. So in essence, our approach is about ''cryptographically induced equality'': such is the basis for any real democracy. For this reason we introduce another variable to its ''Universal Basic Income'' dynamic,

* E = Amount of ''votes'' allocated to the ''Genesis Identity'' at present block height (T).

We refer to the ''Genesis Identity'' as the very first ''Proof of Identity'' that gets approved by the network. With this information the next validated identity won't begin in disadvantage: it will have a wallet with the same amount of ''votes'' than the first participant in the network currently has. Since this rule applies to every participant it will guarantee ''Equality'' in terms of participation letting everyone have the same amount of Sovereign ''votes'' than everyone else, extending the UBI formula as follows:

[[File:/images/ubi-equality-formula.png|Vᵢ = (E + ((T - Pᵢ) / r)) * Sᵢ]]

With the ''Equality'' variable, if a second participant Bob got validated 1500 blocks after a first one Alice, he won't begin with 0 ''votes'' but rather get an initial amount matching Alice's current balance at that moment (i.e. at a rate of 1 ''vote'' per 250 blocks, it is a total of 6 ''votes''). Bob will continue to get ''votes'' dripped on equal terms with Alice block after block after that. If a third participant Charlie generates a valid ''Proof of Identity'' 1000 blocks later, he will begin with the equivalent amount of ''votes'' that Alice and Bob each currently have by then as well (i.e. a total of 10 ''votes'' each). With this inflation process that rewards every new participant (diluting all pre-existing ones), everyone is guaranteed an ''equal'' share in the overall participating rights of the network. As long as ''replicants'' get successfully banned, the ''vote'' network is a genuinely democratic global commons.

[[File:/images/chart-votes-coins-time.png|Vote emission and inflation rate.]]

Even though the inflation rate might initially seem too aggressive, the total supply of ''votes'' is still fixed to a maximum cap based on the quantity of participants in the network. As more participants engage, the overall inflation will tend to limit 0% since new ''votes'' have a reduced influence in the economy as a whole. When compared to uncapped ''likes'' and ''retweets'' in other social applications, it must be noted that from the subjectivity of each individual the allocation of ''votes'' is still a decision based on a limited resource that implies opportunity costs, forcing a more rational behaviour rather than impulsive liking (i.e. trolling).

====3.3.3 Nakamoto Coefficient====

Significant efforts on quantifying decentralization are being made, including Balaji Srinivasan's work on establishing a [https://news.21.co/quantifying-decentralization-e39db233c28e ''Nakamoto Coefficient''] defined as:

<blockquote>
  The minimum number of entities in a given subsystem required to get to 51% of the total capacity.
</blockquote>

The importance of measuring decentralization relies on finding a metric able to certify the ability of a network to be censorship resistant, being this a fundamental property for self-sovereign currencies such as Bitcoin. But ultimately the question of who is in control of the entities running a networked system must be addressed as well. By establishing a reference network that guarantees an egalitarian distribution of its token based on a ''Proof of Identity'' mechanism designed to prevent ''replicants'', this brings in a new perspective that can help increase the resolution of the Nakamoto Coefficient by means of discernible equal access.

By guaranteeing an equal starting point for every participant regardless of the time they decide to join the network, the ''vote'' network operates as a genuine meritocracy. The proposed ''Equality'' variable is simply a rule for establishing a starting point and by no means a permanent imposition: at any time, any self-sovereign is allowed to either delegate ''votes'' to someone else or use them to start an <code>Organization</code> in the network. In this way, the ''vote'' token can work as a device fit to foster a wave of entrepreneurship even among today's disenfranchised individuals left out by the legacy financial and political systems. But as this happens on the individual level, the overall statistics of the network itself works as a reference framework in which to effectively measure decentralization down to each human across the globe and identify opportunities where its needed as it grows.

The value of the network does not reside on the simulated scarcity but on its ability to register uncoerced decisions among self-sovereigns on the basis of equality. Initially the ''vote'' token might be able to compete with pollsters and any other rudimentary simulations that aim to predict elections, but eventually it can become a sovereign system on its own right as citizenship migrates online. ''Votes'' operate as a signal able to register events recorded on an incorruptible blockchain that stores political history that cannot be erased or modified in any way. Future generations get exposed to their past without intermediaries.

===3.4 Value===

We take three approaches to define the value of the ''vote'' token:

* '''Status-Quo''': Social media offers a clear reference on how ''likes'' get valued online.
* '''Work & Time''': A ''Universal Basic Income'' perspective offers useful insights on how labour time is being valued.
* '''Nation-Sates''': Traditional elections offer useful insights on how votes are valued today.

With those references, we then discuss the divisibility of the ''vote'' token and its implementation to govern a Democracy Support Fund.

====3.4.1 Status-Quo====

A comparative benchmark for the value of the ''vote'' token can be found on the Facebook network currently valuing 2 billion users with a market capitalization of ~$500 billion averaging an estimate of '''$250 per user'''. Democracy Earth Foundation regards Facebook's ''like'' function analogous to using ''votes'' in an open network. It is hard to estimate the quantity of ''likes'' made on this platform since it's private information and raw estimates project ''likes'' happening in the amount of trillions on a daily basis.

Marketers that operate the Facebook advertising machine price ''likes'' in a range that can go from '''$0.10 to as high as $25''' based on the reputation and popularity of the account being used to capture user attention. In this sense, we believe this price reference is relevant for end-users in order to empower them with a token that can be competitive with leading social media platforms. But it must be noted that unlike ''likes'', ''votes'' directly empower holders with the right to participate in any financial benefit that can be connected to their use without intermediation. With ''votes'', profiting from user data will no longer be the exclusive domain of the Facebook middleman but instead will be enabled by a native token generation mechanism that is based on the principles established by the [http://www.un.org/en/universal-declaration-human-rights/ Universal Declaration of Human Rights]:

<blockquote>
  Everyone has the right to freedom of opinion and expression; this right includes freedom to hold opinions without interference and to seek, receive and impart information and ideas through any media and regardless of frontiers. Everyone has the right to freedom of peaceful assembly and association. Everyone has the right to take part in the government of his country, directly or through freely chosen representatives.
</blockquote>

With the creation of Sovereign as an interface for blockchain-based democracies operating with ''vote'' tokens, Democracy Earth Foundation's aim is to deliver a ''Linux moment'' to Facebook: analogous to the rise of open source operating systems in the early 1990's, Linux became an alternative to the monopolizing force of Microsoft's Windows that dominated the market of personal computers and internet servers. A free and open Internet must pursue the creation of a social network where no single entity can excercise algorithmic control of the shared ideas in exchange for the private information of its users. And while Facebook mines user attention for profit, the Democracy Earth network will use the same resource to strengthen the trust of the ''vote'' token with its ''Proof of Identity'' process. As we acknowledge the growing political influence social media already has in the world, the urgency of laying out an open social network that is uncensorable, sovereign and free becomes pressing.

====3.4.2 Work & Time====

Coming from a ''Universal Basic Income'' perspective, a useful reference that values time and labour is the proposed [https://en.wikipedia.org/wiki/Minimum_wage_in_the_United_States minimum wage in the US] based on federal, state and local laws across the country. As of July 2016 it has been set at '''$7.25 per hour'''.

[[File:/images/minimum-wage-us.png|Minimum wage in the US.]]

For the ''vote'' token to effectively become a useful network able to index UBI on a global scale, an expectation regarding its pricing dynamic must be set at 1 ''vote'' unit as equivalent to 1 hour of work. Hence this anchors the initial price of the token at:

  1 vote = $ 7.25

As long as the network successfully bans ''replicants'' and rewards validated self-sovereign identities indexed on the Bitcoin blockchain, then any UBI initiative can trust the present data to allocate resources without the risk of abuse.

====3.4.3 Nation-States====

From a Nation-State perspective, a useful reference can be found in the cost for implementing national elections. The 2016 Presidential Race in the United States had a total cost as high as [https://www.opensecrets.org/overview/cost.php $ 2,386,733,696]. Even though it had the lowest voter turnout in 20 years, an estimated total of [https://en.wikipedia.org/wiki/Voter_turnout_in_the_United_States_presidential_elections ~138,847,000 voters] participated. Hence, a simple calculation can price the vote token issued by the US government for this electoral process at '''$ 17.18 per vote'''. On the other end of the spectrum, developing nations like Argentina offer a similar reference: their 2017 legislative election had an estimated cost of [http://www.lanacion.com.ar/2034493-las-paso-costaran-2800-millones-pero-casi-no-definiran-candidatos $ 164,705,882] with a total of [http://www.elintransigente.com/politica/2017/8/13/cuantos-argentinos-votaron-paso-449552.html ~24,500,000 voters], setting the price at '''$ 6.70 per vote'''. It is within that range of value that Nation-States invest resources to guarantee voting rights to all its citizens.

[[File:/images/cost-of-us-elections.png|Cost of US Elections.]]

According to Facebook's seed investor Peter Thiel, a rule of thumb for technological innovation is that in order to beat a precedent paradigm, an innovation must outperform the task of the previous way of doing things [http://zerotoonebook.com/ by at least a factor of 10] in terms of cost and utility. For example: the digital word processor became successful because it does what a typewriter did in a way that can be considered at least ten times better and ten times cheaper. The same applies to fax in contrast to the postal service; and e-mail in contrast to fax. Hence the transition from traditional voting to a new standard of blockchain based voting should work on the same basis.

A simple comparison shows the strict limitations electoral votes have in comparison with the ''vote'' token proposed on this paper:

* '''Expensive Security''': Nation-State's ''Proof of Identity'' demands several resources to identify citizens during many stages of their life. Birth certificates, passports, driver's license, national ID cards, social security, wedding certificates, death certificates are all aimed at keeping the public record of citizens up to date. This is the leading function of the State and it can lead to persecutory behaviour.
* '''Limited Utility''': Once a citizen casts a vote during an election, it cannot be modified until 4 to 6 years later when the elected positions get renovated. Only those among the elected positions (i.e. senators and congressmen) get the right to spend more votes than the rest of the citizens.
* '''Reduced Bandwidth''': Citizens get to choose from a handful of options only once every 2 or 4 years. If we consider each option as a bit on the system then traditional elections can be regarded as ''8 bit democracies'', such is the current bandwidth for participation under most governments.

In order to maintain the reference price set at the minimum wage in the US while being able to be at least ~10X more efficient than any traditional election, ''vote'' utility must be extended by making the token divisible.

====3.4.4 Divisibility====

The waiting period of 250 blocks for every new dripped ''vote'' limits the perceived gratification delivered by the system to every ~42 hours. This constraint is set in order to tie the economic logic of the ''vote'' token to its capacity of indexing all the successful ''Proof of Identities'' to a ''Universal Basic Income'' dripping dynamic. But the ability to begin interacting with the system itself shouldn't require a long waiting period: by introducing decimal positions, the network can offer instant gratification by adapting the dripping dynamic down to a minimum fraction of human attention.

Considering that,

  1 vote = 250 blocks = 2,500 minutes = 150,000 seconds

To keep the shortest possible decimal extension while adapting the dripping rate to the minimum span of human attention, the ''vote'' network should perform a revolution every 15 seconds:

  15 seconds = 0.0001 votes

In the same way the minimum fraction of a Bitcoin is branded as 1 satoshi (i.e. 100,000,000 satoshis = 1 bitcoin), we consider it is suitable to brand the minimum fraction of a ''vote'' as a ''revolution'' since this concept helps to express the speed at which the network grants political rights,

  1 vote = 10,000 revolutions

Which can also be expressed as,

  1 revolution = 0.0001 votes

By allowing 4 decimal positions in the token, a ''revolution'' gets dripped to a valid ''Proof of Identity'' in the network every 15 seconds. ''Revolutions'' bring almost instant access to political rights while keeping the same utility capacity as ''votes'' with a cost that is comparatively 10,000X more efficient than Nation-State elections:

  1 revolution = 0.0001 votes = $ 0.000725

For the identification of the token in third party applications, we suggest the ''VOTE'' and ''VOT'' tickers.

===3.5 End Game.===

<blockquote>
  “What happened to the governments?” I inquired. 
  “It is said that they gradually fell into disuse. Elections were called, wars were declared, taxes were levied, fortunes were confiscated, arrests were ordered, and attempts were made at imposing censorship — but no one on the planet paid any attention. The press stopped publishing pieces by those it called its ‘contributors,’ and also publishing their obituaries. Politicians had to find honest work; some became comedians, some witch doctors — some excelled at those occupations…”
</blockquote>
'''Jorge Luis Borges''', ''Utopia of a Tired Man''. Writer (1899–1986).

To those who argue about electronic voting online scoring their arguments with Facebook ''likes'': [https://en.wikipedia.org/wiki/The_medium_is_the_message ''the medium is the message'']. The need to establish trusted relations in digital environments is mandatory as human cooperation scales to the whole globe. But the generational opportunity to collaboratively build this possibility must be able to learn from the great lessons of History. The origins of computing goes back to [https://en.wikipedia.org/wiki/History_of_IBM#1880s.E2.80.931924:_The_origin_of_IBM the first tabulating machine built by IBM for the 1890 US census] and the tallying of national elections after that. The very first proto-computers built by Alan Turing where made as a war effort able to beat nazi encryption ultimately demonstrating how intelligence can beat violence. The transition from analog to digital communications began with the [https://wheatoncollege.edu/provost/2016/03/21/claude-shannon-and-the-magna-carta-of-the-information-age/ Magna Carta of the Information Age] published by Claude Shannon in 1948 laying out the foundations for digital code and vast networks for the transmission of intelligence, a vision made real by Sir Tim Berners-Lee's creation of the ''world wide web'' protocols. When Satoshi Nakamoto published the Bitcoin paper he inaugurated the era that is giving rise to the transition from analog to digital ''institutions''. An inevitable leap from maturing our shared understanding of the properties of information security. Blockchains are giving our world a new canvas in which to lay foundations that shall govern us all to the point of being worthy of not needing governance anymore. After all [https://en.wikiquote.org/wiki/Alfred_North_Whitehead civilization advances by extending the number of important operations which we can perform without thinking about them]. Digital technology has proven to possess a greater capacity in the reach and quality of its messaging abilities and as new generations grow connected under a global commons, information architectures will regulate our political and financial relations without the physical restrictions of the past. The undeniable success of the Bitcoin experiment consistently beating even the most radical forecasts throughout a decade speaks greatly about the unleashed potential humanity has found. The status-quo will always speak from a skeptical position since halting progress can only come from a position of comfort. But just as the Internet didn't wait for the adaptation of age-old empires, blockchains won't care for political promises: a technologically advanced society can enter agreements of mutual cooperation without falling back to the means of coercion and violence. Such is the remarkable consequence of disintermediation of trust without boundaries, a reality that won't emerge in a single isolated part of a country or region of the globe, but will be distributed across the entire planet. The ''next Silicon Valley'' is not in a far away land or on any land at all, but a new frontier of the internet itself rising as the one true open, free and sovereign network of peers.

----

==4. About.==

The Democracy Earth Foundation is an effort made possible by collaborators, donors and supporters of all kinds. We are a 501 (c) 3 not for profit organization from California and with presence in New York, Paris, Buenos Aires and San Francisco.

===4.1 Team & Collaborators.===

Santiago Siri, Virgile Deville, Paula Berman, Eduardo Medina, Herb Stephens, Sandra Miller, Dwight Wilson, Mair Williams, Louis Margot-Duclot, Felipe Alvarez, Cyprien Grau, Peter Schurman, Andrew James Benson, Gonzalo Stupenengo, Lucas Isasmendi.

===4.2 Advisory Board.===

Pia Mancini, Alexis Ohanian, Matias Mosse, Ariel Kogan, Ernesto Dal Bó, Kate Courteau, Giorgio Jackson, Julio Coco, Dan Swislow.

===4.3 Individual Donors.===

Ricardo Gorodisch, Matias Mosse, Krishna Bahrat, Wenceslao Casares, Dwight Wilson, Marcos Galperin, Alejandro Estrada, Chris & Hedy Eyre, Kevin	Barenblat, Clinton Yara, Tom Preston-Werner, Lloyd Nimetz, Eduardo Medina, Jim D'Amico, Erik Walter, Vivek Krishnappa, Kevin Berk, Micah Rosenbloom, Karén Gyulbudaghyan, Satoshi Nakamoto, Paul Wehrley, Josh Jacobson, Allison Sparks, Ahin Thomas, Ron Hirson, Ken Ettinger, Sharon Goldstein, Shreenath Regunathan, Matt Price, Josh Zaretsky, Heejae Lim, Allison Koblick.

===4.4 Acknowledgements.===

These are some of the minds that inspired the ideas expressed on this document.

Nick Szabo, Nubis Bruno (Bitex.la), Cesar Hidalgo (MIT), Balajis Srinivasan (21.co & Anderssen Horowitz), Andrea Antonopoulos (Bitcoin Evangelist), Peter Asaro (Stanford), Naval Ravikant (Angel List), Guillermo Rauch (Zeit), Andrew DeSantis (E8), Greg Slepak (Open Turtles), Demian Brener (Zeppelin), Manuel Araoz (Zeppelin), Ralph Merkle, Satoshi Nakamoto (Bitcoin), Vitalik Buterin (Ethereum), Vlad Zamfir (Ethereum), Joseph Lubin (Consensys), Ryan Shea (Blockstack), Muneeb Ali (Blockstack), Luis Cuende (Aragon), Vinny Lingham (Civic), Luke Duncan, David Graeber (London School of Economics), Peter Schurman (One Global Democracy), Jim D'Amico, Federico Ast, Harry Halpin, Guy Standing (University of London), Sebastian Serrano.

===4.5 Supporters.===

These organizations supported our work through grants, partnerships and recognition to our research and development efforts.

[[File:/images/grants-awards-support-organizations.png|Grants, awards and support from these leading organizations.]]