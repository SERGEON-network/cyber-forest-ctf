# 🌲 Welcome to the Cyber Forest CTF Challenge! 🌲

## 🎯 Your Mission

You are a cyber explorer lost in a digital forest. Your goal is to navigate through a maze of files and find **three hidden flags**. But beware: this forest is full of traps! Some files are malicious and will temporarily disable your terminal if you open them.

**Can you find all the flags without getting infected?**

---

## 🕹️ How to Play

1.  **Click on the website link** provided by your instructor to start the challenge.
2.  You will see a **terminal interface** in your web browser.
3.  Use the following commands to explore the filesystem:

| Command | Example | What it does |
| :--- | :--- | :--- |
| `ls` | `ls` or `ls Documents/` | Lists files in the current (or specified) directory |
| `cd` | `cd Documents/` | Changes to a different directory |
| `cat` | `cat note.txt` | Displays the contents of a file |
| `file` | `file mystery.exe` | Reveals the true type of a file |
| `clear` | `clear` | Clears your terminal screen |
| `help` | `help` | Shows available commands |

---

## 🏁 The Flags

There are **three flags** hidden in the system. Each flag is a string that looks like this: **`CTF{something_here}`**.

*   **Flag 1:** Hidden in a file most people ignore.
*   **Flag 2:** In a place where documents are stored.
*   **Flag 3:** Hidden within an image's metadata.

The scoreboard at the bottom of the screen will track your progress.

---

## ☠️ WARNING: Traps!

Some files are **malicious**! If you open them, your terminal will be **disabled for 10 seconds** and you'll see a scary (but harmless) virus animation.

*   **Think before you `cat`!** Maybe use the `file` command first to check what type of file you're dealing with.
*   Be especially careful with files in the `Downloads/` and `bin/` directories.

---

## 🏆 Winning the Challenge

The first player to find all **three flags** wins! The challenge tracks your completion time.

**Pro Tip:** The flags are not always in obvious places. Look for hidden files and think about where you might hide something valuable.

---

## 🆘 Need Help?

If you get stuck, try these strategies:
1.  Use `ls -a` to see hidden files (those starting with a `.`)
2.  The `file` command is your best friend for avoiding traps
3.  Check everywhere—even where it seems obvious

**Remember:** This is a simulation. No real systems are being harmed.

---

Good luck, explorer! The forest awaits... 🌲💻
