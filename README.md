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

split(outputs('Compose_RawText'), decodeUriComponent('%0A'))


outputs('Compose_Lines')

@and(
  greater(length(trim(item())), 0),
  not(contains(item(), '-->')),
  not(equals(trim(item()), 'WEBVTT')),
  or(
    contains(toLower(item()), 'a'),
    contains(toLower(item()), 'e'),
    contains(toLower(item()), 'i'),
    contains(toLower(item()), 'o'),
    contains(toLower(item()), 'u')
  )
)



Step 9: Add Compose Oneline
Below Filter TextLines, + Add an action → Compose.
FieldValueInputsExpression: join(body('Filter_TextLines'), ' ')
Rename to: Compose Oneline
Step 10: Add Create TXT File
Below Compose Oneline, + Add an action → SharePoint → Create file.
FieldValueSite AddressSame siteFolder PathClick the folder picker icon 📁 → browse to AllTranscripts_TXT (your target folder)File NameExpression: replace(string(triggerOutputs()?['body/{FilenameWithExtension}']), '.vtt', '.txt')File ContentExpression: outputs('Compose_Oneline')




{
  "id": "@{item()?['Session ID']}",
  "technology": "@{item()?['Technology']}",
  "query": "@{item()?['Query']}",
  "solution": "@{item()?['Solution']}",
  "articles": "@{item()?['MyHub Assist Articles']}"
}





You match a user question against a knowledge base of past Q&A pairs.

   User question:

   Knowledge base entries (JSON array):


Task:
   - Find the entry whose "query" best answers the user's question.
   - A strong match means the user's intent clearly aligns with the entry's query, not just shared keywords.
   - If a strong match exists, respond ONLY with this exact JSON shape:
     {"matchFound": true, "solution": "<solution text>", "articles": "<articles text or empty string if none>"}
   - If no entry strongly matches, respond ONLY with:
     {"matchFound": false, "solution": "", "articles": ""}

   Do not add markdown, code fences, or any text outside the JSON.


how do I set up a connection in a dedicated environment


[{"id":"1","query":"setup connections in dedicated environment","solution":"Use a service account for connections. Once created, you do not need to recreate it unless new connections are added.","articles":"https://myhub.example.com/article/123"}]

@contains(toLower(item()?['query']), toLower(triggerBody()['text']))


{
    "matchFound": true,
    "solution": "sample solution text",
    "articles": "https://example.com"
  }


@contains(toLower(item()?['query']), toLower(triggerBody()['text']))




if(empty(body('Find_Match')), json('{"matchFound":false,"solution":"","articles":""}'), json(concat('{"matchFound":true,"solution":', string(first(body('Find_Match'))?['solution']), ',"articles":', string(first(body('Find_Match'))?['articles']), '}')))
