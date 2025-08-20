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



