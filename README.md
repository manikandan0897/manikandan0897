<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mani Kandan | Blockchain Engineer</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: #0f172a;
      color: #e2e8f0;
      line-height: 1.6;
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 40px 20px;
    }

    header {
      text-align: center;
      margin-bottom: 40px;
    }

    header h1 {
      font-size: 2.5rem;
      color: #38bdf8;
    }

    header p {
      color: #94a3b8;
      margin-top: 10px;
    }

    .section {
      margin-bottom: 40px;
    }

    .section h2 {
      margin-bottom: 15px;
      border-left: 4px solid #38bdf8;
      padding-left: 10px;
      color: #38bdf8;
    }

    .about p {
      color: #cbd5f5;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skill {
      background: #1e293b;
      padding: 8px 12px;
      border-radius: 6px;
      font-size: 14px;
      border: 1px solid #334155;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
    }

    .card {
      background: #1e293b;
      padding: 20px;
      border-radius: 10px;
      border: 1px solid #334155;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      border-color: #38bdf8;
    }

    .card h3 {
      margin-bottom: 10px;
      color: #38bdf8;
    }

    .card p {
      font-size: 14px;
      color: #cbd5f5;
    }

    .contact a {
      color: #38bdf8;
      text-decoration: none;
      margin-right: 15px;
    }

    footer {
      text-align: center;
      margin-top: 40px;
      color: #64748b;
    }
  </style>
</head>

<body>
  <div class="container">

    <!-- Header -->
    <header>
      <h1>Hi 👋, I'm Mani Kandan</h1>
      <p>Senior Blockchain Engineer | DeFi Architect | Cross-Chain Systems</p>
    </header>

    <!-- About -->
    <section class="section about">
      <h2>👨🏻‍💻 About Me</h2>
      <p>
        Blockchain engineer with 5+ years of experience designing and building
        secure, scalable DeFi systems, DEX architectures, and cross-chain protocols.
        Specialized in Solidity, Rust, and Node.js with a strong focus on gas optimization,
        system reliability, and secure smart contract design.
      </p>
    </section>

    <!-- Skills -->
    <section class="section">
      <h2>🛠 Tech Stack</h2>
      <div class="skills">
        <div class="skill">Solidity</div>
        <div class="skill">Rust</div>
        <div class="skill">Node.js</div>
        <div class="skill">TypeScript</div>
        <div class="skill">React</div>
        <div class="skill">MongoDB</div>
        <div class="skill">Redis</div>
        <div class="skill">EVM</div>
        <div class="skill">Cosmos (IBC)</div>
        <div class="skill">LayerZero</div>
        <div class="skill">Stargate</div>
        <div class="skill">Hyperledger</div>
      </div>
    </section>

    <!-- Projects -->
    <section class="section">
      <h2>🚀 Key Projects</h2>
      <div class="projects">

        <div class="card">
          <h3>DEX (Uniswap v2/v3)</h3>
          <p>Built high-performance decentralized exchange handling 1000+ daily swaps with optimized liquidity logic.</p>
        </div>

        <div class="card">
          <h3>Cross-Chain Lottery</h3>
          <p>Developed LayerZero-based lottery system with Chainlink VRF and 99.9% reliability.</p>
        </div>

        <div class="card">
          <h3>RWA Tokenization</h3>
          <p>Implemented ERC-3643 compliant asset tokenization platform with KYC/AML enforcement.</p>
        </div>

        <div class="card">
          <h3>Hyperledger Supply Chain</h3>
          <p>Enterprise-grade blockchain system with tamper-proof tracking and audit trails.</p>
        </div>

      </div>
    </section>

    <!-- Contact -->
    <section class="section contact">
      <h2>🔗 Connect</h2>
      <a href="https://github.com/maniclarisco" target="_blank">GitHub</a>
      <a href="#" target="_blank">LinkedIn</a>
      <a href="mailto:manidsamy888@gmail.com">Email</a>
    </section>

    <!-- Footer -->
    <footer>
      <p>© 2026 Mani Kandan | Built with ❤️ in Web3</p>
    </footer>

  </div>
</body>
</html>
