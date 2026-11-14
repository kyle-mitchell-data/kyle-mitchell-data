<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:29b5e8&height=200&section=header&text=Kyle%20Mitchell&fontSize=54&fontColor=ffffff&fontAlignY=36&desc=Data%20Platform%20Engineer&descSize=18&descAlignY=58" alt="Kyle Mitchell — Data Platform Engineer" />
</p>

<p align="center">
  <a href="https://github.com/kyle-mitchell-data">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=29B5E8&center=true&vCenter=true&width=640&lines=Making+Snowflake+fast+and+cheap+%E2%9D%84%EF%B8%8F;Turning+messy+sources+into+clean+dbt+models;Designing+ETL+that+doesn't+page+you+at+3am;Homelab+tinkerer+%7C+ESP32+wrangler+%7C+builder" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/experience-~10%20years-29B5E8?style=flat-square" />
  <img src="https://img.shields.io/badge/focus-data%20platforms-0f2027?style=flat-square" />
  <img src="https://img.shields.io/badge/based%20in-Kansas-203a43?style=flat-square" />
  <img src="https://komarev.com/ghpvc/?username=kyle-mitchell-data&style=flat-square&color=29B5E8&label=profile%20views" />
</p>

---

### `SELECT * FROM kyle;`

```sql
SELECT
    'Kyle Mitchell'                                   AS name,
    'Data Platform Engineer'                          AS role,
    '~10 years'                                       AS experience,
    ARRAY_CONSTRUCT('Snowflake', 'dbt', 'AWS', 'Python', 'SQL')
                                                      AS daily_drivers,
    ARRAY_CONSTRUCT('warehouse optimization',
                    'ETL / ELT architecture',
                    'platform modernization')         AS specialties,
    'cost per query goes down, trust in data goes up' AS mission
FROM engineers
WHERE curiosity = 'unbounded'
QUALIFY ROW_NUMBER() OVER (ORDER BY coffee_consumed DESC) = 1;
```

---

### 🧰 Tech stack

<p align="left">
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white" />
  <img src="https://img.shields.io/badge/Home%20Assistant-18BCF2?style=for-the-badge&logo=homeassistant&logoColor=white" />
  <img src="https://img.shields.io/badge/Ubiquiti-0559C9?style=for-the-badge&logo=ubiquiti&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailscale-242424?style=for-the-badge&logo=tailscale&logoColor=white" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" />
  <img src="https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" />
</p>

---

### 🏗️ How I think about data platforms

```mermaid
flowchart LR
    A[(Sources<br/>APIs · DBs · files)] -->|ingest| B[Raw / landing<br/>S3 · stages]
    B -->|load| C[(Snowflake)]
    C -->|dbt: staging| D[Clean, typed,<br/>deduped]
    D -->|dbt: marts| E[Business-ready<br/>models]
    E --> F[BI · apps · ML]
    C -.->|monitor| G{{Cost & performance<br/>tuning}}
    G -.-> C
```

- **Snowflake optimization** — warehouse sizing, clustering, query profiling, and squeezing credits until they squeak
- **ETL / ELT architecture** — reusable ingestion patterns that teams can actually follow
- **dbt done right** — layered models, tests, docs, and CI so nobody is afraid to merge
- **Platform modernization** — migrating legacy pipelines into something simpler, cheaper, and observable

---

### 🚧 Currently building

| Project | What it is |
|---|---|
| ✈️ **traveler** | A website that never stays put — it redeploys itself to a random AWS region every few minutes, animates a live "flight" between regions, and serves up facts about wherever it just landed. An excuse to play with AWS architecture. |
| ❄️ **Snowflake + dbt flagship** | A self-deploying Snowflake + dbt project on large public data — spin up a fresh account and watch the whole platform build itself. |
| ⌚ **Garmin Connect IQ** | Custom watch faces, sensor-data capture, and smarter alerts for a Venu 3, written in Monkey C. |

---

### 🔧 Off the clock

- 🖥️ **Homelab** — UniFi network, a PowerEdge waiting for Proxmox, Home Assistant, self-hosted media, and GPU-streamed remote desktop over Tailscale
- 🔌 **Tinkering** — taking electronics apart and building ESP32 / Arduino gadgets nobody asked for
- 🕹️ **Builds** — a DIY arcade cabinet and a large smart art frame in the works
- 📱 **Personal software** — recommendation engines, productivity dashboards, and Android apps built to scratch my own itch
- 🖨️ **Next up** — getting into 3D printing and designing my own parts

---

<p align="center">
  <i>“Make it work, make it right, make it cheap on Snowflake.”</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:29b5e8,50:203a43,100:0f2027&height=110&section=footer" />
</p>
