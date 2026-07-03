<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d1a,50:2d1b69,100:4c1d95&height=180&section=header&text=Hey%2C%20I'm%20Vrishali%20%F0%9F%91%8B&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=Full-Stack%20Developer&descAlignY=60&descAlign=50&descSize=18"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=C084FC&center=true&vCenter=true&width=650&height=45&lines=Node.js+%2B+React+%2B+PostgreSQL;Shipping+secure%2C+tested%2C+documented+APIs;Integrating+LLMs+into+real+products;B.Tech+CSE+%2725+%7C+Open+to+Opportunities" />

<br/>

<img src="https://komarev.com/ghpvc/?username=vrishali-jadhav&style=flat-square&color=9333ea&label=profile+views" />
<img src="https://img.shields.io/github/followers/Vrishali34?style=flat-square&color=6366f1&label=followers" />
<img src="https://img.shields.io/badge/Open%20to-Opportunities-22c55e?style=flat-square" />

</div>

---

### 👋 About Me

I like building things that actually work in production — secure, tested, well-documented.
- 🎓 B.Tech Computer Engineering (2025 Graduate)
- 📍 From India
- 🚧 Currently:  building full-stack projects, learning system design ,learning AI .....basically learning things and implementing them.
- 💡 Interests: Web Development, API Design, Problem Solving, Open Source


---

## 🚀 Featured Projects

### 🔍 [LogSight](https://github.com/Vrishali34/logsight) — AI-Powered Log Monitoring Platform
**[Live demo →](https://logsight.onrender.com)**

A full-stack observability tool: apps ship logs to it via API, it tracks error rates in real time, fires threshold-based alerts, and uses an LLM to turn raw log spikes into a plain-English root-cause summary.

- **Backend:** Node.js + Express 5, PostgreSQL (Supabase), raw SQL with window functions for analytics
- **AI integration:** Groq + Llama 3.3 70B for natural-language log analysis — provider-agnostic service layer, easy to swap models
- **Security:** JWT auth, bcrypt, per-resource ownership checks on every endpoint (tested: user A cannot read user B's data), rate limiting, Helmet.js headers, Zod validation
- **Frontend:** React + Vite + Recharts for real-time dashboards
- **Quality:** 26 passing tests (Jest + Supertest), Dockerized, deployed on Render

`Node.js` `React` `PostgreSQL` `Groq/Llama 3` `JWT` `Docker`

---

### ✅ [Taskion](https://github.com/Vrishali34/taskion) — Production-Style Task Management API
**[Live demo →](https://taskion.onrender.com)** · **[API docs (Swagger) →](https://taskion.onrender.com/api-docs)**

A REST API built like it had to go to production, not just pass a demo — because that's the standard I hold my own code to.

- **Security:** JWT auth with bcrypt hashing, route-level authorization, tiered rate limiting (global + stricter on auth), Helmet.js headers, Joi validation on every input
- **API design:** Full CRUD with pagination, filtering, and sorting; documented with Swagger/OpenAPI so it's usable without reading the source
- **Observability:** Structured logging with Winston + Morgan (request audit trail, error stack traces)
- **Quality:** 19 passing tests (Jest + Supertest), one-command Docker Compose setup, centralized error handling

`Node.js` `Express` `PostgreSQL` `JWT` `Swagger` `Docker`

---

### 🤖 [GitSpy](https://github.com/Vrishali34/gitspy) — AI Agent for GitHub Insights

An agent that answers natural-language questions about any GitHub account or repo — built to understand how AI agents actually work under the hood, not just call an API and print the response.

- **Agent loop:** the LLM (via Groq) decides which tool to call, Python executes the real GitHub API request, results feed back to the LLM, which responds in natural language — with full conversation memory for follow-ups
- **Tools implemented:** repo stats (stars, issues, language), account-level aggregation (total stars, top repo, most-used language), and repo listing sorted by popularity
- **Stack:** Python, Groq API (`gpt-oss-20b`) for function-calling, Flask backend with session memory, GitHub REST API

`Python` `Groq` `Flask` `LLM Function-Calling`

---

## 🛠️ Tech Stack

<div align="center">

**Languages**
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vite](https://img.shields.io/badge/Vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

**Backend & APIs**
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![Flask](https://img.shields.io/badge/Flask-%23000000.svg?style=for-the-badge&logo=flask&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-%23000000.svg?style=for-the-badge&logo=fastapi&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-%2385EA2D.svg?style=for-the-badge&logo=swagger&logoColor=black)

**AI / LLM**
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)
![LLM Function Calling](https://img.shields.io/badge/LLM%20Function%20Calling-412991?style=for-the-badge&logo=openai&logoColor=white)

**Database**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-%233FCF8E.svg?style=for-the-badge&logo=supabase&logoColor=white)

**DevOps & Testing**
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-%23C21325.svg?style=for-the-badge&logo=jest&logoColor=white)

**Tooling**
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-%23FF6C37.svg?style=for-the-badge&logo=postman&logoColor=white)

</div>

---




## 🏆 Problem Solving

I keep my fundamentals sharp alongside shipping projects — 500+ problems solved on LeetCode, 5★ on HackerRank, 1450 rating on CodeChef.

---

## 🔗 Let's Connect

<div>

[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Vrishali34)

</div>
<div>



</div>
<div align="center">
   4 words I keep in mind (always)
  <div align="center"> Consistency is the key 🏅</div>
</div>
