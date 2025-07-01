<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <link rel="stylesheet" href="./script.css"/>
  <title>MEDBETA</title>
</head>
<body background="./Children's Hospital Colorado - ArtHouse Design.jpeg">
  <section>
    <div class="header">
      <h1><em>MEDBETA</em></h1>
      <p><img src="./723b7d2f-604a-4712-8bb4-1549c7455b7e.jpeg" alt="logo"/></p>
    </div>

    <div class="blur-box">
      <nav>
        <em>
          <a href="#home" id="first">home</a>
          <a href="#services" id="seco">services</a>
          <a href="#emergency" id="third">emergency</a>
        </em>
      </nav>
    </div>

    <section>
      <h1 id="services">Services offered</h1>
      <ol>
        <li>Online Consultation</li>
        <li>Doctor Appointments</li>
        <li>Health Monitoring</li>
        <li>Emergency Support</li>
      </ol>
    </section><br/>

    <section id="Cardiologist">
      <h1><em>CARDIOLOGIST</em></h1>
      <p>Get to have your booked consultation from anywhere in the country on our telemedicine platform.</p>
      <p>We have fully specialized cardiologists ready to offer the best care.</p>
      <input type="button" value="CHECK DETAIL" class="doctor-button" data-dept="cardiologist"/>
    </section><br/>

    <section id="Dermatologist">
      <h1><em>DERMATOLOGIST</em></h1>
      <p>Get your skin treated by top dermatologists from anywhere in the country.</p>
      <p>Book a slot now at your nearest hospital facility.</p>
      <input type="button" value="CHECK DETAIL" class="doctor-button" data-dept="dermatologist"/>
    </section><br/>

    <section id="Pediatrician">
      <h1><em>PEDIATRICIAN</em></h1>
      <p>Ensure your children receive the best healthcare from trusted pediatricians nationwide.</p>
      <input type="button" value="CHECK DETAILS" class="doctor-button" data-dept="pediatrician"/>
    </section><br/>

    <section class="ambulance" id="emergency">
      <h1><em>EMERGENCY</em></h1>
      <div class="container">
        <div class="box">
          <h1><em>AIR AMBULANCE TEAM</em></h1>
          <ul>
            <li>Deploy helicopters or aircraft for rapid transport</li>
            <li>Equipped for critical care in the air</li>
            <li>Ideal for remote or sensitive emergencies</li>
          </ul>
          <input type="button" value="CALL NOW" class="doctor-button" data-dept="airambulance"/>
        </div>

        <div class="box">
          <h1><em>Paramedics & EMTs (Emergency Medical Technicians)</em></h1>
          <ul>
            <li>Stabilize patients during transport</li>
            <li>Emergency ambulances available</li>
            <li>Provide first aid and advanced life support</li>
          </ul>
          <input type="button" value="CALL NOW" class="doctor-button" data-dept="emt"/>
        </div>
      </div>
    </section>

 <script src="./index.js"></script>
</body>
</html>



body{
    background-color: rgb(235, 238, 243);
    
    
}
.header{
    text-align: center;
    font-size: x-large;
    font-weight: bold;
    font-style: oblique;
    color: rgb(12, 12, 12);
    border-radius: 45px;
    padding-block: 20px;
    margin: auto;
    backdrop-filter: blur(10px);
    


}

#services{
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    margin: auto;
    padding: 20px;
    border-radius: 45px;
    backdrop-filter: blur(10px);
    border-style: groove;
    color: rgb(14, 13, 13);
    font-size: x-large;
    font-weight: bolder;
    margin: auto;
    align-items: center;
    text-align: center;
    background-color: rgb(255, 255, 255,0.2);
    width: 450px;
    align-content: center;
    
}

#Cardiologist{
    scroll-padding: 2rems;
    width: 450px;
    height: 450px;
    margin: auto;
    border-radius: 50px;
    border-style: hidden;
    border-color: khaki;
    background-image: url(./Red\ heart\ and\ stethoscope\ on\ black\ paper_\ flat\ lay\ essential\ items\ for\ doctor\ using\ treat\ and\ care\ patient\ in\ hospital.\ _\ Premium\ Photo);
    align-content: center;
    text-align: center;
    color: antiquewhite;
}

#buttoname{
    width: 200px;
    height: 40px;
    border-radius: 40px;
    background: rgb(240, 206, 16);

}

#name{
      width: 150px;
    height: 40px;
    border-radius: 30px;
}

#Dermatologist{
    scroll-padding: 2 rems;
    width: 450px;
    height: 450px;
    margin: auto;
    border-radius: 50px;
    border-style: hidden;
    background-image: url(./f39377ed-4a26-4d94-9621-0762e2d7ed64.jpeg);
    align-content: center;
    text-align: center;
    color: antiquewhite;
}

#Pediatrician{
    scroll-padding: 2rems;
     width: 450px;
    height: 450px;
    margin: auto;
    border-radius: 50px;
    border-style: hidden;
    background-image: url(./Foto\ de\ um\ bebê\ fofo\ brincando\ com\ brinquedos\ _\ imagem\ Premium\ gerada\ com\ IA.jpeg);
    align-content: center;
    text-align: center;
    color: rgb(3, 3, 3);
}

.blur-box{
    border-radius: 10px;
    backdrop-filter: blur(10px);
    background: rgba(49, 47, 47, 0.2);
    width: 405px;
    height: 55px;
    font-size: larger;
    font-weight: bolder;
    font-display: auto;
    align-items: center;
    color: antiquewhite;
    text-align: center;
    align-content: center;
    padding: 20px;

}

#first{
    border-radius: 20px;
    text-align: center;
    color: antiquewhite;
    background-color: rgb(87, 83, 38);
    box-shadow: 10px;
}
#seco{
      border-radius: 20px;
    text-align: center;
    color: antiquewhite;
    background-color: rgb(87, 83, 83);
    box-shadow: 10px;
}

#third{
      border-radius: 20px;
    text-align: center;
    color: antiquewhite;
    background-color: rgb(87, 83, 83);
    box-shadow: 10px;

}
img{
    border-radius: 50px;
    margin: auto;
    width: 100px;
    height: 100px;
}


.container{
    display: flex;
    justify-content: space-between;
    gap: 20px;
}

.box{
     border-radius: 10px;
    backdrop-filter: blur(10px);
    background: rgba(49, 47, 47, 0.2);
    width: 405px;
    height: 505px;
    font-size: larger;
    font-weight: bolder;
    font-display: auto;
    align-items: center;
    color: antiquewhite;
    text-align: center;
    align-content: center;
    padding: 20px;
    


}
.doctor-button{
    background-color: rgb(238, 107, 60);
    border-radius: 35px;
}



 document.addEventListener('DOMContentLoaded', function () {
    const doctorButtons = document.querySelectorAll('.doctor-button');

    doctorButtons.forEach(function (button) {
      button.addEventListener('click', function () {
        const department = button.getAttribute('data-dept');
        const patientName = prompt(`Enter patient's full name to book a ${department} consultation:`);

        if (!patientName || patientName.trim() === "") {
          alert("Booking cancelled. Please enter a valid name.");
          return;
        }
        const apiURL = `https://medbetaapi.com/api/doctors?department=${department}`;

        fetch(apiURL)
          .then(response => {
            if (!response.ok) {
              throw new Error('Network response was not ok');
            }
            return response.json();
          })
          .then(data => {
            if (data && data.length > 0) {
              const selectedDoctor = data[0]; // Pick the first doctor for simplicity
              alert(
                `✅ Booking confirmed!\n\nPatient: ${patientName}\nDoctor: Dr. ${selectedDoctor.name}\nHospital: ${selectedDoctor.hospital}\nDepartment: ${department}`
              );
            } else {
              alert(`No available ${department} doctors found.`);
            }
          })
          .catch(error => {
            console.error('API Error:', error);
            alert('Booking failed. Please try again later.');
          });
      });
    });
  });
