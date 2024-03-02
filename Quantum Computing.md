## Outline:
1. Title of the publication : An Investigation of Post-Quantum Secure Cryptographic Mechanisms for Blockchain Technology
2. List of authors :  Aditya Deshmukh, Jappveer Singh, Pratik Mahajan, Vansh Juneja
3. Abstract 
4. Keywords
5. [[Introduction]]
6. Literature survey
7. References

## Structure:
1. Introduction
2. Blockchain
	1. Structure of Blockchain
	2. Vulnerabilities in existing blockchain
	3. Quantum Threats to existing blockchain
3. Post quantum solutions for blockchain
	1. QKD
	2. PQC
		1. Lattice Based
		2. Multivariate
	3. 

## Outline:
### 1. Introduction

- Provide an overview of the importance of blockchain technology and the rising threat of quantum computing to traditional cryptography.
- State the purpose of the literature review and outline the main sections.

### 2. Blockchain Technology

- Summarize key concepts and features of blockchain technology.
- Discuss its applications in various industries and its significance in ensuring security and transparency.

### 3. Traditional Cryptography and Its Vulnerabilities

- Explain the basics of traditional cryptographic techniques.
- Highlight vulnerabilities and limitations, especially in the context of quantum computing.

### 4. Quantum Computing and Its Threats

- Provide an overview of quantum computing principles and recent advancements.
- Discuss how quantum computing poses a threat to traditional cryptographic schemes.

### 5. Post-Quantum Cryptography Solutions

- Describe various post-quantum cryptography approaches, including:
    - Quantum Key Distribution (QKD)
    - Post-Quantum Cryptography (PQC) algorithms such as:
        - Lattice-based cryptography
        - Multivariate cryptography
- Review recent research developments and findings in these areas.

### 6. Applications of Post-Quantum Cryptography in Blockchain

- Explore the potential of integrating post-quantum cryptography solutions into blockchain systems.
- Discuss case studies or examples of projects that have implemented or proposed such solutions.

### 7. Challenges and Future Directions

- Identify challenges and limitations in implementing post-quantum cryptography in blockchain.
- Discuss potential future research directions and areas for improvement.

### 8. Conclusion

- Summarize the key findings from the literature review.
- Highlight the significance of adopting post-quantum cryptography in blockchain technology.
- Provide recommendations for future research and practical implementations.

### References

- List all the references cited throughout the literature review in IEEE format.


## Keywords:
Quantum Computing, Cryptography, Blockchain, Shor’s Algorithm, Quantum key 
distribution (QKD), Grover's algorithm

## Cryptographic Algorithms:
These algorithms could resist a quantum based attack: (https://spectrum.ieee.org/qa-with-postquantum-computing-cryptography-researcher-jintai-ding)
 1. Lattice-based cryptography
 2. Multivariate cryptography
 3. Hash-based cryptography
 4. Code-based cryptography
 5. Isogeny-based cryptography (Not mentioned in the article)

## To Study:
1. Cryptographic Algorithms
2. Shor's Algorithm
3. Grover's Algorithm
4. Regev's Algorithm
5. McEliece Algorithm


## Links and Articles:
1. http://www.pqcrypto.org/quantum.html
2. https://en.wikipedia.org/wiki/Quantum_cryptography
3. https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Quantentechnologien-und-Post-Quanten-Kryptografie/Quantenkryptografie/quantenkryptografie.html
4. https://en.wikipedia.org/wiki/Post-quantum_cryptography



## Abstracts:

1. Quantum-secured blockchain
```
Blockchain is a distributed database which is cryptographically protected against malicious modifications. While promising for a wide range of applications, current blockchain platforms rely on digital signatures, which are vulnerable to attacks by means of quantum computers. The same, albeit to a lesser extent, applies to cryptographic hash functions that are used in preparing new blocks, so parties with access to quantum computation would have unfair advantage in procuring mining rewards. Here we propose a possible solution to the quantum-era blockchain challenge and report an experimental realization of a quantum-safe blockchain platform that utilizes quantum key distribution across an urban fiber network for information theoretically secure authentication. These results address important questions about realizability and scalability of quantum-safe blockchains for commercial and governmental applications.
```

2. Vulnerability of blockchain technologies to quantum attacks
```
Quantum computation represents a threat to many cryptographic protocols in operation today. It has been esti-
mated that by 2035, there will exist a quantum computer capable of breaking the vital cryptographic scheme
RSA2048. Blockchain technologies rely on cryptographic protocols for many of their essential sub-routines. Some
of these protocols, but not all, are open to quantum attacks. Here we analyze the major blockchain-based cryp-
tocurrencies deployed today—including Bitcoin, Ethereum, Litecoin and ZCash, and determine their risk exposure
to quantum attacks. We ﬁnish with a comparative analysis of the studied cryptocurrencies and their underlying
blockchain technologies and their relative levels of vulnerability to quantum attacks.
```


## Final Abstract:

As the advent of quantum computing looms closer, the security landscape of blockchain technology faces unprecedented challenges. This research delves into the intricate interplay between quantum algorithms and conventional cryptographic mechanisms employed in blockchain systems. Through a comprehensive survey, various quantum algorithms posing threats to existing cryptographic primitives utilized in blockchain are analyzed and categorized. Specifically, the vulnerabilities of prominent blockchain platforms such as Bitcoin, Ethereum, Litecoin, and ZCash to quantum attacks are assessed in detail. Furthermore, this study proposes a novel system architecture designed to withstand quantum threats, aiming to ensure the long-term security and resilience of blockchain networks in the quantum era. By shedding light on the implications of quantum computing on blockchain security and presenting potential solutions, this research contributes to the ongoing discourse surrounding post-quantum secure cryptographic mechanisms for blockchain technology.

## Important points
1. Blockchain, originally block chain, is a continuously growing list of records, called blocks, which are linked and secured using cryptography and one of the most prominent applications of blockchain are cryptocurrencies. The World Economic Forum (WEF) has identified blockchain technology as one of its six mega-trends in a new report broadly aimed at outlining the expected transition to a more digital and connected world.
2. It is estimated that it will take 4,000 qubits to break the strongest encryption standards of today.
3. The reason that quantum computers are such a threat to RSA and ECC is that such machines compute using quantum physics. Unlike a classical computer, in which a bit can represent either 1 or 0, in a quantum computer a bit can represent 1 or 0 or a mixture of the two at the same time, letting the computer perform many computations simultaneously. That would shorten the time needed to break a strong 1024-bit RSA code from billions of years to a matter of minutes, says Martin Novotný, assistant professor of electrical engineering at the Czech Technical University, in Prague. (https://spectrum.ieee.org/cryptographers-take-on-quantum-computers)
4. But quantum computers don’t have an advantage over every type of cryptography scheme. Experts say there are four major candidates to replace RSA and ECC that would be immune to a quantum computer attack. One prominent possibility is an ECC digital-signature replacement known as a hash-based signature scheme. A hash function is an algorithm that transforms text into a relatively short string of bits, called the signature. Its security is based on being able to produce a unique signature for any given input. Even inputs that are only slightly different from one another should produce different hashes, says Buchmann.(https://spectrum.ieee.org/cryptographers-take-on-quantum-computers)
5. In the end, he found he would need only _n_1.5 gates to factor an _n_-bit integer. It’s the first substantial improvement on Shor’s algorithm in 30 years, Vaikuntanathan says. “Nobody has really succeeded beyond shaving off a little bit.”(https://www.science.org/content/article/surprising-and-supercool-quantum-algorithm-offers-faster-way-hack-internet-encryption)
6. As of 2022, the U.S. federal government has proposed a roadmap for organizations to start migrating toward quantum-cryptography-resistant algorithms to mitigate these threats.(https://www.sdxcentral.com/articles/analysis/harvest-now-decrypt-later-concern-boosts-quantum-security-awareness/2022/09/), (https://www.cisa.gov/news-events/alerts/2022/07/05/prepare-new-cryptographic-standard-protect-against-future-quantum-based-threats)
7. “Harvest now, decrypt later” refers to an attack where threat actors collect encrypted data from target organizations today, anticipating that data can be decrypted later on when quantum computing reaches a maturity level capable of rendering some existing cryptographic algorithms obsolete, according to Deloitte. The consulting firm [surveyed](https://www2.deloitte.com/us/en/pages/risk/solutions/cyber-risk-services.html) over 400 professionals from organizations that have considered quantum computing benefits and found that over half (50.2%) of respondents believe their organizations are at risk for “harvest now, decrypt later” attacks. (https://www.sdxcentral.com/articles/analysis/harvest-now-decrypt-later-concern-boosts-quantum-security-awareness/2022/09/)
8. **[Brute-force attack](https://en.wikipedia.org/wiki/Brute-force_attack "Brute-force attack")**: If data is not adequately encrypted it may be possible to decrypt it through brute-force methods. Newer technology such as [quantum computing](https://en.wikipedia.org/wiki/Post-quantum_cryptography "Post-quantum cryptography") increases the potential to allow brute-force attacks to become more efficient in the future.[[4]](https://en.wikipedia.org/wiki/Crypto-shredding#cite_note-4) However, [quantum computing](https://en.wikipedia.org/wiki/Quantum_computing "Quantum computing") is less effective against specific encryption methods such as [symmetric encryption](https://en.wikipedia.org/wiki/Symmetric_encryption "Symmetric encryption") than others that are more vulnerable to brute-force attacks such as [public-key encryption](https://en.wikipedia.org/wiki/Public-key_encryption "Public-key encryption"). Even when data is secured via use of symmetric encryption, there are methods such as [Grover's algorithm](https://en.wikipedia.org/wiki/Grover%27s_algorithm "Grover's algorithm") that make these kinds of attacks more effective, though this can be mitigated by other enhancements, such as using larger key values.[[5]](https://en.wikipedia.org/wiki/Crypto-shredding#cite_note-5)