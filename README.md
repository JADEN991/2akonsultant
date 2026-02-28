[2akonsultant.html](https://github.com/user-attachments/files/25640685/2akonsultant.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>2A Konsultant - Empowering Your Digital Future</title>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
  />
  <link
    href="https://fonts.googleapis.com/css?family=Montserrat:400,700&display=swap"
    rel="stylesheet"
  />
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: "Montserrat", sans-serif;
      background: #021828;
      color: #b0b8c9;
      scroll-behavior: smooth;
    }
    a {
      text-decoration: none;
      color: inherit;
    }
    .header {
      display: flex;
      align-items: flex-start;
      padding: 40px 6vw 0 6vw;
      height: 85px;
    }
    .brand {
      color: #fff;
      font-weight: 700;
      font-size: 2rem;
      display: flex;
      align-items: flex-end;
    }
    .brand .logo {
      color: #16e4fa;
      font-size: 2.6rem;
      font-weight: 700;
      margin-right: 8px;
    }
    .brand-details {
      font-size: 0.9rem;
      margin-top: 7px;
      font-weight: 400;
      color: #b0b8c9;
      margin-left: 18px;
      letter-spacing: 2px;
      text-transform: uppercase;
      user-select: none;
    }
    .hero-section {
      padding: 38px 6vw 0 6vw;
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      flex-wrap: wrap;
    }
    .hero-text {
      flex-basis: 55%;
    }
    .hero-section h1 {
      color: #21c6dd;
      font-size: 2.5rem;
      font-weight: 500;
      margin-bottom: 16px;
      line-height: 1.15;
    }
    .hero-section .btn {
      background: none;
      border: 1.5px solid #21c6dd;
      color: #21c6dd;
      border-radius: 22px;
      padding: 10px 26px;
      font-size: 1rem;
      cursor: pointer;
      margin-top: 20px;
      transition: background 0.2s, color 0.2s;
    }
    .hero-section .btn:hover,
    .hero-section .btn:focus {
      background: #21c6dd;
      color: #fff;
      outline: none;
    }
    .hero-img {
      flex-basis: 38%;
      max-width: 340px;
      margin-top: -30px;
    }
    .hero-img img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 6px 30px rgba(0, 0, 0, 0.23);
      display: block;
    }
    .about-section {
      text-align: center;
      margin: 72px auto 0 auto;
      padding: 0 6vw;
      max-width: 850px;
    }
    .about-section h2 {
      color: #21c6dd;
      font-size: 2rem;
      margin-bottom: 18px;
      font-weight: 500;
    }
    .about-section p {
      font-size: 1.15rem;
      color: #f3f3f3;
      margin-bottom: 56px;
      line-height: 1.6;
    }
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 24px;
      margin-bottom: 50px;
    }
    .service-card {
      background: #091f2e;
      border-radius: 14px;
      padding: 32px 24px;
      flex: 1 1 230px;
      max-width: 250px;
      min-width: 220px;
      text-align: center;
      box-shadow: 0 2px 11px rgba(30, 87, 110, 0.08);
      margin-bottom: 30px;
      border: 0.5px solid rgba(33, 198, 221, 0.05);
      transition: transform 0.15s, box-shadow 0.18s;
      cursor: pointer;
      position: relative;
      z-index: 1;
    }
    .service-card:hover,
    .service-card:focus {
      transform: translateY(-6px) scale(1.022);
      box-shadow: 0 10px 36px rgba(33, 198, 221, 0.1);
      border-color: #21c6dd80;
      outline: none;
    }
    .service-card i {
      font-size: 2.5rem;
      margin-bottom: 16px;
      color: #21c6dd;
    }
    .service-card h3 {
      color: #21c6dd;
      font-size: 1.18rem;
      margin-bottom: 6px;
      font-weight: 500;
    }
    .modal {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      background: rgba(7, 26, 44, 0.93);
      z-index: 2000;
      align-items: center;
      justify-content: center;
      animation: fadeInBg 0.25s;
    }
    @keyframes fadeInBg {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }
    .modal-content {
      position: relative;
      background: #0d2236;
      border-radius: 14px;
      padding: 38px 28px 30px 28px;
      max-width: 440px;
      width: 93vw;
      box-shadow: 0 6px 29px rgba(33, 198, 221, 0.15);
      color: #f3f3f3;
      animation: popin 0.19s;
      max-height: 85vh;
      overflow-y: auto;
    }
    @keyframes popin {
      from {
        transform: scale(0.94) translateY(30px);
        opacity: 0;
      }
      to {
        transform: none;
        opacity: 1;
      }
    }
    .modal-close {
      background: none;
      border: none;
      font-size: 1.7rem;
      color: #21c6dd;
      cursor: pointer;
      position: absolute;
      right: 14px;
      top: 16px;
      transition: color 0.14s;
    }
    .modal-close:hover,
    .modal-close:focus {
      color: #fff;
      outline: none;
    }
    .modal-content h2 {
      color: #21c6dd;
      font-size: 1.4rem;
      font-weight: 600;
      margin: 0 0 13px 0;
      letter-spacing: -1px;
    }
    .modal-content .modal-icon {
      font-size: 2.2rem;
      color: #16e4fa;
      margin-bottom: 14px;
      margin-top: -12px;
      display: block;
    }
    .modal-content ul {
      color: #c2f3ff;
      font-size: 1.01rem;
      margin-top: 14px;
      margin-bottom: 0;
      padding-left: 1.1em;
      text-align: left;
      line-height: 1.6;
    }
    .modal-content ul li {
      margin-bottom: 5px;
    }
    .modal-content p {
      color: #f3f6fa;
      margin-bottom: 10px;
      line-height: 1.54;
    }
    #consultationModal .modal-content {
      background: #091f2e;
      border-radius: 14px;
      padding: 32px 24px;
      max-width: 430px;
      box-shadow: 0 4px 24px rgba(33, 198, 221, 0.15);
      color: #f3f3f3;
    }
    #consultationModal h2 {
      color: #21c6dd;
      font-size: 1.55rem;
      margin: 0 0 8px 0;
      font-weight: 500;
    }
    #consultationModal label {
      margin-top: 14px;
      display: block;
      color: #b0b8c9;
      font-size: 0.97em;
      text-align: left;
    }
    #consultationModal input,
    #consultationModal textarea {
      width: 100%;
      margin-top: 5px;
      padding: 9px;
      border-radius: 7px;
      border: none;
      background: #112238;
      color: #fff;
      font-family: inherit;
      font-size: 1rem;
      box-sizing: border-box;
    }
    #consultationModal textarea {
      min-height: 80px;
      resize: vertical;
    }
    #consultationModal button[type="submit"] {
      margin-top: 22px;
      width: 100%;
      padding: 12px;
      border-radius: 22px;
      background: #21c6dd;
      color: #091f2e;
      font-weight: 600;
      font-size: 1.1rem;
      border: none;
      cursor: pointer;
      transition: background 0.2s;
    }
    #consultationModal button[type="submit"]:hover,
    #consultationModal button[type="submit"]:focus {
      background: #19aabe;
      outline: none;
    }
    .logos-section {
      text-align: center;
      margin: 40px 0;
      max-width: 900px;
      padding: 0 6vw;
    }
    .logos-section h4 {
      color: #21c6dd;
      margin-bottom: 16px;
      font-weight: 600;
      font-size: 1.5rem;
    }
    .logos-row {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 22px;
    }
    .ai-logo {
      height: 38px;
      width: 140px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: #162636;
      border-radius: 8px;
      border: 1px solid #223;
      font-size: 1rem;
      color: #16e4fa;
      font-weight: 600;
      letter-spacing: 0.5px;
      filter: grayscale(60%);
      transition: filter 0.3s, color 0.3s, background 0.3s;
      padding: 6px 10px;
      cursor: default;
      user-select: none;
      box-shadow: 0 0 15px rgba(22, 228, 250, 0.1);
    }
    .ai-logo:hover,
    .ai-logo:focus {
      filter: none;
      outline: none;
      color: #21c6dd;
      background: #0a2c43;
      cursor: pointer;
    }
    .ai-logo i {
      font-size: 1.3em;
      margin-right: 8px;
    }
    .testimonials {
      max-width: 800px;
      margin: 44px auto 0 auto;
      text-align: center;
      padding: 0 6vw;
    }
    .testimonials h4 {
      color: #21c6dd;
      font-weight: 600;
      font-size: 1.5rem;
      margin-bottom: 24px;
    }
    .testimonial-block {
      font-style: italic;
      color: #e3ecfa;
      margin-bottom: 32px;
      font-size: 1.1rem;
      line-height: 1.5;
      position: relative;
      padding: 0 24px;
    }
    .testimonial-block:before {
      content: "“";
      font-size: 4rem;
      color: #21c6dd;
      position: absolute;
      left: 8px;
      top: -12px;
      font-family: serif;
      opacity: 0.2;
    }
    .testimonial-block span {
      color: #21c6dd;
      font-weight: 600;
      display: block;
      margin-top: 12px;
      font-size: 1rem;
    }
    footer {
      margin-top: 60px;
      padding: 32px 0;
      text-align: center;
      background: #091f2e;
      color: #b0b8c9;
      user-select: none;
    }
    footer .socials {
      margin-bottom: 12px;
    }
    footer .socials a {
      margin: 0 12px;
      color: #21c6dd;
      transition: color 0.3s;
      font-size: 1.5rem;
    }
    footer .socials a:hover,
    footer .socials a:focus {
      color: #16e4fa;
      outline: none;
    }
    footer .copyright {
      font-size: 0.98em;
    }
    @media (max-width: 900px) {
      .header,
      .hero-section,
      .about-section,
      .logos-section,
      .testimonials {
        padding: 28px 3vw 0 3vw;
      }
      .header {
        height: auto;
        flex-direction: column;
        align-items: flex-start;
      }
      .hero-section {
        flex-direction: column;
      }
      .hero-img {
        margin: 32px auto 0 auto;
      }
      .hero-text {
        flex-basis: 100%;
      }
      .logos-row {
        gap: 10px;
      }
      .service-card {
        max-width: none;
        flex-basis: 100%;
      }
    }
    .btn,
    .service-card {
      outline-offset: 3px;
    }
  </style>
</head>
<body>
  <header class="header" role="banner">
    <div>
      <span class="brand" aria-label="Brand name">
        <span class="logo">2A</span>Konsultant
      </span>
      <div class="brand-details">INNOVATE · IMPLEMENT · IMPACT</div>
    </div>
  </header>
  <main>
    <section class="hero-section" aria-label="Hero banner">
      <div class="hero-text">
        <h1>Empowering Your Digital Future</h1>
        <button
          class="btn"
          type="button"
          aria-haspopup="dialog"
          aria-controls="consultationModal"
          id="openConsultationBtn"
        >
          Request a Consultation
        </button>
      </div>
      <div class="hero-img">
        <img
          src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=500&q=80"
          alt="Person working on a laptop"
          loading="lazy"
        />
      </div>
    </section>
    <section
      class="about-section"
      aria-labelledby="about-title"
    >
      <h2 id="about-title">About us</h2>
      <p>
        We help startups, SMEs, and enterprises scale using cutting-edge IT
        strategies and AI-powered technologies.
      </p>
      <div
        class="services"
        role="list"
        aria-label="Our services"
        id="services"
      >
        <div
          tabindex="0"
          class="service-card"
          data-service="consulting"
          aria-haspopup="dialog"
          aria-controls="modal-consulting"
        >
          <i class="fa-solid fa-mobile-screen" aria-hidden="true"></i>
          <h3>IT Consulting</h3>
        </div>
        <div
          tabindex="0"
          class="service-card"
          data-service="support"
          aria-haspopup="dialog"
          aria-controls="modal-support"
        >
          <i class="fa-solid fa-wrench" aria-hidden="true"></i>
          <h3>Support & Maintenance</h3>
        </div>
        <div
          tabindex="0"
          class="service-card"
          data-service="development"
          aria-haspopup="dialog"
          aria-controls="modal-development"
        >
          <i class="fa-solid fa-code" aria-hidden="true"></i>
          <h3>Web & Software Development</h3>
        </div>
        <div
          tabindex="0"
          class="service-card"
          data-service="aicoding"
          aria-haspopup="dialog"
          aria-controls="modal-aicoding"
        >
          <i class="fa-solid fa-user-astronaut" aria-hidden="true"></i>
          <h3>AI Coding Assistant</h3>
        </div>
        <div
          tabindex="0"
          class="service-card"
          data-service="aisolutions"
          aria-haspopup="dialog"
          aria-controls="modal-aisolutions"
        >
          <i class="fa-solid fa-robot" aria-hidden="true"></i>
          <h3>AI Solutions</h3>
        </div>
        <div
          tabindex="0"
          class="service-card"
          data-service="training"
          aria-haspopup="dialog"
          aria-controls="modal-training"
        >
          <i class="fa-solid fa-graduation-cap" aria-hidden="true"></i>
          <h3>Training & Placement</h3>
        </div>
      </div>
    </section>
    <section
      class="logos-section"
      aria-label="Trusted by leading organizations"
    >
      <h4>Trusted by Leading Organizations</h4>
      <div class="logos-row" role="list">
        <div
          class="ai-logo"
          title="Fireflies.ai – Meeting AI"
          tabindex="0"
          role="listitem"
          ><i class="fa-solid fa-fire"></i>Fireflies.ai</div
        >
        <div
          class="ai-logo"
          title="MindsDB – AutoML"
          tabindex="0"
          role="listitem"
          ><i class="fa-solid fa-brain"></i>MindsDB</div
        >
        <div
          class="ai-logo"
          title="Arthur AI – Model Monitoring"
          tabindex="0"
          role="listitem"
          ><i class="fa-solid fa-user-robot"></i>Arthur AI</div
        >
        <div
          class="ai-logo"
          title="Shield AI – Autonomous AI"
          tabindex="0"
          role="listitem"
          ><i class="fa-solid fa-shield"></i>Shield AI</div
        >
        <div
          class="ai-logo"
          title="Deepgram – Speech AI"
          tabindex="0"
          role="listitem"
          ><i class="fa-solid fa-wave-square"></i>Deepgram</div
        >
      </div>
    </section>
    <section
      class="testimonials"
      aria-label="Customer testimonials"
    >
      <h4>What Our Clients Say</h4>
      <div class="testimonial-block" tabindex="0">
        “2A Konsultant enabled our digital transformation journey with expertise
        and speed.”
        <span>— CTO, FinTech Startup</span>
      </div>
      <div class="testimonial-block" tabindex="0">
        “Their AI-driven solutions boosted our software delivery velocity by 40%.”
        <span>— Head of Engineering, SaaS Company</span>
      </div>
      <div class="testimonial-block" tabindex="0">
        “Reliable support and proactive maintenance saved us from several
        critical outages.”
        <span>— IT Manager, Retail Chain</span>
      </div>
    </section>
  </main>

  <!-- Service Modals -->
  <div
    id="modal-consulting"
    class="modal"
    role="dialog"
    aria-modal="true"
    tabindex="-1"
    aria-labelledby="modal-consulting-title"
    aria-describedby="modal-consulting-desc"
  >
    <div class="modal-content">
      <button
        class="modal-close"
        aria-label="Close IT Consulting details"
        onclick="closeServiceModal('consulting')"
      >
        &times;
      </button>
      <span class="modal-icon"
        ><i class="fa-solid fa-mobile-screen"></i
      ></span>
      <h2 id="modal-consulting-title">IT Consulting</h2>
      <p id="modal-consulting-desc">
        Unlock your business potential with our <b>holistic IT consulting
        services</b>, as trusted by Fortune 500–style clients. From digital
        strategy to cloud & security transformation, we empower you to drive
        innovation, resilience, and efficiency.
      </p>
      <ul>
        <li>Business &amp; digital transformation roadmaps</li>
        <li>Technology stack selection &amp; architecture advisory</li>
        <li>Process automation &amp; cost optimization</li>
        <li>Cloud migration and cybersecurity</li>
        <li>IT risk assessment, compliance and governance</li>
      </ul>
      <p style="margin-top: 1em; color: #21c6dd; font-size: 1.02em;">
        Engage with experts who shaped transformations for banks, retail giants,
        and high-growth startups.
      </p>
    </div>
  </div>

  <div
    id="modal-support"
    class="modal"
    role="dialog"
    aria-modal="true"
    tabindex="-1"
    aria-labelledby="modal-support-title"
    aria-describedby="modal-support-desc"
  >
    <div class="modal-content">
      <button
        class="modal-close"
        aria-label="Close Support & Maintenance details"
        onclick="closeServiceModal('support')"
      >
        &times;
      </button>
      <span class="modal-icon"><i class="fa-solid fa-wrench"></i></span>
      <h2 id="modal-support-title">Support & Maintenance</h2>
      <p id="modal-support-desc">
        Ensure mission-critical systems run <b>seamlessly 24×7</b>. Like
        industry leaders IBM and TCS, we deliver robust, proactive support—from
        IT infrastructure and cloud platforms to custom applications.
      </p>
      <ul>
        <li>24/7 monitoring &amp; helpdesk</li>
        <li>Proactive issue diagnosis &amp; healing</li>
        <li>Security patching, upgrades, backup &amp; DR</li>
        <li>Managed cloud and on-premises environments</li>
        <li>SLAs aligned to your business</li>
      </ul>
      <p style="margin-top: 1em; color: #21c6dd; font-size: 1.02em;">
        Our retained support partners see <b>30%+ reduction in downtime</b> and
        improved user satisfaction scores.
      </p>
    </div>
  </div>

  <div
    id="modal-development"
    class="modal"
    role="dialog"
    aria-modal="true"
    tabindex="-1"
    aria-labelledby="modal-development-title"
    aria-describedby="modal-development-desc"
  >
    <div class="modal-content">
      <button
        class="modal-close"
        aria-label="Close Web & Software Development details"
        onclick="closeServiceModal('development')"
      >
        &times;
      </button>
      <span class="modal-icon"><i class="fa-solid fa-code"></i></span>
      <h2 id="modal-development-title">Web & Software Development</h2>
      <p id="modal-development-desc">
        Drive growth with <b>custom solutions that scale</b>. From mobile-first
        web apps to enterprise platforms, we deliver human-centric, secure and
        high-performance software per best practices of ThoughtWorks, Cognizant,
        and global digital leaders.
      </p>
      <ul>
        <li>End-to-end product engineering (web, mobile, cloud)</li>
        <li>API development &amp; integration</li>
        <li>Microservices architectures</li>
        <li>UX/UI design with agile delivery</li>
        <li>Security, scalability &amp; future-proofing</li>
      </ul>
      <p style="margin-top: 1em; color: #21c6dd; font-size: 1.02em;">
        Trusted by global startups and established brands for delivering, on-time
        and on-budget.
      </p>
    </div>
  </div>

  <div
    id="modal-aicoding"
    class="modal"
    role="dialog"
    aria-modal="true"
    tabindex="-1"
    aria-labelledby="modal-aicoding-title"
    aria-describedby="modal-aicoding-desc"
  >
    <div class="modal-content">
      <button
        class="modal-close"
        aria-label="Close AI Coding Assistant details"
        onclick="closeServiceModal('aicoding')"
      >
        &times;
      </button>
      <span class="modal-icon"><i class="fa-solid fa-user-astronaut"></i></span>
      <h2 id="modal-aicoding-title">AI Coding Assistant</h2>
      <p id="modal-aicoding-desc">
        Supercharge your engineers’ productivity with state-of-the-art <b>AI
        code assistants</b>—trained on best-in-class tech stacks (Python, Java,
        JS, Cloud) and prompt engineering practices. Inspired by the accelerators
        used at top-notch digital labs.
      </p>
      <ul>
        <li>AI/ML-powered code suggestions &amp; error detection</li>
        <li>Automated documentation and refactoring</li>
        <li>Code review and security scanning tools</li>
        <li>Seamless IDE, cloud &amp; CI/CD integration</li>
        <li>Fine-tuning for your internal libraries and APIs</li>
      </ul>
      <p style="margin-top: 1em; color: #21c6dd; font-size: 1.02em;">
        Boost code velocity and quality with our proprietary AI tooling stack.
      </p>
    </div>
  </div>

  <div
    id="modal-aisolutions"
    class="modal"
    role="dialog"
    aria-modal="true"
    tabindex="-1"
    aria-labelledby="modal-aisolutions-title"
    aria-describedby="modal-aisolutions-desc"
  >
    <div class="modal-content">
      <button
        class="modal-close"
        aria-label="Close AI Solutions details"
        onclick="closeServiceModal('aisolutions')"
      >
        &times;
      </button>
      <span class="modal-icon"><i class="fa-solid fa-robot"></i></span>
      <h2 id="modal-aisolutions-title">AI Solutions</h2>
      <p id="modal-aisolutions-desc">
        Transform data into impact with <b>tailored AI solutions</b>—from
        business intelligence to natural language automation—taking cues from
        leading consultancies like Accenture, Capgemini, and Infosys.
      </p>
      <ul>
        <li>Custom AI and machine learning workflows</li>
        <li>Predictive analytics and decision automation</li>
        <li>Data engineering pipelines &amp; feature stores</li>
        <li>Conversational bots, RPA, and process intelligence</li>
        <li>Deployment on AWS, Azure, or GCP</li>
      </ul>
      <p style="margin-top: 1em; color: #21c6dd; font-size: 1.02em;">
        Get advanced, secure AI in production—at scale and at speed.
      </p>
    </div>
  </div>

  <div
    id="modal-training"
    class="modal"
    role="dialog"
    aria-modal="true"
    tabindex="-1"
    aria-labelledby="modal-training-title"
    aria-describedby="modal-training-desc"
  >
    <div class="modal-content">
      <button
        class="modal-close"
        aria-label="Close Training & Placement details"
        onclick="closeServiceModal('training')"
      >
        &times;
      </button>
      <span class="modal-icon"><i class="fa-solid fa-graduation-cap"></i></span>
      <h2 id="modal-training-title">Training & Placement</h2>
      <p id="modal-training-desc">
        Prepare your workforce for tomorrow’s tech landscape! Our training and
        placement services (inspired by proven global models) bridge the gap
        between talent and opportunity for organizations and aspiring
        professionals alike.
      </p>
      <ul>
        <li>Industry-focused technical curriculum (AI, cloud, devops, software)</li>
        <li>Soft skills, leadership &amp; agile workshops</li>
        <li>Hands-on projects &amp; live case-study exposure</li>
        <li>Resume building and interview readiness bootcamps</li>
        <li>Strong corporate placement network &amp; mentoring</li>
      </ul>
      <p style="margin-top: 1em; color: #21c6dd; font-size: 1.02em;">
        We empower careers—hundreds of professionals placed at leading
        enterprises, startups, and digital product firms.
      </p>
    </div>
  </div>

  <!-- Consultation Modal -->
  <div
    id="consultationModal"
    class="modal"
    role="dialog"
    aria-modal="true"
    tabindex="-1"
    aria-labelledby="consultModalTitle"
  >
    <div class="modal-content">
      <div
        class="modal-header"
        style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 0;"
      >
        <h2 id="consultModalTitle">Request a Consultation</h2>
        <button
          type="button"
          class="modal-close"
          aria-label="Close Consultation form"
          onclick="closeModal()"
        >
          &times;
        </button>
      </div>
      <form
        id="consultForm"
        action="#"
        method="POST"
        novalidate
        autocomplete="off"
      >
        <label for="name">Full Name* </label>
        <input
          type="text"
          id="name"
          name="name"
          required
          autocomplete="name"
          aria-describedby="name-error"
        />
        <span id="name-error" class="error" style="color:#ff8080;display:none;">Please enter your name.</span>

        <label for="email">Email* </label>
        <input
          type="email"
          id="email"
          name="email"
          required
          autocomplete="email"
          aria-describedby="email-error"
        />
        <span id="email-error" class="error" style="color:#ff8080;display:none;">Please enter a valid email.</span>

        <label for="phone">Phone </label>
        <input type="tel" id="phone" name="phone" autocomplete="tel" />

        <label for="company">Company/Organization </label>
        <input type="text" id="company" name="company" autocomplete="organization" />

        <label for="requirements">How can we help you?* </label>
        <textarea
          id="requirements"
          name="requirements"
          required
          aria-describedby="req-error"
        ></textarea>
        <span id="req-error" class="error" style="color:#ff8080;display:none;"
          >Please provide your requirements.</span
        >

        <button type="submit">Submit Request</button>
    </form>
    </div>
  </div>

  <footer role="contentinfo">
    <div class="socials" aria-label="Social media links">
      <a
        href="https://linkedin.com/in/yourprofile"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="LinkedIn"
      >
        <i class="fab fa-linkedin"></i>
      </a>
      <a
        href="https://twitter.com/yourprofile"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Twitter"
      >
        <i class="fab fa-twitter"></i>
      </a>
      <a
        href="https://www.instagram.com/2a.konsultant"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Instagram"
      >
        <i class="fab fa-instagram"></i>
      </a>
      <a
        href="https://www.facebook.com/twoakonsultant"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Facebook"
      >
        <i class="fab fa-facebook"></i>
      </a>
      <a href="mailto:2akonsultant@gmail.com" aria-label="Email 2A Konsultant">
        <i class="fas fa-envelope"></i>
      </a>
    </div>
    <div class="copyright">© 2025 2A Konsultant. All rights reserved.</div>
  </footer>

  <!-- EmailJS SDK -->
  <script src="https://cdn.jsdelivr.net/npm/emailjs-com@3/dist/email.min.js"></script>
  <script>
    (function () {
      emailjs.init("YOUR_EMAILJS_USER_ID"); // <-- Replace with your EmailJS user ID
    })();

    const serviceMap = {
      consulting: "modal-consulting",
      support: "modal-support",
      development: "modal-development",
      aicoding: "modal-aicoding",
      aisolutions: "modal-aisolutions",
      training: "modal-training",
    };

    document.querySelectorAll(".service-card").forEach((card) => {
      card.addEventListener("click", () => openServiceModal(card));
      card.addEventListener("keydown", (e) => {
        if (e.key === "Enter" || e.key === " ") {
          e.preventDefault();
          openServiceModal(card);
        }
      });
    });

    function openServiceModal(card) {
      const key = card.getAttribute("data-service");
      if (serviceMap[key]) {
        const modal = document.getElementById(serviceMap[key]);
        modal.style.display = "flex";
        modal.setAttribute("tabindex", "-1");
        modal.focus();
        document.body.style.overflow = "hidden";
      }
    }

    function closeServiceModal(key) {
      if (serviceMap[key]) {
        const modal = document.getElementById(serviceMap[key]);
        modal.style.display = "none";
        document.body.style.overflow = "";
      }
    }

    Object.values(serviceMap).forEach((id) => {
      const modal = document.getElementById(id);
      modal.addEventListener("click", (e) => {
        if (e.target === modal) {
          modal.style.display = "none";
          document.body.style.overflow = "";
        }
      });
      modal.addEventListener("keydown", (e) => {
        if (e.key === "Escape") {
          modal.style.display = "none";
          document.body.style.overflow = "";
        }
      });
    });

    const consultationModal = document.getElementById("consultationModal");
    const consultationBtn = document.getElementById("openConsultationBtn");
    consultationBtn.addEventListener("click", () => {
      consultationModal.style.display = "flex";
      consultationModal.setAttribute("tabindex", "-1");
      consultationModal.focus();
      document.body.style.overflow = "hidden";
    });

    function closeModal() {
      consultationModal.style.display = "none";
      document.body.style.overflow = "";
      clearValidationErrors();
    }

    consultationModal.addEventListener("click", (e) => {
      if (e.target === consultationModal) closeModal();
    });

    consultationModal.addEventListener("keydown", (e) => {
      if (e.key === "Escape") closeModal();
    });

    const consultForm = document.getElementById("consultForm");

    // Validation helper:
    function showError(id, show) {
      const el = document.getElementById(id);
      if (el) el.style.display = show ? "block" : "none";
    }
    function clearValidationErrors() {
      showError("name-error", false);
      showError("email-error", false);
      showError("req-error", false);
    }

    function validateEmail(email) {
      // Simple regex for email validation
      const re = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
      return re.test(String(email).toLowerCase());
    }

    consultForm.addEventListener("submit", function (e) {
      e.preventDefault();

      clearValidationErrors();

      let valid = true;

      const name = this.name.value.trim();
      const email = this.email.value.trim();
      const requirements = this.requirements.value.trim();

      if (!name) {
        showError("name-error", true);
        valid = false;
      }
      if (!email || !validateEmail(email)) {
        showError("email-error", true);
        valid = false;
      }
      if (!requirements) {
        showError("req-error", true);
        valid = false;
      }

      if (!valid) return;

      // Prepare EmailJS parameters (template params must match your EmailJS template)
      const templateParams = {
        from_name: name,
        from_email: email,
        phone: this.phone.value.trim() || "N/A",
        company: this.company.value.trim() || "N/A",
        message: requirements,
      };

      // Use your own Service ID, Template ID, and User ID from EmailJS dashboard
      emailjs
        .send("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", templateParams)
        .then(
          function () {
            alert("Thank you! Your request was submitted.");
            consultForm.reset();
            closeModal();
          },
          function (error) {
            alert(
              "Oops! There was a problem submitting the form.\n" +
                error.text ||
                ""
            );
          }
        );
    });

    // Optional: Trap focus inside modals for accessibility
    const focusableSelectors =
      'a[href], area[href], input:not([disabled]), select:not([disabled]), textarea:not([disabled]), button:not([disabled]), iframe, object, embed, [tabindex="0"]';

    function trapFocus(element) {
      const focusableEls = element.querySelectorAll(focusableSelectors);
      if (focusableEls.length === 0) return;
      const firstFocusableEl = focusableEls[0];
      const lastFocusableEl = focusableEls[focusableEls.length - 1];
      element.addEventListener("keydown", (e) => {
        if (e.key === "Tab") {
          if (e.shiftKey) {
            if (document.activeElement === firstFocusableEl) {
              e.preventDefault();
              lastFocusableEl.focus();
            }
          } else {
            if (document.activeElement === lastFocusableEl) {
              e.preventDefault();
              firstFocusableEl.focus();
            }
          }
        }
      });
    }
    Object.values(serviceMap).forEach((id) => trapFocus(document.getElementById(id)));
    trapFocus(consultationModal);
  </script>
</body>
</html>
