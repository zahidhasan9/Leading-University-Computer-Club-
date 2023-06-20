## demo







# Leading-University-Computer-Club-

Leading university Computer Club website would offer benefits to both advisor and members. Student can register to be as members by using web application. Admin can control the action of the members.

This online club website has the following benefits for member and club: 

	LUCC website saves time: Students do not have to stand in queues in club’s booth  to register for their membership. They can register from their anywhere and do not have to spend time standing in the queue.

	Management: The admin panel can have their control over the members. They can add or remove members as they wish. 

	Availability: The website is open on 365x24x7. So, time does not act as a barrier, wherever the admin and members.

	Online tracking: The club can track down their members information and status.

	Online payment: The member can make payment on the events and membership in online.

	No pressure joining: Generally, in club’s booth, the club representatives try to influence the students to join the club. On the online website the student can choose to join if he or she wants or not.

	Less waiting: The student do not have to wait a long time for registration, payment or any kind of information.


Project Module
The project we build has specific module for Super-admin, Admin, User. We going to discuss
about the feature that includes in these modules.
3.2.1 For Super-Admin
1. Super admin has all access about the website.
2. Super admin can add new admin.
3. Super admin can remove admin.
4. Super admin can everything the admin can do.
3.2.2 For Admin
1. Admin sign/ sign out.
2. Admin Dashboard.
3. Admin can approve user.
4. Admin can delete user.
5. Admin can add and delete sponsor.
6. Admin can activate and deactivate user status.
7. Admin can manage events.
8. Admin can set countdown time before the events started.
9. Admin can filter the user data stored in the database.
10. Admin can set counter information for member, advisor, committee member.
-8-11. Admin can set rank of user based on the committee.
12. Admin can set schedule and provide pdf download link for the events.
3.2.3 For User
1. User sign/ sign out.
2. User can view information of advisor, founder and committee members.
3. User can edit own profile.
4. User can make payment using transaction id from (bKash,Nagad, Rocket).
5. User can provide blood group information as well as can get blood group information in the
time of need.
6. User can participate directly in the events without registering specifically for the event like
outsides do.
7. User can check if they are approved in the events or not solely by visiting the website.

3.3 Features
The Leading University Computer Club has some exclusive features solving the problem we
mentioned above. In this section we are going to talk about those features in detail.

3.3.1 Registration and Login
This is one of the most needed feature in an website. Our website also have its own login and
registration process. Every single module have their own particular login and registration system.
The users can login the user-site and the admin has different site to login with.

3.3.2 Search Filter
Searching is one of the most crucial features in today’s websites. The user can search by using
the name or the id to search for their specific individual.

-9-3.3.3 Admin Authority
Our website has a separate admin panel for our admin from where the admin can control user
actions, events, payments and other extra functions. Admin has the power to add and remove users
on behalf of their actions.

3.3.4 Super-admin Authority
There is another role above admin and that is super-admin. A super-admin has the ability to
make someone an admin and remove them from the admin. This is the key feature of super-admin.
A super-admin can perform all the work that an admin can do.

3.3.5 Events Registration
The Leading University Computer Club organizes several events every year. A huge number of
participants tried to attend the events. The user can submit their registration through a form. The
users can give their information such as their name, team name, email, phone number and what
event they want to participate. Then the admin can manage the event according to their response.

3.3.6 Instant Payment
The user can give their payment information through transaction id in the form. The admin
then can approve the participant while verifying the information. The user can check their status
by visiting the website to see if they can join the events.

3.3.7 Differentiate Users
There are many participants join in the other than the member of the club. So, we made a
distinct section for each. There is two separate section. One for the members of the club who
participate in the events, and the other one is those who joins from outside. The partition is created
for admin so he know who is club member and who is not while having the events.

-10-3.3.8 Security
Security is one of the most crucial features of any website. We added some special security for
our website. We used JWT (Json Web Token) to authenticate. When the user is valid, the token is
generated. JWTs use commonly signed using algorithms: HS256 (HMAC using SHA256). If the
token returns true, the data will be sent from the back-end. The token that generates keeps the user
from logging out automatically for a certain time phase unless the user themselves wants to log out.
The event module has a payment system where the chosen contestants can make their payment via
transaction id But they can not use the transaction id for different payment. Since our website does
not have a merchant site, we created the rule where the user can use their transaction id for once.

3.3.9 Blood Group Information
The website has a particular section about blood information where users can find other blood
group information and share their own blood information so anyone can use that information in the
time of need. There are several times people need a certain type of blood; they run here and there
in search of that particular blood type to save their loved once from certain death and illness. The
main objective of creating this segment of this website is to help those individuals while they need
it the most.
![image](https://user-images.githubusercontent.com/44033232/221378454-fcf217e8-6c9c-4fc7-a3a9-a64a931745a5.png)
