---
title: Home
layout: default
---

<h2>Introduction</h2>
<p>AppReliance is a tool for verifying a .NET assembly can resolve all of its dependencies. This project came about as part of a Quality Assurance drive where Visual Studio does implicit references, or uses the Global Assembly Cache during the build and thus doesn't include all the necessary files into the output folder.</p>
<p>This tool has been designed to be used as a standalone command line tool, which can also be used as part of a build script.</p>
<h2>Getting Started</h2>
<h3>Downloading AppReliance</h3>
<div class="alert">
<p>If you downloaded AppReliance from somewhere other the <a href="http://appreliance.codeplex.com">Codeplex project</a> or <a href="https://github.com/dhgms-solutions/appreliance">Github Project</a> please check your download.  There are various mirrors on advert driven download sites who are hosting a copy without our involvement, due to the license they're not required to get our permission. Codeplex and Github are the only sites where we have control of the content of the download, we can not guarantee modifications, malicious or otherwise have not been carried out on other mirrors.</p>
</div>
<p>AppReliance is available from the <a href="http://appreliance.codeplex.com/releases/">CodePlex Release Page</a>.</p>
<h3>Running the console application</h3>
<p>AppReliance has a single command line argument which is the filename of the assembly you wish to validate.</p>
<h2>Roadmap</h2>
<p>Coming soon</p>
<h2>Future Possibilities</h2>
<ul>
  <li>Output the report to XML or Text file.</li>
  <li>GUI Desktop application.</li>
</ul>