# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<HTml>
    <head>NEST & NECESSITIES <br> <img src="https://images.pexels.com/photos/6035313/pexels-photo-6035313.jpeg?auto=compress&cs=tinysrgb&w=400" alt="h1"></head>
    <body>
        <p>Welcome to Nest & Necessities! Your go-to destination for all your home essential needs </p>
        <p><ol >
            <li>Kitchen</li>
            <li>bathroom</li>
            <li>organisers</li>
            <li>decor</li>
        </ol>
    <ul>
        <li>cooking storage containers <br> <img src="https://images.pexels.com/photos/3847466/pexels-photo-3847466.jpeg?auto=compress&cs=tinysrgb&w=400" alt="this is a picture of a kitchen" with="350" height="350"> </li>
        <li>racks <br><img src="https://images.pexels.com/photos/3316926/pexels-photo-3316926.jpeg?auto=compress&cs=tinysrgb&w=400" alt="this is a picture of a bathroom" with="350" height="350"></li>
        <li>orgarnisers <br> <img src="https://images.pexels.com/photos/11885892/pexels-photo-11885892.jpeg?auto=compress&cs=tinysrgb&w=400" alt=" this is an example of an organisers" with="350" height="350"></li>
        <li>decor <br> <img src="https://images.pexels.com/photos/1099816/pexels-photo-1099816.jpeg?auto=compress&cs=tinysrgb&w=400" alt="this is an example of decor item" with="350" height="350"></li>
    </ul>
<h3>NN</h3>
<dl><dt>
    <dd>Nest & Necessities</dd>
</dt></dl>
</p>
<table border="1">
    <thead></thead>
    <CAption>OUR STORES COUNTRYWIDE</CAption>
    <TR>
        <th>NAME</th>
        <th>ADDRESS </ADDRess></th>
        <th>MOBILE </th>
        <th>EMAIL </th>
    </TR>
    <tbody>
    <tr>
        <td>NN MOMBASA</td>
        <td>CBD</td>
        <td>0710000000</td>
        <td>nn@mombasa.com</td>
    </tr>
    <tr>
        <td>NN NAIROBI</td>
        <td>CBD</td>
        <td>0720000000</td>
        <td>nn@nairobi.com</td>
    </tr>
    <tr>
        <td>NN NAKURU</td>
        <td>CBD</td>
        <td>0730000000</td>
        <td>nn@nakuru.com</td>
    </tr>
    <tr>
        <td>NN KISUMU</td>
        <td>CBD</td>
        <td>0740000000</td>
        <td>nn@kisumu.com</td>
    </tr>
    <tr>
        <td>NN BUSI</td>
        <td>CBE</td>
        <td>0750000000</td>
        <td>nn@busia.com</td>
    </tr>
    </tbody>
<BR></BR>
</table>
    
    </body>
    <BR></BR>
    <form>
        <caption>tell us where you are from</caption> <br>
        <label for="name">NAME</label>
        <input type="text" id="name" name="name of customer" required>
         <br> 
        <label for="Location">COUNTY:</label>
        <select name="location" name="County" required>
        <option --select county--></option>
        <option value="NAIROBI"></option>
        <option value="MOMBASA"></option>
        <option value="KISUMU"></option>
        <option value="NAKURU"></option>
        <option value="BUSIA"></option>
        <br> 
        
    </form>
    <br><br> <br>
         <!-- Footer Section -->
         <footer>
            Contact us: 0716555636 / 0799854243    | Location: Nairobi & Mombasa |    We Deliver Countrywide
        </footer>
</HTml>
