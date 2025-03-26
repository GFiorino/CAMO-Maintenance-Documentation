<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="../styles.css">
</head>
<body>
  <main>
    <h1>AMP Update Procedure</h1>

   <h2>Overview</h2>
    <p>The <strong>Aircraft Maintenance Programme (AMP)</strong> defines all mandatory and recommended maintenance tasks required to keep an aircraft airworthy. Over time, the AMP must be updated due to regulatory changes, manufacturer revisions, or in-service experience.</p>

   <p>This document outlines how a CAMO Technical Administrator supports AMP updates in compliance with <strong>EASA Part-M</strong> and <strong>Part-CAMO</strong> regulations.</p>

   <h2>Why AMP Updates Are Needed</h2>
    <ul>
      <li><strong>Manufacturer revisions</strong> (e.g., updated Maintenance Planning Document)</li>
      <li><strong>New Airworthiness Directives (ADs)</strong></li>
      <li><strong>Operational changes</strong> (e.g., usage in harsher environments)</li>
      <li><strong>Regulatory updates</strong> or authority findings</li>
      <li><strong>Corrective actions</strong> after audits or ARC reviews</li>
    </ul>

  <h2>AMP Update Workflow</h2>

   <h3>1. Identify the Change</h3>
    <p>Example triggers:</p>
    <ul>
      <li>New AD requiring repetitive inspections</li>
      <li>OEM increases lubrication interval from 500FH to 600FH</li>
    </ul>

  <h3>2. Analyze Impact</h3>
    <ul>
      <li>Engineering reviews safety implications</li>
      <li>Check for overlap with existing AMP tasks</li>
      <li>Determine if change is <strong>mandatory</strong> or <strong>optional</strong></li>
    </ul>

   <h3>3. Determine Approval Path</h3>
    <table>
      <thead>
        <tr><th>Type of Change</th><th>Approval Required</th></tr>
      </thead>
      <tbody>
        <tr><td>Major (e.g., new AD)</td><td>Direct authority approval</td></tr>
        <tr><td>Minor (e.g., task interval tweak)</td><td>Indirect approval (if CAMO has privilege)</td></tr>
      </tbody>
    </table>

  <h3>4. Draft the Revision</h3>
    <ul>
      <li>Add, remove, or revise affected task(s)</li>
      <li>Update revision log:
        <pre>Rev 3 – Added engine oil check at 400FH (OEM SB 79-001), interval change on task 32-11-02</pre>
      </li>
    </ul>

  <h3>5. Review and Approve</h3>
    <ul>
      <li>Internal review by Continuing Airworthiness or Quality Manager</li>
      <li>Submit to authority if required, or process under indirect approval</li>
    </ul>

  <h3>6. Implementation</h3>
    <ul>
      <li>Notify Maintenance Planning and update schedule</li>
      <li>Inform maintenance provider of new tasks</li>
      <li>Upload revised AMP to control system</li>
      <li>Archive previous revision properly</li>
    </ul>

   <h3>7. Example: AMP Revision Log</h3>
    <table>
      <thead>
        <tr><th>Revision</th><th>Date</th><th>Summary</th><th>Approval Type</th></tr>
      </thead>
      <tbody>
        <tr><td>Rev 3</td><td>2025-03-10</td><td>Added 400FH oil check; extended flap lube to 600FH</td><td>Indirect (QA)</td></tr>
        <tr><td>Rev 2</td><td>2024-08-22</td><td>Initial AMP for A320 MSN12345</td><td>Direct (CAA)</td></tr>
      </tbody>
    </table>

   <h2>Key Takeaways</h2>
    <ul>
      <li>All AMP changes must be traceable and approved per EASA rules</li>
      <li>Documentation must include revision history and effective date</li>
      <li>CAMO Admin supports the process by updating files and notifying teams</li>
    </ul>

  <blockquote><strong>✈️ Proper AMP control ensures continued safety and compliance — a cornerstone of CAMO operations.</strong></blockquote>
  </main>
</body>
</html>
