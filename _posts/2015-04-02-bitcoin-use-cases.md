---
layout: post
title: Bitcoin's use cases
excerpt: "Bitcoin’s use cases are huge, but mostly illegal in the US. There’s much hype around the legal use cases, but those have little value."
tags: [sample post, code, highlighting]
modified: 2015-04-02
comments: true
public: true
---

> TLDR; Bitcoin’s use cases are huge, but mostly illegal in the US. There’s much hype around the legal use cases, but those have little value.

Money needs to be used, else it has no value. So what’s the use for Bitcoin? For the average consumer, the answer is simple - buying drugs online. However, Bitcoin enthusiasts disagree, claiming illicit activity is practically non-existent. Instead, they preach decentralization, trustlessness and smart contracts - none of which are benefits but merely features.

The average consumer lacks vision but is honest, the Bitcoin enthusiast sees glimpses of the future but ignores the truth. The truth is uncomfortable. Here’s how I see it:

<img src="/images/bitcoin.jpg">


# Illegal, and Useful

## Fully illegal

Bitcoin is great for illegal goods/services. These make up a significant portion of transactions.

Traditionally, drug dealers had no other way to accept money online, because banking services are denied to them - the chokepoint. You can’t buy crack online with AMEX, but Bitcoin is accepted.

Tax evasion and escaping capital controls are also possible with Bitcoin, in the same way cash smuggling works. However, it’s more convenient to do it online via Bitcoin.

Bitcoin is powerful because it allows people to circumvent regulations, as it does not rely on the traditional banking system. It is both a standalone currency and payment system, combining the function of the US Dollar and VISA into one protocol.

However, Bitcoin’s future is pessimistic if its only use cases are anti State policies. The DEA is armed with $3bn/year[^1] to sustain the drug war, and the US Government simply isn't going to tolerate people using Bitcoin to evade income taxes.

## Semi-illegal

The secret is that opportunities lie in the grey areas. Enter the world of ‘high risk merchants’. Stripe’s prohibited businesses list[^2] provides some great examples. They are mostly gambling, marijuana, and porn - all huge markets.

Payment processors and banks won't serve these businesses because their legal status is uncertain, many violate “sin clauses”, and chargeback fraud is high. In 2013, the Department of Justice's (DoJ) “Operation Choke Point” initiative[^3] pressured banks to cut off bank services to merchants deemed “high risk”. They need not prove these merchants had even violated the law. This initiative has since been abandoned but processors and banks still remain rightfully cautious. They don’t want to get their funds seized or damage their reputation if the DoJ flips the other way.

Many of these goods/services are not against public policy, and the law is changing. But there’s a limbo phase where banking services will still be denied. Bitcoin fills this gap.

## Gambling

Online gambling is a $30bn+ market worldwide, $300bn including offline[^4]. The potential is even greater if Americans and Chinese consumers could gamble. However, online gambling is illegal in the US and depositing/withdrawing money into foreign sites is difficult.

Since 2006, the UIGEA[^5] has legally prevented payment processing for gambling transactions, even for offshore sites. However, many gambling sites still engaged in bank fraud to circumvent these rules. This collapsed in 2011 when the DoJ crackdown cracked down on the Poker Sites[^6]. The payment processors serving these sites had their entire accounts seized, and end users ultimately lost all their money.

Given the huge latent demand for gambling since, it’s no surprise gamblers have embraced Bitcoin to fund their activities. Not only does Bitcoin enable them to fund their accounts on unlicensed gambling sites, it also gives them control of their funds and instant deposits/withdrawals. A plethora of unlicensed operators have emerged to serve these customers. Gambling is the one of the most active threads on BitcoinTalk[^7].

Most developments in Bitcoin gambling will occur outside the US, because basing operations in the US will result in criminal prosecution. For example, Bryan Micon[^8], the operator of the largest Bitcoin Poker site, was recently arrested in his home in Nevada. Even UK based public gambling company CEOs (e.g. David Carruthers[^9]) have faced arrests during transit flights in the US. The DoJ is letting the world know they don’t care about international law and whether or not operators are licensed in another jurisdiction. If operators accept money from US players, the DoJ deems them to have broken US law and will prosecute.

The alternative for operators is to avoid the US. Moreover, no country will extradite operators to the US if their operation is legal within that country. Gambling billionaire Calvin Ayre, for example, still enjoys his life in the Caribbeans despite being indicted in Maryland[^10].


# Legal, and not Useful

## Normal Merchants
Normal merchants (such as Overstock, Dell and Newegg) have only marginal advantages in accepting such Bitcoin.

Coinbase and Bitpay (the “Paypals for Bitcoin”) preach accepting Bitcoin will mean:

1. no chargebacks, and
2. only 0-1% in merchant fees rather than 2-3%.

However, "no chargebacks” is not a benefit. It simply pushes the responsibility to the buyer, resulting in a “buyers beware” model and eliminates consumer protection. With credit cards and paypal, you could at least do a chargeback if the merchant is dishonest and refuses refunds. There are probably better ways to handle disputes, but Bitcoin itself does not solve for this.

Furthermore, consumers still need to pay exchange fees when buying Bitcoin (~1% on Coinbase). Coinbase then charges the merchant 1%. Given the risk of volatility, 0-1% in net savings is marginal. Some will argue that volatility will decrease when there are more transactions. That’s a catch 22. There won’t be more transactions if Bitcoin doesn’t have a clear use case. Some services (such as BitReserve) are attempting to insure/hedge against volatility, but that won’t experience net savings because the round trip conversions will cost another ~2%.

The main benefit of adopting Bitcoin is press coverage and the temporary spike in sales.

## Remittance

Remittance using Bitcoin is not useful because the overall transaction costs are still high. Bitcoin transactions are very low cost, but users need to factor in the exchange rate spread and service fees. Assuming the receiver wants local currency, not Bitcoin, 2 currency conversions need to take place. Sure, if the receiver wants Bitcoin then this remittance model works. But again, that’s a catch 22.

Also, receivers in emerging economies often don’t have access to banking services. Rather, they collect the money from “local agents” such as restaurants or convenience stores. This is the “last mile” problem, which Western Union solves. However, establishing and managing a distribution network of local agents can be expensive. Bitcoin itself doesn’t solve that.

There are more promising models for remittance, such as TransferWise’s P2P model[^11] which avoids the need for correspondent banking. For example, instead of converting USD to BTC to Peso and getting screwed on the exchange spread, users convert USD directly into Mexican Peso at the spot rate amongst each other. This is made possible by getting paired with a transaction coming the opposite way.

## Micro-transactions

Micro-transactions using the Blockchain are not useful because the fees are only marginally lower. It’s also uncertain whether these fees will remain low as block rewards are lowered. Any micro-transaction service will need to build their own payment network atop the Blockchain to avoid the miner fees, and only use the Blockchain for settlement.

Companies like Dwolla[^12], who have already built such payment networks on atop ACH are more promising for micro-transactions. Users can also send and receive money directly in USD for 25c or lower. International micro-transactions can then be paired with a P2P model (e.g. TransferWise).

## Speculation

Speculation is not a use case. Its function is to provide liquidity to the market.


# Illegal, and not Useful

## Scams

Bitcoin enables a new class of scams because it can be used anonymously online.

For example Trendon Shaver’s Bitcoin Savings and Trust was the largest scam in Bitcoin history[^13]. It was a classic ponzi scheme that promised a guaranteed daily profit for 1% before disappearing with 500,000 Bitcoins in August 2012. For whatever reason, he did not chose to remain anonymous. Soon enough, the SEC charged him with defrauding investors in a Ponzi scheme and he now faces a $40m fine and up to 20 years in prison.

## Unregistered Digital Assets

Assets such as stocks and bonds issued via counterparty are illegal if they are not registered with the SEC. The SEC has already taken action against unregistered asset issuers. For example, Eric Vorhees was fined $50,000 for his illegal Satoshi Dice IPO[^14].

However, registering with the SEC defeats the purpose of digital assets whose promise was to become self-regulating and cost effective. Once rule of law is reintroduced, the compliance costs make digital assets no better than “paper” assets. The alternative, again, is to become an asset issuer outside the reach of US jurisdiction.


# Legal, and Useful

The magical unicorn everyone is trying to find is something both legal and useful.

## Non US-Jurisdiction

Legality depends on jurisdiction. Entrepreneurs could simply base themselves in a place where the “Illegal and Useful” use cases are “Legal and Useful”. Antigua is one such jurisdiction to operate an online gambling site. There’s even international legal precedent that suggests this is acceptable[^15] However, entrepreneurs would need to give up ever coming back to the US, as the DoJ doesn’t care about international law.

## Internet of Things protocol.

One possibility is using Bitcoin’s core technology, the Blockchain, as a middleware protocol for IoT communications. In the Internet of Things, there’s a “basket of remotes”[^16] problem where hundreds of applications need to interface with hundreds of devices. Right now, they don’t share common protocols and there is a lack of standards in areas of security, privacy, architecture and communications.

Large companies (e.g. Apple, Samsung) will no doubt jockey for market power and push their proprietary “standard”. This will force consumers to buy 100% into Apple devices for their homes to have a true IoT experience. Whole buildings will need to decide upfront whether they wish to be Samsung or Apple compatible.

The Blockchain could solve for compatibility and interoperability. IBM’s ADEPT protocol[^17] is a promising first jab at this. It utilises 3 P2P technologies (including Ethereum’s blockchain) for authentication, bartering and data transfer. This could lead to a better world where things are truly connected and not restrained to vendor ecosystems. It will fuel more innovation and experimentation because open networks attract development. The cost of co-operation and doing business would be greatly reduced. Unlike financial services and bitcoin, innovators in IoTs won’t need to deal with the legacy issues of the old world.

# Conclusion

It’s incorrect to say Bitcoin doesn’t have a use case. It does. It's just illegal in the US.

---

[^1]: <http://www.dea.gov/docs/1207_fact-sheet.pdf>
[^2]: <https://stripe.com/us/prohibited-businesses>
[^3]: <http://en.wikipedia.org/wiki/Operation_Choke_Point>
[^4]: <http://www.statista.com/statistics/270728/market-volume-of-online-gaming-worldwide/> and <http://www.statista.com/topics/1368/gambling/>
[^5]: <https://www.law.cornell.edu/uscode/text/31/5363>
[^6]: AKA Poker Black Friday <http://www.cnbc.com/id/42649117>
[^7]: <https://bitcointalk.org/index.php?board=56.0>
[^8]: <http://www.pokernews.com/news/2015/02/seals-with-clubs-chairman-bryan-micon-police-raid-20740.htm>
[^9]: <http://en.wikipedia.org/wiki/David_Carruthers>
[^10]: <http://www.apcw.org/legal-documents/Bodog%20Indictment.pdf>
[^11]: <https://transferwise.com>
[^12]: <https://www.dwolla.com>
[^13]: <https://www.sec.gov/litigation/complaints/2013/comp-pr2013-132.pdf>
[^14]: <https://www.sec.gov/litigation/admin/2014/33-9592.pdf>
[^15]: <http://www.usitc.gov/publications/332/journals/online_gambling_dispute.pdf>
[^16]: <http://www.mondaynote.com/2014/01/12/internet-of-things-the-basket-of-remotes-problem/>
[^17]: <http://www.scribd.com/doc/252917347/IBM-ADEPT-Practictioner-Perspective-Pre-Publication-Draft-7-Jan-2015>
