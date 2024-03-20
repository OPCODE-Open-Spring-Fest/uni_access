# About the project
## Introduction of the project
The college's multifunctional card system, aptly named the "Card," serves as a comprehensive solution for various campus needs, including verification, identification, and payment gateways. This innovative system is designed to streamline administrative processes and enhance convenience for students, faculty, and staff.

One of the key features of the Card is that only the admin has the authority to issue these cards, ensuring security and control over their distribution. Each Card prominently displays comprehensive student details on one side, making it easy to identify and verify individuals. This not only helps in maintaining campus security but also facilitates smooth access to various campus facilities and services.

On the reverse side, the Card features a unique payment gateway ID, allowing users to securely make transactions within the campus ecosystem. This feature eliminates the need for multiple cards or accounts for different purposes, simplifying financial transactions for users.

## Uses of the card
1) ID Card: The system provides a multifunctional ID card that serves as a comprehensive solution for various campus needs.

2) Verification: The ID card ensures quick and reliable verification of individuals within the campus ecosystem, enhancing security and convenience.

3) Payment: The ID card features a built-in payment gateway ID, enabling secure transactions within the campus and eliminating the need for separate payment methods.

4) Valid ID Proof: The ID card acts as a valid ID proof, displaying comprehensive student details on one side and a unique ID for payment gateways on the other, ensuring easy identification and verification.

## Functionalities of the card(Solidity part)
1) Data Storage: The system includes a secure data storage feature to store user information safely.The user needs to enter his Name,Roll Number,Batch,Stream,Photo,Signature and aadhar number(this will not be displayed but will be used to generate user_kechhhak).

2) Picture and Signature to NFT: Users can convert their pictures and signatures into non-fungible tokens (NFTs), ensuring their uniqueness and authenticity.

3) Link Account to NFT: Users can link their accounts to their NFTs, providing a secure and verifiable connection between their identity and digital assets.

4) Generate Kechhak256 with Details: The system generates a unique Kechhak256 hash for each userlet's call it user_kechhak, incorporating their details for              identification purposes and this same kechhak will be useful during payment.

5) Admin Contract: An admin-exclusive contract is utilized to generate a unique Kechhak256 hash let's call it admin_kechhak and enter user details securely.

6) User ID and Password Generation: Using the Kechhak256 hash provided by the admin, the system generates a user ID and password. The user ID is unique and can only be generated once, but a "forget password" option is available.

7) Forget Password Process: To reset a password, users can utilize the admin_Kechhak256 hash along with their user ID for authentication.

8) Password Protection: If an incorrect password is entered more than three times, the card is automatically blocked for 24 hours as a security measure.

9) Limited User Details: When a user sends their details, only their name and batch information are visible to maintain privacy.

## Frontend of the card
 
 Frontend of the card : The frontend part of the card will be made in Reactjs, Html and Tailwind CSS .
 
 Front part of the card : The card will be divided of two section, the left section which will contain Profile pucture and signature while the right section will caontain Name,Roll Number,Batch,Stream,Profile picture and sign.

 Back part of the card : The card will be divided into three rows where the topmost part will contain the college logo along with college name , the middle part will display the kechhak(user_lechhak) of the student and this will redirect us to the payment gateway , and the last row will contain the normal guidlines of a normal card.

 ## Backend of the card

 The database for the backend of the card can be made in any framework according to your choice. 
 
