<p><strong>UiPath &ndash; UAC Integration</strong></p>
<p>This Universal Task allows Stonebranch users to schedule, trigger &amp; monitor the UiPath (RPA) process directly from the Universal Controller.&nbsp;</p>
<p><strong>Key Features:</strong></p>
<ul>
<li>This task uses a Python request module to make REST-API calls to the UiPath orchestrator.</li>
<li>It can trigger the RPA process in UiPath using just UiPath process name, orchestrator base URL, UiPath account name and service instance.</li>
<li>The task triggers the UiPath process for execution, monitors until process completion, and populates the results in Universal Controller.</li>
<li>It also features a tight integration with ITSM tools, meaning that it can auto-create incidents in case of UiPath RPA process execution failure.</li>
</ul>
<p><strong>Additional Information:</strong></p>
<p><span style="color: #000000; font-family: Roboto, RobotoDraft, Helvetica, Arial, sans-serif; white-space: pre-wrap;">Please note that the UiPath access token is consumed by this universal task from the Global Variable named : Uipath_access_token , You may update the access token periodically through a web services task.</span></p>


Please visit this link to find key features, prerequisites, installation instructions, configuration instructions, and examples of how to use this integration. 
<a href="https://docs.stonebranch.com/confluence/display/UC69/UAC+-+UiPath+for+UAC+Integration" target="_self">UAC - UiPath for UAC Integration</a>.&nbsp;</li>
