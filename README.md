# SAP RAP Managed Scenario Project – Internship

This project was developed during my internship, focused on building an end-to-end CRUD application using the **SAP RESTful ABAP Programming Model (RAP)** in a **Managed scenario**. The application was designed to manage simple business entities through modern ABAP development on SAP BTP or S/4HANA.

## 📌 Project Overview

The project involved creating a Fiori Elements-based application using CDS Views, Behavior Definitions, and OData V4 service binding. The objective was to understand and implement the full RAP lifecycle including data modeling, behavior implementation, and UI annotations.

### Key Features:
- Created a **Product Management** app with full CRUD operations.
- Implemented **CDS Views** for data modeling and UI exposure.
- Developed **Behavior Definitions** (Managed scenario) for handling business logic.
- Created **OData V4 services** using Service Definition and Binding.
- Integrated **Fiori Elements** for frontend UI generation.

## ⚙️ Technologies Used

- SAP BTP / SAP S/4HANA (On-Prem or Cloud)
- ABAP RAP (Managed Scenario)
- ABAP Development Tools (ADT in Eclipse)
- Core Data Services (CDS)
- Behavior Definition & Implementation
- OData V4 & Fiori Elements

## 📁 Project Components

| Object Type         | Object Name          | Description                            |
|---------------------|----------------------|----------------------------------------|
| CDS Interface View  | ZI_PRODUCT           | Base interface view                    |
| CDS Consumption View| ZC_PRODUCT           | Consumption view exposed to UI         |
| Metadata Extension  | ZC_PRODUCT_MTX       | UI annotations for Fiori Elements      |
| Behavior Definition | ZBP_PRODUCT          | Managed behavior for CRUD              |
| Service Definition  | ZUI_PRODUCT_SRV      | Exposes entity via OData               |
| Service Binding     | ZUI_PRODUCT_BINDING  | OData V4 service binding               |

## 🚀 How to Run the Project

1. Open Eclipse with ADT and connect to your SAP system.
2. Create and activate the CDS views (`ZI_PRODUCT`, `ZC_PRODUCT`).
3. Add Metadata Extensions for Fiori UI annotations.
4. Define and implement Behavior Definitions (`ZBP_PRODUCT`).
5. Create Service Definition and Binding.
6. Preview and test the application using the Fiori preview.

## 📷 Screenshots



## 🧠 Learnings and Outcomes

- Gained hands-on experience in **SAP RAP architecture**.
- Understood **Managed scenario workflows** in RAP.
- Learned how to integrate CDS, behaviors, and Fiori with minimal frontend coding.
- Improved understanding of OData V4, metadata annotations, and Eclipse-based ABAP development.

## 📚 References

- [SAP Help Portal – RAP Programming Model](https://help.sap.com)
- [SAP Zero to Hero Blog on RAP](https://sapzero2hero.com/2022/11/29/sap-rap-managed-scenario-simple-example/)

---

