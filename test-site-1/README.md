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
