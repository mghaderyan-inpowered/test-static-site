test details:

test type: local
benji environment: dev
user credentials:
username: site_owner_21
password: site_owner_21

customerId: 2623
campaignId: 19014

pages:
http://localhost.com:8080/test-site-1/page1.html
http://localhost.com:8080/test-site-1/page2.html
http://localhost.com:8080/test-site-1/page3.html

scenario 1: no frequency option -> should show next action as ususal
scenario 2: page level frequency option -> should show next action as ususal across pages but in each page it should respect the frequency

---

test type: qa
benji environment: qa
user credentials:
username: siteowner2
password: (same as prod)

customerId: 3143
campaignId: 39120

pages:
https://mghaderyan-inpowered.github.io/test-static-site/test-site-qa/page1.html
https://mghaderyan-inpowered.github.io/test-static-site/test-site-qa/page2.html
https://mghaderyan-inpowered.github.io/test-static-site/test-site-qa/page3.html
