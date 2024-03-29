# Welcome to HotelHub!

HotelHub is a cross-platform desktop app powered by Electron. HotelHub boosts your productivity by creating a centralized environment for all hotel data and analytics.

## Features

- [ ] Reservations/Front-Desk Support
- [ ] Inventory Management
- [ ] Restaurant Invoices & Billing
- [ ] Account Reports
- [ ] Time Keeping
- [ ] Graphs of Data Analytics

## UML diagrams

HotelHub follows the following diagram convention:

```mermaid
graph LR
A[Login] -->|Authentication| B{Checks Permissions}
B -->|Manager| C[Manage Hotel]
B -->|Employee| D[Manage Reservations]
B -->|Restaurant| E[Manage Inventory]
B -->|Cleaner| F[Access Rooms]
B -->|Accountant| G[Manage Reports]
```
![Screenshot](https://github.com/pseudodan/HotelHub/blob/master/HotelHub_UML.png)

## Usage

<kbd>Command/ctrl + R</kbd> - Reload

<kbd>command + q</kbd> - Quit Application


## Built with
- Electron](https://electron.atom.io)

