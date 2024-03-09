<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Senior High School Enrollment Portal</title>
 </head>
<body>
   
 <div style="background-color:LightBlue;width:500px;border:1px solid black;padding:15px;">
 <H1 style="color:DodgerBlue;">Senior High School Enrollment Portal</H1> 
   
    <label for="track">Grade Level to Enroll:</label>
        <select id="track" name="track" required>
            <option value="">Select Grade Level</option>
            <option value="Grade 11">Grade 11</option>
            <option value="Grade 12">Grade 12</option>
           </select><br><br>


           
            <label for="strand">Preferred Strand:</label>
        <select id="Strand" name="Strand" required>
            <option value="">Select Strand</option>
            <option value="STEM">STEM</option>
            <option value="ABM">ABM</option>
            
            <option value="TVL">TVL</option>
            <option value="MARITIME">MARITIME</option>
        </select><br><br>
        
       
            
       <label for="lrn">Learner Reference Number (LRN):</label>
        <input type="text" id="lrn" name="lrn" required><br><br>
                        
        <label for="Current School Enrolled">Current School Enrolled</label>
        <input type="text" id="Current School Enrolled" name="Current School Enrolled" required> <br> <br>
        
        <hr style="height:2px;border-width:0;color:gray;background-color:gray">

      
    <H1 style="color:black">STUDENT INFORMATION</H1> 
   <hr style="height:2px;border-width:0;color:gray;background-color:gray">

   
      <label for="PSA Birth Certificate No. (if applicable upon registration):">PSA Birth Certificate No. (if applicable upon registration):</label> <br><br>
        <input type="text" id="name" name="name" required><br><br>
       
       
      <p3>Name<p3/><br><br>
      
      
      <label for="name">Last name:</label>
      <input type="text" id="name" name="name" required><br><br>
      <label for="name">First name:</label>
       <input type="text" id="name" name="name" required><br><br>
        <label for="name">Middle name:</label>
        <input type="text" id="name" name="name" ><br><br>
        <label for="name">Extension name:</label>
        <input type="text" id="name" name="name" ><br><br>
        
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>
        <label for="name">Age:</label>
        <input type="text" id="name" name="name" ><br><br>
        <label for="gender">Sex:</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>
         <label for="name">Mother Tongue:</label>
      <input type="text" id="name" name="name" required><br><br>
       <label for="contact">Contact Number:</label>
        <input type="tel" id="contact" name="contact" required><br><br>
        <label for="email">Facebook Account:</label>
        <input type="email" id="email" name="email" required><br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>
        <label for="email">4Ps Household ID Number:</label>
        <input type="email" id="email" name="email"><br><br>
        <label for="track">Belonging to any Indigenous People (IP)<br>
        Community/Indegenous Cultural Community:</label>
        <select id="track" name="track" required>
            <option value="">Select</option> <br>
            <br>
            <option value="Grade 11">YES</option>
            <option value="Grade 12">NO</option>
           </select><br><br>
           <label for="email">Emergency Contact No.:</label>
        <input type="email" id="email" name="email" required><br><br><br>
        
        
        <p3>Is the child a Learner with disability<p3/>
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">YES
    <input type="checkbox" id="terms" name="terms" required>
     <label for="terms">NO<br><br>
    
<p3>If yes, specify the type of disability:<p3/><br><br>
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Visual Impairment<br>
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">a. blind
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">b. low vision<br>
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Hearing Impairment
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Learning Disability
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Intellectual Disability<br>
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Autism Spectrum Disorder 
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Emotional-Behavioral Disorder<br>
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Orthopedic
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Speech/Language Disorder
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Cerebal Palsy<br>
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Chronic Disease
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">a. cancer<br><br><br>


<hr style="height:2px;border-width:0;color:gray;background-color:gray">



         <p3>CURRENT ADDRESS<p3/><br><br> 
       <label for="address">Province:</label>
        <input type="text" id="address" name="address" required><br><br>
        <label for="address">Municipality/City:</label>
        <input type="text" id="address" name="address" required><br><br>
        <label for="address">Barangay:</label>
        <input type="text" id="address" name="address" required><br><br>
       <label for="address">House no. and street:</label>
        <input type="text" id="address" name="address" required><br><br>
<label for="address">Zip Code:</label>
        <input type="text" id="address" name="address" required><br><br><br>
        



<p3>PERMANENT ADDRESS<p3/><br><br> 
       <label for="address">Province:</label>
        <input type="text" id="address" name="address" required><br><br>
        <label for="address">Municipality/City:</label>
        <input type="text" id="address" name="address" required><br><br>
        <label for="address">Barangay:</label>
        <input type="text" id="address" name="address" required><br><br>
       <label for="address">House no. and street:</label>
        <input type="text" id="address" name="address" required><br><br>
        <label for="address">Zip Code:</label>
        <input type="text" id="address" name="address" required><br><br><br>
        
        <hr style="height:2px;border-width:0;color:gray;background-color:gray">




 <p3>PARENT/GUARDIAN'S INFORMATION<p3/><br><br> 
<p3>Father's Name<p3/><br><br>
<label for="address">Last Name:</label>
        <input type="text" id="address" name="address" required><br><br>
    <label for="address">First Name:</label>
        <input type="text" id="address" name="address" required><br><br>
        <label for="address">Middle Name:</label>
        <input type="text" id="address" name="address" required><br><br>
<label for="address">Contact Number:</label>
        <input type="text" id="address" name="address" required><br><br><br>




<p3>Mother Maiden's Name<p3/><br><br>
<label for="address">Last Name:</label>
        <input type="text" id="address" name="address" required><br><br>
    <label for="address">First Name:</label>
        <input type="text" id="address" name="address" required><br><br>
        <label for="address">Middle Name:</label>
        <input type="text" id="address" name="address" required><br><br>
<label for="address">Contact Number:</label>
        <input type="text" id="address" name="address" required><br><br><br>

    
<p3>Legal Guardian's Name<p3/><br><br>
<label for="address">Last Name:</label>
        <input type="text" id="address" name="address" required><br><br>
    <label for="address">First Name:</label>
        <input type="text" id="address" name="address" required><br><br>
        <label for="address">Middle Name:</label>
        <input type="text" id="address" name="address" required><br><br>
<label for="address">Contact Number:</label>
        <input type="text" id="address" name="address" required><br><br><br>
<hr style="height:2px;border-width:0;color:gray;background-color:gray">


        
<p3>For Returning Learner (Balik-Aral) and Those Who will Transfer/Move In<p3/><br><br>
<label for="address">Last Grade Level Completed:</label>
        <input type="text" id="address" name="address" required><br><br>
<label for="address">Last School Attended:</label>
        <input type="text" id="address" name="address" required><br><br>
<label for="address">Last School Year Completed:</label>
        <input type="text" id="address" name="address" required><br><br>
<label for="address">School ID:</label>
        <input type="text" id="address" name="address" required><br><br><br>

<hr style="height:2px;border-width:0;color:gray;background-color:gray">



<p3>For Learner's in Senior High School<p3/><br><br>
<p3>Semester<p3/>
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">1st
    <input type="checkbox" id="terms" name="terms" required>
     <label for="terms">2nd<br><br>
    
<label for="address">Track:</label>
        <input type="text" id="address" name="address" required><br><br>
<label for="address">Strand:</label>
        <input type="text" id="address" name="address" required><br><br><br>



<p3>If school will implement other distance learning modalities asiide from face-to-face instruction, what whould you prefer?<p3/><br><br>
<p3>Choose all that apply:<p3/><br><br>
   <input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Modular (Print)
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Online
    <input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Radio-Based instruction<br>

<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Modular (Digital)
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Educational Television
    
<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Homeschooling<br>

<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">Blended<br><br><br>
    


<p3>NEW ENROLMENT POLICY FOR SENIOR HIGH SCHOOL<br>
Effective Date: January 29, 2024

This policy outlines the enrolment procedures and fees for incoming Senior High
Eligibility:<br>
• JHS Public School Completers: Applicants who have successfully completed their Junior
High School education in a public school are eligible for free enrolment.<br>
• JHS Private School Completers: Applicants who have successfully completed their Junior High School education in a private school are eligible for enrolment but must pay a tuition fee of P3,500 per year provided they have ESC Voucher.<br>
Returnees:<br>
• Students who previously withdrew and wish to re-enrol are considered returnees.<br>
• Returnees must pay half of the regular tuition fee per semester, amounting to Php 8,750.<br>
Withdrawal Policy:<br>
• Once enrolled, students are expected to complete the academic year.<br>
• Withdrawals are only permitted for very valid reasons, such as documented medical conditions with proof or recommendation from a licensed physician.<br>
• Withdrawal fees will apply:<br>
• Php 500 processing fee for all withdrawals.
• Php 1,750 if withdrawing within the first day to one month after the first day of classes.<br>
• An additional P1,750 per succeeding month of attendance will be charged for withdrawals beyond the first month,
The creation of this policy is based on DepEd Order No. 88, s. 2010 (2010 Revised Manual of Regulations for Private Schools in Basic Education) Section 180. Tuition and other Student Fees. Each private school shall determine its rate of tuition and other school fees or charges, The rates and charges adopted by schools pursuant to this provision shall be collectible, and their application or use authorized, subject to rules and regulations promulgated by the Department.<br><br>
By implementing this policy, Southwestern College of Maritime, Business and Technology Inc. aims to ensure fairess and transparency in the enrolment process and promote responsible student commitment to their academic pursuits.
By signing, we, the student and guardian fully understand and acknowledge this
policy.<br><br>







        <p3>Signature Over Printed Name of Parent/Guardian <p3/>
        <input type="file" name="documents" accept=".pdf, .doc, .docx"><br><br>
        <hr style="height:2px;border-width:0;color:gray;background-color:gray">





<input type="checkbox" id="terms" name="terms" required>
     <label for="terms">I agree to the terms and conditions.<br><br>
    
 
 
 <p1>I hereby certify that the above information given is true and correct to the best of my knowledge and I allow the Department of Education to use my details to create and/or update his/her learner profile in the Learner Information System. The information herein shall be treated as confidential in compliance with the Data Privacy Act of 2012.<p1/> <br><br>
       

        
        
        <input type="submit" value="Enroll">
    </form>
</body>
</html>
