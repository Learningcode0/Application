<html>
  <head>
    <meta>
    <link rel="stylesheet" type="text/css" href="styles.css" />
    <title>Survey Form</title>
  </head>
  <body>
<h1 id="title">
  <div id="title"<h1>Handicap Survey Form</h2>
<p id="description">
  Men over 50 can sign this form !
</p>
<form id="survey-form" action="">
<label for="name" id="name-label"
          ><p>Name:</p>
          <input 
          type="text" 
          id="name" 
          placeholder="required"
          required
          
          />
        </label>
        <label for="email" id="email-label"
          ><p>Email:</p>
          <Input
            type="email"
            id="email"
            placeholder="required" 
            required
            
          />
        </label>
        <label for="age" id="number-label"
          ><p>Age<em>(optional)</em>:</p>
          <input
            type="number"
            id="number"
            placeholder= required
            min="66"
            max="50"
          />
        </label>
        <label for="interest" id="interest-label"
          ><p>which wheelchair do you need?</p>
          <select id="dropdown">
            <option selected disabled hidden></option>
            <option id="Small">Small</option>
            <option id="medium">medium</option>
            <option id="large">large</option>
            <option id="exrta large">exrta large</option>
          </select>
        </label>
        <p>Are you over 50?</p>
        <label for="yes">
          <input
            id="togepi"
            type="radio"
            name="favorite"
            value="togepi"
          />yes
        </label>
        <label for="no">
          <input
            id="pikachu"
            type="radio"
            name="favorite"
            value="pikachu"
          />no
        </label>
        <label for="other">
          <input id="other" type="radio" name="favorite" value="other" />Other
        </label>
        <p>Do you rather online or come to the store?</p>
        <label for="store">
          <input
            id="newsletter"
            type="checkbox"
            name="communications"
            value="newsletter"
          />store
        </label>
        <label for="online">
          <input
            id="events"
            type="checkbox"
            name="communications"
            value="events"
          />online
        </label>
        <label for="either">
          <input
            id="updates"
            type="checkbox"
            name="communications"
            value="updates"
          />either
        </label>
        <p>Any other information you would like to share?</p>
        <textarea id="additional-information" rows="4" cols="50">
You can provide comments, suggestions, or feedback here.</textarea
        >
        <p>
          <em
            >Please note: This form is a proof of concept. Submitting the form
            will not actually transmit your data.</em
          >
        </p>
        <button type="Submit" id="submit">Submit</button>
      </form>
    </main>
  </body>
  <footer>
    <a href="../">Return to Project List</a> |
    <a href="">Return to HomePage</a>
  </footer>
</html>



main {
  text-align: center;
  background-color: #92869c;
  background-blend-mode: lighten;
  max-width: 500px;
  margin: 20px auto;
  border-radius: 50px;
  box-shadow: 10px 10px rgba(0, 0, 0, 0.5);
  color: black;
}
body {
  text-align: center;
  background: #3a3240;
  color: white;
}
input, textarea, select, button {
  background: #3a3240;
  color: white;
}
a {
  color: white;
}
