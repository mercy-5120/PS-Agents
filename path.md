## 3. Optimal Path Calculation

Using the Google Maps search feature to calculate the driving distances between these towns, we evaluated the path costs for the self-driving trailer. The path cost function is the sum of the distances between the towns on each route.

**Path Cost Formulations:**
*   **Path A (Central Rift):** Nairobi → Naivasha (90 km) → Nakuru (69 km) → Kericho (107 km) → Kisumu (83 km)
    *   **Total Cost:** 90 + 69 + 107 + 83 = **349 km**
*   **Path B (South Rift):** Nairobi → Narok (142 km) → Bomet (82 km) → Kericho (77 km) → Kisumu (83 km)
    *   **Total Cost:** 142 + 82 + 77 + 83 = **384 km**
*   **Path C (North Rift):** Nairobi → Naivasha (90 km) → Nakuru (69 km) → Eldoret (154 km) → Kisumu (117 km)
    *   **Total Cost:** 90 + 69 + 154 + 117 = **430 km**

**Optimal Path Verdict:**
The optimal path for the self-driving trailer from Nairobi to Kisumu is **Path A (Nairobi → Naivasha → Nakuru → Kericho → Kisumu)**, as it results in the lowest overall path cost of **349 km**.
