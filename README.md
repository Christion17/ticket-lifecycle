<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket - Ticket Lifecycle (Intake to Resolution)</h1>

<p>
This project demonstrates the full lifecycle of a support ticket within <b>osTicket</b>, from initial intake through assignment, escalation, and resolution.
</p>

<p>
The objective is to simulate a real-world IT support workflow by handling a business-critical incident and applying proper prioritization, communication, and resolution practices.
</p>

<br />

<h2>Environment</h2>
<ul>
  <li>Microsoft Azure (Virtual Machine)</li>
  <li>Windows 10</li>
  <li>Remote Desktop</li>
  <li>osTicket</li>
</ul>

<br />

<h2>Ticket Lifecycle Overview</h2>
<ul>
  <li><b>Intake</b> – Ticket is created by the end user</li>
  <li><b>Assignment & Triage</b> – Priority, SLA, and ownership are defined</li>
  <li><b>Work & Communication</b> – Issue is investigated and updates are provided</li>
  <li><b>Resolution</b> – Issue is resolved and ticket is closed</li>
</ul>

<br />

<h2>Scenario: Business Critical Outage</h2>
<ul>
  <li><b>Issue:</b> Mobile online banking system is down</li>
  <li><b>Impact:</b> Customers unable to access services (revenue impact)</li>
  <li><b>Severity:</b> SEV-A (highest priority)</li>
</ul>

<br />

<h3>1. Ticket Intake</h3>
<ul>
  <li>User submits a new ticket through the osTicket portal</li>
  <li>Help Topic: <b>Business Critical Outage</b></li>
  <li>Issue Summary: Mobile banking system unavailable</li>
  <li>This classification ensures the ticket is routed appropriately and treated with urgency</li>
</ul>

<br />

<h3>2. Assignment and Triage</h3>
<ul>
  <li>Agent reviews the ticket</li>
  <li>Priority set to <b>Emergency</b> based on business impact</li>
  <li>SLA Plan assigned: <b>SEV-A (1 hour response time)</b></li>
  <li>Ticket assigned to <b>System Administrators</b></li>
  <li>This step establishes ownership and aligns response expectations with severity</li>
</ul>

<br />

<h3>3. Working the Issue</h3>
<ul>
  <li>Agent begins investigation and coordinates with appropriate teams</li>
  <li>Progress updates are communicated to the user</li>
  <li>Example: “Currently working with SysAdmins to restore service”</li>
  <li>Clear communication improves transparency and user trust</li>
</ul>

<br />

<h3>4. Resolution</h3>
<ul>
  <li>Root cause identified and resolved (e.g., infrastructure issue)</li>
  <li>Service is restored</li>
  <li>User is notified of resolution</li>
  <li>Ticket status updated to <b>Resolved</b> and then closed</li>
</ul>

<br />

<h2>Decision Breakdown</h2>
<ul>
  <li><b>Why SEV-A?</b> → Customer-facing outage with direct business impact</li>
  <li><b>Why System Administrators?</b> → Issue relates to infrastructure/backend systems</li>
  <li><b>Why 1-hour SLA?</b> → Critical service requires rapid response time</li>
</ul>

<br />

<h2>Key Takeaways</h2>
<ul>
  <li>Ticket priority should reflect business impact, not just technical difficulty</li>
  <li>SLAs enforce accountability and response expectations</li>
  <li>Effective communication is critical throughout the lifecycle</li>
  <li>Proper routing ensures issues are handled by the correct team</li>
  <li>Resolution includes both technical fix and user-facing communication</li>
</ul>

<br />

<h2>What This Demonstrates</h2>
<ul>
  <li>Understanding of end-to-end ticket lifecycle management</li>
  <li>Ability to prioritize incidents based on business impact</li>
  <li>Experience with SLA-driven support workflows</li>
  <li>Practical application of osTicket in a simulated IT environment</li>
</ul>

<br />

<h3 align="right">
Previous Project - 
<a href="https://github.com/Christion17/post-install-config">
osTicket - Post-Install Configuration
</a>
</h3>
