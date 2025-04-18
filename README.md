Hello and welcome to my University of Essex Online e-portfolio!

I’m currently studying towards an MSc in Artificial Intelligence, and this space will serve as a living record of my journey through the course. Here, I’ll be documenting my progress, sharing reflections, showcasing assignments, and highlighting the skills and knowledge I gain along the way.

This e-portfolio is very much a work in progress and will continue to evolve as I move through the programme. Thanks for stopping by, and feel free to check back for updates as my learning unfolds.

---

<div style="width: 95%; margin: 20px auto; border: 1px solid #ccc; padding: 16px; border-radius: 8px;">
  <h3 style="margin-top: 0;">
    <a href="machine_learning" style="text-decoration: none;">Machine Learning</a>
  </h3>
  <p>Machine learning is a way for computers to learn from data and improve over time without being explicitly programmed. It's a key part of artificial intelligence, helping machines make decisions, recognize patterns, and adapt. This module deals with foundational algorithms, practical implementation, and real-world applications of machine learning across various domains...
  <br/>
  <a href="machine_learning" style="text-decoration: none; margin-left:10px; float: right;">more</a>
  </p>
</div>


<div style="width: 95%; margin: 20px auto; border: 1px solid #ccc; padding: 16px; border-radius: 8px;">
  <h3 style="margin-top: 0;">
    <a href="pdp" style="text-decoration: none;">Personal Development Plan</a>
  </h3>
  <p>Explore my Personal Development Plan to see how I’m actively working on my skills, goals, and growth as a professional. Join me on my journey as I continue to learn, improve, and reach new milestones...
  <br/>
<a href="pdp" style="text-decoration: none; margin-left:10px; float: right;">more</a>
  </p>
</div>

<div id="hamburgerMenu">
  <div id="menuToggle">&#9776;<div id="menuLabel" style="display: none;">MENU</div></div>
  <div id="menuLinks">
    <a href="/">Home</a>
    <a href="/machine_learning/">Machine Learning</a>
    <a href="/pdp/">Professional Development Plan</a>
  </div>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    const toggle = document.getElementById('menuToggle');
    const links = document.getElementById('menuLinks');
    const label = document.getElementById('menuLabel');
    const menu = document.getElementById('hamburgerMenu');

    toggle.addEventListener('click', function () {
        const isVisible = links.style.display === 'block';
        links.style.display = isVisible ? 'none' : 'block';
        label.style.display = isVisible ? 'none' : 'inline';
    });

    menu.addEventListener('mouseleave', function () {
      links.style.display = 'none';
      label.style.display = 'none'; 
    });
  });
</script>