# Leave Management System – ServiceNow

This mini project demonstrates a basic Leave Management application built on the ServiceNow platform. It allows employees to raise leave requests and track approvals through the system.

---

## 🎯 Project Use Case

Employees can submit leave requests by selecting the leave type, start/end date, and reason. The request is reviewed and updated by the HR/Admin team.

---

## ✅ Features Implemented

- Custom table: `Leave Request [u_leave_request]`
- Fields: Leave Type, From Date, To Date, Reason, Status, Approver Comments
- Business Rule: Auto-change status to "Approved" if leave type is less than "24 hours"
- Notifications: Sent to the approver and requester upon status change

---

## 🧾 Field Details

| Field Name        | Type      | Description                          |
|-------------------|-----------|--------------------------------------|
| Leave Type        | Choice    | Sick Leave, Casual Leave, etc.       |
| From Date         | Date      | Leave start date                     |
| To Date           | Date      | Leave end date                       |
| Reason            | String    | Reason for leave                     |
| Status            | Choice    | Pending, Approved, Rejected          |
| Approver Comments | Journal   | Remarks by the approver              |

---

## 🧑‍💻 Admin Work Done

| Feature         | Tool Used           |
|-----------------|---------------------|
| Table Creation  | Table Module        |
| Form Design     | Form Designer       |
| Automation      | Business Rules      |
| Notifications   | Notification Module |
| Dashboard       | List Filters        |

> 🚫 *UI Policies were not used in this version. All fields remain static. Future enhancements may include conditional mandatory fields or hiding comments field before approval.*

---

## 📘 What I Learned

- Creating custom forms and data models in ServiceNow
- Automating workflow using Business Rules
- Setting up email notifications
- Creating an end-to-end HR-type mini system

---

## 📄 Author

**Pragnasri** – ServiceNow Admin Fresher  
📧 saipragnachowdary@gmail.com  
🔗 GitHub: [@pragnasri123456](https://github.com/pragnasri123456)


