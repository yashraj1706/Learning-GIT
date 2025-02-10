Here’s your **Git Module - Section 1 Notes** formatted in a structured manner similar to your reference example:

---

# Git Module - Section 1 Notes

## 1. Setting Up the Workspace

- **Opening the Terminal and Navigating to Desktop:**
  ```sh
  cd Desktop
  ```
- **Creating a New Directory and Entering It:**
  ```sh
  mkdir Story
  cd Story
  ```
- **Verifying the Directory is Empty:**
  ```sh
  ls
  ```

---

## 2. Creating and Editing Files

- **Creating a Text File:**
  ```sh
  touch chapter1.txt
  ```
- **Opening the File and Editing:**
  - Open using a text editor or terminal-based editor like `nano` or `vim`.
  - Add content, save, and exit.

---

## 3. Initializing a Git Repository

- **Initializing Git in the Current Directory:**
  ```sh
  git init
  ```
- **Verifying Git Initialization:**
  ```sh
  ls -a
  ```
  - This should show a hidden `.git` folder, indicating that the directory is now a Git repository.

---

## 4. Understanding Git Terminology

- **Working Directory:** The folder where Git tracks files and changes.
- **Staging Area:** A space where selected changes are placed before committing.
- **Local Repository:** Stores committed changes, allowing version tracking.

---

## 5. Tracking File Changes

- **Checking the Status of Files in Git:**
  ```sh
  git status
  ```
- **Adding a File to the Staging Area:**
  ```sh
  git add chapter1.txt
  ```
- **Verifying the Staging Area Status:**
  ```sh
  git status
  ```

---

## 6. Committing Changes

- **Committing the Staged File with a Message:**
  ```sh
  git commit -m "Complete chapter 1"
  ```
- **Checking Commit History:**
  ```sh
  git log
  ```
  - This shows a list of past commits along with their unique commit IDs.

---

## 7. Adding Multiple Files

- **Creating New Files:**
  ```sh
  touch chapter2.txt chapter3.txt
  ```
- **Staging Multiple Files at Once:**
  ```sh
  git add .
  ```
- **Committing Changes with a Message:**
  ```sh
  git commit -m "Complete chapter 2 and 3"
  ```
- **Verifying Commit History:**
  ```sh
  git log
  ```

---

## 8. Understanding Git Workflow

1. **Working Directory:** All project files exist here.
2. **Staging Area:** Files that are prepared for commit.
3. **Local Repository:** Stores committed changes permanently.

---

## 9. Reverting Changes

- **Checking File Status:**
  ```sh
  git status
  ```
- **Undoing Uncommitted Changes:**
  ```sh
  git checkout -- chapter3.txt
  ```
  - This resets the file to its last committed state.

---

This structured format ensures clarity, making it easier to review key Git concepts efficiently. Let me know if you need any refinements! 🚀
