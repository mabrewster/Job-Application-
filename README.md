# Job-Application-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Career Planning Job Application</title>

style.css

https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.jsscript>
</head>

<body>

<header>
    <h1>Career Planning Job Application</h1>

    <div class="progress-container">
        <div id="progressBar"></div>
    </div>

    <p id="progressText">0% Complete</p>
</header>

<div class="button-bar">
    <button onclick="downloadPDF()">Download PDF</button>
    <button onclick="window.print()">Print</button>
    <button onclick="clearForm()">Clear Form</button>
</div>

<form id="jobForm">

<section>
<h2>Personal Information</h2>

<label>Full Name</label>
<input type="text">

<label>Date</label>
<input type="date">

<label>Mailing Address</label>
<input type="text">

<label>City, State, Zip</label>
<input type="text">

<label>Phone Number</label>
<input type="tel">

<label>Email</label>
<input type="email">

<label>If Under 18, Age</label>
<input type="number">
</section>

<section>
<h2>Job Details</h2>

<label>Position Applying For</label>
<input type="text">

<label>Availability</label>

<div class="checkbox-row">
<label><input type="radio" name="availability"> Full-Time</label>
<label><input type="radio" name="availability"> Part-Time</label>
<label><input type="radio" name="availability"> Either</label>
</div>

<label>Hours Per Week</label>
<input type="number">

<label>Can You Work Nights?</label>
<select>
<option></option>
<option>Yes</option>
<option>No</option>
</select>

<label>Date Available to Begin</label>
<input type="date">
</section>

<section>
<h2>Education</h2>

<div class="education">
<h3>School 1</h3>

<input type="text" placeholder="School Name">
<input type="text" placeholder="Address">
<input type="text" placeholder="Dates Attended">
<select>
<option>Graduated?</option>
<option>Yes</option>
<option>No</option>
</select>
</div>

<div class="education">
<h3>School 2</h3>

<input type="text" placeholder="School Name">
<input type="text" placeholder="Address">
<input type="text" placeholder="Dates Attended">

<select>
<option>Graduated?</option>
<option>Yes</option>
<option>No</option>
</select>
</div>

<div class="education">
<h3>School 3</h3>

<input type="text" placeholder="School Name">
<input type="text" placeholder="Address">
<input type="text" placeholder="Dates Attended">

<select>
<option>Graduated?</option>
<option>Yes</option>
<option>No</option>
</select>
</div>
</section>

<section>
<h2>Work Experience #1</h2>

<input type="text" placeholder="Company">

<input type="text" placeholder="Supervisor">

<input type="text" placeholder="Address">

<input type="text" placeholder="City, State, Zip">

<input type="tel" placeholder="Phone Number">

<input type="date">

<input type="date">

<input type="text" placeholder="Starting Salary">

<input type="text" placeholder="Final Salary">

<input type="text" placeholder="Last Job Title">

<input type="text" placeholder="Reason for Leaving">

<textarea placeholder="Describe job duties and responsibilities"></textarea>
</section>

<section>
<h2>Work Experience #2</h2>

<input type="text" placeholder="Company">

<input type="text" placeholder="Supervisor">

<input type="text" placeholder="Address">

<input type="text" placeholder="City, State, Zip">

<input type="tel" placeholder="Phone Number">

<input type="date">

<input type="date">

<input type="text" placeholder="Starting Salary">

<input type="text" placeholder="Final Salary">

<input type="text" placeholder="Last Job Title">

<input type="text" placeholder="Reason for Leaving">

<textarea placeholder="Describe job duties and responsibilities"></textarea>
</section>

<section>
<h2>Additional Information</h2>

<label>Previously Employed by Company?</label>
<select>
<option></option>
<option>Yes</option>
<option>No</option>
</select>

<label>Authorized to Work in the U.S.?</label>
<select>
<option></option>
<option>Yes</option>
<option>No</option>
</select>

<label>Driver's License?</label>
<select>
<option></option>
<option>Yes</option>
<option>No</option>
</select>

<label>Military Service?</label>
<select>
<option></option>
<option>Yes</option>
<option>No</option>
</select>

<label>Felony Conviction?</label>
<select>
<option></option>
<option>Yes</option>
<option>No</option>
</select>

<textarea placeholder="If yes, please explain"></textarea>
</section>

<section>
<h2>References</h2>

<textarea placeholder="Reference #1"></textarea>

<textarea placeholder="Reference #2"></textarea>

<textarea placeholder="Reference #3"></textarea>
</section>

<section>
<h2>Certification</h2>

<p>
I certify that all answers and statements on this application are true and complete to the best of my knowledge.
</p>

<label>Digital Signature</label>
<input type="text">

<label>Date</label>
<input type="date">

</section>

</form>

script.jsscript>

</body>
</html>
