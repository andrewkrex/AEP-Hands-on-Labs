Lab - Profiles - UPS Review
==========
<table style="border-collapse: collapse; border: none;" class="tab" cellspacing="0" cellpadding="0">

<tr style="border: none;">

<div align="left">
<td width="600" style="border: none;">
<table>
<tbody valign="top">
      <tr width="500">
            <td valign="top"><h3>Objective:</h3></td>
            <td valign="top"><br>In this lab, you will look up your Customer Profile.
            </td>
     </tr>
     <tr width="500">
           <td valign="top"><h3>Prerequisites:</h3></td>
           <td valign="top"><br>none</td>
     </tr>
</tbody>
</table>
</td>
</div>

<div align="right">
<td style="border: none;" valign="top">

<table>
<tbody valign="top">
      <tr>
            <td valign="middle" height="70"><b>section</b></td>
            <td valign="middle" height="70"><img src="https://github.com/adobe/AEP-Hands-on-Labs/blob/master/assets/images/left_hand_nav_menu_segments.png?raw=true" alt="Profiles"></td>
      </tr>
      <tr>
            <td valign="middle" height="70"><b>version</b></td>
            <td valign="middle" height="70">1.0.1</td>
      </tr>
      <tr>
            <td valign="middle" height="70"><b>date</b></td>
            <td valign="middle" height="70">2020-01-06</td>
      </tr>
</tbody>
</table>
</td>
</div>

</tr>
</table>

In Adobe Experience Platform there's a new feature of visualizing the entire real-time customer profile. This one feature is what all of our customer's have been trying to get for years: a single view of the customer.

Instructions:
-----------------
1. 	Log in to Adobe Experience Platform by going to this URL: https://platform.adobe.com
2.	After logging in, you'll land on the homepage of Adobe Experience Platform.
3.	Make sure you are in the 'Prod(VA7)' instance and not in your sandbox instance.
4.	In the menu on the left side, go to Profiles.
5.	Click on the 'Browse' tab. You will see a UI in which a namespace and an ID can be entered.
 
<kbd><img src="./images/profile_view.png"  /></kbd>
 
6.	Next, go to https://americaspot3-publish.adobedemo.com/content/we-travel/language-masters/en.html# in a browser and click into a category page
7.	In the left margin, click on the “person” icon. This will display the X-ray panel from this website.
 
<kbd><img src="./images/person_panel_travel.png"  /></kbd>
 
8.	Expand the 'Real-time Customer Profile section' and observe the identities and their linkage to a namespace
 
<kbd><img src="./images/identities-ECID.png"  /></kbd>
 
9.	Copy the ECID value & go back to Profiles Browse view
10.	Select "ECID" in the "Identity namespace" dropdown and paste the ECID value copied previously into the "Identity value" field.
11.	Click into Profile ID
 
<kbd><img src="./images/identities-ECID AEP.png"  /></kbd>
 <kbd><img src="./images/completed_linked profile_travel.png"  /></kbd>

Return to [Lab Agenda Directory](https://github.com/adobe/AEP-Hands-on-Labs/blob/master/labs/travel/README.md#lab-agenda)
