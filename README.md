[![LinkedIn](https://img.shields.io/badge/LinkedIn-dan--ghincul-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/dan-ghincul/)
[![Email](https://img.shields.io/badge/Email-dan.ghincul01%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dan.ghincul01@gmail.com)

## Education

### Undergraduate Student at Politehnica University of Timișoara
#### Bachelor of Science in Computer Engineering (2023–2027)

[View My Resume](https://github.com/DSElement/DSElement/blob/main/Dan_Ghincul_CV.pdf)

---

## Featured Projects

### [QuizMaster](https://github.com/DSElement/Access-Quizmaster)
Full-stack quiz platform, rebuilt from scratch after the AC Labs training program at The Access Group. Users take official quizzes, write their own and share them with the community; accounts use ASP.NET Core Identity with admin and user roles, and answers are graded on the server without exposing the answer key. Uploaded PDFs are indexed by a background worker into overlapping chunks, embedded with Gemini and stored in PostgreSQL with pgvector for similarity search. A Gemini tool-calling agent then searches the document and writes a quiz draft, which is rejected and retried until every question has four distinct options, no giveaway answer and a citation to a chunk the agent actually read.

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

### [MeshDrop](https://github.com/DSElement/MeshDrop)
AirDrop-style file sharing over the local network with zero configuration, built by a 2-person team. Devices find each other through mDNS and stream files over a custom framed TCP protocol in 64 KB chunks, encrypted with ChaCha20-Poly1305 under per-transfer X25519 keys. My part was the device-trust layer: Ed25519-signed handshakes, 6-digit pairing codes derived from the handshake transcript, trust saved only after a mutually signed confirmation, and automatic resend once pairing succeeds.

![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-00B4AB?style=for-the-badge)

---

### [Concurrent Stock Exchange](https://github.com/DSElement/PCBE/tree/main/Stock-Exchange)
Team project I lead: an in-memory stock exchange where traders submit and modify orders concurrently. Orders are matched asynchronously on a thread pool with partial fills and a trade history. Both orders in a trade are locked in a fixed ID order to prevent deadlocks, and price and quantity are re-checked under the locks so stale orders never trade.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

---

### [MRET — My Reverse Engineering Tool](https://github.com/DSElement/Small-Projects/tree/main/MyReverseEngineeringTool)
Command-line tool that turns any JAR into text or PlantUML class diagrams using Java reflection: members, generics, annotations and extends/implements/uses relationships, with package filters for fat JARs and renderer plugins loaded at runtime.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white)

---

### [Frequency Game](https://github.com/DSElement/Frequency-Game) · [Play it live](https://poetic-shortbread-21cf39.netlify.app)
Browser ear-training game: listen to a tone and find its frequency over 5 rounds. Web Audio synthesis with live preview, logarithmic scoring, pointer/touch/keyboard controls and shareable challenge links, all client-side.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Web Audio API](https://img.shields.io/badge/Web_Audio_API-333333?style=for-the-badge)

---

More in [Small-Projects](https://github.com/DSElement/Small-Projects): OpenMP alpha-beta search, Raft leader election over MPI, event-driven Java, simulations and computer vision. Also [osu! Automation](https://github.com/DSElement/Osu-Automation) (C#, Win32) and an [8086 microsystem design](https://github.com/DSElement/Microsistem-cu-Microprocesorul-8086).

---

![GitHub Streak](https://streak-stats.demolab.com?user=DSElement&theme=dark)

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DSElement/DSElement/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/DSElement/DSElement/output/github-contribution-grid-snake.svg">
    <img alt="GitHub contribution grid snake animation" src="https://raw.githubusercontent.com/DSElement/DSElement/output/github-contribution-grid-snake.svg">
  </picture>
</div>
