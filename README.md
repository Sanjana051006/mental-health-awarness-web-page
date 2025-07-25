<title> mental-health-awarness-web-page </title>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Mental Health Awareness</title>
  <style>
    /* Reset and base styles */
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      margin: 0;
      background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%);
      color: #333;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      background-color: #34675c;
      color: #e0f7fa;
      padding: 30px 20px;
      text-align: center;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
      border-bottom: 5px solid #f67280;
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
      font-weight: 700;
      letter-spacing: 2px;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.2);
    }

    main {
      max-width: 900px;
      margin: 40px auto 60px;
      padding: 0 20px;
      flex-grow: 1;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.08);
    }

    section {
      padding: 30px 20px;
      border-bottom: 1px solid #e0e0e0;
    }

    section:last-child {
      border-bottom: none;
    }

    section h2 {
      color: #34675c;
      font-size: 2rem;
      margin-bottom: 15px;
      border-left: 6px solid #f67280;
      padding-left: 15px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 15px;
    }

    ul {
      list-style-type: square;
      margin-left: 20px;
      color: #555;
      font-size: 1.1rem;
    }

    ul li {
      margin-bottom: 8px;
    }

    a {
      color: #f67280;
      font-weight: 600;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    a:hover {
      color: #d94f5a;
      text-decoration: underline;
    }

    footer {
      background-color: #34675c;
      color: #e0f7fa;
      text-align: center;
      padding: 15px 10px;
      font-size: 1rem;
      box-shadow: 0 -3px 6px rgba(0,0,0,0.1);
      border-top: 5px solid #f67280;
    }

    /* Responsive */
    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      main {
        margin: 20px 10px 60px;
      }
      section h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Mental Health Awareness</h1>
  </header>

  <main>
    <section>
      <h2>What is Mental Health?</h2>
      <p>
        Mental health includes our emotional, psychological, and social well-being. It affects how we think, feel, and act, as well as how we handle stress, relate to others, and make choices.
      </p>
    </section>

    <section>
      <h2>Common Mental Health Issues</h2>
      <ul>
        <li>Depression</li>
        <li>Anxiety Disorders</li>
        <li>Bipolar Disorder</li>
        <li>Post-Traumatic Stress Disorder (PTSD)</li>
        <li>Schizophrenia</li>
      </ul>
    </section>

    <section>
      <h2>How to Maintain Good Mental Health</h2>
      <p>Here are some tips to take care of your mental well-being:</p>
      <ul>
        <li>Stay connected with friends and family</li>
        <li>Exercise regularly</li>
        <li>Get enough sleep</li>
        <li>Practice mindfulness or meditation</li>
        <li>Seek professional help if needed</li>
      </ul>
    </section>

    <section>
      <h2>Resources</h2>
      <p>
        If you or someone you know is struggling, consider reaching out to these organizations:
      </p>
      <ul>
        <li><a href="https://www.mentalhealth.gov/" target="_blank" rel="noopener">MentalHealth.gov</a></li>
        <li><a href="https://www.nami.org/" target="_blank" rel="noopener">NAMI (National Alliance on Mental Illness)</a></li>
        <li><a href="https://www.samhsa.gov/" target="_blank" rel="noopener">SAMHSA (Substance Abuse and Mental Health Services Administration)</a></li>
      </ul>
    </section>
  </main>

  <footer>
    &copy; 2025 Mental Health Awareness. All rights reserved.
  </footer>
</body>
</html>

