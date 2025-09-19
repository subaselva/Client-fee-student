**🎓 Student Fee Management System**

A role-based fee management system built with ASP.NET Core (Web API) and Blazor WebAssembly.
Manages student details and student fee records, with different workflows for CEO and Accountant roles.

**🚀 Step-by-Step System Workflow**
**🏗️ Raw System Design (Step-by-Step Workflow)**

START
  │
  ▼
[CEO Logs In] → (Predefined Email)
  │
  ▼
[CEO Registers Accountant(s)]
  │
  ▼
[Accountant Logs In]
  │
  ▼
[Accountant Enters Student & Fee Details]
  │
  ▼
[Accountant Edits Student/Fee Records]
  │
  ▼
[CEO Approves Edits]
  │
  ├──> Changes Saved to Database
  │
  ▼
[CEO Directly Add/Update/Delete Student & Fee Records]
  │
  ▼
[Deleted Items?] ──> [Recovery System (Hangfire)] ──> Recovered Items
  │
  ▼
[CEO Defines Term Fee Dates]
  │
  ▼
[Students’ Term Fee Details Displayed]
  │
  ▼
[Dashboard Display]
  │
  ├──> Total Students
  ├──> Pending Fees
  └──> Pending Approvals
  │
  ▼
[Export Feature]
  ├──> Accountants Export Excel
  └──> CEO Export Excel
  │
  ▼
END

**✅ This raw design shows all main flows:**

-Login/Register

-Role-based actions

-Approval process

-Recovery system

-Calendar/term fee workflow

-Dashboard & Export
