# Logic-App-Dev (Microsoft-Azure) _by Khoj Info.Pvt. Ltd._

## Logic App-2

**What it does:**  
Address validation using an HTTP trigger (if condition)

### 🔹 Steps:
1. Trigger → **"When an HTTP request is received"**  
2. Action → **"Compose Request"**  
3. Condition → **"Address Validation"**  
4. True Branch → **"Response"**  
5. False Branch → **"Response"**  

---

### 🖼 Workflow Design
<img width="915" height="644" alt="image" src="https://github.com/user-attachments/assets/ae671cd5-fda3-4e52-85c6-24c8548be75b" />

---

### 📄 The JSON File
<img width="923" height="260" alt="image" src="https://github.com/user-attachments/assets/c39061b5-fb53-4f4b-a720-aefff588fcda" />

---

### ✅ The Output
<img width="1077" height="557" alt="image" src="https://github.com/user-attachments/assets/d0807a16-b277-4fc8-bc7f-5f10c9c166ab" />  
<img width="1188" height="573" alt="image" src="https://github.com/user-attachments/assets/4499305c-1bf0-411f-8d15-37a26dfcb0d9" />

---
## Logic App-3

**What it does:**  
Order status handling using a **Switch** control and HTTP trigger.

### 🔹 Steps:
1. Trigger → **"When an HTTP request is received"**  
2. Switch → **"Order Status"**  
   - Case 1 → **Released → Response**  
   - Case 2 → **Confirmed → Response 1**  
   - Case 3 → **Return → Response 2**  
   - Default → **Response 3**  


### 🖼 Workflow Design
<img width="1387" height="621" alt="image" src="https://github.com/user-attachments/assets/5ca6ad70-98c3-4078-a402-38e2d2d94529" />

### ✅ The JSON File
<img width="913" height="278" alt="image" src="https://github.com/user-attachments/assets/afa724d6-6f5d-4774-912b-cb3f236de82b" />

### The Output
<img width="1374" height="604" alt="image" src="https://github.com/user-attachments/assets/61de0513-dd6d-4c97-bfcc-0134e4b2687e" />
<img width="1384" height="610" alt="image" src="https://github.com/user-attachments/assets/1ded5429-fd38-4341-ab59-a2b366790d5d" />
<img width="1371" height="616" alt="image" src="https://github.com/user-attachments/assets/633dea93-ecce-4422-bb58-7b923c370908" />

---
## Logic App-4
Overview: This Logic App demonstrates how to use parallel branches in Azure Logic Apps so that multiple actions run at the same time.

1. Create Logic App (Consumption)

Trigger → HTTP Request
Add a sample JSON body (so you can test from Postman):
<img width="642" height="196" alt="image" src="https://github.com/user-attachments/assets/fa9cf86e-f608-4412-b7a1-325c3a0cd196" />
<img width="929" height="685" alt="image" src="https://github.com/user-attachments/assets/a9122d5b-1eff-4ae5-901e-7e922a81d4ce" />

2. Add Parallel Branch

After the HTTP trigger → click "+" → Add a parallel branch.
Now you’ll see two columns (branches).

Compose (branch-1)
<img width="1090" height="343" alt="image" src="https://github.com/user-attachments/assets/89269f16-472e-440c-95ca-12450302524f" />

Compose 1(branch-2)
<img width="1090" height="326" alt="image" src="https://github.com/user-attachments/assets/04568ab9-4989-433a-a196-90554100db03" />

3. Join the Branches

Below both branches, add a Response action.
In the Response Body, include both results:
<img width="1090" height="701" alt="image" src="https://github.com/user-attachments/assets/8b654673-b498-42e6-a647-c37c83cf6ce9" />

Now, if you want to merge it, go to settings->run after (then choose the desired action)
<img width="1090" height="589" alt="image" src="https://github.com/user-attachments/assets/05179166-5163-43ea-b9f3-8c8d1225cc80" />

Output:
<img width="1090" height="472" alt="image" src="https://github.com/user-attachments/assets/87605d94-ed59-42e0-9db0-d21ea843890e" />

Workflow
<img width="1090" height="690" alt="image" src="https://github.com/user-attachments/assets/b06a5c3c-7b46-4f9e-ba33-f2f2a0676bf3" />




