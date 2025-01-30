# OKTA-Identity-Access-Management-IAM-

Set up user profiles and rules in Okta to ensure secure access for Alexandra Cooper account.
   
   Use Case 1

![Image](https://github.com/user-attachments/assets/1cf9ce13-6bee-43d2-a9f3-c21f03b7e4e2)


NOTE: Copy, paste, and log in to the ORG1 and ORG2 links in the Info Tab. Both ORG1 and ORG2 share the same username and password.

![Image](https://github.com/user-attachments/assets/2570f8bb-d9c2-41e2-aa10-b2e48bce6893)


1.	Log in to your assigned Org 1 as User Admin using the credentials provided. Using the table, create the Alexandra Cooper account.


OKTA-> Directory-> People -> Add Person (Fill out name accordingly), then save.

![Image](https://github.com/user-attachments/assets/35e6e2b4-6b43-43fe-a99b-7ee415404049)


2.	After creating the account, please ensure that Alexandra can log in using the password Testme321!
   
Sign-out of Account (Account 1), resigned into the account with login credentials and password.

![Image](https://github.com/user-attachments/assets/13a5f27e-c21d-493b-97de-21a34fe1b7c1)

3.	Create a new read-and-write attribute with a display name of Preferred Name and a variable name of preferredName.(SIGN in to ADMIN ACCOUNT)

Sign out of Alexandria Cooper (Account 1) and sign in as admin. Click on the INFO tab for the admin credentials. Login:

![Image](https://github.com/user-attachments/assets/8efcf3ed-4f15-43ce-bed9-2d8ea5b2d195)

Click ADMIN on top right ->, go to USER 1 for Alexender Cooper credential.











 **Access Directory**
   - Go to "People" and select "Alexender Cooper."

 **Edit Profile**
   - Open Profile Editor and go to User Default.

 **Add Attributes**
   - Copy "Preferred Name" into "Displayed Name."
   - Paste “preferredName” into the variable name box.

![Image](https://github.com/user-attachments/assets/51a0a93c-c2cd-412e-b9e3-b1051fb16288)

**Finalize**
   - Check "Read-Rite" and save changes.
  
![Image](https://github.com/user-attachments/assets/bb3babb3-cc20-4924-b331-c884d3f2feb0)

**Verify Updates**

4. Edit Alexandra’s OKTA profile and update the following Attributes (Stay in the Admin Account, Access Alexandra Account):

![Image](https://github.com/user-attachments/assets/486a13c0-6cb2-495b-94b7-0d5854a1e6ac)


Directory -> People -> Alexandra Cooper -> (FILL IN WITH LISTED CREDENTIAL) -> SAVED

![Image](https://github.com/user-attachments/assets/b43a7c2b-1fe2-4d1b-8b4b-051f4fa4eeaa)


5.	Create an OKTA group based on the following:

![Image](https://github.com/user-attachments/assets/275bb649-3ab8-4a84-953b-d4ebdbade535)


Directories -> Groups -> ADD GROUP -> enter the group name and description accordingly in the row ‘Contractor | All Contractors. Save. Here is a picture:

![Image](https://github.com/user-attachments/assets/e5547bb9-37ad-45df-98f1-31fba0c97964)


6.	Using the Division attribute of Contractors, define logic in OKTA to filter users with the attribute defined into the Contractors group. Verify that Alexandra has been added to the Contractors group using this definition. NOTE: She should not be added to the group manually. (Stay in ADMIN).
   
Directory -> Groups -> Rules -> ADD RULES

![Image](https://github.com/user-attachments/assets/7436093f-5577-4a7c-b2dd-35e037c7f10b)

ADD RULES 

![Image](https://github.com/user-attachments/assets/f6742fc9-3850-44c6-b4de-36e89aa03167)

Attribute/Name: Contractors Rule->

![Image](https://github.com/user-attachments/assets/1a617fac-8c6a-4b63-9500-4c50820cc605)

IF: ![Image](https://github.com/user-attachments/assets/e6c13146-f389-4c27-aec1-5e374f963636)


THEN ASSIGN TO: ![Image](https://github.com/user-attachments/assets/6fb4af27-28f4-4eb0-b6c2-215a64e6bc14)


Save: 

![Image](https://github.com/user-attachments/assets/5c32d1e7-3d4b-45be-aa30-66793567e6a8)

Click INACTIVATE to ACTIVATE:

![Image](https://github.com/user-attachments/assets/bb4c3a65-ae68-4588-a09d-2da4c142e124)











