Here is the revised **skill.md** file, optimized with **Operational Procedures** and **Constraints** to transform it from a knowledge base into a functional tool for an AI agent.

# **⚙️ Operations Management AI Agent Skill**

## **1\. Process & Bottleneck Analysis**

**Goal**: Identify the "Herbie" (constraint) to maximize system throughput.

### **📋 Operational Procedure:**

1. **Map Flow**: Identify every step from entry to exit.  
2. **Define Flow Unit**: Determine if you are measuring customers, parts, or orders.  
3. **Calculate Capacity**: For each resource, use (Available Time / Task Time) \* Number of Resources.  
4. **Identify Bottleneck**: The step with the **lowest** capacity or **highest** utilization.  
5. **Calculate Utilization**: Actual Throughput / Capacity. If \> 100%, the system is failing.

### **⚠️ Constraints:**

* Improving a non-bottleneck does **not** improve the system.  
* High WIP (Work-in-Progress) is a symptom of a bottleneck or poor flow.

## ---

**2\. Inventory & Supply Chain Management**

**Goal**: Balance ordering costs against holding costs and mitigate the Bullwhip Effect.

### **📋 Operational Procedure:**

1. **Calculate EOQ**: Use SQRT((2 \* Annual Demand \* Ordering Cost) / Annual Holding Cost per Unit).  
2. **Analyze Bullwhip**: Check if order fluctuations are higher than actual demand spikes.  
3. **Implement JIT**: Reduce batch sizes to increase flow and reduce lead times.

### **⚠️ Constraints:**

* **EOQ** assumes constant demand; do not use for highly seasonal or volatile items.  
* Low inventory increases the risk of stockouts during supply chain disruptions.

## ---

**3\. Queuing & Service Management**

**Goal**: Minimize wait times and optimize resource allocation.

### **📋 Operational Procedure:**

1. **Determine Rates**: Identify Arrival Rate ($\\lambda$) and Service Rate ($\\mu$).  
2. **Calculate Wait Time ($Wq$)**: Use ρ / (μ \* (1 \- ρ)) where ρ \= λ / μ.  
3. **Control Variability**: If wait times are high despite low utilization, suggest cross-training or better scheduling.

### **⚠️ Constraints:**

* Queuing formulas assume a "steady state." They fail if $\\lambda \\geq \\mu$ (the line grows infinitely).

## ---

**4\. Strategic Operations & Lean**

**Goal**: Align operational execution with business goals (Making Money).

### **📋 Operational Procedure:**

1. **Check Goal Alignment**: Does the action increase **Throughput** while decreasing **Inventory** and **Operating Expense**?.  
2. **Evaluate Make vs. Buy**: Weigh "Made in USA" branding/quality benefits against a $50M domestic cost vs. outsourcing.  
3. **Omnichannel Check**: Ensure UX quality is treated as a revenue multiplier, not a speed trade-off.

## ---

**🛠️ Agent Execution Loop (The Five Focusing Steps)**

When tasked with optimizing a process, follow this iterative logic:

1. **Identify** the system's constraint (The Bottleneck).  
2. **Exploit** the constraint (Ensure it never sits idle/wastes time).  
3. **Subordinate** everything else (Non-bottlenecks must work at the bottleneck's pace).  
4. **Elevate** the constraint (Add capacity/new machines to the bottleneck).  
5. **Prevent Inertia**: If the bottleneck moves, go back to Step 1\.

Sources:

* [BreakfastAtTheParamount.pdf](https://drive.google.com/open?id=1mk3jurp1d3IvyfI2HrsstOunEvMFdCea)  
* [Chris\_Pennell\_Case 3: Breakfast at the Paramount](https://drive.google.com/open?id=1Qsty4MU_Ae0o6dX8anrrGBJWSQrPjM_myFWNspnZCPw)  
* [Step-by-Step Process for Operations and Bottleneck Analysis](https://drive.google.com/open?id=1XYaG8uQ9Lp8V0Ova4wt8TuBn8LpUE71vU_CptcozqEE)  
* [Chris\_Pennell\_Case 2: Paediatric Orthopaedic Clinic](https://drive.google.com/open?id=1gXP9t__r3MXPPdPP1X4-IlmHo1EiuoYiogMaMs7zzKY)  
* [Chris\_Pennell\_Final Exam.docx](https://drive.google.com/open?id=13h3zUwP8GdTTzHWr0QJ_Mq5XMaH9pJox)  
* [The Goal A Process of Ongoing Improvement 30th.pdf](https://drive.google.com/open?id=1oBbipdIJsFlgmdfivIjK4XxxhwVFEFsy)  
* [Chris\_Pennell\_Case 5: The Goal](https://drive.google.com/open?id=1FQkW_64r8WbBLeHx9LY5fHi6O_1ZO0CDDUSdPM3MvZE)  
* [NewBalanceAthleticShoeIncAbridged.pdf](https://drive.google.com/open?id=15hvXYYRvQU9ezRmiZ2p_TL7ynxY8aOno)  
* [📢 Your Product is Scaling—But is Your UX](https://drive.google.com/open?id=1gauUELmnBKtRFJkxfVuAtlRpW-fwZwiGbbSWSh153TQ)  
* [Chris\_Pennell\_Case 1: New Balance](https://drive.google.com/open?id=10wKVAq4fqBZ2Xq89bfhZHMleIaUxjNzd8Q5a6cTiQgU)