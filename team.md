---
title: Team
layout: default
permalink: /team/
---

<h1 class="team-page-title">Meet Our Team</h1>

<!-- /Page Styling  -->
<style>

body {
  font-family: Poppins,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif
  color: #333; 
  padding-left: 40px;
  padding-right: 40px;
}

.team-page-title {
  font-family: 'Georgia', serif; 
  font-size: 2em;
  color: #CC3333; /* Custom color */
  text-align: left;
  margin-bottom: 20px;
}

.vacancies-title {
  font-family: 'Georgia', serif; /* Example font family */
  font-size: 1.8em;
  color: #CC3333; /* Custom color */
  text-align: left;
  margin-bottom: 30px;
}

.team-container {
  display: flex;
  justify-content: space-between; /* Spread out the team members evenly */
  flex-wrap: wrap; /* Ensure the members wrap on smaller screens */
  gap: 10px; /* Space between each team member block */
  padding: 10px;
}

/* Individual team member block */
.team-member {
  flex-basis: 28%; /* Ensure each team member takes up around 22% of the row width */
  text-align: center; /* Center the text */
  max-width: 250px; /* Set a max width for each block */
  flex-grow: 1;
}

/* Circular image styling */
.team-member-photo {
  width: 180px; /* Fixed width for the images */
  height: 180px; /* Fixed height for the images */
  object-fit: cover; /* Ensure image scales correctly */
  border-radius: 50%; /* This makes the image circular */
  border: 5px solid #CCCCFF; /* Optional: add a border to the images */
  margin-bottom: 15px;
}

/* Styling for team member name */
.team-member h3 {
  margin: 10px 0 5px 0;
  font-size: 1.4em;
}

/* Styling for team member description */
.team-member p {
  font-size: 1em;
  margin: 5px 0;
}

/* Responsive design - stack team members vertically on small screens */
@media (max-width: 768px) {
  .team-container {
    justify-content: center; /* Center the team members on small screens */
  }
  
  .team-member {
    flex-basis: 45%; /* Make team members take up more space on smaller screens */
  }
}

@media (max-width: 480px) {
  .team-member {
    flex-basis: 100%; /* Full width on very small screens */
    max-width: none;
  }
}

/* Styling for the text before and after the team blocks */
.team-page-intro, .team-page-outro {
  font-size: 1.2em;
  margin-bottom: 50px; /* Adds space between text and team blocks */
  line-height: 1.6;
  text-align: center; /* Optional: center the text */
}

.team-page-outro {
  margin-top: 40px; /* Adds space above the closing text */
}

</style>



<!-- Text before the team blocks -->
<div class="team-page-intro">
Our science depends on teamwork and collaboration between individuals trained in medicine, biology, and bioinformatics.
</div>

<!-- Team members block -->
<div class="team-container">
  <div class="team-member">
    <img src="{{ '/assets/img/team/laura_jardine_bw_cp.png' | relative_url }}" alt="Laura Jardine" class="team-member-photo" />
    <h3>Laura Jardine</h3>
    <p>Group Leader</p>
  </div>

  <div class="team-member">
    <img src="{{ '/assets/img/team/keir_pickard_bw_cp.png' | relative_url }}" alt="Keir Pickard" class="team-member-photo" />
    <h3>Keir Pickard</h3>
    <p>PhD Student</p>
  </div>

  <div class="team-member">
    <img src="{{ '/assets/img/team/manisha_chahal_bw_cp.png' | relative_url }}" alt="Manisha Chahal" class="team-member-photo" />
    <h3>Manisha Chahal</h3>
    <p>PhD Student</p>
  </div>

  <div class="team-member">
    <img src="{{ '/assets/img/team/koraki_folli_bw_cp.png' | relative_url }}" alt="Varvara Koraki Folli" class="team-member-photo" />
    <h3>Varvara Koraki Folli</h3>
    <p>Assistant Research</p>
  </div>
</div>

<!-- Text after the team blocks -->
<h1 class="vacancies-title">Current vacancies:</h1>
<div class="team-page-outro">
We have no vacancies at present. However, we’d still like to hear from you if you are enthusiastic about our work and have skills or interests that align with our research. 
</div>