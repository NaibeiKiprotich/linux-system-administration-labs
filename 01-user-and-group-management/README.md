# User and Group Management Lab

## Objective

To understand Linux user administration, group management, and privilege assignment in a CentOS Linux environment.

---

## Lab Environment

| Component | Details |
|---|---|
| Operating System | CentOS Linux 7 |
| Virtualization | Oracle VirtualBox |
| Terminal | Konsole |

---

## Tasks Performed

### 1. Create a New User

```bash
sudo useradd analyst1
```

---

### 2. Set User Password

```bash
sudo passwd analyst1
```

---

### 3. Create a New Group

```bash
sudo groupadd socteam
```

---

### 4. Add User to Group

```bash
sudo usermod -aG socteam analyst1
```

---

### 5. Verify User Information

```bash
id analyst1
```

---

## Expected Output

```bash
uid=1001(analyst1) gid=1001(analyst1) groups=1001(analyst1),1002(socteam)
```

---

## Key Concepts Learned

- Linux user management
- Group administration
- Access control
- Principle of least privilege
- System administration fundamentals

---

## Skills Demonstrated

- Linux administration
- Identity and access management
- Command-line operations
- Security-focused system configuration

---

## Conclusion

This lab demonstrated the process of managing Linux users and groups while implementing controlled privilege allocation within a CentOS environment.
