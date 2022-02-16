# Removing User Profile Windows with Powershell

<h1> HOWTO </h1>
<ol>
	<li>Go to the source [tinyurl.com/wupdel](https://raw.githubusercontent.com/arifams/remove_user_profiles_windows/main/remove_userprofiles.ps1)  </li>
	<li>Save the script.</li>
	<li>Open Powershell as an admin</li>
	<li>Run this script into Powershell</li>
</ol>

<h1>WHY?</h1>
<p>Many reasons of course. For my situation is, a 128Gb HD computer has been logged by approximately more than 20-40 users per month. New windows update takes hard disk space around 1-2 Gb/users. Every update in users computer will took a big chunk of hard disk and makes PC's getting shittier every day (This is client words, not mine hehe). So I need this script to run in our 100+ PC to clean up user profile faster and easier.</p>

<h1>Errors</h1>

<h3>GetException Error</h3>
<p>It means you run Powershell without admin user</p>
