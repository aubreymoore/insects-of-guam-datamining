## Adding Form Elements Dynamically

<https://stackoverflow.com/questions/44167047/how-to-add-a-div-with-bootstrap-form-elements-dynamically>

my form is here:

https://www.w3schools.com/code/tryit.asp?filename=G3SW5IKAP4F1

https://www.w3schools.com/code/tryit.asp?filename=G3SWJDZT3D3X

## Turkle

<http://52.197.249.190:18080/>

## Private Workers

https://www.quora.com/Is-there-a-private-version-or-use-case-for-mechanical-turk-that-could-be-used-internally-for-companies

One way to get an employee-only qual is to set up one that has no test. In this case, you must add approved workers to the list manually. When your employees create a MTurk worker account, you ask them to send you their worker ID, and you add it to the list. A more hands-off method would be to set up a qualifier test with a single question such that only your employees know the answer, essentially a company secret. Using the latter method, Amazon would automatically handle the bookkeeping for the qual.

The final step is to check the box when you create HITs that says that unqualified workers cannot see a preview. That way outsiders do not have access to any corporate informaiton. Of course Amazon employees might be able to see your information, but this is true for lots of cloud-based technologies. If you're really paranoid, you could make an external HIT hosted on your own web site, and use IP checking to only serve it up for Turkers coming from your own corporate IPs.