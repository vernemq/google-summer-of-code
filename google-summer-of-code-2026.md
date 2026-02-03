# Google Summer of Code 2026

## 📂 Project Ideas

### 💡 Revive the VerneMQ Kubernetes Operator project

👥 **Mentor(s):** NN

📢 **Communication Channel:** 

💬 **Description:**

The VerneMQ Operator is a project to create, configure and manage VerneMQ clusters (stateful sets).
The project is in alpha state and needs some updates, to ensure it is working with latest releases of Kubernetes and VerneMQ.
Functions can be extended, if needed.

Current status: https://github.com/vernemq/vmq-operator/

💪 **Desired Skills:** Kubernetes, Operator knowledge, Golang

🎯 **Goals/Deliverables:**

⏳ **Project Duration:** 

📈 **Difficulty:** intermediate

-----

### 💡 Complete and extend the VerneMQ WebAdmin project

👥 **Mentor(s):** NN

📢 **Communication Channel:** 

💬 **Description:**

The VerneMQ WebAdmin is a user contributed frontend project to provide VerneMQ with a web-based management GUI. It uses an exporter plugin that is fully integrated into latest VerneMQ releases. The WebAdmin project is currently not part of a VerneMQ release, due to its alpha state.

Current status: https://github.com/vernemq/vmq_webadmin/

💪 **Desired Skills:** Vue.js, Typescript

🎯 **Goals/Deliverables:**

⏳ **Project Duration:** 

📈 **Difficulty:** intermediate

-----

### 💡 Add `vmq_discovery` extension for dynamic clustering

👥 **Mentor(s):** NN

📢 **Communication Channel:** 

💬 **Description:**

Add an OTP application to VerneMQ that can offer dynamic discovery and clustering features. The application should be usable for all deployments (bare metal, Kubernetes). We could also add static clustering, where a given number of static cluster nodes are added to the VerneMQ config file, enabling auto-clustering.

💪 **Desired Skills:** Erlang

🎯 **Goals/Deliverables:** vmq_discovery Erlang application

⏳ **Project Duration:** 

📈 **Difficulty:** intermediate

-----

### 💡 Add a database of your choice to hold authentication and authorization information.

👥 **Mentor(s):** NN

📢 **Communication Channel:** 

💬 **Description:**

You could do this natively (Erlang), or use the Lua layer as the current database integrations do. Both ways will require a useable Erlang-based and appropriately licensed database driver. Using Lua, you can use the existing Lua scripts as a template but you will have to implement a part of the extension as Erlang modules.

💪 **Desired Skills:** Lua, Erlang

🎯 **Goals/Deliverables:**

⏳ **Project Duration:** 

📈 **Difficulty:** intermediate
