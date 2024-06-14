<h1>Postmortem</h1>

<p>This project contains tasks for learning about writing a postmortem.</p>

<h2>0. My first postmortem</h2>

<p><strong>Blog_Post.md</strong> contains a blog post that meets the following requirements:</p>

<h3>INFO:</h3>

<p>Using one of the web stack debugging project issues or an outage you have personally faced, write a postmortem. Most of you will never have faced an outage, so just get creative and invent your own :)</p>

<p>While postmortem format can vary, stick to this one so that you can get properly reviewed by your peers.</p>

<h4>Requirements:</h4>

<ul>
  <li><strong>Issue Summary</strong> (that is often what executives will read) must contain:
    <ul>
      <li>Duration of the outage with start and end times (including timezone).</li>
      <li>What was the impact? (What service was down/slow? What were user experiencing? How many % of the users were affected?)</li>
      <li>What was the root cause?</li>
    </ul>
  </li>
  <li><strong>Timeline</strong> (format bullet point, format: time - keep it short, 1 or 2 sentences) must contain:
    <ul>
      <li>When was the issue detected?</li>
      <li>How was the issue detected (monitoring alert, an engineer noticed something, a customer complained…)</li>
      <li>Actions taken (what parts of the system were investigated, what were the assumption on the root cause of the issue).</li>
      <li>Misleading investigation/debugging paths that were taken.</li>
      <li>Which team/individuals was the incident escalated to?</li>
      <li>How the incident was resolved.</li>
    </ul>
  </li>
  <li><strong>Root cause and resolution</strong> must contain:
    <ul>
      <li>Explain in detail what was causing the issue.</li>
      <li>Explain in detail how the issue was fixed.</li>
    </ul>
  </li>
  <li><strong>Corrective and preventative measures</strong> must contain:
    <ul>
      <li>What are the things that can be improved/fixed (broadly speaking).</li>
      <li>A list of tasks to address the issue (be very specific, like a TODO, example: patch Nginx server, add monitoring on server memory…).</li>
    </ul>
  </li>
</ul>

<p>Be brief and straight to the point, between 400 to 600 words.</p>

<h2>1. Make people want to read your postmortem</h2>

<p>We are constantly stormed by a quantity of information, it’s tough to get people to read you.</p>
