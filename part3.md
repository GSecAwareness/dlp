# 🛡️ DLP Policy Creation (Based on Sensitive Info Type)

## 🏷️**Creating Classifiers**  

Navigate to **DLP > Classifiers > Sensitive Info Type**  

## 📜**Creating the Policy**  

Navigate to **DLP > Policies > Create Policy > Custom**  

Specify the following:  
- **Custom Policy:** > Next      
- **Name:** `Employee ID Policy` > Next
- **Choose Where to Apply the Policy:** Defaults, except `On-premises repositories` > Next  
- **Define Policy Settings:** defaults > Next  
- **Customize advanced DLP rules** > Create    
Specify the following:
- **Name** Monitor for `Employee ID Keyword`
- **Condition:**  Content contains (Add) > Sensitive Info Type `Employee ID Keywords`

---
![get-content](https://github.com/GSecAwareness/dlp/blob/main/Employee%20ID%20keywords.png)  

---

- **Actions** > **Add an Action:** > `Audit or restrict activities on devices`
---

![get-content](https://github.com/GSecAwareness/dlp/blob/main/Block%20with%20override.png)  

---

- **Use Email incident reports to notify you when a policy match occurs:** toggle ‘On’  
- **Send notifications to these people:** `Add or remove users` (Admins) > Save

---

 ![get-content](https://github.com/GSecAwareness/dlp/blob/main/Email%20Incident%20report.png)  

---
- **Policy Mode:**  `Turn the policy on immediately` > Submit

**_Once your policy is complete, return to the main policy screen to view the current policies and their status. You can also see the priority of each, which is indicated by a number. The lower the number, the higher the priority._**  

---

![get-content](https://github.com/GSecAwareness/dlp/blob/main/priority.png)  

---

