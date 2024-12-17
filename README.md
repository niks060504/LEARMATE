/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: 'Arial', sans-serif;
    line-height: 100    ;
    background: linear-gradient(to right, #ff0000, #ff7f00, #ffff00, #00ff00, #0000ff, #4b0082, #9400d3);
    color: #000000;
    padding: 0;
    margin: 0;
  }
  
  .hero-section h1 {
    font-size: 3rem;
    margin-bottom: 20px;
  }
  
  .hero-section p {
    font-size: 1.5rem;
    max-width: 800px;
    margin: 0 auto;
  }
  
  /* Introduction Section */
  .introduction {
    padding: 40px 20px;
    /*background: linear-gradient(to bottom, #FF7F50, #1E90FF);*/
    text-align: center;
  }
  
  .introduction h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }
  
  .introduction p {
    font-size: 1.1rem;
    max-width: 1000px;
    margin: 0 auto 20px;
  }
  
  /* Services Section */
  .services {
    padding: 40px 20px;
    /*background: linear-gradient(to bottom, #FF7F50, #1E90FF);*/
  }
  
  .services h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 30px;
  }
  
  .tabs {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
  }
  
  .tab {
    /*background: linear-gradient(to bottom, #FF7F50, #1E90FF);*/
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    width: 22%;
    padding: 20px;
    margin-bottom: 20px;
    text-align: center;
  }
  
  .tab h3 {
    font-size: 1.8rem;
    margin-bottom: 10px;
  }
  
  .tab p {
    font-size: 1.1rem;
  }
  
  /* Shared Services Section */
  .shared-services {
    padding: 40px 20px;
    /*background: linear-gradient(to bottom, #FF7F50, #1E90FF);*/
    text-align: center;
  }
  
  .shared-services h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }
  
  .shared-services ul {
    list-style: none;
  }
  
  .shared-services li {
    font-size: 1.1rem;
    margin-bottom: 10px;
  }
  
  /* Upcoming Services Section */
  .upcoming-services {
    padding: 40px 20px;
    /*background: linear-gradient(to bottom, #FF7F50, #1E90FF);*/
    text-align: center;
  }
  
  .upcoming-services h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }
  
  .upcoming-services ul {
    list-style: none;
  }
  
  .upcoming-services li {
    font-size: 1.1rem;
    margin-bottom: 10px;
  }
  
  /* About Us Section */
  .about-us {
    padding: 60px 20px;
    /*background: linear-gradient(to bottom, #FF7F50, #1E90FF);*/
    text-align: center;
  }
  
  .about-us h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }
  
  .about-us h3 {
    font-size: 2rem;
    margin-top: 20px;
  }
  
  .about-us p {
    font-size: 1.1rem;
    max-width: 900px;
    margin: 20px auto;
    line-height: 1.6;
  }
  
  /* Get In Touch Section */
  .get-in-touch {
    padding: 40px 20px;
    /*background: linear-gradient(to bottom, #FF7F50, #1E90FF);*/
    text-align: center;
  }
  
  .get-in-touch h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }
  
  .get-in-touch a {
    font-size: 1.2rem;
    color: #0056b3;
    text-decoration: none;
  }
  
  .get-in-touch a:hover {
    text-decoration: underline;
  }
  
  /* Blog/Resources Section */
  .blog-resources {
    padding: 40px 20px;
    /*background: linear-gradient(to bottom, #FF7F50, #1E90FF);*/
    text-align: center;
  }
  
  .blog-resources h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }
  
  .blog-resources a {
    font-size: 1.2rem;
    color: #0056b3;
    text-decoration: none;
  }
  
  .blog-resources a:hover {
    text-decoration: underline;
  }
  
  /* Quick Links Section */
  .quick-links {
    padding: 40px 20px;
    /*background: linear-gradient(to bottom, #FF7F50, #1E90FF);*/
    text-align: center;
  }
  
  .quick-links h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }
  
  .quick-links ul {
    list-style: none;
  }
  
  .quick-links li {
    margin-bottom: 10px;
  }
  
  .quick-links a {
    font-size: 1.2rem;
    color: #0056b3;
    text-decoration: none;
  }
  
  .quick-links a:hover {
    text-decoration: underline;
  }
  
  /* Social Media Section */
  .social-media {
    padding: 40px 20px;
    /*background: linear-gradient(to bottom, #FF7F50, #1E90FF);*/
    text-align: center;
  }
  
  .social-media h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }
  
  .social-media ul {
    list-style: none;
  }
  
  .social-media li {
    display: inline;
    margin: 0 10px;
  }
  
  .social-media a {
    font-size: 1.2rem;
    color: #333;
    text-decoration: none;
  }
  
  .social-media a:hover {
    color: #0056b3;
  }
  
  /* Mobile Responsiveness */
  @media (max-width: 768px) {
    .tabs {
      flex-direction: column;
      align-items: center;
    }
  
    .tab {
      width: 80%;
      margin-bottom: 20px;
    }
  
    .services h2, .about-us h2, .get-in-touch h2, .blog-resources h2, .quick-links h2, .social-media h2 {
      font-size: 2rem;
    }
  
    .hero-section h1 {
      font-size: 2.5rem;
    }
  
    .hero-section p {
      font-size: 1.2rem;
    }
  }
  
