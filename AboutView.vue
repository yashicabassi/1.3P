<template>
  <div class ="main-container">
    <div class="container-one">
      <div class="profile">
        <h3> YASHICA BASSI</h3>
        <p>BACHELOR OF IT STUDENT</p>
      </div>
    </div>
  </div>
  <div class = "container-two">
    <div class="about-me">
      <h1> About Me</h1>
      <p>I am a dedicated Bachelor of Information Technology (IT) student with a strong passion for technology and a thirst for knowledge. Throughout my academic journey, I have gained a solid foundation in programming, web development, and database management. I am enthusiastic about solving complex problems and thrive in collaborative team environments. My goal is to leverage my IT skills and continue learning to make a meaningful impact in the tech industry</p>
    </div>
    <div class ="technology-section">
      <h1> Technologies Studied</h1>
      <ul>
        <h4><li>JAVA</li> </h4>
        <h4><li>C++</li> </h4>
        <h4><li>PYTHON </li> </h4>
        <h4><li>VUE 3</li> </h4>
      </ul>

    </div>
  </div>
  <div class="project-list">
      <h1>  PROJECT LIST</h1>
      <table>
        <thead>
          <tr>
            <th>HTML</th>
            <th>Creating a website of portfolio.</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>REPORT MAKING</td>
            <td> Creating reports related to ICT.</td>
          </tr>
          <tr>
            <td>MY SQL</td>
            <td>Handling and storing data.</td>
          </tr>
          
        </tbody>
      </table>
    </div>
    <div class="hobbies">
    <h1>MY HOBBIES </h1>
    <ul>
      <li>Photography</li>
      <li>Reading</li>
      <li>Hiking</li>
      
    </ul>
  </div>
    <div class="contact-form">
      <h1>CONTACT ME</h1>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
         <br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br>
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>
        <br>
        <button type="submit">Submit</button>
      </form>
    </div>
</template>
<script>

</script>
<style scoped>
.main-container{
  background-color: lightseagreen;
}
.container-one{
  background-color: #ffb0b0;
}
.container-two{
  background-color: #cdc0fc;
}
.project-list {
  margin-top: 20px;
  background-color: skyblue;
}

table {
  width: 100%;
  border-collapse: collapse;
}

table, th, td {
  border: 1px solid #000;
}

th, td {
  padding: 10px;
  text-align: left;
}
.contact-form{
  background-color: beige;
}
.hobbies{
  background-color: lightgreen;
}


</style>
