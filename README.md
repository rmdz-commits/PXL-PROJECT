<div align="center">

  <h1>📂 PXL PROJECT | Data Repository</h1>
  
  <p>
    <strong>The Centralized JSON Database & Configuration Source for the <br> 📱 PXL PRO Application</strong>
  </p>

  <p>
    <img src="https://img.shields.io/badge/App-PXL_PRO-blueviolet?style=for-the-badge" />
    <img src="https://img.shields.io/badge/Format-JSON_Array-black?style=for-the-badge&logo=json&logoColor=white" />
    <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
    <img src="https://img.shields.io/badge/Data-Dynamic-orange?style=for-the-badge" />
  </p>

  <br>

  [📖 About](#-about-this-repository) • [⚙️ Data Format](#-data-format) 

</div>

---

## 📖 About This Repository

This repository serves as the **core database storage** for the **PXL PRO** application. 

Instead of hardcoding data directly into the application source code, **PXL PRO** retrieves its content dynamically from the JSON files hosted here. This architecture allows for:

* **Real-time Updates:** Content can be updated without releasing a new APK/App version.
* **Centralized Management:** All data arrays are maintained in a single, organized location.
* **Scalability:** Easy to add new items or categories to the app just by editing the JSON lists.

---

## ⚙️ Data Format

The database relies on **JSON ArrayLists**. Every file in this repository is structured to be lightweight and easily parsable by the application's client side.

### JSON Schema Example
All data strictly follows the JSON Array format `[...]` containing Objects `{...}`:

```json
[
  {
    "id": 1,
    "title": "Item Name Example",
    "description": "Content description for PXL PRO app.",
    "url": "[https://example.com/resource.png](https://example.com/resource.png)",
    "active": true
  },
  {
    "id": 2,
    "title": "Second Item",
    "description": "Another data entry.",
    "url": "[https://example.com/resource2.png](https://example.com/resource2.png)",
    "active": true
  }
]
