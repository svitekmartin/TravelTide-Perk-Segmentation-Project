# TravelTide Perk Segmentation Project

This project is part of the Masterschool Data Analyst program and focuses on developing a **personalized perk recommendation system** for the fictional travel platform **TravelTide**.
-

## 🔍 Project Objective

The goal is to assign a **personalized perk** to each user, based on their behavior on the platform as persona  
Only perks supported by available data are included.

### Defined Perks

- ✅ Free checked bag  
- ✅ No cancellation fees  
- ✅ Exclusive discounts  
- ✅ One night free hotel with flight  
- ✅ Free hotel meal 


## 🔄 Workflow Overview

### 1. Raw Data  
- Raw CSVs loaded via public links  
- Initial exploration, schema inspection, and validation

### 2. Cleaned  
- Dropped columns not needed for perk validation  
- Standardized data types  

### 3.Filtered  
- Filtered to users with ≥ 7 sessions since January 4, 2023  
- Only trips and records related to these users are kept  
- Used as the input for clustering

### 4. 👥 Segmentation & Clustering  
- User-level behavior is aggregated across all tables  
- Clustering algorithm applied to segment customers into personas
- Each cluster is matched with a perk based on its persona
  
### 5. 🎯 Final Deliverable
- A data-driven strategy that assigns each user to a behavioral segment formed into personas
- Each segment receives a perk recommendation grounded in actual usage patterns by personas


## 🧠 Personalization Scope

Perks are assigned based exclusively on **user behavior** formed to personas 
This includes:

- Booking and cancellation patterns  
- Discount usage  
- Session volume and engagement  
- Travel behavior (e.g., hotel + flight combinations)

### Defined Personas

✅ Busy Parents – Ages 35–50, with children
✅ Young Explorers – Ages 18–30, no children
✅ Loyal Vacationers – Ages 30–55
✅ Frequent Flyers – Ages 25–45
✅ Retired Relaxers – Age 55+
✅ Unclassified – 
  


## 📬 Contact

For questions or feedback, please reach out to me 
