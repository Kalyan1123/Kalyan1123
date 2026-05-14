<h1 align="center">Hi 👋, I'm Kalyan Chary</h1>
<h3 align="center">A passionate Software Engineer from India</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=kalyan1123&label=Profile%20views&color=0e75b6&style=flat" alt="kalyan1123" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=kalyan1123" alt="kalyan1123" /></a> </p>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/https://www.linkedin.com/in/kalyan-chary-5502ab273/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/kalyan-chary-5502ab273/" height="30" width="40" /></a>
<a href="https://instagram.com/https://www.instagram.com/kalyan_____________/?utm_source=ig_web_button_share_sheet" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="https://www.instagram.com/kalyan_____________/?utm_source=ig_web_button_share_sheet" height="30" width="40" /></a>
<a href="https://www.leetcode.com/https://leetcode.com/u/rkalyanchary423/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="https://leetcode.com/u/rkalyanchary423/" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.oracle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=kalyan1123&show_icons=true&locale=en&layout=compact" alt="kalyan1123" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=kalyan1123&show_icons=true&locale=en" alt="kalyan1123" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=kalyan1123&" alt="kalyan1123" /></p>



..
....


Step 1 — Configure the Trigger
You'll now see the trigger card open.

Site Address → Select your SharePoint site from the dropdown
Library Name → Select your VTT transcription document library


Step 2 — Add a Condition

Click "+ New step"
Search for "Condition"
Select the Condition control action
In the condition box, click on the first field (left side)
Click "Expression" tab in the dynamic content popup
Paste this:

triggerOutputs()?['body/{FilenameWithExtension}']

Click OK
The middle dropdown — set it to "ends with"
In the right field, type:

.vtt

Everything from this point goes inside the "If yes" branch


Step 3 — Get File Content

Inside the "If yes" branch, click "Add an action"
Search for "Get file content using path"
Select "Get file content using path — SharePoint"
Site Address → Select your SharePoint site
File Path → Click the field, go to Dynamic content tab, and select "Full Path"


Step 4 — Compose: Decode VTT Content

Click "Add an action"
Search for "Compose"
Select "Compose — Data Operation"
Click on the Inputs field
Go to Expression tab and paste:

base64ToString(body('Get_file_content_using_path')?['$content'])

Click OK
Rename this Compose step to Decode VTT Content

Click the three dots (...) on the top right of the card → Rename




Step 5 — Compose: Split Lines

Click "Add an action"
Add another Compose action
Click the Inputs field
Go to Expression tab and paste:

split(outputs('Decode_VTT_Content'), decodeUriComponent('%0A'))

Click OK
Rename this step to Split Lines


Step 6 — Filter Array

Click "Add an action"
Search for "Filter array"
Select "Filter array — Data Operation"
In the From field → go to Expression tab and paste:

outputs('Split_Lines')

Click OK
Now click "Edit in advanced mode" (small link below the condition row)
Replace whatever is there with:

@and(
  not(contains(item(), '-->')),
  not(equals(trim(item()), 'WEBVTT')),
  not(equals(trim(item()), ''))
)

Click OK


Step 7 — Compose: Join Clean Text

Click "Add an action"
Add another Compose action
Click the Inputs field
Go to Expression tab and paste:

join(body('Filter_array'), decodeUriComponent('%0A'))

Click OK
Rename this step to Clean Text


Step 8 — Compose: Build TXT Filename

Click "Add an action"
Add another Compose action
Click the Inputs field
Go to Expression tab and paste:

concat(replace(triggerOutputs()?['body/{FilenameWithExtension}'], '.vtt', ''), '.txt')

Click OK
Rename this step to TXT Filename


Step 9 — Create File in TXT Library

Click "Add an action"
Search for "Create file"
Select "Create file — SharePoint"
Site Address → Select your SharePoint site
Folder Path → Type the name of your TXT document library

Example: /Transcriptions-TXT
Or click the folder icon to browse and select it


File Name field → Go to Expression tab and paste:

outputs('TXT_Filename')

Click OK
File Content field → Go to Expression tab and paste:

outputs('Clean_Text')

Click OK













✅ STEP 1 — Trigger: When an agent calls the flow
FieldValueTrigger NameWhen an agent calls the flowInput NameTranscriptFileNameInput TypeTextDescriptionName of the transcript file sent by the agent

✅ STEP 2 — Compose: Strip .txt & Build Video Filename
Action: Data Operation → Compose
FieldValueAction NameCompose_VideoFileNameInputs (expression)concat(replace(triggerBody()?['text'], '.txt', ''), '.mp4')

This takes PowerApps_Basics.txt → strips .txt → adds .mp4 → gives PowerApps_Basics.mp4


✅ STEP 3 — Get Files (Properties Only): Find the MP4
Action: SharePoint → Get files (properties only)
FieldValueSite Addresshttps://organizationcloud.sharepoint.com/teams/powerhubLibrary NameShared DocumentsFolderRecorded Tutorials/Webinar Recordings/PublishedFilter QueryFileLeafRef eq '@{outputs('Compose_VideoFileName')}'Top Count1

✅ STEP 4 — Create Sharing Link
Action: SharePoint → Create sharing link for a file or folder
FieldValueSite Addresshttps://organizationcloud.sharepoint.com/teams/powerhubLibrary NameShared DocumentsItem IDfirst(body('Get_files_(properties_only)')?['value'])?['ID']Link TypeViewLink ScopeOrganization

✅ STEP 5 — Compose: Build Final Message
Action: Data Operation → Compose
FieldValueAction NameCompose_FinalResponseInputsbody('Create_sharing_link')?['sharingLinkInfo']?['Url']

✅ STEP 6 — Return Value to Agent
Action: Return value(s) to Power Virtual Agents
Output NameTypeValueVideoLinkTextoutputs('Compose_FinalResponse')

📌 Quick Reference — Your SharePoint Details
ValueSite Addresshttps://organizationcloud.sharepoint.com/teams/powerhubTranscripts FolderPrivate Documents/Events/Demo/Registration DataRecordings FolderRecorded Tutorials/Webinar Recordings/PublishedLibrary Name (both)Shared Documents


You are a learning assistant for PowerHub. Search through session transcripts to answer user questions. Always provide the relevant video recording link along with your answer.


GLW-Switching from Tableau to PBI.txt



concat('https://organizationcloud.sharepoint.com/', items('For_each')?['{Path}'])


concat('https://organizationcloud.sharepoint.com/', items('For_each')?['{FullPath}'])


concat('https://organizationcloud.sharepoint.com/teams/powerhub/', replace(items('For_each')?['{FullPath}'], ' ', '%20'))



items('For_each')?['{Link}']


Hi Sailaja,

As you know, I created both of the flows that are currently running — one to convert the existing .vtt files to .txt files, and another to fetch the correct recording links.

Unfortunately, Ashrita made changes in SharePoint without informing me earlier. She moved the existing test folder’s .vtt content into a new folder called “Transcription Files.” If this change was already planned or known, I really wish I had been informed before I started creating and configuring these flows. It would have saved a lot of time and effort.

Because of this sudden change, both of the flows have now crashed, and I need to reconfigure everything again from the beginning. I’m honestly very frustrated and disappointed, as a lot of work has been impacted due to a change that was not communicated in advance.



endswith(triggerOutputs()?['body/{FilenameWithExtension}'], '.vtt')
