<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body>
  <h1 style="color:black; text-align:center; padding-top: 50vh;">
</body>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Learn the basics of HTML5 semantic tags, accessibility, and SEO through this simple sample web page." />
  <meta name="keywords" content="HTML5, Semantic HTML, Accessibility, SEO, Web Development" />
  <meta name="author" content="oladipupo israel" />
  <title>Welcome to My HTML5 Page</title>
</head>
<body>

  <header>
    <h1>My HTML5 Semantic Web Page</h1>
    <nav aria-label="Main navigation">
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about" aria-labelledby="about-heading">
      <h2 id="about-heading">About This Page</h2>
      <p>This simple web page demonstrates how to use HTML5 semantic elements to build accessible and SEO-friendly websites. It includes proper structure, heading levels, and metadata.</p>
    </section>

    <section id="features" aria-labelledby="features-heading">
      <h2 id="features-heading">Key Features</h2>
      <article>
        <h3>Semantic HTML5 Tags</h3>
        <p>Using elements like <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;section&gt;</code>, and <code>&lt;footer&gt;</code> makes the structure more meaningful.</p>
      </article>
      <article>
        <h3>Accessibility Best Practices</h3>
        <p>Landmark roles and heading structure help screen readers understand the content hierarchy better.</p>
      </article>
      <article>
        <h3>SEO-Friendly Content</h3>
        <p>Descriptive headings and metadata improve search engine indexing and visibility.</p>
      </article>
    </section>

    <section id="contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact Information</h2>
      <p>You can reach out via email at <a href="mailto:example@example.com">oladipupoisrael181@gmail.com</a>.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 oladipupo israel.</p>
  </footer>

</body>
</html>

