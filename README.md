<h1>Deforumation google colab Setup Tutorial</h1> <br>
This tutorial will guide you through the process of setting up Deforumation, a tool to control Deforum on Google Colab from your local machine.<br><br>

<h2>Prerequisites :</h2>
- Make sure you have Ngrok installed on your local machine. If not, you can download it from the official Ngrok website.<br><br>
<h2>Instructions :</h2>
<div>Open your terminal or command prompt. <br>
Install Ngrok and make sure it's properly set up on your local machine.<br>
Run the following command to start Ngrok: <code>ngrok tcp 8765</code>.<br>
Once Ngrok starts, it will provide you with a port number. Take note of this port number.<br>
<code>Open the deforum_mediator.py</code> file and replace the Ngrok port with the port number you obtained in the previous step.<br>
Run the mediator.py file by entering the following command in your terminal: <code>python mediator.py</code>.<br>
Run the deforumation.py file by entering the following command in your terminal: <code>python deforumation.py</code>.<br>
Now, go to your Google Drive where you have the Deforum installation.<br>
Find the modified file within the deforum_helpers folder and replace the corresponding file in the Deforum installation.<br>
Finally, run the Deforum tool on Google Colab as usual. You can now control it using Deforumation running on your local machine.<br>
