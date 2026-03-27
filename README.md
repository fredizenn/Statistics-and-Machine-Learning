# Statistics and Machine Learning Module

#### This template provides a pre-structured folder hierarchy for the *Statistics and Machine Learning* module, covering weeks 1 to 5. It is designed to streamline assignment management and ensure consistency in submissions.
---
## 1. Features
- **Weeks 1–4** each contain:  
  - `Lecture-Assignments`: for exercises given during lectures  
  - `Lab-Assignments`: for practical lab tasks  

- **Week 5** contains:  
  - `Final-Project-Examination`: for the final project submission  

- Pre-created folders include `.gitkeep` placeholders to preserve structure  
- `README.md` includes a student information table and instructions for adding assignments  
- Start working immediately using this template without creating any folders  
---

## 2. Repository Structure
```
Week-1/
  ├── Lecture-Assignments/
  │     └── .gitkeep
  └── Lab-Assignments/
        └── .gitkeep

...

Week-5/
  └── Final-Project-Examination/
        └── .gitkeep
```
---

## 3. Student Information
Fill in the details of the group members (3-5 students) and indicate who is the **project coordinator**.

| Full Name       | Student ID|
|-----------------|-----------|
|                 |           |
|                 |           |
|                 |           |
|                 |           |
|                 |           |
--- 

## 4. Template Usage
Once you have the template with all subfolders, please do the following:

## 4.1. Create a Private Repository

1. Go to [GitHub](https://github.com/) and log in.  
2. Click **New Repository** → choose **Private**.  
3. Name it appropriately (e.g., `Statistics-and-Machine-Learning`).  
4. Do **not** initialize with a README (you already have one).  
---

## 4.2. Add Collaborators

1. In your repository, go to **Settings → Collaborators**.  
2. Add your teammates’ GitHub **usernames**.  
3. Add the following as **read or write collaborators** so they can monitor submissions:  
   - Prof. Dr. Mehrdad Jalali's username: `MehrdadJalali-AI`
   - Dr. Ghadeer Mobasher's username: `mobashgr`

---

## 4.3. Push the Template to GitHub
From your **local machine**:
```bash
# change to your exact path
cd path/to/statistics-and-machine-learning
git init
git add .
git commit -m "Initial commit: add template with folders"
git branch -M main
# change to your private repo's url
git remote add origin <your-repository-url>
git push -u origin main
```
---

## 4.4 Adding Assignments
For each week:

- navigate to the corresponding folder (e.g., week-1).
- choose the appropriate subfolder:
  - lecture-assignments
  - lab-assignments
- add your assignment files using a clear naming convention:

```
assignment_<number>_<short_description>.ipynb
assignment_<number>_<short_description>.py
```

example:

```
assignment_1_miniproject.ipynb
```
---

### 4.5. Committing changes

```
git add .
git commit -m "add week-x assignment"
git push
```

---

## General Notes
- Do not modify the folder structure unless explicitly instructed. In other words, always work in the provided subfolders.
- Maintain consistency in the file naming and formatting.
- Ensure that all submissions are well-structured and documented.
- Commit often to ensure all submissions are tracked.
- Prof. Dr. Mehrdad Jalali and Dr. Ghadeer Mobasher will **monitor the team progress through GitHub**.
- For Questions related to the Lectures, please contact [Prof. Dr. Mehrdad](mailto:mehrdad.jalali@srh-hochschulen.de).
- For Questions related to the Labs, please contact [Dr. Ghadeer](mailto:ghadeer.mobasher@srh-hochschulen.de).



