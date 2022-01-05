---
layout: page
# title: Book Me
# subtitle: Please use the form below to complete your booking request.
---


<div style="width: 60%; float:left">
   #left content in here
</div>
<div style="width: 40%; float:right">
<h2 class="text-center">Work with Me</h2>
<form id="fs-frm" name="booking-form" accept-charset="utf-8" action="https://formspree.io/f/mknygpvb" method="POST">
<p> Book me as your next keynote, moderator, host, or panelist. Use the form to work with my team on getting me to your next event. </p>
<br>
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Full Name *</label>
    <br>
    <input type="text" name="name" id="full-name" placeholder="First and Last" required="">
    <br>
    <br>
    <label for="email-address">Email Address *</label>
    <br>
    <input type="email" name="_replyto" id="email-address" placeholder="E.g. email@domain.com" required="">
    <br>
    <br>
    <label for="Company">Company *</label>
    <br>
    <input type="text" name="Company" id="company-name" placeholder="Your company name here" required="">
    <br>
    <br>
    <label for="date">Project date * </label>
    <br>
    <input type="date" name="date" id="date-name" placeholder="" required=""> 
    <br>
    <br>
    <label for="time">What time should I arrive? *</label>
    <br>
    <input type="time" name="time" id="time-name" placeholder="" required=""> 
    <br>
    <br>
    <label for="servicetype">I'd like to book Emmanuel for... * </label>
    <br>
     <select name="servicetype" required="">
        <option value="" selected="" disabled="">Select an option</option>
      	<option value="IK">Inspirational Keynote</option>
      	<option value="PM">Panel Moderation</option>
        <option value="PP">Panel Participation</option>
        <option value="SE">Speaking Engagement</option>
        <option value="PI">Press Interview</option>
        <option value="EH">Event Host</option>
        <option value="OO">Other</option>
     </select>  
     <br> 
     <br>  
    <label for="note">Tell me more about this project *</label>
    <br>
    <textarea rows="2" name="note" id="note" placeholder="What do I need to know about the project? Feel free to include any additional information"></textarea>
    <br>
    <br>
    <label for="budget">Budget *</label>
    <br>
    <input type="text" name="budget" id="budget-id" pattern="[$0-9]+" placeholder="E.g. $1000" required="">
    <br>
    <br>
      <label for="aboutus">How did you hear about us?</label>
      <br>
       <select name="aboutus" >
        <option value="" selected="" disabled="">Select an option</option>
      	<option value="PW">Personal Website</option>
      	<option value="CR">Client Referral</option>
        <option value="IR">Industry Referral</option>
        <option value="GG">Google</option>
        <option value="IG">Instagram</option>
        <option value="IN">LinkedIn</option>
        <option value="OO">Other</option>
        <option value="UU">Unknown</option>
     </select>
    <br>
    <br>
  <input type="hidden" name="_subject" id="email-subject" value="Speaking Engagement Request Form Submission">
  </fieldset>
  <input type="submit" value="Submit">
</form>
</div>


