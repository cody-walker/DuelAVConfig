<h1>Duel Antivirus Configuration</h1>

<h2>Description</h2>
The project aims to configure two different antivirus software to run side-by-side at different intervals without slowing down the machine. Avast will be the daily scanner and Malwarebytes will scan every 30 days. This allows the user to take advantage of Malwarebytes's virus scanner and Avast's malware and ransomware protection as well as a firewall. The project requires the user to configure the exclude list on each AV's settings to exclude the file and folder structure of the counter AV. It's important to note that if you want to schedule the 30-day scan in Malwarebytes, you must pay for the Premium subscription. However, we will just run it manually every 30 days using the free version of the software.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Avast Antivirus</b> 
- <b>Malwarebytes Antivirus</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (22H2)

<h2>Program walk-through:</h2>

<p align="center">
Download Avast: <br/>

 ![Screenshot 2023-10-29 061412](https://github.com/cody-walker/DuelAVConfig/assets/148695140/ccd1129a-aee4-41ab-a744-65b762d66ea7)
<br />
<br />
<p align="center">
Download Malwarebytes: <br/>

![Screenshot 2023-10-29 063044](https://github.com/cody-walker/DuelAVConfig/assets/148695140/be613e46-e2e3-4a07-9f6c-07ae25935897)

<br />
<br />
<p align="center">
Locate and configure exception/allow list in each AV's settings to exclude the counter AV: <br/>

![Screenshot 2023-12-07 224337](https://github.com/cody-walker/DuelAVConfig/assets/148695140/e01953c3-8bf7-4ee5-8878-157bbd3bb72d)

![Screenshot 2023-12-07 224218](https://github.com/cody-walker/DuelAVConfig/assets/148695140/5d363cf2-612e-4013-ad65-76aa0501d107)

<br />
<br />
<p align="center">
Edit custom scan frequency in Avast to daily:
 
![Screenshot 2023-12-07 231600](https://github.com/cody-walker/DuelAVConfig/assets/148695140/1ec301b9-7b06-469c-abf2-8ed60aa2f26a)

<br />
<br />
<p align="center">
Configure Avast firewall in settings:

![Screenshot 2023-12-07 232219](https://github.com/cody-walker/DuelAVConfig/assets/148695140/d3c3f988-c86a-4b4c-ac51-b25bac4ff196)

<br />
<br />
<p align="center">
 Restart machine:  <br/>


 <br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
