# Reassessing the Poption Project

## Insights from the Poption Endeavor

For the past two years, I have been engrossed in developing a DeFi derivative called Poption. Despite my efforts, I've decided to move away from this venture. My confidence in DeFi as a solution to the problems I aimed to solve has diminished. Nevertheless, I believe there's value in sharing the lessons learned from this experience, as we can often gain insights even from endeavors that don't pan out as expected.

## Identifying Financial Market Challenges

The financial landscape two years ago was punctuated by several significant events: the GME short squeeze, WTI's dive into negative pricing, and the London Nickel squeeze. These events inspired me to explore strategies to prevent such market anomalies. I came up with several approaches that could offer solutions:

1. **Contractual Precision:** It is crucial to have precise and unambiguous contracts from the start. Mid-course alterations, like changing a non-negative number to an arbitrary one, can lead to chaos. Thus, any contract modifications must be handled with utmost care.
2. **Hedging on Native Markets:** Relying on distant markets with only similar products for hedging introduces substantial and unforeseen risks.
3. **Rethinking the Atom unit in Option Trading:** The market should aim to reduce unnecessary naked short selling. Echoing Elon Musk's views, it is unfair for large entities to sell what they don't own. A viable alternative could be for market makers to trade in bundled option strategies such as call/put spreads or butterflies, which can help in managing high-risk positions more responsibly, as seen in the GME scenario.

## Blockchain: Potential and Pitfalls

Initially, I was optimistic about blockchain being the panacea. Its trustless nature and the clarity of smart contracts seemed to perfectly align with the needs for **contractual precision** and establishing **native markets**. My plan included a decentralized exchange (DEX) on the blockchain, facilitating trades in Poption, my innovative derivative designed to offer the benefits of traditional options but without the necessity for naked selling.

However, I encountered significant roadblocks. The lack of a robust derivatives market in the blockchain space was a major impediment. Traditional assets already well-served by conventional derivative markets didn't transition well into this new space. Furthermore, the inherent high-risk nature of cryptocurrencies reduced the demand for derivatives to manage and swap risks. Another critical issue was the inefficiency of DeFi; it proved to be more costly compared to traditional finance methods. 


## Key Insights from the Project

Although the project didn't achieve its original goals, it offered valuable learning experiences. Here are some key concepts that I believe are still relevant and beneficial:

### Code as Contract
The "code as contract" concept represents a major shift in how we approach agreements in the digital era. Unlike traditional software standards that relied heavily on textual documentation, modern practices are increasingly integrating these standards directly into software. This approach offers several advantages:

1. **Determinism:** Software ensures consistent, predetermined outcomes. This contrasts with document-based contracts that are open to varied interpretations, as code provides a clear, uniform execution path.
2. **Simulatability:** Code enables users to simulate different scenarios, offering insights into potential outcomes and allowing for a more practical understanding of the contract in various contexts.

The emergence of 'smart contracts' in blockchain technology highlights this concept's advancement and its potential to revolutionize contract theory and practice, despite current challenges.

#### Advantages

* **Automation and Precision:**
  Smart contracts automate contractual obligations, executing predefined actions automatically under certain conditions. This precision and automation streamline transactions, making them quicker and more cost-effective.
  
* **Accessibility and Efficiency:**
  Smart contracts are more accessible compared to traditional legal contracts. They are designed for straightforwardness, reducing the need for extensive legal knowledge and making them more understandable to those without a legal background, although a basic understanding of coding is necessary.

#### Challenges
  However, "smart contracts" come with their own set of challenges. Key issues include:

* **Risk of Bugs:** The potential for bugs in smart contracts is a significant concern, as they can cause considerable losses. With increasing complexity, ensuring bug-free code becomes more difficult. Auditing is a solution, but it can be costly, often exceeding the expenses of traditional legal or accounting services.
  
* **Limited Real-World Applicability:** Smart contracts have restricted utility in real-world legal situations. They are accepted as they are, which can be limiting, particularly in cases requiring legal intervention or court resolution.

#### Potential for Development
The "code as contract" concept is continually evolving. 

(I want to expand this paragraph. Tell some thing like in AI era, 'code as contract' may change the world. But something shall be done, 1. EVM will not be the future. Gas calculating is rediculars. Machine pay more cpu circus in the gas calculation than the actural calculation. EVM is too weak to do a lot of things. it is something from acient area. A modern account system usually containing a db based resistant system. A parallable processisten.)


#### Hedging in Native Markets

Blockchain technology has the potential to fulfill the hedging requirements of native markets by enhancing transparency and security. In such a system, off-chain facilities could manage storage and the tokenization of real products, ensuring simplicity and legal stability. Meanwhile, the trading and derivatives transactions could be handled on the blockchain, accommodating more complex operations. Currently, this concept faces hurdles due to technological limitations, regulatory uncertainties, and a lack of widespread understanding and trust in blockchain. Over time, as these challenges are overcome, blockchain could surpass traditional financial hubs like Chicago or London in offering more efficient and secure hedging services.

#### Making Option Trading Safer

To enhance safety in the options market, we could minimize trades that carry high risk during rare market events. Typically, selling a call option and a bull spread call (with a high high strick price) (a safer trade with limited loss potential) perform similarly under normal conditions. However, their outcomes diverge significantly during market anomalies, such as sharp price increases. A naked call, where the seller doesn't hold the underlying asset, carries greater risk compared to a bull spread call. By altering the standard practices of traders, particularly market makers, we can foster a more secure trading environment. Shifting the basic trading unit from simple calls or puts to structured strategies like spread calls/puts or butterflies could reduce overall market risk, benefiting nearly all participants by making trading inherently safer.

