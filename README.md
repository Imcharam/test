# test
```mermaid
gantt
    dateFormat YYYY-MM-DD
    tickInterval 3day        %%  <-- full word “day”
    axisFormat %d/%m
    title Fundraising Golf Tournament Project Timeline

    section Project Management
    Define project charter and objectives        :pm1, 2025-06-16, 5d
    Assign roles and responsibilities             :pm2, after pm1, 4d
    Schedule weekly team meetings and Zoom calls  :pm3, 2025-06-16, 33d
    Create communication protocols                :pm4, 2025-06-18, 7d
    Track project milestones and KPIs             :pm5, 2025-06-20, 29d
    Risk assessment and mitigation planning       :pm6, 2025-06-16, 33d
    Documentation and reporting                   :pm7, 2025-06-16, 33d

    section Strategy & Planning
    Identify fundraising & awareness targets      :sp1, 2025-06-16, 5d
    Develop event narrative & comms strategy      :sp2, 2025-06-16, 7d
    Build high‑level promotion calendar           :sp3, 2025-06-18, 4d
    Lock in event date & registration deadlines   :sp4, 2025-06-20, 3d
    Define success metrics & cost thresholds      :sp5, 2025-06-20, 5d

    section Marketing & Outreach
    Design digital & print assets                 :mkt1, 2025-06-16, 10d
    Create sign‑up & payment system               :mkt2, 2025-06-20, 19d
    Posters on shop & golf course                 :mkt3, 2025-06-23, 7d
    Email campaign to businesses & groups         :mkt4, 2025-06-16, 24d
    Social media campaign launch                  :mkt5, 2025-07-01, 18d
    Media outreach (radio)                        :mkt6, 2025-07-01, 18d
    BRS opens                                     :mkt7, 2025-07-09, 0d

    section Sponsorship & Fundraising
    Identify & approach sponsors                  :sf1, 2025-06-16, 14d
    Confirm sponsors                              :sf2, after sf1, 5d
    Manage tracking & donations                   :sf3, 2025-06-16, 24d

    section Event Preparation & Logistics
    Confirm venue arrangements                    :log1, 2025-07-10, 5d
    Design & print signage                        :log2, 2025-07-10, 5d
    Prepare materials (photo backdrop)            :log3, 2025-07-12, 3d
    Coordinate on‑site roles & content capture    :log4, 2025-07-10, 8d
    Implement contingency plans                   :log5, 2025-07-10, 8d

    section Event Execution
    On‑site coordination & live updates           :exec1, 2025-07-18, 1d
    Content capture (photos, videos, stories)     :exec2, 2025-07-18, 1d
    Participant management & support              :exec3, 2025-07-18, 1d
    Sponsor recognition during event              :exec4, 2025-07-18, 1d

    section Post‑Event Activities
    Publish results & thank‑you posts             :post1, 2025-07-19, 3d
    Send personalised acknowledgements            :post2, 2025-07-22, 2d
    Final report writing & KPI analysis           :post3, 2025-07-24, 2d

    section Contingency Planning
    Secure backup event date                      :cont1, 2025-06-16, 33d
    Develop raffle event plan                     :cont2, 2025-06-16, 33d
    Distribute raffle tickets                     :cont3, 2025-06-23, 16d
    Organise live draw & prize distribution       :cont4, 2025-07-10, 8d
    Communicate changes to stakeholders           :cont5, 2025-06-16, 33d
    Provide support (refunds, transfers)          :cont6, 2025-07-18, 3d

classDef pmSection   fill:#AED6F1,stroke:#333,stroke-width:1px;
classDef spSection   fill:#ABEBC6,stroke:#333,stroke-width:1px;
classDef mktSection  fill:#F5B7B1,stroke:#333,stroke-width:1px;
classDef sfSection   fill:#F9E79F,stroke:#333,stroke-width:1px;
classDef logSection  fill:#A3E4D7,stroke:#333,stroke-width:1px;
classDef execSection fill:#FADBD8,stroke:#333,stroke-width:1px;
classDef postSection fill:#D2B4DE,stroke:#333,stroke-width:1px;
classDef contSection fill:#D5DBDB,stroke:#333,stroke-width:1px;

class pm1,pm2,pm3,pm4,pm5,pm6,pm7 pmSection
class sp1,sp2,sp3,sp4,sp5         spSection
class mkt1,mkt2,mkt3,mkt4,mkt5,mkt6,mkt7 mktSection
class sf1,sf2,sf3                 sfSection
class log1,log2,log3,log4,log5    logSection
class exec1,exec2,exec3,exec4     execSection
class post1,post2,post3           postSection
class cont1,cont2,cont3,cont4,cont5,cont6 contSection
```
