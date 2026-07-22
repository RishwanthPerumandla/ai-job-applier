

Job Sources
    │
    ├── Pasted job links
    ├── Greenhouse boards
    ├── Lever boards
    ├── Ashby boards
    └── Workday career pages
             │
             ▼
Job Ingestion and Normalization
             │
             ▼
Profile Matching and Eligibility Engine
             │
      ┌──────┴──────┐
      │             │
   Reject/Skip    Qualified
                    │
                    ▼
          Resume Tailoring Engine
                    │
                    ▼
          Application Answer Engine
                    │
                    ▼
              User Approval
                    │
                    ▼
          ATS Application Adapter
                    │
        ┌───────────┴───────────┐
        │                       │
   Direct HTTP/API        Playwright Browser
        │                       │
        └───────────┬───────────┘
                    ▼
           Submission Verification
                    │
                    ▼
       Receipt, Screenshot and Audit Log
                    │
                    ▼
             Application Tracker
                    │
                    ▼
        Email Inbox and OTP Processor


