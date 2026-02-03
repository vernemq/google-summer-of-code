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

-----

### 💡 TraceDump: Extend Tracing Tool for MQTT Traffic in VerneMQ

👥 **Mentor(s):** Dhruv Jain, Vivek Pipaliya

📢 **Communication Channel:** VerneMQ Slack Workspace/Mailing list

📝 **Repository:** https://github.com/vernemq/vernemq

💬 **Description:**
  The existing vmq-admin tracing functionality in VerneMQ is limited to a single session and lacks filtering by topics, users, or MQTT packet types. This project aims to extend the existing tracing tool for VerneMQ that can support multiple concurrent tracing sessions, fine-grained filtering, and real-time dumping of MQTT events to external files.

💪 **Desired Skills:** Erlang, MQTT

🎯 **Goals/Deliverables:**
  - Support for concurrent tracing of multiple clients or sessions on a single node
  - Fine-grained filtering by topic, username, client ID, and MQTT packet type
  - Real-time dumping of MQTT events to external files
  - Optional replay or playback of captured traces for analysis and debugging

⏳ **Project Duration:** 90 hours

📈 **Difficulty:** Intermediate

-----

### 💡 gRPC-Based Webhook Events Plugin for VerneMQ

👥 **Mentor(s):** Dhruv Jain, Vivek Pipaliya

📢 **Communication Channel:** VerneMQ Slack Workspace/Mailing list

📝 **Repository:** https://github.com/vernemq/vernemq

💬 **Description:**
The present webhook events plugin is using HTTP/1.1 that affects the broker's performance at high load. The goal of this project is to design and implement a new VerneMQ webhook events plugin based on gRPC, enabling structured, strongly-typed event delivery with support for both asynchronous streaming and synchronous request–response modes.

💪 **Desired Skills:** Erlang, MQTT, GRPC

🎯 **Goals/Deliverables:**
  - Implement a gRPC-based webhook events plugin
  - Support both asynchronous event streaming and synchronous event handling
  - Provide clearly defined protobuf schemas for webhook events
  - Enable configurable delivery modes, timeouts, and retry semantics
  - Ensure minimal performance impact and safe backpressure handling
  - Load test using MzBench for 10,000 rps send/receive rate with 100K concurrent connections

⏳ **Project Duration:** 175 hours

📈 **Difficulty:** Intermediate

-----

### 💡 MQTT over QUIC Support in VerneMQ

👥 **Mentor(s):** Dhruv Jain

📢 **Communication Channel:** VerneMQ Slack Workspace/Mailing list

📝 **Repository:** https://github.com/vernemq/vernemq

💬 **Description:**
This project aims to add support for MQTT connections over the QUIC protocol as an additional listener option in VerneMQ. It must allow MQTT clients to connect using QUIC while preserving MQTT protocol semantics and security guarantees.

💪 **Desired Skills:** Erlang, MQTT, QUIC

🎯 **Goals/Deliverables:**
  - Add a QUIC listener option to VerneMQ alongside existing TCP/TLS listeners
  - Support secure connections using TLS 1.3 as required by QUIC
  - Ensure compatibility with existing MQTT protocol versions and client libraries
  - Handle session lifecycle, flow control, and backpressure appropriately
  - Stress test to evaluate performance, latency, and resource usage compared to TCP/TLS
  - Document configuration, limitations, and best practices

⏳ **Project Duration:** 175 hours

📈 **Difficulty:** Intermediate
