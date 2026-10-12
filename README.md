<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#102448">
<meta name="description" content="Sarah Mahmoud Abdallah — Pharmaceutical Production Technology student with experience in pharmaceutical sales and customer relations, and interests in programming, web development, automation and AI.">
<title>Sarah Mahmoud Abdallah | Portfolio</title>

<style>
:root {
  --navy: #102448;
  --blue: #2563eb;
  --light-blue: #eff6ff;
  --background: #f4f7fc;
  --text: #1e293b;
  --muted: #64748b;
  --border: #e2e8f0;
  --white: #ffffff;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: 25px;
}

body {
  font-family: Arial, sans-serif;
  background: var(--background);
  color: var(--text);
  line-height: 1.8;
}

a {
  overflow-wrap: anywhere;
}

header {
  background: var(--navy);
  color: white;
  padding: 18px 6%;
}

nav {
  max-width: 1150px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 18px;
  flex-wrap: wrap;
}

.logo {
  font-size: 23px;
  font-weight: bold;
  color: white;
  text-decoration: none;
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 16px;
  flex-wrap: wrap;
}

.nav-links a {
  color: #e2e8f0;
  font-size: 13px;
  text-decoration: none;
}

.nav-links a:hover {
  color: #93c5fd;
}

.lang-btn {
  border: 1px solid #93c5fd;
  background: transparent;
  color: white;
  padding: 7px 13px;
  border-radius: 20px;
  cursor: pointer;
  font-weight: bold;
}

.hero {
  background: linear-gradient(135deg, #102448, #1d4b83);
  color: white;
  text-align: center;
  padding: 75px 20px;
}

.avatar {
  width: 105px;
  height: 105px;
  border-radius: 50%;
  background: #dbeafe;
  color: var(--navy);
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 20px;
  font-size: 36px;
  font-weight: bold;
  border: 3px solid white;
}

.hero h1 {
  font-size: clamp(28px, 5vw, 44px);
  line-height: 1.35;
  margin-bottom: 14px;
}

.hero .headline {
  color: #bfdbfe;
  font-size: clamp(15px, 2.5vw, 19px);
  font-weight: bold;
  margin: 10px auto;
}

.hero .intro {
  max-width: 760px;
  margin: 15px auto;
  color: #e2e8f0;
}

.hero .location {
  color: #cbd5e1;
  font-size: 14px;
  margin-top: 12px;
}

.buttons {
  display: flex;
  justify-content: center;
  gap: 12px;
  flex-wrap: wrap;
  margin-top: 26px;
}

.btn {
  display: inline-block;
  padding: 11px 20px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  font-size: 14px;
}

.btn-primary {
  background: #3b82f6;
  color: white;
}

.btn-outline {
  border: 1px solid white;
  color: white;
}

.container {
  width: 90%;
  max-width: 1050px;
  margin: 38px auto;
}

.section {
  background: white;
  border: 1px solid var(--border);
  border-radius: 15px;
  padding: 30px;
  margin-bottom: 24px;
  box-shadow: 0 5px 20px #10244808;
}

.section h2 {
  color: #163d70;
  font-size: 25px;
  margin-bottom: 18px;
}

.section p {
  color: #475569;
  margin-bottom: 10px;
}

.section h3 {
  color: #1e3a5f;
  font-size: 18px;
  margin-bottom: 8px;
}

.eyebrow {
  color: var(--blue);
  font-size: 12px;
  font-weight: bold;
  letter-spacing: 1px;
  text-transform: uppercase;
  margin-bottom: 5px;
}

.skills {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
  gap: 12px;
  margin-top: 16px;
}

.skill {
  background: var(--light-blue);
  border: 1px solid #dbeafe;
  padding: 13px 15px;
  border-radius: 9px;
  color: #1e40af;
  font-size: 14px;
  font-weight: bold;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(235px, 1fr));
  gap: 16px;
  margin-top: 18px;
}

.card {
  border: 1px solid var(--border);
  border-radius: 12px;
  padding: 22px;
  background: #fbfdff;
}

.card-number {
  width: 42px;
  height: 42px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #dbeafe;
  color: #1d4ed8;
  border-radius: 10px;
  font-size: 19px;
  font-weight: bold;
  margin-bottom: 14px;
}

.card p {
  font-size: 14px;
}

.tag {
  display: inline-block;
  background: #eff6ff;
  color: #1d4ed8;
  border-radius: 20px;
  padding: 5px 10px;
  margin: 4px 3px;
  font-size: 12px;
}

.experience-item,
.education-item,
.project {
  border-left: 3px solid #3b82f6;
  padding: 5px 0 8px 18px;
  margin: 18px 0;
}

[dir="rtl"] .experience-item,
[dir="rtl"] .education-item,
[dir="rtl"] .project {
  border-left: none;
  border-right: 3px solid #3b82f6;
  padding: 5px 18px 8px 0;
}

ul {
  padding-inline-start: 22px;
  color: #475569;
}

li {
  margin-bottom: 7px;
}

.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 14px;
  margin-top: 18px;
}

.contact-item {
  padding: 15px;
  border: 1px solid var(--border);
  border-radius: 10px;
  background: #fbfdff;
}

.contact-item strong {
  display: block;
  color: #163d70;
  margin-bottom: 5px;
}

.contact-item a {
  color: #1d4ed8;
  text-decoration: none;
  font-size: 14px;
}

footer {
  text-align: center;
  padding: 26px 15px;
  background: var(--navy);
  color: #cbd5e1;
  font-size: 13px;
}

@media (max-width: 650px) {
  header {
    padding: 16px;
  }

  nav {
    justify-content: center;
  }

  .nav-links {
    justify-content: center;
    gap: 12px;
  }

  .hero {
    padding: 48px 18px;
  }

  .section {
    padding: 21px;
  }

  .skills {
    grid-template-columns: 1fr 1fr;
  }
}

@media (max-width: 380px) {
  .skills {
    grid-template-columns: 1fr;
  }
}
</style>
</head>

<body>

<header>
  <nav>
    <a class="logo" href="#home">Sarah.</a>

    <div class="nav-links">
      <a href="#about" data-ar="نبذة عني" data-en="About">About</a>
      <a href="#skills" data-ar="المهارات" data-en="Skills">Skills</a>
      <a href="#experience" data-ar="الخبرة" data-en="Experience">Experience</a>
      <a href="#education" data-ar="التعليم" data-en="Education">Education</a>
      <a href="#contact" data-ar="تواصل معي" data-en="Contact">Contact</a>
      <button class="lang-btn" id="langBtn" type="button">العربية</button>
    </div>
  </nav>
</header>

<section class="hero" id="home">
  <div class="avatar">SM</div>

  <h1>SARAH MAHMOUD ABDALLAH</h1>

  <p class="headline"
     data-ar="المبيعات وعلاقات العملاء | تكنولوجيا الصناعات الدوائية | البرمجة والذكاء الاصطناعي"
     data-en="Sales & Customer Relations | Pharmaceutical Production Technology | Programming & AI">
    Sales & Customer Relations | Pharmaceutical Production Technology | Programming & AI
  </p>

  <p class="intro"
     data-ar="طالبة تكنولوجيا الصناعات الدوائية لديها خبرة عملية في مبيعات الأدوية وخدمة العملاء، واهتمام بتطوير مهاراتها في ضمان الجودة والبرمجة وتطوير الويب والأتمتة والذكاء الاصطناعي."
     data-en="A Pharmaceutical Production Technology student with practical experience in pharmaceutical sales and customer service, interested in developing skills in Quality Assurance, programming, web development, automation and artificial intelligence.">
    A Pharmaceutical Production Technology student with practical experience in pharmaceutical sales and customer service, interested in developing skills in Quality Assurance, programming, web development, automation and artificial intelligence.
  </p>

  <p class="location"
     data-ar="الإسكندرية، مصر"
     data-en="Alexandria, Egypt">
    Alexandria, Egypt
  </p>

  <div class="buttons">
    <a href="#contact" class="btn btn-primary"
       data-ar="تواصل معي" data-en="Contact Me">Contact Me</a>

    <a href="#experience" class="btn btn-outline"
       data-ar="استكشف خبراتي" data-en="Explore My Experience">Explore My Experience</a>
  </div>
</section>

<main class="container">

  <section class="section" id="about">
    <p class="eyebrow" data-ar="من أنا؟" data-en="INTRODUCTION">INTRODUCTION</p>
    <h2 data-ar="نبذة عني" data-en="About Me">About Me</h2>

    <p
      data-ar="أنا سارة محمود عبد الله، طالبة في تكنولوجيا الصناعات الدوائية بجامعة برج العرب التكنولوجية. لدي خبرة عملية لمدة عامين في خدمة العملاء ومبيعات الأدوية داخل الصيدلية، بالإضافة إلى خبرة متقطعة في التسويق التليفوني والتواصل مع العملاء عبر الإنترنت."
      data-en="I am Sarah Mahmoud Abdallah, a Pharmaceutical Production Technology student at Borg El Arab Technological University. I have two years of practical experience in pharmacy customer service and pharmaceutical sales, as well as intermittent experience in online telemarketing and customer communication.">
      I am Sarah Mahmoud Abdallah, a Pharmaceutical Production Technology student at Borg El Arab Technological University. I have two years of practical experience in pharmacy customer service and pharmaceutical sales, as well as intermittent experience in online telemarketing and customer communication.
    </p>

    <p
      data-ar="أهتم بتطوير مسيرتي المهنية في المبيعات وعلاقات العملاء، واستكشاف فرص مناسبة في صناعة الأدوية، خاصة ضمان الجودة. كما أعمل على تطوير معرفتي بالبرمجة وتطوير الويب والأتمتة والذكاء الاصطناعي من خلال التعلم والتطبيق العملي."
      data-en="I am interested in developing my career in sales and customer relations, exploring suitable opportunities in the pharmaceutical industry, especially Quality Assurance, and building my knowledge of programming, web development, automation and AI through continuous learning and practical projects.">
      I am interested in developing my career in sales and customer relations, exploring suitable opportunities in the pharmaceutical industry, especially Quality Assurance, and building my knowledge of programming, web development, automation and AI through continuous learning and practical projects.
    </p>
  </section>

  <section class="section" id="skills">
    <p class="eyebrow" data-ar="ما الذي أقدمه؟" data-en="WHAT I BRING">WHAT I BRING</p>
    <h2 data-ar="المهارات الأساسية" data-en="Core Skills">Core Skills</h2>

    <div class="skills">
      <div class="skill">Customer Relations & Communication</div>
      <div class="skill">Telemarketing Fundamentals</div>
      <div class="skill">Active Listening</div>
      <div class="skill">Product Explanation</div>
      <div class="skill">Customer Engagement</div>
      <div class="skill">Objection Handling</div>
      <div class="skill">Problem-Solving</div>
      <div class="skill">Adaptability & Fast Learning</div>
      <div class="skill">Digital Marketing Fundamentals</div>
      <div class="skill">C++ Programming Fundamentals</div>
      <div class="skill">Automation & AI — Academic Background</div>
      <div class="skill">Web Development — Learning</div>
      <div class="skill">Communication & Interpersonal Skills</div>
      <div class="skill">Continuous Learning</div>
    </div>
  </section>

  <section class="section" id="interests">
    <p class="eyebrow" data-ar="مجالات اهتمامي" data-en="CAREER INTERESTS">CAREER INTERESTS</p>
    <h2 data-ar="المسارات المهنية" data-en="Career Interests">Career Interests</h2>

    <div class="cards">
      <div class="card">
        <div class="card-number">01</div>
        <h3 data-ar="صناعة الأدوية وضمان الجودة" data-en="Pharmaceutical Industry & QA">
          Pharmaceutical Industry & QA
        </h3>
        <p
          data-ar="مهتمة باستكشاف فرص في صناعة الأدوية، خاصة ضمان الجودة (QA)، وربط دراستي بالتطبيقات العملية والالتزام بمعايير الجودة."
          data-en="Interested in pharmaceutical industry opportunities, especially Quality Assurance (QA), and in applying my academic background to practical quality systems and standards.">
          Interested in pharmaceutical industry opportunities, especially Quality Assurance (QA), and in applying my academic background to practical quality systems and standards.
        </p>
        <span class="tag">Pharmaceutical Production</span>
        <span class="tag">Quality Assurance (QA)</span>
      </div>

      <div class="card">
        <div class="card-number">02</div>
        <h3 data-ar="المبيعات وعلاقات العملاء" data-en="Sales & Customer Relations">
          Sales & Customer Relations
        </h3>
        <p
          data-ar="لدي خبرة في مبيعات الأدوية وخدمة العملاء بالصيدلية، بالإضافة إلى التواصل التليفوني عبر الإنترنت، وأسعى إلى تطوير مهارات البيع والتواصل."
          data-en="Experienced in pharmaceutical sales and pharmacy customer service, with additional exposure to online telemarketing. Interested in developing sales and customer communication skills.">
          Experienced in pharmaceutical sales and pharmacy customer service, with additional exposure to online telemarketing. Interested in developing sales and customer communication skills.
        </p>
        <span class="tag">Sales</span>
        <span class="tag">Customer Service</span>
        <span class="tag">Telemarketing</span>
      </div>

      <div class="card">
        <div class="card-number">03</div>
        <h3 data-ar="البرمجة وتطوير الويب والذكاء الاصطناعي"
            data-en="Programming, Web Development & AI">
          Programming, Web Development & AI
        </h3>
        <p
          data-ar="أطوّر معرفتي بأساسيات البرمجة بلغة C++، وأتعلم تطوير الويب، ولدي خلفية أكاديمية في الأتمتة والذكاء الاصطناعي."
          data-en="Developing foundational programming knowledge in C++, learning web development, and building on academic exposure to automation and artificial intelligence.">
          Developing foundational programming knowledge in C++, learning web development, and building on academic exposure to automation and artificial intelligence.
        </p>
        <span class="tag">C++</span>
        <span class="tag">Web Development</span>
        <span class="tag">Automation & AI</span>
      </div>
    </div>
  </section>

  <section class="section" id="experience">
    <p class="eyebrow" data-ar="خبرتي العملية" data-en="WORK HISTORY">WORK HISTORY</p>
    <h2 data-ar="الخبرة المهنية" data-en="Professional Experience">Professional Experience</h2>

    <div class="experience-item">
      <h3 data-ar="مبيعات الأدوية وخدمة العملاء بالصيدلية"
          data-en="Pharmaceutical Sales & Pharmacy Customer Service">
        Pharmaceutical Sales & Pharmacy Customer Service
      </h3>
      <p data-ar="سنتان من الخبرة" data-en="Two years of experience">
        Two years of experience
      </p>
      <ul>
        <li data-ar="مساعدة العملاء في الاستفسارات المتعلقة بالأدوية والمنتجات المتاحة."
            data-en="Assisted customers with inquiries about medicines and available products.">
          Assisted customers with inquiries about medicines and available products.
        </li>
        <li data-ar="شرح الخيارات المتاحة للعملاء ومساعدتهم على فهم المنتجات."
            data-en="Explained available product options and helped customers understand their choices.">
          Explained available product options and helped customers understand their choices.
        </li>
        <li data-ar="تطوير مهارات التواصل والاستماع وفهم احتياجات العملاء."
            data-en="Developed communication, active listening and customer-needs assessment skills.">
          Developed communication, active listening and customer-needs assessment skills.
        </li>
      </ul>
    </div>

    <div class="experience-item">
      <h3 data-ar="التسويق التليفوني والتواصل مع العملاء عبر الإنترنت"
          data-en="Online Telemarketing & Customer Communication">
        Online Telemarketing & Customer Communication
      </h3>
      <p data-ar="خبرة متقطعة خلال عام" data-en="Intermittent experience over one year">
        Intermittent experience over one year
      </p>
      <ul>
        <li data-ar="التواصل مع العملاء عبر المكالمات والرسائل في سياقات مرتبطة بالمبيعات."
            data-en="Communicated with customers through calls and messages in sales-related interactions.">
          Communicated with customers through calls and messages in sales-related interactions.
        </li>
        <li data-ar="التدرب على التعامل مع استفسارات العملاء واعتراضاتهم."
            data-en="Practiced responding to customer questions and objections.">
          Practiced responding to customer questions and objections.
        </li>
        <li data-ar="اكتساب معرفة أولية بعمليات التواصل والمبيعات عن بُعد."
            data-en="Gained exposure to online communication and remote sales processes.">
          Gained exposure to online communication and remote sales processes.
        </li>
      </ul>
    </div>
  </section>

  <section class="section" id="education">
    <p class="eyebrow" data-ar="خلفيتي الأكاديمية" data-en="ACADEMIC BACKGROUND">ACADEMIC BACKGROUND</p>
    <h2 data-ar="التعليم والتدريب" data-en="Education & Training">Education & Training</h2>

    <div class="education-item">
      <h3 data-ar="بكالوريوس تكنولوجيا الصناعات الدوائية"
          data-en="Bachelor of Technology in Pharmaceutical Production">
        Bachelor of Technology in Pharmaceutical Production
      </h3>
      <p
        data-ar="جامعة برج العرب التكنولوجية — الإسكندرية، مصر"
        data-en="Borg El Arab Technological University — Alexandria, Egypt">
        Borg El Arab Technological University — Alexandria, Egypt
      </p>
    </div>

    <div class="education-item">
      <h3 data-ar="التدريب الصناعي" data-en="Industrial Training">Industrial Training</h3>
      <p data-ar="Infra Pharm — تدريب صناعي"
         data-en="Infra Pharm — Industrial Training">
        Infra Pharm — Industrial Training
      </p>
      <p data-ar="Pharco Corporation — تدريب صناعي"
         data-en="Pharco Corporation — Industrial Training">
        Pharco Corporation — Industrial Training
      </p>
    </div>

    <div class="education-item">
      <h3 data-ar="الخلفية التقنية والأكاديمية"
          data-en="Technical & Academic Background">
        Technical & Academic Background
      </h3>
      <ul>
        <li data-ar="أساسيات البرمجة بلغة C++."
            data-en="Foundational knowledge of C++ programming.">
          Foundational knowledge of C++ programming.
        </li>
        <li data-ar="دراسة الأتمتة والذكاء الاصطناعي ضمن المقررات الجامعية."
            data-en="Studied Automation and Artificial Intelligence as part of university coursework.">
          Studied Automation and Artificial Intelligence as part of university coursework.
        </li>
        <li data-ar="تعلّم أساسيات تطوير الويب والبرمجة من خلال التطبيق."
            data-en="Learning web development and programming fundamentals through practice.">
          Learning web development and programming fundamentals through practice.
        </li>
      </ul>
    </div>
  </section>

  <section class="section" id="projects">
    <p class="eyebrow" data-ar="التعلم بالتطبيق" data-en="LEARNING BY DOING">LEARNING BY DOING</p>
    <h2 data-ar="المشاريع" data-en="Projects">Projects</h2>

    <div class="project">
      <h3 data-ar="الموقع الشخصي — Portfolio"
          data-en="Personal Portfolio Website">
        Personal Portfolio Website
      </
