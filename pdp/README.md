# Personal Development Plan

Lately, with my current MSc project, I’ve felt the pressure of juggling work, study, and everything in between. I’ve noticed I end up cramming or skimming through material without really absorbing or applying it. That’s why I’m leaning into a Professional Growth Plan—it gives me a way to step back, see the bigger picture, and build consistency. Instead of just reacting to deadlines, I can be intentional with how I use my limited time. It’s not about doing more—it’s about making what I do count, learning deeply, and actually growing through this process, not just surviving it.

## Skills Matrix

| Skill Area               | Current | Target | Why It Matters                                             | Micro-Focus Area                                     |
|--------------------------|---------|--------|------------------------------------------------------------|------------------------------------------------------|
| Focus / Distraction Mgmt | 2       | 4      | I don’t have time to waste on distractions               | Work in “flight mode” blocks                         |
| Time & Energy Mgmt       | 2       | 4      | Keeps me consistent without burnout                       | Protected MSc time + recovery                        |
| Strategic Reading        | 3       | 5      | Smarter reading → better ideas, faster learning            | 2 focused articles/papers/week + highlight key takeaways |
| ML Application Practice  | 2       | 5      | Applying things makes it stick (plus builds a portfolio)| Weekly mini-projects, 1–2 hours/week                |

---

## Development Plan

### Daily Routine (Max 2 Hours)

| Time       | Focus                  | Purpose                                              |
|------------|------------------------|------------------------------------------------------|
| 25–30 min  | Strategic Reading      | Skim + read deeply on 1 idea or ML technique         |
| 60 min     | Deep MSc / Project Work| Implement, write, or analyze                         |
| 20–30 min  | Review / Practice      | Notes, spaced repetition, or ML mini-experiment      |

---

### Weekly Schedule

| **Day**       | **Focus**                                                    |
|---------------|--------------------------------------------------------------|
| **Monday**    | Finalise and submit MSc writing / assignments                |
| **Tuesday**   | Reading + Plan week’s MSc tasks                             |
| **Wednesday** | MSc deep work (assignments, coding, research) + outline portfolio/note |
| **Thursday**  | ML technique application (small experiment, Kaggle/Colab)   |
| **Friday**    | Strategic reading + reflect on applied work                 |
| **Saturday**  | Live Life    |
| **Sunday**    | Weekly Review (30 mins) + Do any outstanding assignment-related tasks |


---

## Monthly Review

1. What did I learn or apply this month?  
2. What distracted me most often?  
3. Is my 2-hour routine working, or do I need to adjust?  
4. What’s one small experiment I can try next month?


[Back to Machine Learning](/machine_learning/)


<div id="hamburgerMenu">
  <input type="checkbox" id="menuToggle" />
  <label for="menuToggle" id="menuButton">&#9776;</label>

  <nav id="menuArea">
    <div id="menuLinks">
      <a href="/">Home</a>
      <a href="/machine_learning/">Machine Learning</a>
      <a href="/pdp/">Professional Development Plan</a>
    </div>
  </nav>
</div>

<style>
  #hamburgerMenu {
    position: fixed;
    top: 20px;
    right: 20px;
    z-index: 1000;
    font-family: Arial, sans-serif;
  }

  input[type="checkbox"] {
    display: none;
  }

  #menuButton {
    background: #333;
    color: white;
    padding: 10px 15px;
    border-radius: 5px;
    display: inline-block;
    cursor: pointer;
    font-weight: bold;
    user-select: none;
  }

  #menuButton span {
    margin-left: 8px;
  }

  #menuArea {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.3s ease-out;
    background: #333;
    margin-top: 10px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
  }

  #menuLinks a {
    display: block;
    padding: 10px 15px;
    text-decoration: none;
    color: white;
  }

  #menuLinks a:hover {
    background-color: rgb(90, 91, 97);
  }

  /* Show menu when checkbox is checked */
  #menuToggle:checked ~ #menuArea {
    max-height: 500px;
  }

  /* Close menu when not hovered */
  #hamburgerMenu:not(:hover) input:checked ~ #menuArea {
    max-height: 0;
  }

  @media (min-width: 768px) {
    #hamburgerMenu {
      display: none;
    }
  }
</style>
