# Lambda_Layers_requests
using requests Library as a Layer

Lambda function that uses the 'requests' library provided by a Lambda layer.

Steps:
1. Remove any previous python directories that are there, and Create a new Python directory.
   We are creating this because Lambda searches for all the libraries/depenencies from python directory,

   mkdir python
   

   <img width="560" height="202" alt="Screenshot 2026-06-22 093035" src="https://github.com/user-attachments/assets/b21e6aea-e102-490c-a660-a68d3e986a91" />

2. Install Package into current directory (' . ')
   pip install requests -t .

   
   <img width="661" height="242" alt="Screenshot 2026-06-22 093139" src="https://github.com/user-attachments/assets/4e5f28c6-dbd4-4370-bca3-36e775ef280b" />

3. check if  requests is installed
   
   <img width="655" height="175" alt="Screenshot 2026-06-22 093207" src="https://github.com/user-attachments/assets/4f965906-87d3-4b80-a527-8dd26c7485db" />


4. Zip the Layer

   <img width="648" height="344" alt="Screenshot 2026-06-22 093354" src="https://github.com/user-attachments/assets/a1b8e920-3c6c-410a-9ba7-bafc806d9064" />

5. check if requests.zip is there
   
   <img width="506" height="76" alt="Screenshot 2026-06-22 093438" src="https://github.com/user-attachments/assets/62600be5-7ee2-40c1-98d8-33325d18aae4" />

6. Create the iam role
   
   <img width="442" height="118" alt="image" src="https://github.com/user-attachments/assets/9775b6cf-5ce6-4f34-9142-9eb232c3eb8c" />

   o/p will be as below, iam role is created :

   <img width="611" height="252" alt="image" src="https://github.com/user-attachments/assets/2fac2983-5d46-4d28-bdd5-459b2ce0d25e" />

7. Attach a policy

   aws iam attach-role-policy \
  --role-name LambdaLayersExecutionRole \
  --policy-arn arn:aws:iam::aws:policy/service-role/AWSLambdaBasicExecutionRole

   <img width="500" height="38" alt="Screenshot 2026-06-22 125009" src="https://github.com/user-attachments/assets/ac5833a8-3de4-49dd-b8d3-df0240cee673" />


9. verify the role and details in a tabuar form

   <img width="588" height="139" alt="image" src="https://github.com/user-attachments/assets/42c89db3-118b-4e49-83cd-fdc4071be62b" />




   





