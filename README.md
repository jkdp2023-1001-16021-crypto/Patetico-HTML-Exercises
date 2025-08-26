<!DOCTYPE html>
<html>
    <!--2 - Page Title-->
    <head>
        <title>Sunflemon’s Art Portfolio</title>
        <!--25 - Favicon-->
        <link rel="icon" type="images" href="images/sunflemon-transparent.png">
    </head>

<body>
    <!--40 - Progress Bar-->
    <p>Task Progress:</p>
    <progress value="70" max="100"></progress>
    <hr>

    <p>This portfolio consists of the artist’s personal journey in art and shows how each piece
        has been made with intention, and drive to be better at the practice of arts.</p>

    <!--3 - Main Heading-->
    <img src="images/sunfemon2.png" alt="My Photo" width="200">
    <h1><b>Jeshiah Kaye D. Patetico</b></h1>

    <!--4 - Subheading-->
    <h2><strong>Important information</strong> about the artist so please <em>read carefully</em></h2>
    
    <!--5 -Paragraph-->
    <p>Hi! I am Jehsiah Kaye D. Patetico or you can call me Kai.</br>
    I am currently a <u>3rd Year student under the program BS-IT Animation at Bicol University Polangui.</u></br>
    Some of my interests include <i>marvel films, </i> <i>study of animation, </i> and <i>making youtube videos</i>
    </p>
    <hr>

    <!--INPUT INFORMATION-->
    <h3>Before we Start!</h3>
    <p>Please input your information for a better experience.</p>
    <h2>Input Personal Information</h2>

    <!--17 and 18 - Forms for Text and Password-->
    <h2>Submit your Log-in Infromation!</h2>
    <form>
        Name: <input type="text" name="full name">
    </form>
    <form>
        Password: <input type="password" name="pwd">
    </form>

     <!--19 - Button-->
    <form>
        <button type="submit">Submit</button>
    </form>

    <!--21 - Form radio btns-->
    <form>
        <p>Gender: </p>
        <input type="radio" name="gender" value="male"></br>
        <input type="radio" name="gender" value="female"></br>
        <input type="radio" name="gender" value="non-binary">
    </form>

     <!--22 - From Checkboxes-->
    <form>
        <p>What are your Hobbies/Interests?</p>
        <input type="checkbox" name="hobby" value="baking">Baking</br>
        <input type="checkbox" name="hobby" value="cooking">Cooking</br>
        <input type="checkbox" name="hobby" value="reading">Reading</br>
        <input type="checkbox" name="hobby" value="movies">Watching Movies</br>
        <input type="checkbox" name="hobby" value="workingout">Wokring Out</br>
        <input type="checkbox" name="hobby" value="singing">Singing</br>
        <input type="checkbox" name="hobby" value="dancing">Dancing</br>
        Others: <input type="text" name="hobby">
    </form>

    <!--23 - Form Dropdown-->
    <form>
        <label for="country">Select SEA Country</label>
        <select id="country">
            <option>Philippines</option>
            <option>Brunei</option>
            <option>Cambodia</option>
            <option>Indonesia</option>
            <option>Laos</option>
            <option>Malaysia</option>
            <option>Myanmar</option>
            <option>Singapore</option>
            <option>Thailand</option>
            <option>Timor-Leste</option>
            <option>Vietnam</option>
        </select>
    </form>
    <hr>

    <!--26 - Audio Player-->
    <h3>For a more fun experience, turn on some music!</h3>
    <audio controls>
        <source src="audios/Tataya by COJ.mp3" type="audio/mpeg">
    </audio>
    <hr>

    <!--11 and 12 - Ordered and Unordered List-->
    <h3>My Favorite food:</h3>
    <ol>
        <li>Lemon Bars</li>
        <li>Lumpiang Shanghai</li>
        <li>Chicken Alfredo Pasta</li>
        <li>Blueberry Muffins</li>
        <li>Honey Biscuits</li>
    </ol>
    <h3>Hobbies in my down time:</h3>
    <ul>
        <li>Baking</li>
        <li>Roller Skating</li>
        <li>Making Animatics</li>
        <li>Drawing</li>
        <li>Going on long Walks</li>
    </ul>
    <hr>

    <!--16 - Table List-->
    <h2>Friends List</h2>
    <table>
        <tr>
            <td>Name</td>
            <td>Age</td>
            <td>Campus</td>
        </tr>
        <tr>
            <td>Chan</td>
            <td>20</td>
            <td>BU IDEA</td>
        </tr>
        <tr>
            <td>Fran</td>
            <td>20</td>
            <td>BU Polangui</td>
        </tr>
        <tr>
            <td>Keizha</td>
            <td>20</td>
            <td>Bu Main</td>
        </tr>
        <tr>
            <td>Aikee</td>
            <td>20</td>
            <td>BU Daraga</td>
        </tr>
    </table>
    <hr>

    <!--28 - Iframe Embed Website-->
    <iframe src="https://www.google.com" width="600" height="400"></iframe>
    <hr>

    <!--29 - IFrame Embed Youtube Video-->
    <h3>Some examples of my Animatics!</h3>
    <iframe width="560" height="615" src="https://youtu.be/d0mLFAv-K24?si=Jld1cBoXvoe0D0pI" frameborder="0" allowfullscreen></iframe>
    <iframe width="560" height="615" src="https://youtu.be/Iy332g9mJ_c?si=3RbUXx4Z4r-q6vLr" frameborder="0" allowfullscreen></iframe>
    <iframe width="560" height="615" src="https://youtu.be/3fw3Meq7syU?si=0ngbg3G7MrtFXOyS" frameborder="0" allowfullscreen></iframe>
    <iframe width="560" height="615" src="https://youtu.be/a17h9boK0WE?si=_TRI4qYqRTwouXgs" frameborder="0" allowfullscreen></iframe>

    <!--30 and 31 - Superscript and Subscript-->
    <p>Did you know?</p>
    <p>The formula for Water: H<sub>2</sub>O</p>
    <p>x multiplied by x = x<sup>2</sup></p>

    <!--24 - Form Text Area-->>
    <hr>
    <h2>What are your thoughts and suggestions?</h2>
    <form>
        <label for="message">Message</label></br>
        <textarea id="message" rows="4" cols="30"></textarea>
    </form>

    <!--35 and 36 - Block and Inline Quote-->
    <blockquote>"Fueled with Sunflowers and Lemons and the firey passion of a thousand Stars."</blockquote>
    <p>She then said as a closing to this Portfolio, <q>Thank you so much for your interest and appreciation!</q></p>
    <hr>

    <!--27 - Video Player-->
    <h3>Would like to get to know more about what's it like being an Animation Student? Click this Video!</h3>
    <video width="1080px" height="720px" controls>
        <source src="videos/What's it like being an animation student.mp4" type="video/mp4">
    </video>
    <hr>

    <!--37 and 39 - Abbreviation and Mark Highlight-->
    <p><abbr title="HyperText Markup Language">HTML</abbr> is the language of this website.</p>
    <p>This is a <mark>self made starter</mark> website.</p>

    <!--38 - Address-->
    <hr>
    <h3><i>Address</i></h3>
    <address>
        Created by: Jeshiah Kaye D. Patetico
        Bicol, Philippines</br>
    </address>

    <!--14 and 15 - Links and Email to-->
    <h3><i>Links and Contacts</i></h3>
    <a href="https://www.google.com">Visit Google!</a>
    <a href="mailto:jkdp2023-1001-16021@bicol-u.edu.ph">Email Me!</a>
    <hr>

    <!--34 - Small text-->
    <p><small>&copy; Sunflemon 2025</small></p>

</body>
</html>
