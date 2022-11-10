![](/images/ahlsbanner.png)
<h1 id='CaOACAwxHHG'>A-HLS - DataRaptor Library Documentation - DRgetDocumentTemplates</h1>

<i>This DataRaptor acts as a base for developers to get information about available 'Active Document Templates'.</i><br/>

<hr style='width:100%'><h2 id='CaOACAJtWvK'>Overview</h2>

A DataRaptor is a mapping tool to help read, transform, and write Salesforce data. There are four types of DataRaptors: <span style="color:#1e1e1c" textcolor="#1e1e1c">Turbo Extract, Extract, Load, and Transform. You can use these four methods to extract data for digital customer interactions and business processes to present data. </span><br/>

<br/>

The 'DRGetDocumentTemplates' DataRaptor Extract collects meaningful information about specific Available Document Templates that are currently available for use.<br/>

<hr style='width:100%'><h2 id='CaOACA2bZFe'>Business Objective</h2>

The Business objective is to quickly extract information about specific ‘Document Templates’ that can be meaningful to achieve the jobs to be done for a business user or reporting.<br/>

<h2 id='CaOACAq0baj'><span style="color:#333333" textcolor="#333333">Business Value and Benefits</span></h2>

<div style="" data-section-style='5' class=""><ul id='CaOACAWVnqf'><li id='temp:C:CaOfdf3fef7118a432d9f7b0daf1' class='' value='1'><span style="color:#0e101a" textcolor="#0e101a">Decrease IT costs associated with custom build</span>

<br/></li><li id='temp:C:CaO697f4ece80fc42dbb27a903e8' class=''>Improve user experience

<br/></li></ul></div><hr style='width:100%'><h2 id='CaOACANyujC'>Export-Package Includes</h2>

<h3 id='CaOACALKzrG'><b>DataRaptor (1)</b></h3>

<div style="" data-section-style='5' class=""><ul id='CaOACAKPhNn'><li id='CaOACAM4IAH' class='' value='1'>DRGetDocumentTemplates

<br/></li></ul></div><h2 id='CaOACAmU32a'><b>JSON Reference</b></h2>

<div style="" data-section-style='5' class=""><ul id='CaOACA7zzQa'><li id='CaOACAxabBH' class='' value='1'>{<br>  "DocumentTemplate": {<br>    "Name": "Text",<br>    "VersionNumber": "Text",<br>    "Id": "Text",<br>    "TemplateType": "Text"<br>  }<br>}

<br/></li></ul></div><hr style='width:100%'><h2 id='CaOACAedfEI'>Configuration Requirements</h2>

<div style="" data-section-style='5' class=""><ul id='CaOACAoJukd'><li id='CaOACAbCp3q' class='' value='1'>The Data Raptor is ready to be imported and customized. No further base configuration requirements are necessary.

<br/></li></ul></div><h4 id='CaOACA42QKz'>Install the Data Pack</h4>

<div data-section-style='6' class="" style=""><ul id='CaOACA6oCQ6'><li id='CaOACAHQzAY' class='' value='1'>The Data Pack folder in the following GitHub repository contains one (1) DPA Data Pack. Please download the Data Pack and save them to your desktop: <a href="https://github.com/HLS-Accelerate/DataRaptor-Library/tree/main/DRgetDocumentTemplates">https://github.com/HLS-Accelerate/DataRaptor-Library/tree/main/DRgetDocumentTemplates</a>

<br/></li><li id='CaOACASwWs2' class='parent'>Then, complete the following steps to import them into your Salesforce org.

<br/></li><ul><li id='CaOACAsTkFB' class=''>To Import, in your destination Salesforce org, Click on <b>App Launcher</b> → Search for '<b>OmniStudio DataPacks</b>' and click on it.

<br/></li><li id='CaOACAylm25' class=''>Click on '<b>Installed</b>' and on the right side click on '<b>Import from</b>'.

<br/></li><li id='CaOACACXjTm' class=''>Select '<b>From File</b>' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '<b>Install</b>'.

<br/></li></ul><li id='CaOACAbURpV' class=''>More about DataRaptors: <a href="https://trailhead.salesforce.com/content/learn/modules/omnistudio-dataraptors">https://trailhead.salesforce.com/content/learn/modules/omnistudio-dataraptors</a>

<br/></li></ul></div><hr style='width:100%'><h2 id='CaOACAnBi1d'><span style="color:#333333" textcolor="#333333">Assumptions</span></h2>

<div style="" data-section-style='5' class=""><ul id='CaOACAVmbC5'><li id='CaOACACReBT' class='' value='1'>A customer has licenses for Health Cloud and the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.

<br/></li><li id='CaOACADN3vU' class=''>A customer is assuming Salesforce Lightning Experience — not Classic.

<br/></li><li id='CaOACAPPKEr' class=''>Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are available.

<br/></li><li id='CaOACAaHtGm' class=''>The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their branding.

<br/></li></ul></div><h2 id='CaOACA1V5E0'>Installed Packages Requirement</h2>

<div style="" data-section-style='5' class=""><ul id='CaOACASbuia'><li id='CaOACAt4aTt' class='' value='1'>HealthCloud (HealthCloudGA) - Version 236.1 or higher

<br/></li><li id='CaOACA5PPU0' class=''>Vlocity Insurance (vlocity_ins) - Version 890.317 or higher

<br/></li></ul></div><hr style='width:100%'><h2 id='CaOACATlp2v'>Revision History</h2>

<div style="" data-section-style='5' class=""><ul id='CaOACAHk6xk'><li id='CaOACApvcEr' class='parent' value='1'><b>Revision Short Description (May 12, 2022)</b>

<br/></li><ul><li id='CaOACAUJjdP' class=''>Error correction from previous versions to adapt to the new Data Model.

<br/></li><li id='CaOACAucRY7' class=''>Initial export with QA.

<br/></li></ul><li id='CaOACAZIXz3' class='parent'><b>Revision Short Description (June 21, 2022)</b>

<br/></li><ul><li id='CaOACAK0LDx' class=''>Updated Documentation.
