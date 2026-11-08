[index.html](https://github.com/user-attachments/files/34550316/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Portfolio</title>
</head>
<body>
          <!--Navbar-->
   <header>
        <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Work</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Resume</a></li>
        </ul>
   </header>
           <!--Section-->
           <main>
           <section id="home">
            <h1>Welcome to my Portfolio</h2>
           </section>

           <section id="about">
            <h2>About me</h2>
            <p>I am a web developer , I love to build,and bring solutions </p>
           </section>

           <video src="AI video.mp4" controls poster="AI.jpg" width="320" height="200"> </video>
                 
           <section id="work">
            <h2>My Works</h2>
            <ul>
                <li>Website Building</li>
                <li>Project 2 AI assistant and recommendations</li>
            </ul>
           </section>

           <section id="resume">
            <h2>Resume</h2>
            <table border="1">
                <tr>
                    <th>Year</th>
                    <th>Role</th>
                </tr>
                <tr>
                    <td>2026</td>
                    <td>Web Developer</td>
                </tr>
            </table>
           </section>

           <section id="contact">
            <h2>Contact:</h2>
            <form action="#">
            <label for="name">Name</label>
            <input type="text" id="name" required /><br /><br />

            <label for="msg">Message:</label> 
            <textarea id="msg" required></textarea><br /><br />

            <button type="submit">Submit</button>
            </form>
           </section>
        </main>

         <!-- Footer -->
          <footer>
            <P>&copy; 2026 Portfolio</P>
          </footer>
   

</body>
</html>
