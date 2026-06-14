# Odoo 17 Hospital Management System (HMS)

An Odoo 17 custom module designed to manage hospital operations efficiently. This system automates patient records, doctors' assignments, and medical history tracking.

---

## 🚀 Features

* **Patient Management**: Seamless creation and tracking of patient profiles (including age, birthdate, blood type, and medical history).
* **Doctor Assignment**: Link patients with their assigned doctors.
* **Medical History**: Track patient logs and history updates automatically.
* **Automated Age Calculation**: Dynamically computes patient age based on date of birth.
* **Access Control & Security**: Defined user roles and access rights for doctors, nurses, and managers.
* **Interactive Wizards**: Easy-to-use wizards for quick actions like adding historical logs.

---

## 🛠️ Project Structure

```text
hms/
├── models/          # Core Python business logic and fields
├── views/           # XML views (Forms, Trees, Menus, Actions)
├── security/        # Ir.model.access.csv and security groups
├── wizard/          # Transient models and quick action wizards
├── reports/         # Custom QWeb PDF reports (if applicable)
├── static/          # Assets, CSS, JS, and Images
├── __init__.py      # Python package initialization
└── __manifest__.py  # Odoo module metadata description
