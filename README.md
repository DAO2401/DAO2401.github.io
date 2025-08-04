# DAO2401.github.io
# 🧾 Purchase Order Management System

This is a Flask-based web application that allows customers to:

- Submit Purchase Orders (POs)
- Automatically receive order confirmations
- Download invoices/reports
- Track their order status online

---

## 🚀 Features

- Customer PO submission form
- Auto-generated PO ID
- Email confirmation sent to customer
- Admin dashboard to view all orders
- PDF invoice generation and export
- Order status tracking

---

## 🛠️ Tech Stack

- **Frontend**: HTML, Bootstrap
- **Backend**: Python (Flask)
- **Database**: SQLite (easy to set up)
- **Email**: Flask-Mail (Gmail SMTP)
- **PDF Export**: xhtml2pdf

---

## 🔧 Installation

```bash
git clone https://github.com/your-username/purchase-order-system.git
cd purchase-order-system
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt


