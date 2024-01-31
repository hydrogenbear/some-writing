# Reassessing the Poption Project

For the past two years, I have been engrossed in developing a DeFi derivative called Poption. Despite my efforts, I've decided to move away from this venture. My confidence in DeFi as a solution to the problems I aimed to solve has diminished. Nevertheless, I believe there's value in sharing the lessons learned from this experience, as we can often gain insights even from endeavors that don't pan out as expected.

## Identifying Financial Market Challenges

The financial landscape two years ago was punctuated by several significant events: the GME short squeeze, WTI's dive into negative pricing, and the London Nickel squeeze. These events inspired me to explore strategies to prevent such market anomalies. I came up with several approaches that could offer solutions:

1. **Contractual Precision:** It is crucial to have precise and unambiguous contracts from the start. Mid-course alterations, like changing a non-negative number to an arbitrary one, can lead to chaos. Thus, any contract modifications must be handled with utmost care.
2. **Hedging on Native Markets:** Relying on distant markets with only similar products for hedging introduces substantial and unforeseen risks.
3. **Rethinking the Atom unit in Option Trading:** The market should aim to reduce unnecessary naked short selling. Echoing Elon Musk's views, it is unfair for large entities to sell what they don't own. A viable alternative could be for market makers to trade in bundled option strategies such as call/put spreads or butterflies, which can help in managing high-risk positions more responsibly, as seen in the GME scenario.

## Blockchain: Potential and Pitfalls

Initially, I was optimistic about blockchain being the panacea. Its trustless nature and the clarity of smart contracts seemed to perfectly align with the needs for **contractual precision** and establishing **native markets**. My plan included a decentralized exchange (DEX) on the blockchain, facilitating trades in Poption, my innovative derivative designed to offer the benefits of traditional options but without the necessity for naked selling.

However, I encountered significant roadblocks. The absence of a robust derivatives market in the blockchain space posed a major impediment. Traditional assets, already well-served by conventional derivatives markets, did not transition smoothly into this new domain (e.g., tokenized gold exists, but it sees little trading activity). Moreover, the inherently high-risk nature of cryptocurrencies diminished the demand for derivatives to manage and exchange risks. Another critical issue was the inefficiency of DeFi; it proved to be not only more costly but also more susceptible to front-running compared to traditional finance methods.

The Poption project's reflections serve as a valuable learning resource for navigating the complex interplay between technological innovation and financial market dynamics. While the path to integrating blockchain with financial derivatives remains fraught with challenges, the lessons learned pave the way for more nuanced, practical approaches in the future.

## Insights Gained from the Project

Although the project did not meet its initial objectives, it provided invaluable learning opportunities. Below are several key insights that have broader relevance beyond just the blockchain domain:

### Code as Contract

The growing trend of encoding protocols directly into software is reducing the ambiguity of traditional text-based contracts, offering a clearer and more accurate way to establish agreements. Despite the advantages, the risk of bugs presents a significant challenge. Nonetheless, the "code as contract" concept is poised to become increasingly important, especially as we enter the AI era, indicating its crucial role in future developments.

### Hedging in Native Markets

Blockchain technology offers potential solutions for hedging in native markets, primarily by enhancing transparency and security. This approach could involve the off-chain management of storage and the tokenization of products, complemented by on-chain trading and derivatives activities for added complexity. Despite current challenges, such as technological limitations, regulatory uncertainty, and a lack of trust, blockchain has the potential to become a valuable addition to the traditional financial ecosystem. It can offer specialized options that existing systems might not provide.

### Safer Option Trading Strategies

To enhance safety in the options market, we could minimize trades that carry high risk during rare market events. Typically, selling a call option and a bull spread call (with a high high strick price) (a safer trade with limited loss potential) perform similarly under normal conditions. However, their outcomes diverge significantly during market anomalies, such as sharp price increases. A naked call, where the seller doesn't hold the underlying asset, carries greater risk compared to a bull spread call. By altering the standard practices of traders, particularly market makers, we can foster a more secure trading environment. Shifting the basic trading unit from simple calls or puts to structured strategies like spread calls/puts or butterflies could reduce overall market risk, benefiting nearly all participants by making trading inherently safer.

## Conclusion

The Poption project, while not achieving its intended goals, has provided profound insights into the intersection of blockchain technology and financial market innovations. The exploration into DeFi derivatives like Poption reveals both the transformative potential and the inherent challenges of leveraging blockchain for financial instruments. Despite the hurdles encountered, such as the lack of a mature derivatives market in the blockchain space and the inefficiencies of DeFi, the project underscores the importance of innovation, precision in contracts, and the exploration of new hedging strategies in native markets.