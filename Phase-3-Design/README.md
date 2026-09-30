# Phase 3: Project Design Phase
- **System Architecture:** Modular architecture consisting of a Frontend (HTML/CSS, Jinja2), Backend (FastAPI), AI Layer (Google Gemini APIs), and Database (SQLite + SQLAlchemy).
- **Database Design:**
  - `User` Table: Stores `id`, `name`, `age`, `weight`, `goal`, `intensity`, and `schedule`.
  - `WorkoutPlan` Table: Stores `user_id`, `original_plan`, and `updated_plan`.
- **UI/UX Design:** Gym-themed background aesthetics, clear form labeling on `index.html`, structured layout for `result.html`, and tabular format for the admin view (`all_users.html`).
-
