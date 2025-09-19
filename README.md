**🎓 Student Fee Management System**

A role-based fee management system built with ASP.NET Core (Web API) and Blazor WebAssembly.
Manages student details and student fee records, with different workflows for CEO and Accountant roles.

**🚀 Step-by-Step System Workflow**
**🏗️ Raw System Design (Step-by-Step Workflow)**

echo "START"
echo "  │"
echo "  ▼"
echo "[CEO Logs In] → (Predefined Email)"
echo "  │"
echo "  ▼"
echo "[CEO Registers Accountant(s)]"
echo "  │"
echo "  ▼"
echo "[Accountant Logs In]"
echo "  │"
echo "  ▼"
echo "[Accountant Enters Student & Fee Details]"
echo "  │"
echo "  ▼"
echo "[Accountant Edits Student/Fee Records]"
echo "  │"
echo "  ▼"
echo "[CEO Approves Edits]"
echo "  │"
echo "  ├──> Changes Saved to Database"
echo "  │"
echo "  ▼"
echo "[CEO Directly Add/Update/Delete Student & Fee Records]"
echo "  │"
echo "  ▼"
echo "[Deleted Items?] ──> [Recovery System (Hangfire)] ──> Recovered Items"
echo "  │"
echo "  ▼"
echo "[CEO Defines Term Fee Dates]"
echo "  │"
echo "  ▼"
echo "[Students’ Term Fee Details Displayed]"
echo "  │"
echo "  ▼"
echo "[Dashboard Display]"
echo "  │"
echo "  ├──> Total Students"
echo "  ├──> Pending Fees"
echo "  └──> Pending Approvals"
echo "  │"
echo "  ▼"
echo "[Export Feature]"
echo "  ├──> Accountants Export Excel"
echo "  └──> CEO Export Excel"
echo "  │"
echo "  ▼"
echo "END"

**✅ This raw design shows all main flows:**

-Login/Register

-Role-based actions

-Approval process

-Recovery system

-Calendar/term fee workflow

-Dashboard & Export
