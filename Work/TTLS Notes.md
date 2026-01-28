# POC
- Fika Sun - HRBP
- 张少松 - +1, hiring manager
- 罗世欣 - round 2 interviewer 
- 赵郭桃 - round 1 interviewer
- liu qiang - probably mentor, based in SG
## TTLS GNE Scope
1. Policy-setting, Rules-making, Standards Definition, Risks Definition, User (Merchant, Creator, Customer) Tiering
2. Defining Penalty and Education outcomes, commensurate to the severity of risks and experience we wish to provide users
3. New Risks Discovery and Risks Investigation
4. Moderation, Model Training, Service Delivery Efficiency and Quality Standards
5. Management of GNE-related BPO, Compensation, and overall GNE Budget Management
6. Case Handling, Emergency Escalations and Responses, User Feedback Collection and Response
# Services
- Food service
- Beauty service
- Travel & tourism 
# Market Entry Strategies:
### Semi-closed Loop (Open Loop) - 开环
- Merchants link to external websites, avoiding TikTok's platform fees
- No platform restrictions on merchant operations
- More dominant in early phases, and western markets where third party integrations are preferred
- For in store reservations, jump to third-party website to complete the booking action
- Receive post-paid coupons online and verify consumption offline
- Prepaid in-store coupons by completing payment and verification on a third party page
### Closed Loop - 闭环
- The entire e-commerce process (discovery, payment, logistics, feedback) occurs within the TikTok ecosystem
- Eliminates redirects to external sites, improving user experience and retaining platform GMV (Gross Market Value)
- TikTok charges a commission and manages logistics
-  Adopted in markets where cross border trade is restricted, like Indonesia

## Businesses
- Open loop
	- Hotels and Travel 酒旅
	- Dine in 到综
- Closed loop
	- F&B 餐饮

![[Screenshot 2025-12-29 at 5.25.15 PM.png]]

### TTLS Value Proposition
- TTLS Platform
	- **Compliance (P0): Ensure that operations are compliant with the region's regulations
	- POI Supply (P0): Promote diverse POIs and supply of consumer goods
	- Creator Content (P0): Ensure sufficient content output to enable POI visibility
	- Merchant Growth (P0): Sufficient merchants are available on the platform, especially paying merchants so that content creators can partner with them
	- **Business Model (P1): Balance relationships between all stakeholders to ensure a healthy ecosystem**
- Merchant
	- Product Consumption (P0): Focus on consumption, conversion, transactions, word of mouth, observing GMV and profit
	- **Business Environment (P0): Ensure a compliant, fair, and stable business environment**
- Creator
	- Conversion (P0): Commission
	- **Business Environment (P1): Compliant (with age regulations, tax regulations) , stable, operational market environment**
		- Fake merchants cause people to leave the platform
- Consumer
	- Product/Service Consumption (P0): Ensure diversity of product categories, good quality of products, competitive prices, and attractive content, etc.
	- Consumption Environment (P1): Platform credibility, product and content quality, secure fund transactions
		- Coupons being written off before they are used
		- Irrelevant POI
		- Product description mismatch
		- Food safety issues
### North Star Metrics
- Content VVR (Violative Video Rate)
- Listing VVR 
- POI VVR & POI VVR

### Governance Infra
- Governance gateway
	- Used for traffic coloring, context management
- Workflow engine
- Case file
### Governance Platform
- Tagging platform
- Moderation platform
	- Risk identification
	- Human moderation
	- Machine moderation
- Sentinel
	- Risk perception
	- Risk assessment
- Decision-making and Disposal 
### Governance Products and Tooling
- Policy center
	- Policy making
- Data dashboard
- Disposal tool
- Claims center
- Report & appeal

# Recent projects
- POI & 评价
- 达人内容
	- Managing creator fulfillment and price control
		- Creator fulfillment: incentivize creators to complete brand deals and post videos after accepting orders
		- Price control: making advertised price same as in-store price
	- Inaccurate POI
		- Creators take advantage of the publish streaming quota 
	- Collaborating with the existing ecosystem and TnS teams to minimize false positives
	- 
- 


![[Screenshot 2025-12-31 at 3.31.27 PM.png]]![[Screenshot 2025-12-31 at 3.31.37 PM.png]]

# todos
- [ ] need to come up with a contribution to the existing one pager for the team
- [ ] choose between the following to write a one pager for: 业务-评价、平台-审核、稳定性(translation: Business - Evaluation, Platform - Moderation, Stability)
- [ ] goal setting for probation
- [ ] daily reports for the first two weeks
- [ ] shift to weekly reports until the end of the probation period
- [ ] Daily report filling time: Complete it before the end of work every day/Friday/bi-weekly Friday, and write it in reverse chronological order according to the date

food for thought:
## 可以尝试回答几个启发性问题

## can try answering a few thought-provoking questions

> 持续补充
> 
> Continuous replenishment

- 业务：TTLS 季度业务目标是什么
    
- Business: What are the quarterly business objectives of TTLS?
    
- 业务：TTLS GNE 当前的重点项目有哪些，为什么是它们
    
- Business: What are the current key projects of TTLS GNE, and why are they the key ones?
    
- 组织：串讲阶段主攻的方向，协作最紧密的人有哪些
    
- Organization: What are the main directions during the summary phase, and who are the people with the closest collaboration?
    
- 流程：SDLC，火车发布流程是怎样的？
    
- Process: SDLC, what is the train release process?

治理基建
- dossier - 卷宗
- governance gateway - 网关
- GNE engine - 流程
- sentry - 哨兵
- feature platform - 特征平台
哨兵&卷宗&特征&流程&网关