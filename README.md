# ☕ WiredBrainCoffee Customers App (WPF)

A desktop customer management application built with C# and WPF using the MVVM (Model-View-ViewModel) architecture pattern.

The application allows users to manage a list of customers through a modern desktop interface that includes customer selection, data binding, editable customer details, and UI controls for customer management actions.

The project was created to practice WPF application development, XAML layouts, MVVM architecture, data binding, and component-based UI organization in C#.

---

# Features

- Customer list display
- Customer selection system
- Editable customer information
- MVVM architecture implementation
- Data binding between View and ViewModel
- Custom reusable UI controls
- Structured project organization
- Image and asset integration
- Responsive WPF layout
- Basic customer management interface

---

# Application Overview

The application interface is divided into multiple sections:

- A custom header with branding and version information
- A customer list panel
- Action buttons for managing customers
- A details section for editing customer information

When a customer is selected from the list:
- the customer data is displayed automatically
- the form fields update through data binding
- the UI reflects the selected item in real time

---

# Technologies Used

- C#
- WPF (Windows Presentation Foundation)
- XAML
- MVVM Architecture
- .NET
- Data Binding
- Observable Collections

---

# Project Structure

```txt
WiredBrainCoffee/
│
├── Controls/
│   └── HeaderControl.xaml
│
├── Data/
│   └── CustomerDataProvider.cs
│
├── Images/
│   ├── add.png
│   ├── logo.png
│   └── move.png
│
├── Model/
│   └── Customer.cs
│
├── View/
│   └── CustomersView.xaml
│
├── ViewModel/
│   └── CustomersViewModel.cs
│
├── App.xaml
├── MainWindow.xaml
├── AssemblyInfo.cs
└── README.md
```

---

# MVVM Architecture

The project follows the MVVM (Model-View-ViewModel) design pattern:

## Model
Contains the application data structures.

```txt
Model/Customer.cs
```

Represents the customer entity and stores customer-related information.

## View
Handles the user interface and XAML layouts.

```txt
View/CustomersView.xaml
```

Responsible for displaying customer data and user interaction components.

## ViewModel
Acts as the connection layer between the View and the Model.

```txt
ViewModel/CustomersViewModel.cs
```

Manages:
- customer collections
- selected customer logic
- data binding behavior
- UI state updates

---

# Custom Components

The application includes reusable custom UI components such as:

```txt
Controls/HeaderControl.xaml
```

This control is used to display:
- application branding
- logo
- title
- version information

---

# Data Management

Customer information is currently provided through:

```txt
Data/CustomerDataProvider.cs
```

This component supplies mock/sample customer data for the application interface.

---

# User Interface

The UI was built using XAML and WPF layout containers.

The application includes:
- list controls
- text inputs
- checkboxes
- image assets
- custom styling
- responsive desktop layout behavior

---

# Assets

The application uses image assets stored inside the `Images/` folder for:
- buttons
- branding
- icons
- navigation visuals

---

# Project Purpose

This project was created to practice and improve knowledge of:

- WPF desktop development
- XAML UI design
- MVVM architecture
- Data binding
- Observable collections
- Component-based UI structure
- Desktop application organization
- Separation of concerns
- C# application development
