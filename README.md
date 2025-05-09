# 🏢 TechNova Office Simulation (Linux User & Group Practice)

This is a Linux-based office simulation project designed to practice user, group, and permission management.

## 📁 Structure

We simulate a real IT company with the following departments:

- `frontend/` → alice (Frontend Developer)
- `backend/` → bob (Backend Developer)
- `support/` → eva (Customer Support)
- `hr/` → lisa (HR Manager)
- `ceo/` → ceo (Project Leader)

Each folder contains a `tasks.md` file with realistic responsibilities.

## 👥 Users & Groups

- Users: `alice`, `bob`, `eva`, `lisa`, `ceo`
- Groups: `dev`, `support`, `hr`, `ceo`

Users were created with:
```bash
sudo useradd -m alice
sudo useradd -m bob
...
