# WATERLEVEL-ALERT-DETECTION-USING-BOLT-IOT
A water level sensor project that sends alert through buzzer and sms when water level exceeds threshold values. It is made using bolt IOT.

<h1>Things used in this project</h1>

1. Breadboard (generic)
2. water sensor [REES52]
3. 5 mm LED: Yellow
4. Buzzer
5. Jumper wires (generic)
6. Resistor 330 ohm
7. USB-A to Micro-USB Cable
<img src="1.jpg">
<img src="2.jpg">
<img src="3.jpg">
<img src="4.jpg">
<img src="5.jpg">
<img src="6.jpg">
<img src="7.jpg">
<img src="8.jpg">
<h1>Software apps and online services</h1>
1. Bolt IoT Bolt Cloud
2. Bolt IoT Android App
3. Notification Reader - Shouter
4. telegram
<h1>Thanks to BOLT !</h1>
<p>
	I thank Bolt platform which made my work easier to complete my project. it is a very user friendly and convenient platform. it made me clarify my doubts and issues by posting them in the bolt forum.
</p>
<h1>Project:</h1>
<p>I used a REES52 Water Sensor in this project which is an easy-to-use, cost-effective high level/drop recognition sensor which is obtained by having a series of parallel wires exposed traces measured droplets/water volume in order to determine the water level.

The Python Script checks the REES52 Water Sensor value sent from bolt device to the Bolt Cloud for every 10 sec and the sensor value doesn't exceed 10 until the water comes in contact with the sensor and as soon as the water falls on the sensor it crosses threshold value then it switches on the BUZZER and LED which goes off in 1 min during that time it requests the Twillio API to send SMS to your phone number. The telegram bot you created sends a message to channel that has your employees and we even get a VOICE notification, and we will even get a MAIL from the python program through Mailgun.</p>
<h2>
1.Creating an account on the IOT cloud service(if you already have an account you can just skip to the next step)</h2>
Open www.cloud.boltiot.com on your web browser.
<img src="bolt_login.jpeg">
you can sign up by filling your details. Then you will be getting the following page.
<img src="blot_home.jpeg">
<h2>2.Linking the Bolt module to the cloud</h2>
Step 1: Open the playstore app on your mobile and search for Bolt Iot app and install it.
Step 2: Login using the bolt cloud credentials and Follow the instructions specified by the app, using those instructions Link your Bolt Module to the cloud.
<img src="after_login.jpeg">
After linking your bolt cloud page would be looking like...
<img src="mobile_app.jpeg">
<h2>3. Hardware Setup</h2>
<img src="hardware_setup.jpeg">
