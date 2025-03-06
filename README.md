# 📊 Pixela Habit Tracker  

A Python-based **habit tracking** application that integrates with **Pixela** API to log daily activities like reading, workouts, or coding.  

---

## ✨ Features  
- **Create a Pixela account** via API.  
- **Set up a graph** to track your habit (e.g., number of pages read).  
- **Log daily progress** with a single command.  
- **Update or delete entries** as needed.  

---

## 🛠 Setup Instructions  

### 1️⃣ Install Dependencies  

Ensure Python is installed, then install the required library:  

```bash
pip install requests
```

---

### 2️⃣ Create a Pixela Account  

- Go to **[Pixela](https://pixe.la/)** and create an account.  
- Get your **Username** and **Token**.  

---

### 3️⃣ Configure API Keys  

In `main.py`, replace the placeholders with your **Pixela credentials**:  

```python
USERNAME = "your_pixela_username"
TOKEN = "your_pixela_token"
GRAPH_ID = "your_graph_id"
```

---

### 4️⃣ Run the Application  

To log your habit, run the script:  

```bash
python3 main.py
```

You'll be prompted to **enter the number of pages read (or any unit you choose)**, and the data will be logged on Pixela.

---

## 📜 How It Works  

1. **Create a Pixela account** using the API.  
2. **Set up a graph** on Pixela to track your habit.  
3. **Log daily progress** by entering the number of pages read.  
4. **Modify or delete entries** as needed via API calls.  
