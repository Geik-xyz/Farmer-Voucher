# Farmer Voucher Module

A Farmer plugin module that issues “Farmer tickets” to players, creating or upgrading their Farmer level.

---

## 📦 Installation

1. Drop the `Farmer-Voucher` folder into `plugins/Farmer/modules/`.  
2. Restart your server.  
3. A `config.yml` and matching language file will be generated under `plugins/Farmer/modules/Farmer-Voucher/`.

---

## ⚙️ Features

- **Farmer Voucher Issuance**  
  Grant Farmer access as “voucher” via command.

- **Level Upgrade or Creation**  
  - If the player already has a Farmer and its level is lower than the ticket level, their Farmer level is increased and the ticket is consumed.  
  - If the player has no Farmer, a new one is created at the ticket’s level.

- **Fully Modular**  
  All behaviors (giving, upgrading, creating) can be toggled on or off in the module’s config.

---

## 🛠 Commands & Permissions

- **Command**  
  `/farmer give <player> <farmer-level> <amount>`  
  Issue the specified number of Farmer tickets at the given level.

- **Permission**  
  `farmer.admin` – Required to run the give command.

---

## 🤝 Contributing

1. Fork the repository.  
2. Add your enhancements or bug fixes.  
3. Open a pull request against the `develop` branch.

Please follow existing code style and update documentation as needed.

---

Thank you for using the **Voucher** module—happy farming!  
