<p align="center">
 <img src="https://i.imgur.com/aSvvHBC.jpg" height="80%" width="80%" alt="Raid Array logo"/>
</p>

<h1>Create a Raid Array</h1>


<h2>Description</h2>
In this exciting demonstration, we will create a powerful RAID array using four  SATA hard drives to serve our video editing workstation. We'll be adding two dynamic volumes with distinct purposes:

First up is the Editing volume, specially designed to store massive amounts of raw video files that are crucial for top-notch editing. With this volume, we'll have lightning-fast access to all of our video content, ensuring a seamless editing experience.

Next, we have the Media volume, a high-capacity storage solution built to house all of our digital photos and completed video files. And the best part? This volume is designed to provide fault tolerance in case of drive failure, giving us the ultimate peace of mind.


<br />

<h2>Environments Used </h2>

 <b>Windows 11</b> 

<h2>Program walk-through:</h2>

<p align="center">
Right-click Start and select Disk Management.
<br/>
<img src="https://i.imgur.com/aTa9FVR.png" height="70%" width="70%" alt="Create Raid Array"/>
<br />
<br />
Select GPT as the partition style.
Select OK to initialize all disks.
<br/>
<img src="https://i.imgur.com/OcMGkdW.png" height="70%" width="70%" alt="Create Raid Array"/>
<br />
<br />
Right-click Disk 1 and select New Striped Volume.
Select Next.
 <br/>
<img src="https://i.imgur.com/2eQuXo3.png" height="70%" width="70%" alt="Create Raid Array"/>
<br />
<br />
Under Available, select Disk 2 then select Add. Select Next.
 <br/>
<img src="https://i.imgur.com/QTzQw3i.png" height="70%" width="70%" alt="Create Raid Array"/>
<br />
<br />
Use the Assign the following drive letter drop-down list to select E.
Select Next.
Make sure NTFS is selected as the file system.
Use Editing as the Volume label.
Select Next.
Select Finish.
 <br/>
<img src="https://i.imgur.com/bSLAXfj.png" height="70%" width="70%" alt="Create Raid Array"/>
<br />
<br />
Select Yes to convert the disks to dynamic disks. <br/>
<img src="https://i.imgur.com/WXsNO5v.png" height="70%" width="70%" alt="Create Raid Array"/>
<br />
<br />
Right-click Disk 3 and select New Mirrored Volume.
Select Next.
 <br/>
<img src="https://i.imgur.com/K9IIE18.png" height="70%" width="70%" alt="Create Raid Array"/>
<br />
<br />
Under Available, select Disk 4. Select Add. Then select next
 <br/>
<img src="https://i.imgur.com/ZIzjMdW.png" height="70%" width="70%" alt="Create Raid Array"/>
<br />
<br />
Use the Assign the following drive letter drop-down list to select M.
Select Next.
Make sure NTFS is selected as the file system.
Use Media as the Volume label; then select Next.
Select Finish.
 <br/>
<img src="https://i.imgur.com/oOWAQXr.png" height="70%" width="70%" alt="Create Raid Array"/>
<br />
<br />
Select Yes to convert the disks to dynamic disks. Your final result should look like this <br/>
<img src="https://i.imgur.com/MsVOmTw.png" height="70%" width="70%" alt="Create Raid Array"/>
<br />
<br />
That's it, we're finished. Simple, right?<br/>
<img src="https://i.imgur.com/e2U2Rhh.jpg" height="80%" width="80%"  alt="Create Raid Array"/>
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
