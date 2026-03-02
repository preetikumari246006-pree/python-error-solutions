# VS Code ConPTY Terminal Issue (Windows) 💻

## ❓ What Is This Error?

Sometimes when running code in VS Code terminal, you may see:

The terminal process failed to launch:
A native exception occurred during launch (Cannot launch conpty)

This usually happens on Windows systems.

---

## 🤔 Why This Happens

Common reasons:

- Corrupted VS Code settings
- Outdated Windows version
- Terminal profile misconfiguration
- Permission issues

---

## 🛠 Step-by-Step Fix

### ✅ Solution 1: Run VS Code as Administrator

1. Close VS Code
2. Right click on VS Code
3. Click **Run as administrator**

---

### ✅ Solution 2: Change Default Terminal

1. Open VS Code
2. Press **Ctrl + Shift + P**
3. Search: Terminal: Select Default Profile
4. Choose **Command Prompt**
5. Restart VS Code

---

### ✅ Solution 3: Reset Terminal Settings

1. Go to:
   File → Preferences → Settings
2. Search: terminal.integrated
3. Reset modified settings

---

## 💡 My Experience

I faced this issue while trying to run Python tasks.
The terminal was not opening due to ConPTY error.

After changing the default terminal profile,
the problem was solved.

---

## 🎯 Tip

If nothing works:
- Update Windows
- Reinstall VS Code

This error is common on Windows but fixable.
