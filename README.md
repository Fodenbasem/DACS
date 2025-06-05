<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>DACS - College of Artificial Intelligence</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

  body {
    margin: 0;
    font-family: 'Roboto', sans-serif;
    background: linear-gradient(135deg, #2c3e50, #4ca1af);
    color: #f0f0f0;
    direction: ltr;
  }

  header {
    background: rgba(255, 255, 255, 0.1);
    padding: 25px 20px;
    text-align: center;
    font-size: 2.5rem;
    font-weight: 700;
    letter-spacing: 4px;
    color: #00ffe7;
    text-shadow: 0 0 10px #00ffe7;
    animation: slideDown 1s ease forwards;
  }

  main {
    max-width: 900px;
    margin: 40px auto;
    background: rgba(255, 255, 255, 0.07);
    padding: 30px 40px;
    border-radius: 15px;
    box-shadow: 0 0 30px rgba(0, 255, 230, 0.3);
    animation: fadeIn 2s ease forwards;
  }

  h2 {
    color: #00ffd0;
    font-size: 2rem;
    margin-bottom: 20px;
    text-align: center;
    text-shadow: 0 0 8px #00ffd0;
  }

  p.description {
    font-size: 1.25rem;
    line-height: 1.6;
    text-align: justify;
  }

  details {
    margin-top: 30px;
    background: rgba(0, 255, 230, 0.1);
    border-radius: 10px;
    padding: 15px 20px;
    box-shadow: 0 0 15px rgba(0, 255, 230, 0.3);
    cursor: pointer;
    transition: background 0.3s ease;
  }

  details:hover {
    background: rgba(0, 255, 230, 0.2);
  }

  summary {
    font-weight: 700;
    font-size: 1.3rem;
    outline: none;
    list-style: none;
    cursor: pointer;
    user-select: none;
  }

  summary::-webkit-details-marker {
    display: none;
  }

  summary::after {
    content: '▼';
    float: right;
    margin-right: 10px;
    transition: transform 0.3s ease;
  }

  details[open] summary::after {
    transform: rotate(180deg);
  }

  @keyframes slideDown {
    0% {
      opacity: 0;
      transform: translateY(-30px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes fadeIn {
    0% {
      opacity: 0;
      transform: translateY(20px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
  }
</style>
</head>
<body>
  <header>
    DACS - College of Artificial Intelligence
  </header>

  <main>
    <h2>About the Site</h2>
    <p class="description">
      The DACS site provides a detailed explanation of all specializations of the College of Artificial Intelligence along with research summaries, allowing you to easily and clearly know the specialization suitable for you.
    </p>

    <details>
      <summary>Specializations of the College of Artificial Intelligence</summary>
      <p>
        The college specializations include: Machine Learning, Natural Language Processing, Computer Vision, Robotics, and Intelligent Support Systems.
        You can explore each specialization, its goals, and the latest related research through the site.
      </p>
    </details>

    <details>
      <summary>Research Summaries</summary>
      <p>
        Simplified summaries of the latest research in various artificial intelligence fields are provided to keep you continuously informed and confidently choose your field of specialization.
      </p>
    </details>
  </main>
</body>
</html>
