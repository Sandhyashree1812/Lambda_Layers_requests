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

   





