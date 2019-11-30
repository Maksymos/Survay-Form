# Survay-Form
Car Insurance Survay Form
<!DOCTYPE html>
<html>
<body>
  <head>
    <style>
      body {
			background-color: lightblue;
			font-family: sans-serif;
		}

		h1 {
			color: white;
			text-align: center;
		}

		h2 {
			text-align: center;
		}

		.form {
			border: 2px grey;
			border-radius: 5px;
			padding: 1px 10px 0px 20px;
			display: grid;
			grid-gap: 3px;
			background-color: #F1F1F1;
  			text-align: center;
  			padding: 10px;
  			width: 800px; 
  			margin:0 auto;
        
		}

		<div class="form">
 			<div class="name-lable">Name</div>
  			<div class="email-label">Email</div>
 			<div class="number-lable">Age</div>
  			<div class="dropdown">Role</div>
 			<div class="input-radio">Input-radio</div>
  			<div class="form-control">Form-control</div>
  			<div class="clue">Clue</div>
  			<div class="input-textarea">input-textarea</div>
		</div>



    </style>
  </head>
<h1 id="title">Car Insurance Form</h1>
	<h2 id="description">Find out the best auto insurance rates with US!</h2>
		</header>
      		 <form action="/action_page.php" id="survey-form">
      		 	<div class="form" style="width: 60%;">
      		 		<input type="text" name="name" placeholder="Enter your name"required><br>
      		 		<input type="text" name="email" placeholder="Enter your Email"required><br>
      		 		<input type="number" name="number" min="18" max="95" placeholder="Age"required><br>
      		 	</div>
      		 	<br>
				<div class="form" style="width: 60%;">
      		 		<p>Which option best describes your current state?</p>
      		 		<select id="dropdown" name="role" class="form-control" required>
      		 			<option value="Student">Student</option>
      		 			<option value="Emploee">Emploee</option>
      		 			<option value="Unemployed">Unemployed</option>
      		 			<option value="Freelancer">Frelancer</option>
      		 			<option value="Prefer not to say">Prefer Not To Say</option>
            			<option value="Other">Other</option>
      		 		</select>
      		 	</div>
      		 	<br>

      		 	<div class="form" style="width: 60%; text-align: left;">
      		 		<label id="number-income" for="income" style="text-align: center;">Annual Income</label>
      		 		<h6>$35,000-60,000</h6>
      		 			<input name="user-recommend" value="ok" type="radio" class="input-radio" checked>

      		 		<h6>$60,000-100,000</h6>
      		 			<input name="user-recommend" value="ok" type="radio" class="input-radio" checked>

      		 		<h6>$101,000-more</h6>
      		 			<input name="user-recommend" value="ok" type="radio" class="input-radio" checked>
      		 	</div>
      		 	<br>
      		 	<div class="form" style="width: 60%;">
      		 		<p>Which type of vehicle are you driving?</p>
      		 		<select name="role" class="form-control" required>
      		 			<option disabled selected value>Select current car</option>
      		 			<option value="Sedan">Sedan</option>
      		 			<option value="SUV">SUV</option>
      		 			<option value="Truck">Truck</option>
      		 			<option value="Other">Other</option>
      		 		</select>	
      		 	</div>
      		 	<br>
      		 	<div class="form" style="width: 60%; text-align: left;">
      		 		<label style="text-align: center;">What insurance companies did you use before?
      		 			<span class="clue">(Check all that apply?</span>
      		 		</label>
      		 			<label for="Progressive">Progressive</label>
      		 			<input type="checkbox" name="Progressive" type="checkbox" class="input-checkbox"><br>

      		 			<label for="Allstate">Allstate</label>
      		 			<input type="checkbox" name="Allstate" type="checkbox" class="input-checkbox"><br>

      		 			<label for="Liberty_Mutual">Liberty Mutual</label>
      		 			<input type="checkbox" name="Liberty Mutual" type="checkbox" class="input-checkbox"><br>

      		 			<label for="MetLife">MetLife</label>
      		 			<input type="checkbox" name="MetLife" type="checkbox" class="input-checkbox"><br>

      		 			<label for="Vanguard">Vanguard</label>
      		 			<input type="checkbox" name="Vanguard" type="checkbox" class="input-checkbox">
      		 	</div>
      		 	<br>
      		 	<div class="form" style="width: 60%;">
      		 		<h4>Any questions or comments?</h4>
      		 		<textarea rows="6" cols="50" class="input-textarea"></textarea>
      		 	</div>
      		 	<br>
      		 	<input class="form" type="submit" style="height: 35px; width: 100px; " value="Submit">
      		 </form>
       
</body>
</html>

