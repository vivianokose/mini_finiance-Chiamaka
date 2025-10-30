# Mini Finance Footer Deployment Log

## Sprint 1 Goal
Ship a visible Mini Finance footer (version + date + author) to EC2 and document progress daily.

### Daily Updates
- **Day 1:** Added static footer and deployed to EC2.
- **Day 2:** Made date dynamic using JavaScript.
	- Implemented JS script (`js/footer.js`) to auto-display today’s date.
	- Footer now updates automatically each deployment.
	- Verified on EC2 and updated README with code snippet.
- **Day 3:** Improved accessibility (contrast, spacing).
	- Adjusted font size and background for better contrast.
	- Verified responsive layout on mobile and desktop.
	- Passed AA contrast ratio test (manual visual check).
- **Day 4:** Added revision hash and /healthz endpoint.
	- Added `/healthz.html` returning “OK” to verify site uptime.
	- Tested via browser and curl command.
	- Deployed successfully to EC2.
- **Day 5:** Recorded demo and captured Burndown Chart.
    - Recorded final 2–3 min demo of deployed EC2 instance.
    - Shared reflections in Jira: what went well, what to improve, pillar/value.
    - Captured Jira board and burndown chart for final submission.
