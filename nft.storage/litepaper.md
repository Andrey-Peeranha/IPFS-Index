# NFT.Storage Litepaper: A public good for NFT preservation
Elizabeth Griffiths

Latest Updated: 4 April 2024

# 1. Overview
Since its launch in April 2021, NFT.Storage has become a cornerstone for NFT longevity, providing solutions for off-chain NFT data resilience and establishing itself as an indispensable public good. NFT.Storage, leveraging the decentralized storage capabilities of the Filecoin Network and the advanced content addressing and peer-to-peer network of IPFS, offers a secure, verifiable, and blockchain-anchored storage solution designed to safeguard NFT data against the test of time. Our commitment, "to preserve all NFTs as timeless assets," drives our efforts to integrate NFT.Storage across all NFT minting platforms, marketplaces, and directly within smart contracts and as layer-1 and layer-2 blockchain primitives.

With milestones including the storage of millions of NFTs, strategic partnerships, and continuous technological innovation, NFT.Storage aims to empower the community with the tools needed for the long-term preservation and verification of digital assets.

# 2. The future of NFTs
NFTs represent a seismic shift in how we understand digital ownership and creativity, encompassing a diverse range of digital artifacts, from art and music to more. As digital realms evolve, the importance of a reliable system to preserve these assets becomes increasingly critical. NFTs are redefining asset management, intellectual property, and the creator economy, ushering in a new era of digital assets characterized by unmatched provenance, liquidity, and cross-platform interoperability.

Additionally, NFTs are unlocking new possibilities in virtual reality, gaming, and digital identities, offering immersive and personalized user experiences. Their fusion with decentralized finance (DeFi) and metaverse innovation is fostering ecosystems where digital ownership takes on enhanced forms of investment, lending, and participation.

As we navigate this maturity, the emphasis on sustainability, accessibility, and ease of use grows. Advances in layer-2 technologies are tackling the challenges of scalability and environmental impact, promising a sustainable and inclusive future for NFTs. This journey promises democratized access to art, innovative monetization models, and a new conception of ownership in the digital world. It underscores the need for solutions that ensure the enduring relevance and security of these priceless digital assets, aligning with our vision at NFT.Storage for a future where every NFT is preserved as a timeless asset.

# 3. NFT limitations 
NFTs mark a profound transformation in digital ownership and expression, spanning a vast spectrum of digital artifacts from art and music to extensive digital assets. This evolution expands the horizons of digital assets and emphasizes the need for robust preservation strategies. As NFTs advance, they introduce new frameworks in asset management, intellectual property, and the creator economy, heralding an era of digital assets marked by unmatched provenance, liquidity, and cross-platform interoperability.

The storage landscape for NFTs underscores an urgent need for durable solutions. A 2022 study by YourNFTs, independently verified by ClubNFT illustrates a concerning trend: only 10% of NFTs are stored on-chain, about 50% rely on IPFS, leaving the rest at risk on private servers. This highlights the imperative for a more resilient storage approach. NFT.Storage tackles this by harnessing IPFS for content addressing and Filecoin's decentralized storage network, aiming to secure NFT longevity and accessibility amidst digital vulnerabilities.

However, NFTs face challenges in proving provenance. While blockchain acts as a reliable "truth machine" for on-chain data, incorporating off-chain truths—like provenance and ownership—into the blockchain presents significant challenges. Off-chain data typically lacks the blockchain's inherent verifiability, creating a gap in authenticating asset origins and histories. Efforts to close this gap through digital certificates and metadata standards often depend on trust in external sources, injecting uncertainty due to the lack of mathematical proof to fully validate off-chain data's authenticity and history.

Addressing these hurdles is essential for bolstering trust, transparency, and longevity in NFT data management. Future innovations aim for a closer integration of on-chain and off-chain worlds, making the blockchain a crucial bridge between digital certainties and physical world complexities. As the NFT ecosystem evolves, devising and adopting strategies that ensure NFTs' long-term viability and integrity becomes paramount, paving the way for a democratized and inclusive digital ownership future.

# 4. NFT.Storage Public Good Solutions
NFT.Storage is reshaping NFT preservation with its suite of innovative solutions, each aiming to ensure the lasting safeguarding of NFTs. Below is an overview of our offering:

## NFT.Storage: Preservation uploader web app and API
Our premier product focuses on the enduring preservation of NFTs, aiming to provide a long-term and cost-effective solution. With a modest one-time fee per GB of storage, payable via fiat and soon through ERC20 tokens, we leverage Filecoin's decentralized storage network, underpinned by an on-chain endowment. This aims to ensure your NFTs remain protected and identifiable, adaptable to future digital shifts. Our service accommodates NFTs across major blockchains, delivering verifiable and long-lasting storage. Should any content become temporarily inaccessible, the NFT data is always available to retrieve from the Filecoin Network..

Complementing our core service, we're enhancing data retrieval from NFT.Storage through collaboration with our Storage Providers to facilitate access via ipfs.io, an IPFS public gateway. While this is currently under development to support efficient data retrieval, we educate users on how to optimally retrieve their stored NFT data from the Filecoin network, tailored to specific use cases. Beyond paying a pinning service to ensure that your images stay pinned to IPFS,  we educate users on direct Filecoin retrieval methods through innovative solutions like Boost and Lassie. Although currently complimentary, future iterations of these retrieval services may introduce fees to maintain high efficiency and access for users.

We're committed to ensuring a great developer experience, offering a user-friendly web app, API, and in the future an SDK for seamless integration and storage management. Looking ahead, our ambition is to integrate NFT.Storage as foundational primitives directly within protocols, layer-, layer-2s and smart contracts. This forward-thinking approach aims to embed NFT storage at the deepest layer of the tech stack, ensuring that our solutions pave the way for mass adoption of digital asset preservation.

## NFT Token Checker 
In 2024 the team plans to launch the NFT Token Checker, which serves as an essential tool for marketplaces, wallets, and creators, offering verification of NFT collections, tokens, and CIDs stored by NFT.Storage. This service provides creators and their customers with confidence in the lasting storage of NFTs by displaying a distinct icon on marketplace pages, indicating the NFT is preserved by NFT.Storage. Furthermore, the Token Checker will be fully integrated on the NFT.Storage website, facilitating easy verification of NFT storage status by anyone.

Our vision is to ultimately integrate the NFT Token Checker with block explorers, enhancing the trust and recognition of NFT.Storage across the NFT community. 

## Classic Uploader
The inaugural product of NFT.Storage launched in April 2021, facilitating off-chain NFT data availability across IPFS and the Filecoin network for free. It abstracts the complexity of IPFS and Filecoin, providing a seamless experience for NFT creators. The data is content-addressed, then pinned to the NFT.Storage Gateway, and securely stored in the Filecoin network at no charge. This solution secures the long-term integrity and availability of the NFTs. 

In our journey to innovate and better serve the evolving requirements of the NFT ecosystem, we are transitioning from NFT.Storage Classic Uploader to a more decentralized storage solution focused on preserving NFTs. Amidst this transition, all data previously uploaded will continue to be accessible across IPFS, safeguarding the enduring integrity and accessibility of creators' digital assets. This approach to data management reaffirms our commitment to both creators, aiming to ensure the long-term storage and accessibility of their NFTs in the dynamic digital landscape.

## Pinning API
The Pinning API facilitates the seamless integration of off-chain NFT data with decentralized storage, targeting data already on the IPFS network. This is particularly beneficial for users transitioning from fee-based pinning services, offering a cost-effective method for decentralized data management. The API enhances data persistence, utilizing Filecoin to store long-term decentrally, and integrates seamlessly with the NFT.Storage Gateway for data accessibility.

User account authorization is required to access this API, highlighting its specific use for significant migrations rather than regular traffic. This service underscores NFT.Storage's commitment to removing obstacles to long-term, decentralized data storage, instilling confidence in creators and collectors regarding the lasting integrity and accessibility of their digital assets.

As part of our ongoing evolution towards more comprehensive and decentralized storage solutions, the Pinning API is transitioning towards NFT preservation storage offerings. This transition aims to further enhance the longevity of NFT data, aligning with NFT.Storage's vision for a future-proof NFT ecosystem.

## NFT.Storage Gateway
The NFT.Storage Gateway is designed to improve the performance and reliability of accessing off-chain NFT data assets that use the Classic Uploader and Pinning API. It enables NFT creators and marketplaces to use the gateway for efficient data access by using NFT.Storage Gateway-specific URLs that facilitate direct retrieval of the NFT content.

As we continue to develop and refine our services to meet the needs of the evolving NFT landscape, our commitment to providing a secure, accessible, and stable environment for the storage and retrieval of NFTs remains steadfast. This dedication reflects our ongoing support for the creators and users within the NFT community, ensuring their invaluable work remains protected and accessible, reinforcing the foundation of a reliable digital ecosystem for NFTs.

# 5. Technical Architecture
NFT.Storage's technical architecture utilizes the decentralized and secure infrastructure of the Filecoin network, complemented by IPFS's content addressing and peer-to-peer network capabilities, aiming to ensure the long-term preservation of NFT data.

## NFT.Storage: Preservation uploader web app and API
NFT.Storage redefines the preservation of NFTs by leveraging the decentralized and verifiable infrastructure of the Filecoin network, augmented by IPFS's content addressing and peer-to-peer networking capabilities. Our platform aims to ensure reliable storage for off-chain NFT data, offering creators and marketplaces the assurance of enduring accessibility and integrity. Here's how our architecture supports NFT longevity:

Content Addressing and Retrieval with IPFS: Prior to storage, data is content-addressed by users through IPFS, generating a unique hash (CID) that reflects the data's content. This process emphasizes the process of content-addressing by users through IPFS, ensuring the integrity and immutability of data.
Decentralized Storage within the Filecoin Network: In the Filecoin network, content-addressed data is stored across a number of independent storage providers, minimizing centralized risks like server downtime or targeted breaches. Filecoin's design ensures a distributed storage model, crucial for enhancing data durability. 
Verifiability through the Filecoin Network: Filecoin's use of blockchain technology not only adds a layer of security but also enables verifiable storage, with each storage agreement and its execution transparently and immutably logged on the blockchain. This transparency combined with other mechanisms  as Proof-of-Spacetime (PoSt) for regular cryptographic checks, means your assets are regularly verified that they are being stored where we say they are being stored, making the integrity of stored data verifiably secure and transparent.
Smart contract-based operations on the Filecoin Virtual Machine (FEVM): Smart Contract-based Replication, Renewal, and Repair (RaaS) within the Filecoin network are managed through smart contracts on the Filecoin Virtual Machine (FEVM). These contracts automate the entire storage deal lifecycle, including renewals, to provide continuous storage without manual intervention. Furthermore, the system employs RaaS functionalities for Replication, Renewal, and Repair, critical for maintaining the longevity and integrity of stored data. Automated replication allows for user-specified data copies, while continuous monitoring ensures timely renewal of storage deals. Swift repair mechanisms address any faulted storage promptly. Together, these features, enabled by the FEVM's smart contract capabilities, contribute to the vision of achieving perpetual data storage on the Filecoin network, ensuring the data's accessibility and security.
Smart Contract-based On-chain Endowment: A smart contract-based endowment on the Filecoin Virtual Machine (FEVM) underpins NFT.Storage's ability to fund the ongoing storage. When users pay for file storage, a portion of the fee is contributed to the endowment, which in turn compensates storage providers on the Filecoin network. This design plans for growth,where accrued fees would be reinvested in the endowment. 
Utilizing Lighthouse.Storage Technology: Initially, NFT.Storage is leveraging Lighthouse's open source technology and Filecoin storage provider deal engine to construct a robust and sustainable infrastructure for. This strategic partnership accelerates development and paves the way for a more decentralized service framework, enhancing our capability to execute storage deals more frequently and efficiently. Furthermore, by aggregating NFT.Storage data with that of Lighthouse, we significantly enhance the system's scalability and reliability, ensuring a smooth and efficient transition towards a service fully dedicated to NFT.Storage as the volume of data uploads grows. This method highlights our dedication to decentralization and our commitment to establishing a secure and enduring repository for NFT data, clearly delineating our trajectory towards a comprehensively decentralized solution.
## NFT Token Checker 
The NFT.Token Checker is designed for marketplaces to verify the secure storage of collections, tokens, or Content Identifiers (CIDs) stored on our platform. Initially employing a centralized approach to data storage, this strategy aims to ensure immediate operational efficiency while laying the groundwork for future scalability and enhanced verification methods.

A pivotal aspect of our roadmap is the transition to on-chain validation mechanisms. This advancement will allow for the direct verification of CIDs against the Filecoin blockchain, enhancing the system's transparency and and moving towards a more trustless product. Such a move aligns perfectly with NFT.Storage’s mission to create a seamless ecosystem for digital assets. Embedding blockchain-based validation is aimed at increasing user awareness in the permanence, authenticity, and storage of their NFTs.

While the initial phase of the Token Checker draws exclusively from data being preserved in the paid NFT.Storage product, we will consider broadening its scope in the future to include data from the Classic Uploader and Pinning API. This decision will be subject to strategic guidance from our DAO, reflecting our commitment to community-driven development and ensuring that verification services evolve in alignment with user needs.

This approach to NFT verification, emphasizing decentralization, transparency, and trustlessness, highlights NFT.Storage's commitment to innovation and community engagement, aiming to set new end user expectations in NFT longevity.

## Classic Uploader
The NFT.Storage Classic Uploader architecture capitalizes on the synergy between IPFS and the Filecoin network to provide a decentralized data storage solution for NFTs. By leveraging IPFS, the Classic Uploader enables unique content addressing through the assignment of Content Identifiers (CIDs) to each data piece. This approach facilitates the efficient location and retrieval of data across the IPFS peer-to-peer network, eliminating reliance on centralized servers and enhancing data accessibility and security within the NFT ecosystem.

Moreover, the integration of the Filecoin network ensures a decentralized, verifiable storage mechanism. Filecoin decentralizes the storage process across a wide network of providers, who are contractually required to accurately store data and submit periodic cryptographic proofs to the blockchain. These proofs validate their storage commitment and adherence to protocol, ensuring the durability and integrity of NFT data over time.

Furthermore, data uploaded through the Classic Uploader is made available via the NFT.Storage Gateway. This dual-technology architecture underpins the Classic Uploader's mission to deliver a reliable, accessible, and transparent storage solution for the NFT community.

## Pinning API
The Pinning API enables users to pin data that's already content addressed by IPFS to the NFT.Storage Gateway and store the data in long-term Filecoin decentralized storage. This specialized product underscores NFT.Storage's commitment to enhancing the accessibility, integrity, and longevity of NFT data. It caters particularly to users transitioning from other storage services, or those looking for additional redundancy, offering a direct, cost-effective means to secure NFT data within a decentralized framework. Access to this API requires specific user account authorization, highlighting its intended use for significant data migration initiatives rather than for regular operational needs.

As part of NFT.Storage's commitment to enhancing and streamlining our services, we are incorporating the functionalities of the Pinning API into a broader, more cohesive product strategy aimed at optimizing user experience and resource allocation. This strategic shift will enable us to focus our efforts on developing features that directly align with our core mission of providing secure, decentralized, and accessible storage solutions for the NFT community. By gradually transitioning away from the standalone Pinning API, we aim to deliver a unified and efficient platform that meets the evolving needs of our users and the wider NFT ecosystem.

## NFT.Storage Gateway
The NFT.Storage Gateway is designed to enhance the efficiency and reliability of retrieving off-chain NFT data stored via the NFT.Storage Classic Uploader and Pinning API. This gateway utilizes a caching layer strategy, primarily leveraging a serverless computing platform to cache popular content at the network's edge, thereby improving performance and reducing load on the underlying IPFS infrastructure. By making parallel requests to multiple public IPFS gateways and selecting the fastest response, the gateway minimizes dependence on any single gateway and mitigates the impact of potential service disruptions.

This architecture optimizes data retrieval, ensuring quick and reliable access to NFT data. The gateway's use of both "path style" and "subdomain style" URLs facilitates easy integration into web applications and libraries, enabling NFT creators and marketplaces to effortlessly access stored NFT content. The strategic use of caching and request routing ensures that NFT.Storage can provide a high-performance, CID-based HTTP retrieval solution that supports the mission of making decentralized data storage the default choice for NFT creators.

Through this gateway, NFT.Storage underscores its commitment to offering a scalable, secure, and user-friendly infrastructure for accessing the wealth of NFT data stored on its platform, aligning with the broader vision of a decentralized and accessible digital asset ecosystem.

# 6. Governance
NFT.Storage's Path to Decentralized Governance

NFT.Storage is transitioning towards a governance model centered around decentralized community participation, reflecting our evolution into a platform that empowers collective insights for guiding strategic and operational decisions. As a public good, it has evolved beyond its initial setup under Protocol Labs to a separate entity with a structure that champions decentralized decision-making and broad community involvement in governance. This shift towards decentralized governance is a testament to our commitment to leveraging the full spectrum of our community's expertise, aiming to solidify our position as an indispensable public good in NFT preservation.

A not-for-profit foundation company, NFT.Storage Limited, exists adjacent to the DAO to permit necessary human and real-world interfaces (including contracting) with an independent Board and audited financials but with dedicated consideration of DAO proposals and votes baked into the constitution of the Foundation.

Seasonal Objectives and Decentralized Decision Making

As we progressively decentralize, so will our governance. We’ll take an iterative and goal-oriented approach, utilizing seasonal cycles to focus on achieving specific outcomes. This strategy allows for better alignment with NFT.Storage's goals, emphasizing the importance of community-driven progress and enabling autonomy. Voting will begin off-chain, and most likely transition to an NFT-based voting mechanism, rather than using a more traditional ERC-20.

NFT.Storage as a DAO

As a specialized form of DAO focused on data governance, members can influence a broad spectrum of strategic directions. Specific to being a DataDAO, this includes policies for data aggregation, data replication strategies, and guiding the nuances of Filecoin storage deals. Such an approach strives to ensure that NFT.Storage’s roadmap resonates with the community's needs, fostering a strong bond between the platform and its contributors. Through the DataDAO, members participate in pivotal decisions, from improving storage mechanisms to introducing new functionalities and spearheading community projects, thereby shaping the future of NFT preservation.

Building a Collaborative Ecosystem

The DAO's establishment is a clear indication of our dedication to fostering an environment of inclusivity, transparency, and collective effort. It underlines the community's essential role in propelling NFT.Storage forward, aiming to navigate the complexities of NFT preservation together.

Membership Structure: Inclusive Engagement

The DAO offers a varied membership model to reflect the different levels of community engagement. This flexible framework accommodates everyone from passive supporters to active contributors, facilitating a wide range of involvement opportunities.

Membership Tiers: Expanding Participation

Friends of NFT.Storage are those aligned with our mission, interested in staying informed and supporting the ecosystem passively.
Contributors are deeply involved in shaping the platform's direction, playing a crucial role in its development and governance.
Stewards take on a more significant responsibility, driving strategic initiatives and enjoying greater visibility within the community.
Strategic Governance Structure

Overseen by a CEO, our governance framework includes five key committees (Advise, Build, Fund, Grow, Govern) focused on different aspects of our mission. Operating seasonally, this structure ensures agility and alignment with our evolving goals, fostering an environment where strategic priorities meet the needs of the NFT community and the wider NFT ecosystem.

The Impact of Membership

Joining NFT.Storage means committing to the growth and innovation of the NFT ecosystem. Members gain access to co-marketing opportunities, networking opportunities, and the chance to contribute to a collective effort that shapes the future of NFT preservation.

# 7. Sustainability & Economics 
Strategic Transition for Sustainability

NFT.Storage is advancing towards a sustainable and decentralized future by transitioning away from the Classic Uploader and Pinning API. This move underscores our commitment to evolving with the platform's economic realities, aiming to address financial sustainability challenges while ensuring the platform's services remain accessible and low-cost for users.

Storage Fee Model and the On-Chain Endowment

A minimal one-time fee model to get access to data storage has been introduced to help build a viable model for long-term storage. As a public good aiming for not-for-profit status, this approach reflects our commitment to maintaining low costs for users and being a public good that is accessible to all. Additionally, the on-chain endowment will be managed within a not-for-profit foundation, with the interest generated helping to cover future storage provider costs, ensuring the sustainability of the platform and accessibility to the wider community.

Our on-chain endowment strategy is designed to aim for the long-term sustainability of NFT storage, striving to offer reliable storage for the foreseeable future. The endowment is dedicated exclusively to covering storage provider costs, with no allocation for operating expenses. This approach emphasizes our commitment to providing a service that is both accessible and affordable, while maintaining the highest standards of data preservation and security.

The utilization of an on-chain mechanism for managing the endowment opens the opportunity for a trustless environment where payments to storage providers are executed programmatically, reinforcing the decentralized nature of our service. This method not only streamlines the payment process but also upholds the integrity and transparency of transactions, embodying our vision of a trustless and decentralized digital preservation ecosystem. Learn more about the endowment.

Fiscal Strategy: Recurring Revenue Streams

Our financial strategy prioritizes generating a sustainable recurring revenue stream through membership fees and leveraging the interest generated from the on-chain endowment. This approach aims to ensure NFT.Storage remains a resilient and accessible public good, emphasizing our commitment as a public good and maintaining low costs for our users.

By focusing on membership as a primary source of revenue, we cultivate a strong community foundation that directly contributes to the platform's growth and sustainability. Simultaneously, the on-chain endowment is strategically invested, with the generated interest specifically allocated to cover future storage provider costs. This methodical financial planning underpins our efforts to aim to ensure the long-term viability of NFT.Storage, aligning with our goal to serve as a cornerstone in the preservation and accessibility of NFTs. 

Exploring future revenue-sharing models with strategic partners such as storage on-ramps will diversify our income sources, further supporting the platform's financial stability and commitment to the NFT preservation ecosystem.

# 8. Conclusion
In conclusion, NFT.Storage heralds a new era of NFT preservation, offering a decentralized, verifiable, solution for NFT preservation. With its visionary approach and commitment to inclusivity, NFT.Storage is poised to become an indispensable public good in the NFT landscape.

# 9. Legal Disclaimers
This document is for informational purposes only and does not constitute legal, financial, or professional advice. NFT.Storage encourages all users to conduct their own due diligence and consult with professional advisors as necessary. This communication is not for distribution to newswire or similar services.
