# 💧 PhilQuench

The **PhilQuench** is a cross-platform desktop app builder built with **Electron**, designed to create fully customized water billing systems tailored for **barangays or small municipalities**.

This project allows developers or utility staff to **generate deployable billing systems** by filling out a short terminal-based setup form. Once completed, the system is personalized with unique branding and configuration — turning it into something like:

> 🏷️ *“Barangay A Water Billing Management System”*

Whether you manage one barangay or deploy systems for multiple regions, this tool enables you to **quickly generate, configure, and package** independent apps for each location.

## 🛠 What It Does

* 🧾 **Form-based Generator**
  A command-line tool that collects essential configuration (e.g. *Barangay Name*, *Company Address*, *Contact Info*, *Billing Settings*, etc.)

* 🏗️ **System Builder**
  Automatically updates static content, configuration files, and assets of the base billing app to match the provided details.

* 📦 **Packaging Ready**
  Packages the result as a complete and branded billing management desktop app for offline use.

## 🎯 Who This Is For

* Developers creating customized billing systems for multiple barangays or LGUs
* Freelancers deploying desktop tools for water utility offices
* Local officials or IT support teams needing a scalable deployment solution

## 📦 Output Example

Run the generator once with Barangay A’s details and it creates a packaged app:

> `Barangay A Water Billing Management System`
> Complete with custom name, address, logo, rates, and templates

Do it again with different form data and you now have:

> `Barangay B Water Billing Management System`
> With its own branding and internal configuration

## 📌 Core Features (in Generated App)

### 📝 Water Connection Application

* Register new applicants
* Track location and connection status
* Approve or reject applications

### 📋 Data Management

* Manage accounts and resident records
* Update statuses and search accounts easily

### 💵 Billing Tools

* Auto-generate monthly bills
* Supports base rates, surcharges, discounts
* Compute totals and due dates automatically

### 📜 History Tracking

* Maintain complete billing/payment logs
* Export data for reports or audits

### 🖨️ Print-Ready Layouts

* Print individual or bulk bills
* Branded headers with barangay or company identity

## ⚙️ How to Use the Generator

### 🔧 Requirements

* [Node.js](https://nodejs.org/) (v14+)
* Terminal access (Windows Command Prompt / macOS Terminal / Linux Shell)

### 🧪 Run the Generator

```bash
# Clone the generator repo
git clone https://github.com/yourusername/water-billing-generator
cd water-billing-generator

# Install dependencies
npm install

# Run the generator
npm run generate
```

Follow the prompts to fill in your desired static data.

The generator will then:

* Replace placeholder data in the app
* Configure metadata and labels
* Prepare assets (logo, address, etc.)
* Output a ready-to-use folder containing your custom billing system

## 🗃️ Suggested File Structure

```
water-billing-generator/
├── generator/             # Generator CLI logic
├── template-app/          # Base water billing app
│   ├── src/
│   └── ...
├── output/                # Generated apps will appear here
├── README.md
└── ...
```

## 🖼️ Screenshots (from Generated App)

* ✅ Custom dashboard with barangay branding
* 🧾 Personalized water connection form
* 📄 Printable bills with logo & address
* 🗂️ Filterable billing history
* 🖨️ Previews for printing

## 🔮 Planned Features

* 🧩 Custom rate configurations per client
* 🌐 Language and regional settings
* 🔐 User authentication with role permissions
* 🗃️ Auto-backup and archive system
* ☁️ Optional cloud sync integration
* 📁 Multi-format export support

## 🇵🇭 Local Government Focus

This system was originally developed for a **Philippine barangay** client. Its features reflect practical local needs:

* Designed to be **offline-first** for rural areas
* Simple GUI using **Electron** with persistent local storage
* Configurable to match **any barangay or LGU**

## 📬 Contact

For technical support, deployment assistance, or custom development:

* **Email**: [samadriansabalo99@gmail.com](mailto:samadriansabalo99@gmail.com)
* **GitHub**: [AceBurgundy](https://github.com/AceBurgundy)

## 📄 License

This project is intended for use by **LGUs or barangay-level water services**. Redistribution and commercial use require permission from the developer.
See the [LICENSE](LICENSE) file for more details.
