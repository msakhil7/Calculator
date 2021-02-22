**Calculator Exercise details:**
Create a web API (using any programming languages) which logs calculations as they happen and shares those calculations with everyone connected to the website.
 
For example, user A and user B request the stream of calculations from your API at the same time. User A sends a request to calculate "5 + 5", which equals "10". This is streamed to both users as "5 + 5 = 10". User B is updated about this calculation right after user A posts it. Now, user B calculates "3 x 4". This calculates to “12”. User A sees this update as "3 x 4 = 12" immediately after user B posts it.
 
Results should remain between sessions. Only show the last 10 calculations descending from most recent to oldest. This exercise is language agnostic.

**Technologies Used:**
HTML, CSS, Javascript, AWS EC2, SQLITE3 Database

**EC2 Instace used:**
RedHat Linux 8

**How to install:**
sudo yum install python3-pip -y
sudo yum install python36
sudo yum install git
sudo yum install sqlite
sudo pip3 install flask
