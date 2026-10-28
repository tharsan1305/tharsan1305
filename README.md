Created README.md

Select all the code inside the box below and paste it directly into your GitHub editor (`tharsan1305/tharsan1305` `README.md`):

```markdown
<div align="center">

<!-- 3D Cyber Security & Cloud Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,50:0f172a,100:00f7ff&height=220&section=header&text=THARSAN%20S&fontSize=56&fontAlignY=36&animation=twinkling&desc=AI%20Security%20Engineer%20%E2%80%A2%20Cloud%20Security%20(AWS)%20%E2%80%A2%20DevSecOps&descSize=17&descAlignY=62" width="100%" alt="Tharsan Header Banner" />

<!-- Cyber Terminal Animated Typing SVG -->
<a href="https://stharsan.onrender.com/">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=22&duration=2600&pause=1000&color=00F7FF&center=true&vCenter=true&width=850&lines=AI+Security+Engineer+%26+Cloud+Security+Specialist;Cloud+Infrastructure+Defender+%26+DevSecOps+Engineer;Core+Security+%26+Full-Stack+Engineer+%40+PragatiX;Pre-Final+Year+Cybersecurity+%40+JJCET+(CGPA+8.3%2F10);Active+Threat+Intelligence+%26+LLM+Security+Researcher" alt="Cyber Typing SVG" />
</a>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=tharsan1305&label=PROFILE+VIEWS&color=00F7FF&style=for-the-badge" alt="Profile Views" />
  <img src="https://img.shields.io/badge/CLEARANCE-CLOUD%20DEFENDER-10b981?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Clearance" />
  <img src="https://img.shields.io/badge/TRYHACKME-TOP%2025%25-red?style=for-the-badge&logo=tryhackme&logoColor=white" alt="THM Rank" />
</p>

<!-- 3D-Look Cyber Quick Action Shields -->
<p align="center">
  <a href="https://stharsan.onrender.com/"><img src="https://img.shields.io/badge/PORTFOLIO-000000?style=for-the-badge&logo=vercel&logoColor=00F7FF" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/tharsan1305"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://drive.google.com/file/d/1Nz2AmiWbBcT22ZLd_xpf_NlX_mpFQoLw/view?usp=sharing"><img src="https://img.shields.io/badge/RESUME_PDF-2563EB?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Resume" /></a>
  <a href="https://tryhackme.com/p/stharsan13052007"><img src="https://img.shields.io/badge/TRYHACKME-212C42?style=for-the-badge&logo=tryhackme&logoColor=red" alt="TryHackMe" /></a>
  <a href="https://www.credly.com/users/tharsan1305"><img src="https://img.shields.io/badge/CREDLY_BADGES-FF6B00?style=for-the-badge&logo=credly&logoColor=white" alt="Credly" /></a>
  <a href="https://builder.aws.com/community/@tharsan"><img src="https://img.shields.io/badge/AWS_BUILDER-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Builder" /></a>
  <a href="https://medium.com/@stharsan.cs"><img src="https://img.shields.io/badge/MEDIUM-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" /></a>
</p>

</div>

---

### 🖥️ `[root@tharsan-secops ~]# whoami`

```bash
> STATUS: Pre-Final Year B.E. CSE (Cybersecurity) @ J.J. College of Engineering & Technology
> ACADEMIC STANDING: 8.3 / 10 CGPA
> SPECIALIZATION: Cloud Security (AWS) • AI Security Guardrails • DevSecOps Automation
> MISSION: Building and defending full-stack, cloud-native production systems against modern attack vectors
> TARGET ROLES: AI Security Engineer • Cloud Security Engineer • DevSecOps Engineer • AppSec Engineer
```

I am a cybersecurity engineer and full-stack software developer who builds resilient, cloud-hardened applications using **AWS, Spring Boot, React, Python, Docker, and CI/CD security automation**. 

I engineer the frontend UI/UX and head the application security architecture for **PragatiX**, a production platform launched across Web, Google Play Store, and iOS App Store. My research spans **LLM security guardrails, automated API penetration testing, and Zero Trust cloud architectures**.

---

### 🧊 3D Contribution Grid (Isometric Activity City)

<div align="center">
  <img src="https://github-profile-3d-contrib.vercel.app/api?username=tharsan1305&theme=tokyo-night" width="100%" alt="3D Contribution Graph" />
</div>

---

### ☁️ Production Cloud Security Architecture (PragatiX Platform)

```mermaid
flowchart TD
    subgraph Internet["Public Edge Layer"]
        User["User Traffic (Web & Mobile)"] --> R53["AWS Route 53 (DNS & Geo-Routing)"]
        R53 --> CF["AWS CloudFront (CDN + Edge SSL/TLS)"]
        CF --> WAF["AWS WAF (DDoS Mitigation & Rate Limiting)"]
    end

    subgraph VPC["Isolated AWS Virtual Private Cloud (VPC)"]
        subgraph PublicSubnet["Public Subnet / Reverse Proxy"]
            ALB["Application Load Balancer / Security Groups"]
        end

        subgraph AppSubnet["Private Application Subnet"]
            EC2["AWS EC2 Cluster<br/>(Spring Boot REST API • JWT • bcrypt)"]
        end

        subgraph DataSubnet["Private Storage Subnet"]
            RDS[("AWS RDS Multi-AZ<br/>(Encrypted MySQL Database)")]
        end

        WAF --> ALB
        ALB --> EC2
        EC2 --> RDS
    end

    subgraph CI_CD["DevSecOps Hardened Pipeline"]
        GH["Git Push"] --> SAST["CodeQL & SonarQube (SAST)"]
        SAST --> SCA["Trivy & Snyk (Dependency Scan)"]
        SCA --> SecretScan["TruffleHog (Secret Detection)"]
        SecretScan --> Deploy["Automated Deploy to AWS EC2"]
    end

    Deploy -.-> EC2

    classDef edge fill:#07090e,stroke:#00f7ff,stroke-width:2px,color:#fff;
    classDef vpc fill:#0c1322,stroke:#3b82f6,stroke-width:2px,color:#fff;
    classDef cicd fill:#0b1120,stroke:#10b981,stroke-width:2px,color:#fff;
    class Internet edge;
    class VPC vpc;
    class CI_CD cicd;
```

---

### 🛡️ Security & Cloud Technical Arsenal

<div align="center">

#### ☁️ Cloud & Infrastructure Security (AWS)
<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,terraform,linux,bash" alt="Cloud Stack" />
</p>
<p><i>AWS (EC2, RDS, CloudFront, Route 53, S3, Security Hub, IAM, VPC) • Docker Security • Terraform IaC</i></p>

#### 🔐 Offensive & Defensive Cybersecurity Tools
<p>
  <img src="https://skillicons.dev/icons?i=kali,wireshark,postman" alt="Security Tools" />
</p>
<p><i>OWASP Top 10 • OWASP API Security • Burp Suite Professional • Nmap • Metasploit • OWASP ZAP • OSINT • Threat Intel • JWT / bcrypt</i></p>

#### 🤖 AI Security & Machine Learning
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,scikitlearn,python" alt="AI Security" />
</p>
<p><i>RAG Architecture • MongoDB Vector Search • Claude Code API • OpenAI API • Prompt Injection Defense • LLM Security Guardrails</i></p>

#### 💻 Full-Stack Software Engineering
<p>
  <img src="https://skillicons.dev/icons?i=spring,react,nodejs,express,mysql,mongodb,postgres,sqlite,git,githubactions" alt="Dev Stack" />
</p>
<p><i>Spring Boot • React.js • Node.js • Express • MySQL RDS • MongoDB • GitHub Actions CI/CD</i></p>

</div>

---

### 🔥 Featured Cloud & Security Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📱 PragatiX: Production Campus Platform</h3>
      <p align="center">
        <a href="https://pragatix.in"><img src="https://img.shields.io/badge/Live_Web-pragatix.in-00F7FF?style=flat-square&logo=googlechrome&logoColor=black" alt="PragatiX Web"/></a>
        <a href="https://play.google.com/store/apps/details?id=jjcet.PragatiX"><img src="https://img.shields.io/badge/Google_Play-Available-34A853?style=flat-square&logo=googleplay&logoColor=white" alt="Google Play"/></a>
        <a href="https://apps.apple.com/us/app/pragatix/id6814354285"><img src="https://img.shields.io/badge/App_Store-iOS-000000?style=flat-square&logo=apple&logoColor=white" alt="App Store"/></a>
      </p>
      <ul>
        <li><b>Stack:</b> Spring Boot REST API, MySQL RDS, React.js Web Portal, Flutter Mobile App.</li>
        <li><b>Cloud Defense:</b> Deployed on AWS (EC2, RDS, CloudFront, Route 53). Built JWT-based RBAC, bcrypt password hashing, and dependency vulnerability scanning in GitHub Actions CI/CD.</li>
        <li><b>Status:</b> Live campus production serving students, faculty, and administrative tiers.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🤖 AI-Powered API Pentesting Agent</h3>
      <p align="center">
        <a href="https://github.com/tharsan1305"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github" alt="GitHub Repo"/></a>
        <img src="https://img.shields.io/badge/OWASP-API_Top_10-E0234E?style=flat-square" alt="OWASP API"/>
      </p>
      <ul>
        <li><b>Features:</b> Ingests OpenAPI/Swagger specs and Postman collections; automatically scans endpoints for BOLA/IDOR, broken authentication, JWT tampering, and injection vectors.</li>
        <li><b>AI Triage:</b> Uses OpenAI API to generate contextual code patches, vulnerability ratings, and executive risk summaries.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🛡️ SENTINEL.AI — Phishing & URL Threat Analyzer</h3>
      <p align="center">
        <a href="https://phishing-email-detection-model-psi.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-SENTINEL.AI-blue?style=flat-square&logo=vercel" alt="Live Demo"/></a>
        <a href="https://github.com/tharsan1305"><img src="https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github" alt="Source"/></a>
      </p>
      <ul>
        <li><b>Tech:</b> Python, Flask, TF-IDF Vectorization, Multinomial Naive Bayes.</li>
        <li><b>Capabilities:</b> Real-time email body scanning, malicious lexical URL heuristics, email sandbox simulator, and risk-breakdown diagnostics.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🔍 Network Vulnerability Scanner</h3>
      <p align="center">
        <a href="https://vulnerability-scanner-eight-delta.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-Scanner_Dashboard-brightgreen?style=flat-square&logo=vercel" alt="Live Demo"/></a>
        <a href="https://github.com/tharsan1305/Vulnerability-Scanner"><img src="https://img.shields.io/badge/Code-Vulnerability--Scanner-181717?style=flat-square&logo=github" alt="Code"/></a>
      </p>
      <ul>
        <li><b>Tech:</b> Python, Flask, Socket Programming, Nmap engine, SQLite.</li>
        <li><b>Capabilities:</b> Real-time TCP port reconnaissance, service banner grabbing, vulnerability signature classification, and downloadable audit reports.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🗺️ Cybersecurity Roadmap 2026</h3>
      <p align="center">
        <a href="https://github.com/tharsan1305/CyberSecurity-Roadmap-2026"><img src="https://img.shields.io/badge/Repository-CyberSecurity--Roadmap-orange?style=flat-square&logo=github" alt="Roadmap"/></a>
      </p>
      <ul>
        <li>A day-by-day learning roadmap covering networking, Linux, Cloud, DevSecOps, Pentesting, SOC, DFIR, and AI Security.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🚀 SIH-2026 Toolkit & Guide</h3>
      <p align="center">
        <a href="https://github.com/tharsan1305/SIH-2026"><img src="https://img.shields.io/badge/Repository-SIH--2026-blueviolet?style=flat-square&logo=github" alt="SIH 2026"/></a>
      </p>
      <ul>
        <li>Comprehensive Smart India Hackathon kit: domain guides (AI/ML, Cyber, Cloud), PPT templates, and evaluation frameworks.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🏆 Verified Certifications & Badges

- 🎖️ **Google Cloud:** Machine Learning Operations (MLOps) for Generative AI — [Verify Profile](https://www.skills.google/public_profiles/4f892d54-bf92-4b00-909f-184b24b497c0)
- 🛡️ **OPSWAT Academy:** Cybersecurity Fundamentals Associate (OCFA) — [Credential d8tvCZZvcg](https://learn.opswatacademy.com/certificate/d8tvCZZvcg)
- 🛡️ **ISC2:** Certified in Cybersecurity (CC) Candidate — [Verify Badge](https://www.credly.com/badges/3c8c1446-a14e-41ab-aea5-d899194d9afa/public_url)
- 🌐 **Cisco:** Introduction to Modern AI — [Verify Badge](https://www.credly.com/badges/11f830d7-01d9-4762-aca3-91299fab2568/public_url)
- 🍃 **MongoDB:** Securing MongoDB Self-Managed Networking & Building RAG Apps — [Credly](https://www.credly.com/users/tharsan1305)
- 🛡️ **Hackviser:** Certified Cybersecurity Foundations (CORE) — [Verify HV-CORE-MO1IKK9E](https://hackviser.com/verify?id=HV-CORE-MO1IKK9E)
- 🎭 **The SecOps Group:** Certified Social Engineering Defense Practitioner (CSEDP) — `ID: 11623889`
- 🧠 **Anthropic:** Claude Code API Development
- 🔍 **ArcX:** Cyber Threat Intelligence Analyst
- 🏢 **Industry Simulations:** Deloitte Cyber • Mastercard Cyber Simulation • Datacom Cloud Ops • Tata Cybersecurity

---

### ✍️ Cloud & Cyber Architecture Articles

- ☁️ [Why Companies Choose AWS: Connect a Frontend, Backend and Security the Easy Way](https://builder.aws.com/content/3KZw5soZusIH7X5wmDVQe6ASZtf/why-companies-choose-aws-connect-a-frontend-backend-and-security-the-easy-way) — *AWS Builder Center*
- ⚡ [Why Amazon EC2 Is the Heart of AWS: A Real-World Example with an Online Shop](https://builder.aws.com/content/3KRTk2TITjBS0uxfSz39GOYoIcp/why-amazon-ec2-is-the-heart-of-aws-a-real-world-example-with-an-online-shop) — *AWS Builder Center*
- 🔐 [Zero Trust Security: Why "Verify Identity" Isn't Enough Anymore (And What's Next for AI Agents)](https://medium.com/@stharsan.cs) — *Medium*
- 💼 [Why Most Cybersecurity Students Never Get Hired](https://linkedin.com/in/tharsan1305) — *LinkedIn*

---

### 📊 Cyber Stats & 3D Trophies

<div align="center">

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tharsan1305&show_icons=true&theme=tokyonight&hide_border=true&bg_color=07090e&title_color=00F7FF&icon_color=6366f1&text_color=94a3b8" height="175" alt="Tharsan's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tharsan1305&layout=compact&theme=tokyonight&hide_border=true&bg_color=07090e&title_color=00F7FF&text_color=94a3b8" height="175" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://leetcard.jacoblin.cool/stharsan13?theme=dark&font=JetBrains%20Mono" height="150" alt="LeetCode Card" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=tharsan1305&theme=tokyonight&no-bg=true&margin-w=10&row=1&column=7" alt="GitHub Trophies" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=tharsan1305&theme=tokyonight&hide_border=true&background=07090e&ring=00F7FF&fire=00F7FF&currStreakNum=00F7FF" alt="GitHub Streak" />
</p>

</div>

---

### 🌐 Secure Communication & Profiles

<div align="center">

| Channel | Identifier | Link |
| :--- | :--- | :--- |
| 🌍 **Portfolio** | `stharsan.onrender.com` | [Open Portfolio](https://stharsan.onrender.com/) |
| 💼 **LinkedIn** | `/in/tharsan1305` | [Connect](https://www.linkedin.com/in/tharsan1305) |
| 📧 **Encrypted Mail** | `stharsan13052007@gmail.com` | [Send Email](mailto:stharsan13052007@gmail.com) |
| 🛡️ **TryHackMe** | `@stharsan13052007` (Top 25%) | [Inspect Profile](https://tryhackme.com/p/stharsan13052007) |
| 📜 **Credly** | `tharsan1305` | [View Badges](https://www.credly.com/users/tharsan1305) |
| 📱 **PragatiX** | `pragatix.in` | [Launch App](https://pragatix.in) |
| 📄 **Resume** | Direct PDF File | [Download Resume](https://drive.google.com/file/d/1Nz2AmiWbBcT22ZLd_xpf_NlX_mpFQoLw/view?usp=sharing) |
| 💻 **LeetCode** | `@stharsan13` | [View Solved](https://leetcode.com/u/stharsan13) |
| 📝 **Medium** | `@stharsan.cs` | [Read Articles](https://medium.com/@stharsan.cs) |
| 🪪 **Google Skills** | Cloud & GenAI Transcript | [Public Profile](https://www.skills.google/public_profiles/4f892d54-bf92-4b00-909f-184b24b497c0) |
| 🎓 **Microsoft Learn** | Learning Profile | [Transcript](https://learn.microsoft.com/en-gb/users/tharsan13/) |
| 🐦 **X (Twitter)** | `@THARSANat6` | [Follow](https://x.com/THARSANat6) |
| 💬 **Discord** | Community Server | [Join](https://discord.gg/ZVBDVU65) |

</div>

<br/>

<div align="center">
  <h3>⚡ Building Secure Systems • Learning Continuously • Creating Impact</h3>
  <p><b>AI Security Engineer</b> • <b>Cloud Security & DevSecOps Specialist</b></p>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,50:0f172a,100:00f7ff&height=120&section=footer" width="100%" alt="Footer Wave" />
```
