<h1 align="center">Egecan Akıncıoğlu - Software Engineer & Language Designer</h1>
<p align="center">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=C181FF&center=true&vCenter=true&width=500&lines=Backend+Engineer+%7C+Java%2C+Spring+Boot%2C+Kafka;Language+Designer+%7C+Creator+of+Arimo;Compiler+Engineer+%7C+Rust%2C+LLVM%2C+FFI;Full-Stack+%7C+TypeScript%2C+Next.js%2C+React" alt="Typing SVG" />
</p>

<table>
  <tr>
    <td width="70%" valign="top">
      <h2>👋 Hi, I'm Egecan Akıncıoğlu</h2>
      <ul>
        <li>Designing and building <strong>Arimo</strong> — a self-hosting compiled programming language with hybrid memory management (borrow checker + GC), bootstrapped in <strong>Rust</strong>.</li>
        <li>Backend Engineer specializing in <strong>Java</strong> and <strong>Spring Boot</strong> microservices with <strong>Redis</strong>, <strong>Kafka</strong>, <strong>RabbitMQ</strong>, <strong>OAuth2</strong>, and <strong>Docker</strong>.</li>
        <li>Full-stack when needed — <strong>TypeScript</strong>, <strong>Next.js</strong>, <strong>React</strong>, <strong>Prisma</strong>, <strong>gRPC</strong>.</li>
        <li>Committed to <strong>clean architecture</strong>, <strong>SOLID principles</strong>, <strong>memory safety</strong>, and <strong>compiler engineering</strong>.</li>
      </ul>
    </td>
    <td width="30%" valign="top" align="center">
      <img src="https://spotify-github-profile.kittinanx.com/api/view.svg?uid=31yghuzwfbpibnm3wvtllfijk4mm&cover_image=true&theme=default&show_offline=false&background_color=121212&interchange=false&bar_color=53b14f&bar_color_cover=true">
    </td>
  </tr>
</table>


<h2 align="left">🔮 Arimo — A Programming Language</h2>

<p>
  <strong>Arimo is a general-purpose, statically-typed, AOT-compiled systems programming language — built from scratch, and already running.</strong>
  Designed to cover the full spectrum from bare-metal kernel and driver development to high-level OOP application code, all within a single language.
  It combines <strong>Java-grade object-oriented expressiveness</strong> (classes, interfaces, generics, abstract types, rich annotations) with
  <strong>systems-level control</strong> (manual memory, inline x86-64 assembly, interrupt handlers, calling conventions) and
  a <strong>3-tier hybrid memory model</strong> that eliminates GC overhead in the default path.
  The compiler generates native <strong>x86-64 PE32+</strong> executables with no dependency on LLVM, GCC, or any external toolchain —
  the entire pipeline lives inside the compiler itself.
  The stage 1 compiler is <strong>written in Arimo</strong>, making it self-hosting.
  Arimo is an attempt to close the gap between systems languages and high-level ones — not with compromises, but by design.
</p>

<table>
  <tr>
    <td><strong>Status</strong></td>
    <td>Built from scratch — compiler is functional, programs compile and run</td>
  </tr>
  <tr>
    <td><strong>Use cases</strong></td>
    <td>OS kernels, device drivers, game engines, high-performance backends, desktop apps</td>
  </tr>
  <tr>
    <td><strong>Memory</strong></td>
    <td>Borrow checker (compile-time, zero cost) → ARC (shared values) → GC (cycles only); <code>@ManualMemory</code> for full control</td>
  </tr>
  <tr>
    <td><strong>Backend</strong></td>
    <td>Native x86-64 → PE32+ — no LLVM, no GCC, no external toolchain; entirely self-contained</td>
  </tr>
  <tr>
    <td><strong>OOP</strong></td>
    <td>Classes, structs (value types), interfaces (with defaults), abstract classes, single inheritance, generics with bounds</td>
  </tr>
  <tr>
    <td><strong>Annotations</strong></td>
    <td><code>@ManualMemory</code> <code>@Freestanding</code> <code>@ForceInline</code> <code>@Pure</code> <code>@Packed</code> <code>@Align</code> <code>@CallingConvention</code> <code>@Likely</code> and more</td>
  </tr>
  <tr>
    <td><strong>Systems</strong></td>
    <td>C FFI, inline x86-64 assembly, interrupt handlers, syscalls, raw pointers, SIMD (<code>Vec4f</code> / <code>Vec8f</code> / <code>Vec4i</code> / <code>Vec8i</code>)</td>
  </tr>
  <tr>
    <td><strong>Bootstrap</strong></td>
    <td>Stage 0 in Rust: Lexer → Parser → TypeChecker → BorrowChecker → IRLower → IRToX64 → PEWriter</td>
  </tr>
  <tr>
    <td><strong>Self-hosting</strong></td>
    <td>Stage 1 compiler (<code>Main.arm</code>) written in Arimo — compiles itself</td>
  </tr>
</table>

<p align="right">
  <a href="https://github.com/egecanakincioglu/arimo"><strong>arimo →</strong></a> &nbsp;·&nbsp;
  <a href="https://github.com/egecanakincioglu/arimo-bootstrap"><strong>arimo-bootstrap →</strong></a>
</p>

<h2 align="left">📂 My Recent Projects on GitHub</h2>


<table>
    <thead>
        <tr>
          <th align="left">Project</th>
          <th align="left">Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>🔮 <a href="https://github.com/egecanakincioglu/arimo"><strong>Arimo</strong></a></td>
            <td>Self-hosting systems programming language. Java-inspired syntax, Rust-like ownership, TypeScript null safety. Compiles to native x86-64 PE32+ with no external toolchain.</td>
        </tr>
        <tr>
            <td>⚙️ <a href="https://github.com/egecanakincioglu/arimo-bootstrap"><strong>Arimo Bootstrap</strong></a></td>
            <td>Stage 0 bootstrap compiler written in Rust. Full pipeline: Lexer → Parser → TypeChecker → BorrowChecker → IRLower → IRToX64 → PEWriter. Generates standalone executables.</td>
        </tr>
        <tr>
            <td>📦 <a href="https://github.com/egecanakincioglu/microservices-platform"><strong>Microservices Platform</strong></a></td>
            <td>Production-grade Spring Boot 3 microservices with Eureka service discovery, API Gateway, JWT authentication, PostgreSQL, Redis, and Docker.</td>
        </tr>
        <tr>
            <td>🤖 <a href="https://github.com/egecanakincioglu/ai-models-arena-tracker"><strong>AI Models Arena Tracker</strong></a></td>
            <td>AI benchmark aggregator using Llama 3 for score normalization. Scrapes LMSYS and Hugging Face leaderboards via 8x daily GitHub Actions pipelines, deploys to Vercel.</td>
        </tr>
    </tbody>
</table>

<h2 align="left">🌐 Tech Stack & Tools</h2>

<table align="center" width="100%">
  <tr>
    <td align="center" valign="top" width="33%">
      <h3>🖥️ Frontend</h3>
      <div align="center">  
        <img src="https://profilinator.rishav.dev/skills-assets/html5-original-wordmark.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/react-original-wordmark.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/nextjs.png" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/angularjs-original.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/vuejs-original-wordmark.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/sass-original.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/logo-title.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/tailwindcss.svg" height="50" />
      </div>
    </td>
    <td align="center" valign="top" width="33%">
      <h3>🛠️ Backend & Systems</h3>
      <div align="center">  
        <img src="https://profilinator.rishav.dev/skills-assets/rust-plain.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/java-original-wordmark.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/c-original.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/cplusplus-original.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/typescript-original.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/python-original.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/nodejs-original-wordmark.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/springio-icon.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/express-original-wordmark.svg" height="50" />
      </div>
    </td>
    <td align="center" valign="top" width="33%">
      <h3>☁️ Database & DevOps</h3>
      <div align="center">  
        <img src="https://profilinator.rishav.dev/skills-assets/docker-original-wordmark.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/postgresql-original-wordmark.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/mysql-original-wordmark.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/redis-original-wordmark.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/nginx-original.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/linux-original.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/kubernetes-icon.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/apache_kafka-icon.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/git-scm-icon.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/rabbitmq-icon.svg" height="50" />
        <img src="https://profilinator.rishav.dev/skills-assets/gnu_bash-icon.svg" height="50" />
      </div>
    </td>
  </tr>
</table>

<h2 align="left">📈 GitHub Statistics</h2>

<table align="center" width="100%">
  <tr>
    <td align="center" width="50%">
      <img 
        src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=egecanakincioglu&layout=compact&hide_border=true&bg_color=00000000"
        width="90%"
      />
    </td>
    <td align="center" width="50%">
      <img 
        src="https://github-readme-stats-eight-theta.vercel.app/api?username=egecanakincioglu&show_icons=true&count_private=true&hide_border=true&bg_color=00000000&custom_title=My%20GitHub%20Profile"
        width="90%"
      />
    </td>
  </tr>
</table>


---

<img src="https://profile-readme-generator.com/assets/pacman.svg" align="center">

---
<br>

<div align="center">
    <a href="https://github.com/egecanakincioglu" target="_blank">
        <img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
    </a>
    <a href="https://gitlab.com/egecanakincioglu" target="_blank">
        <img src=https://img.shields.io/badge/gitlab-330F63.svg?&style=for-the-badge&logo=gitlab&logoColor=white alt=gitlab style="margin-bottom: 5px;" />
    </a>
    <a href="https://stackoverflow.com/users/30934087/egecanakincioglu" target="_blank">
        <img src=https://img.shields.io/badge/stackoverflow-%23F28032.svg?&style=for-the-badge&logo=stackoverflow&logoColor=white alt=stackoverflow style="margin-bottom: 5px;" />
    </a>
    <a href="https://linkedin.com/in/egecan-akincioglu" target="_blank">
        <img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
    </a>
    <a href="https://instagram.com/egecanakincioglu" target="_blank">
        <img src=https://img.shields.io/badge/instagram-%23000000.svg?&style=for-the-badge&logo=instagram&logoColor=white alt=instagram style="margin-bottom: 5px;" />
    </a>  
</div>

<br>

<div align="center">
  <a href="https://www.buymeacoffee.com/egecanakincioglu" target="_blank">
    <img src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-%23FFDD00.svg?&style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt="Buy Me a Coffee"/>
  </a>
</div>
