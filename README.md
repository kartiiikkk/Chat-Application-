## Console-Based Chat Application 

It is a simple command-line based chat application built in C++. It allows users to register, login, send messages, view received messages, delete them, and more — all through a terminal interface using file handling. 

---

## Features

- User Registration & Login System
- Secure password input with masking
- Send messages to registered users
- View received messages
- View message logs (sent messages)
- Delete received messages and logs
- Developer team display
- Console UI with cursor control using `gotoxy`

---

## Technologies Used

- **C++**
- **Windows.h** for console control
- **File Handling** for storing user data and messages
- **ASCII characters** for box-style UI

---

## File Structure

```
.
├── project.cpp          # Main source code
├── Username.txt         # Stores registered usernames
├── Password.txt         # Stores corresponding passwords
├── REG-Entries.txt      # Stores user registration info
├── <user>-message       # Message file for each user
├── <user>-log           # Sent message log file per user
```

---

## How to Run

>  Windows-only due to dependencies on `windows.h` and `conio.h`

1. Open the code in **Dev C++**, **Turbo C++**, or another Windows-based C++ IDE.
2. Compile and run `project.cpp`.
3. Follow the menu to Register or Login.

---

## Sample Usage

1. **Register** with username, password, phone, and name.
2. **Login** using your credentials.
3. Use the menu to:
   - Send messages to another user.
   - View messages you've received.
   - View your sent message log.
   - Delete messages or logs.

---

