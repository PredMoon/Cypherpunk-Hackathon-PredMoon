# [Predmoon] - Solar-SG-hackathon-2025


## 1. Deliverables

- [x] GitHub Repository
- [x] [Deck](https://www.canva.com/design/DAG2PfMVKZM/lUOhxNw80bQNv4kbpQnQag/view?utm_content=DAG2PfMVKZM&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hd0f28c489d)
- [x] Demo Video on youtube: https://youtu.be/RUZHgOvq8hk
- [x] Online Demo Link
  - Onchain version: https://Pred.WTF
  - Offchain version: https://Pred.WTF/t-1 (replace t-1 to t-2,3...17)
  - Pro version(the same UI as PolyMarket): https://pro.Pred.WTF
- [x] Contract Deployment Information

## 2. Team Information Section

### 1) Project Overview
- **deck**: https://www.popai.pro/ppt-share?shareKey=a056195425a5ba622c00b4db784aa2231ef5f49e5c439399886561ea1fa5e953&utm_source=presentationsharepage
- **Project Name**: Predmoon
- **One-line Description**: A prediction market platform that users could trade by their beliefs and knowledge
- **Target Users**: All crypto users
- **Core Problems & Motivation (Pain Points)**: Monetizing Beliefs and getting collective wisdom based on blockchain
- **Solution**: We developed Predmoon using a combination of smart contracts, Vue, Supabase, and Privy to let users trade their knowledge on-chain. The platform operates like Tinder: swiping left or right corresponds to a YES/NO transaction, and users can earn a profit.

### 2) Architecture & Implementation

- **Overview Diagram**: [![structure](./assets/flow.jpg)]
- **Key Modules**:
  - Frontend: Swipe trading system/Embedded wallet/Cross-chain transfer integration
  - Backend: Off-chain order matching/Hybrid decentralized exchange model
  - Contracts: Cross-chain bridge technology/Efficient transaction settlement/Decentralized security/Ecosystem compatibility
  - Others: Self-developed Large Language Model (LLM)
- **Dependencies & Tech Stack**:
  - Frontend: Vue/Nuxt.js, ethers.js, Tailwind CSS, Privy.js
  - Backend: Node.js, Supabase, PostgreSQL
  - Contracts: Rust
  - Deployment: Vercel, AWS


### 4) Run & Reproduce

- **Prerequisites**: Node 18+, pnpm, Git
- **Environment Variables Example**:


- **Quick Start (Local Example)**:

```bash
# Install dependencies
pnpm install

# Start backend
pnpm --filter backend dev

# Start frontend
pnpm --filter frontend dev

# Open http://localhost:3000
```

- **Online Demo**: [pred.wtf](https://pred.wtf)
- **Account & Testing Instructions**: register by your own email

### 5) Demo & Key Flows

- **Video Link (≤3 minutes, Chinese)**: https://youtu.be/RUZHgOvq8hk

<iframe width="560" height="315" src="https://www.youtube.com/embed/RUZHgOvq8hk?si=y6nxl2VZB7Bsxyvi" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- **Key Use Case Steps**:
  - Use Case 1: Login module with Privy (embedded wallet)
  - Use Case 2: Deposit through multi-chain
  - Use Case 3: Trade module

### 6) Verifiable Scope
Due to commercial application reasons, complete system code cannot be provided

### 7) Roadmap & Impact

- **1-3 Weeks Post-Competition**: Complete continuous optimization of pages and system performance, improve user experience and market stability.
- **1-3 Months Post-Competition**: Drive user growth through cold-start operations and community incentive programs;
  Conduct multiple marketing campaigns to enhance brand exposure and prediction market liquidity;
  Gradually launch PredSeed financing plan to provide funding support for subsequent product expansion and ecosystem construction.
- **Expected Value to Ethereum Ecosystem**: Become the first Chinese-language prediction market project in the Ethereum ecosystem, innovating user experience with unique style, and promoting diversified development of global prediction markets.

### 8) Team & Contacts

- **Team Name**: [Royal View Garden 8th Floor 10th Floor Swimming Pool Maintenance Team]
- **Members & Roles**:
  - Adam Ma – Founder
  Adam has extensive experience in both Web2 and Web3 entrepreneurship, as well as years of experience at major tech companies including 360, RC, and iHealth. He has won 20+ global hackathon awards and previously founded a sneaker marketplace with millions in transaction volume, as well as Web3 RWA projects. Notably, he has executed a user cold-start of 5,000+ users in a single day.
  - KK – Co-founder
  KK graduated from HKUST and brings extensive development experience, including years at Tsinghua Research Institute, combined with strong social and creative insight. He leads product design, social media, and brand strategy, and has deep experience with AI tools and innovative product ideation.
  - Ben – Co-founder
  Ben graduated from Shanghai University and has 9 years of solid front-end development experience. He previously worked at Citibank Singapore HQ, specializing in React and Vue development.
  - Other core team members
  Our team consists of 10+ talented professionals, covering development, design, community, and marketing. Together, we bring a balanced mix of technical expertise, creative vision, and operational experience to build PredMoon.
- **Contact Information (Email/TG/X)**: b@pred.wtf
- **Available Demo Times (Timezone)**: free

