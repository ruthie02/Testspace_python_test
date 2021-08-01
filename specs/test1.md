---
testspace:
---

# my_spec_1

<h1>Test1</h1>
This is the 1st test. 

<h2>Test Cases <h2>
Convert geographic to PRS/PTM. 

<li>Navigate to google, and search for the geographic coordinates of Albay.</li>
<li>Copy these coordinates. NEL: 13.1391° N, 123.7438° E, 12.52 m</li>
<li>To validate the results, go to Propeller Coordinates converter.</li>

---
testspace:
before:
  name: github::setup
  input:
    on: "setup is on"
---