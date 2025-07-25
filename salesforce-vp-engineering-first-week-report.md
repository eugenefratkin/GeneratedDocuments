# First-Week Report  
## Role: VP of Engineering — Salesforce  
### Author: Eugene Fratkin  
### Date: <!-- 2025-07-25 -->

---

## 1. Onboarding  

_This section captures logistics, orientation sessions, and early introductions for week 1._

### 1.1 Logistics & Setup  
- Corporate system access (Okta, GitHub Enterprise, Jira): **TBD**  
- Hardware & workspace readiness: **TBD**  
- Development-environment configuration: **TBD**

### 1.2 Orientation Sessions  
| Session | Host | Date | Key Takeaways |
|---------|------|------|---------------|
| New-Hire Orientation | HR | **TBD** | **TBD** |
| Security & Compliance | CISO Office | **TBD** | **TBD** |
| Product Vision & Roadmap | CPO | **TBD** | **TBD** |

### 1.3 Early Introductions  
- 1:1 with **SVP Engineering** — topics: **TBD**  
- Meet & greet with peer VPs (Product, Sales, Customer Success)  
- Introduction to executive assistant & support staff  

---

## 2. Team  

### 2.1 Organizational Chart — Agentforce / Search & Intelligence

```mermaid
graph TD
    %% Root
    VP["VP Engineering\nEugene Fratkin"]

    %% Directs
    VP --> SumK["Sr Mgr • Sumanth Kondakindi"]
    VP --> BrenH["Director • Brendon Hatch"]
    VP --> LakshmiP["Sr Mgr • Lakshmi Reddy Papudippu"]
    VP --> ReneB["Lead • Rene Borm"]
    VP --> TarunB["Architect • Tarundeep Batra"]
    VP --> ColinB["Architect • Colin Brazeau"]

    %% Sumanth Kondakindi org
    SumK --> ZaraC["Zara Chiara Clark"]
    SumK --> CarlosD["Carlos De La Torre"]
    SumK --> AndrewH["Andrew Howe"]
    SumK --> SantoshK["Santhosh Kumar KRS"]
    SumK --> SohiniM["Sohini Majumdar"]
    SumK --> NavidM["Navid Mehrdad"]
    SumK --> VikasK["Vikas Kumar"]
    SumK --> JohnL["John Legelis"]
    SumK --> ManikaM["Manika Mehta"]
    SumK --> AtulR["Atul Ranjan"]
    SumK --> LitoS["Lito Santana"]
    SumK --> HuaS["HuaSheng Su"]

    %% Brendon Hatch – CIP
    BrenH --> LesterG["Lester Garcia Sierra"]
    BrenH --> AvinashK["Avinash Kasipathy"]
    BrenH --> VijayantiK["Vijayanti Kothandaraman"]
    BrenH --> ManeshL["Manesh Kumar Lohano"]
    BrenH --> JhalakM["Jhalak Mahansaria"]
    BrenH --> AjayS["Ajay Singh"]
    BrenH --> SamarthU["Samarth Urs"]

    %% Lakshmi Reddy Papudippu – Product Discovery
    LakshmiP --> MalvikaC["Malvika Choudhary"]
    LakshmiP --> MohammadH["Mohammad Hussain"]
    LakshmiP --> AshutoshJ["Ashutosh Jain"]
    LakshmiP --> GauravK["Gaurav Khengar"]
    LakshmiP --> SoniaK["Sonia Kale"]
    LakshmiP --> RomitK["Romit Kumar"]
    LakshmiP --> SowmyaP["Sowmya Pittala"]
    LakshmiP --> NeeleshJ["Neelesh Jayour"]
    LakshmiP --> VikashS["Vikash Sharma"]
    LakshmiP --> PuneetT["Punit Tripathi"]

    %% Rene Borm – E-com / Chatty
    ReneB --> NayanaA["Nayana Aher"]
    ReneB --> DebankarB["Debankar Banerjee"]
    ReneB --> VinayakB["Vinayak Bhat"]
    ReneB --> PappuC["Pappu Kumar Chaudhary"]
    ReneB --> ShilpiM["Shilpi Mittal"]
    ReneB --> VaibhavP["Vaibhav Pandey"]
    ReneB --> SharadS["Sharad Sharma"]
    ReneB --> ManishT["Manish Torma"]

    %% Tarundeep Batra – Core Search
    TarunB --> MarcelB["Marcel Beck"]
    TarunB --> FedericoD["Federico Donnarumma"]
    TarunB --> TinoG["Tino Glaeser"]
    TarunB --> XinjieH["Xinjie Hao"]
    TarunB --> DilipP["Dilip Patel"]
    TarunB --> AkshayR["Akshay Rajul"]
    TarunB --> AshutoshR["Ashutosh Ravi"]
    TarunB --> AndrewT["Andrew Tickard"]
    TarunB --> YuanSh["Yuanchern Shih"]
    TarunB --> ChrisW["Chris Wang"]
    TarunB --> KannanA["Kannan Alagar"]

    %% Styling
    classDef lead fill:#eef6ff,stroke:#1f78b4,stroke-width:1px;
    classDef ic   fill:#ffffff,stroke:#bbbbbb,stroke-width:0.5px;
    class SumK,BrenH,LakshmiP,ReneB,TarunB,ColinB lead
```

### 2.2 Key Insights  
- Organization spans **65 ICs and 8 managers** across US, India, and Germany.  
- Expertise concentrated in Search, E-commerce merchandising, and Data-intelligence platforms.  
- **21 open headcount** prioritized for infra and AI-driven search initiatives.  

---

## 3. Initial Observations  

### 3.1 Strengths  
1. Deep domain expertise in search & recommendation systems.  
2. Mature CI/CD pipeline leveraging Jenkins & GitHub Actions.  
3. Collaborative culture with clear ownership boundaries.  

### 3.2 Opportunities  
| Area | Observation | Potential Impact |
|------|-------------|------------------|
| Technical Debt | Legacy monolith modules remain critical-path | Slows feature velocity |
| Hiring | 21 open roles across SRE & ML search | Reliability risk / limited bandwidth |
| Documentation | Limited runbooks for on-call rotations | Longer MTTR |

### 3.3 Immediate Next Steps  
1. Complete 1:1s with all direct and skip-level managers (within 2 weeks).  
2. Publish engineering vision & FY OKRs (within 30 days).  
3. Establish dashboard tracking DORA & service-health metrics (within 60 days).  

---

_Last updated: <!-- auto-generated on commit -->_
