<p align="center">
  <img src="assets/banner.png" alt="TailorPro Banner" width="100%">
</p>
flowchart LR
	A[Open Chat App] --> B[Register or log in]
	B --> C[Browse users]
	C --> D[Open a conversation]
	D --> E[Send a message]
	E --> F[Live delivery and read receipt]
	classDef screen fill:#8a9b68,color:#ffffff,stroke:#2b2620,stroke-width:2px;
	classDef action fill:#d5ddbc,color:#2b2620,stroke:#6f7d4a,stroke-width:2px;
	class A,C,D,F screen;
	class B,E action;

