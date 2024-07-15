# Activate Ubuntu Firewall

1. Install ufw if not already installed:
```
sudo apt update
sudo apt install ufw
```

2. Check the current status of ufw:
```
sudo ufw status
```

3. Enable and disable ufw:
```
sudo ufw enable
sudo ufw disable
```

4. To allow incoming traffic on port 8000 (TCP):
```
sudo ufw allow 8000/tcp
```

5. Allow to ssh on port 22  :
```
sudo ufw allow 22/tcp
```
