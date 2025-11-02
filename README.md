## AD_20_Contacts_Manager_App

### 📱 Short Description

A contact management application built using the **MVVM architecture** pattern, employing **Room Database** for local storage and **Data Binding** with **RecyclerView**.

---

### 🧩 Concepts Covered

* **MVVM Architecture** (Model, View, ViewModel layers)
* **Room Database** (data abstraction layer over SQLite)
* **Database Components**: **Entity** (`@Entity`), **DAO** (`@Dao`), and **Database** (`@Database`)
* **Repository** layer for data source management
* **Live Data** for observable data streams from the database
* **Data Binding** integration with **RecyclerView**
* **Swipe-to-Delete** functionality (`ItemTouchHelper`)

---

### 🎯 Learning / Discovery Points

* Defining the structure and schema for local database storage (Entity class with primary key generation).
* Implementing **background thread operations** for database access (using `ExecutorService`) to avoid blocking the UI.
* Using `AndroidViewModel` to initialize the **Room Database** instance by accessing the Application context.
* Implementing **data binding** directly within the custom **RecyclerView adapter** (`ContactListItemBinding`).
* Applying the **singleton pattern** for database instance creation (`getInstance`).

---

### ⚙️ App Features / Usage

* Allows users to **add new contacts** (name, email) via a Floating Action Button (FAB).
* Displays the contact list in a **RecyclerView**.
* Enables **data deletion** by swiping the contact card to the left.

---

### 📝 Note

This project serves as a comprehensive example for mastering **offline data storage** and the **MVVM architectural pattern** in a real-world application.

---
