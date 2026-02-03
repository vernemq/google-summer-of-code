# Google Summer of Code 2026

## 📂 Project Ideas

### 💡 Extend the VerneMQ Kubernetes Operator project

👥 **Mentor(s):** André Fatton

📢 **Communication Channel:** VerneMQ Slack Workspace/Mailing list/VerneMQ Forum

📝 **Repository:** https://github.com/vernemq/vmq-operator/

💬 **Description:**

The VerneMQ Operator is a project to create, configure and manage VerneMQ clusters (stateful sets).
The project is in alpha state and needs some updates, to ensure it is working with latest releases of Kubernetes and VerneMQ. Based on your own experimentation and research, functions can be extended.

💪 **Desired Skills:** Kubernetes, Operator knowledge, Golang

🎯 **Goals/Deliverables:**

- Determine needed updates
- Adapt existing functions
- Adapt and improve configuration of nodes and cluster
- Experiment with your own ideas and add respective functions

⏳ **Project Duration:** medium (175h)

📈 **Difficulty:** intermediate

-----

### 💡 Complete and extend the VerneMQ WebAdmin project

👥 **Mentor(s):** André Fatton

📢 **Communication Channel:** VerneMQ Slack Workspace/Mailing list/VerneMQ Forum

📝 **Repository:** https://github.com/vernemq/vmq_webadmin

💬 **Description:**

The VerneMQ WebAdmin is a user contributed frontend project to provide VerneMQ with a web-based management GUI. It uses an exporter plugin that is fully integrated into latest VerneMQ releases. The WebAdmin project is currently not part of a VerneMQ release, due to its alpha state.

💪 **Desired Skills:** Vue.js, Typescript, Erlang (optional)

🎯 **Goals/Deliverables:**

- Systematically explore `vmq-admin` functions and decide what can be added to Web frontend
- Experiment with your own ideas and add respective functions
- Adapt backend exporter application if the frontend needs it

⏳ **Project Duration:** medium (175h)

📈 **Difficulty:** intermediate

-----

### 💡 Add `vmq_discovery` extension for dynamic clustering

👥 **Mentor(s):** TBD

📢 **Communication Channel:** VerneMQ Slack Workspace/Mailing list/VerneMQ Forum

📝 **Repository:** https://github.com/vernemq/vernemq

💬 **Description:**

Add an OTP application to VerneMQ that can offer dynamic discovery and clustering features. The application should be usable for all deployments (bare metal, Kubernetes). We could also add static clustering, where a given number of static cluster nodes are added to the VerneMQ config file, enabling auto-clustering.

💪 **Desired Skills:** Erlang

🎯 **Goals/Deliverables:** 
- Determine internal API functions to script cluster leaves/joins
- Develop vmq_discovery using the Erlang/OTP application structure
- Integrate into VerneMQ (release) and add a test suite (Erlang Common Test)

⏳ **Project Duration:** small (90h)

📈 **Difficulty:** intermediate

-----

### 💡 Add a database of your choice to hold authentication and authorization information.

👥 **Mentor(s):** NN

📢 **Communication Channel:** VerneMQ Slack Workspace/Mailing list/VerneMQ Forum

📝 **Repository:** https://github.com/vernemq/vernemq

💬 **Description:**

You could do this natively (Erlang), or use the Lua layer as the current database integrations do. Both ways will require a useable Erlang-based and appropriately licensed database driver. Using Lua, you can use the existing Lua scripts as a template but you will have to implement a part of the extension as Erlang modules.

💪 **Desired Skills:** Lua, Erlang

🎯 **Goals/Deliverables:**
- Find an appropriate database driver (Erlang based)
- Implement Erlang modules as an intermediate layer between DB driver and Lua
- Implement authentication and authorization hooks in Lua scripts
- Execute load/performance tests

⏳ **Project Duration:** small (90h)

📈 **Difficulty:** intermediate
