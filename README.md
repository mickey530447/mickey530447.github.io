<div align="center">

# 👋 Hello, I'm Nguyen Le Minh

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D9FF&center=true&vCenter=true&random=false&width=600&lines=Ex+Senior+Software+Engineer+%40+Zalo;Building+Scalable+Systems;Low+Latency+High+Throughput)](https://git.io/typing-svg)

<img src="https://komarev.com/ghpvc/?username=mickey530447&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />

📍 Ho Chi Minh City, Vietnam

</div>

---

## 🚀 About Me

```java
public class MinhNguyen {
    private String role = "Senior Software Engineer";
    private String company = "Zalo";
    private String location = "Ho Chi Minh City";
    
    private String[] techStacks = {
        "Java", "Message Queue", "Thrift",
        "MongoDB", "Redis", "Generative AI (LLMs)"
    };
    
    public String getPhilosophy() {
        return "First, solve the problem. Then, write the code.";
    }
}
```

<div align="center">

### 💼 Experience At

<img src="https://img.shields.io/badge/Zalo-0068FF?style=for-the-badge&logo=zalando&logoColor=white" alt="Zalo"/>

</div>

---

## 💼 Work Experience

### Zalo | Senior Software Engineer
**08/2021 - 03/2026**

- ⚡ **Business Account:**
  - Designed a distributed architecture utilizing **Thrift RPC** for synchronous calls and an **in-house Message Queue** for asynchronous event processing, serving **2M+ users** while maintaining **P99 < 50ms** latency.
  - Ensured high availability through **multi-DC deployment** with automatic failover, **circuit breaker** pattern, and **multi-layer cache/database replication** to eliminate single points of failure.
  - Prevented race conditions in concurrent account creation and upgrade flows by implementing **distributed locking** via an in-house cache-backed mechanism.
  - Adopted an **event-driven architecture** using an in-house pub/sub system with **multiple event topics** (account package changes, eKYC verification, etc.) to decouple and process business side effects asynchronously.
  - Optimized read performance through a layered approach: an in-house **replicated cache cluster** to absorb read traffic, and **read/write database separation** to independently scale query throughput from writes.
  - Proactively detected and resolved performance bottlenecks by establishing real-time observability using **monitoring dashboards (Grafana)**.
- 💳 **zBox Payment Gateway:**
  - Participated in building the zBox payment gateway, optimized for high throughput, processing **2M+ transactions/day**.
  - Implemented a **Redis-based distributed lock** mechanism to ensure idempotency and prevent duplicate transactions under concurrent requests.
  - Integrated multiple payment channels (**ZaloPay, Momo, Napas**) by designing a **unified transaction routing pattern** and a **standalone reconciliation service** consuming payment events and running **scheduled transaction scans** to standardize cross-platform payment flows.
  - Developed the payment checkout landing page, guiding users through product selection, payment method options, and order summary while ensuring secure handling of sensitive user data.
  - **Internal Automation:** Leveraged AI to build a custom API testing tool, streamlining the validation of complex payment flows and reducing manual testing efforts by automating repetitive test cases.
- 🤖 **Engineering Productivity & Automation (Internal):**
  - Developed an **AI-Driven SDLC Orchestrator** to automate end-to-end development tasks; integrated with Jira API to autonomously fetch tickets and delegate sub-tasks (requirement generation, coding, and security scanning) to specialized AI agents.
  - Optimized internal workflows by building leverage tools that accelerated the team's development lifecycle and improved code quality.
- 📱 **PC/Web Core Features (Profile, Friend, Group):**
  - Optimized Zalo core features on PC platform, maintained and improved system performance.

### MGM Technology Partners | Intern
**02/2020 - 06/2020**

- Used **React** to maintain and improve internal websites

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

<img src="https://img.shields.io/badge/Java_(Primary)-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>

**Technologies & Protocols**

<img src="https://img.shields.io/badge/Message_Queue-231F20?style=for-the-badge&logoColor=white" alt="Message Queue"/>
<img src="https://img.shields.io/badge/Thrift-D12127?style=for-the-badge&logoColor=white" alt="Thrift"/>

**AI & Automation**

<img src="https://img.shields.io/badge/Generative_AI_(LLMs)-FF6F00?style=for-the-badge&logoColor=white" alt="Generative AI"/>
<img src="https://img.shields.io/badge/AI_Orchestration-7B1FA2?style=for-the-badge&logoColor=white" alt="AI Orchestration"/>
<img src="https://img.shields.io/badge/Prompt_Engineering-00C853?style=for-the-badge&logoColor=white" alt="Prompt Engineering"/>

**Databases**

<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>

**Tools & Platform**

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira"/>
<img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="CI/CD"/>

**Architecture**

<img src="https://img.shields.io/badge/Microservices-FF6F00?style=for-the-badge&logoColor=white" alt="Microservices"/>
<img src="https://img.shields.io/badge/Distributed_System-4285F4?style=for-the-badge&logoColor=white" alt="Distributed System"/>
<img src="https://img.shields.io/badge/High_Availability-00C853?style=for-the-badge&logoColor=white" alt="High Availability"/>
<img src="https://img.shields.io/badge/Scalability-7B1FA2?style=for-the-badge&logoColor=white" alt="Scalability"/>

</div>

---

## 🏆 Featured Projects

<div align="center">

| Project                    | Description                                                                                        |
| -------------------------- | -------------------------------------------------------------------------------------------------- |
| 📱 **Zalo Core Features**   | Optimized core Zalo features                                                                       |
| 🏢 **Business Account**     | zBusiness Platform - A business account solution helping individuals sell more effectively on Zalo |
| 💳 **zBox Payment Gateway** | High-performance payment gateway, integrating ZaloPay, Napas, Momo                                 |

</div>

---

## 🎓 Education

### University of Greenwich | BSc Computer Science
**2018 - 2021** | Da Nang, Vietnam

- GPA: **3.5/4** — Second Class Honours (1st Division)

### Quoc Hoc Hue | High School for the Gifted
- Major: **Information Technology (IT)**

---

## ✨ Personal Project

*My creative journey, one step at a time*

<div align="center">

### 📚 Arcania Studio

*Với lòng tự hào dân tộc và yêu mến văn hoá, lịch sử nước nhà.*
*Arcania Studio muốn thông qua những dự án truyện tranh để **đem sử Việt ra thế giới**.*

**🎯 Future: Games • Platform • Animation**

<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>

<br/><br/>

<a href="https://www.facebook.com/profile.php?id=61576227615421">
  <img src="https://img.shields.io/badge/Follow_Arcania_Studio-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"/>
</a>

</div>

---


---

## 🤝 Connect with Me

<div align="center">

<a href="mailto:nguyenleminh530447@gmail.com">
  <img src="https://img.shields.io/badge/Email-nguyenleminh530447%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

<a href="https://github.com/mickey530447">
  <img src="https://img.shields.io/badge/GitHub-mickey530447-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://www.linkedin.com/in/le-minh-nguyen-0a4b4413a/">
  <img src="https://img.shields.io/badge/LinkedIn-Le_Minh_Nguyen-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

</div>

---

<div align="center">

### 💭 Favorite Quote

*"First, solve the problem. Then, write the code."* - John Johnson

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>

</div>