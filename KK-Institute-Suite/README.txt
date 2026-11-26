KK Institute Suite — Animated Home + Staff Portal Upgrade
=========================================================

WHAT'S INCLUDED
- Animated, responsive public home page with floating dashboard preview, orbit motion, animated hero, scroll-reveal feature cards, and login calls to action.
- Three login roles: Administrator, Student, and Staff / Faculty.
- Staff Directory remains managed by the administrator.
- Staff login credentials are created/updated in Faculty & Staff.
- Staff Attendance page for administrator to mark daily attendance for every staff member.
- Staff members can sign in and view their own attendance history and staff profile.
- Administrator dashboard includes total staff and staff-present-today indicators.
- Existing student attendance, student directory, TPO/placement modules, and existing LocalStorage keys are retained.
- New staff attendance data is stored separately in `kkInstitute.staffAttendance`.

DEMO LOGIN
- Administrator: username `admin`, password `admin123`
- Student: registered Student ID as username and password (unless changed in the existing account).
- Staff: Staff ID as username. Default password is Staff ID unless the administrator sets a different password in Faculty & Staff.

FIRST-TIME STAFF SETUP
1. Sign in as Administrator.
2. Open Faculty & Staff.
3. Add a staff member and assign a unique Staff ID.
4. Set a login password (or leave it as the Staff ID).
5. Sign out and select Staff / Faculty on the login page.
6. Staff can view their dashboard, profile, and attendance history.
7. Administrator can open Staff Attendance to mark Present, Absent, or Late and save the daily register.

RUN
1. Extract the ZIP.
2. Open the `KK-Institute-Suite` folder in VS Code.
3. Open `index.html` with Live Server.

IMPORTANT
This remains a front-end demo. Data is stored in the current browser's LocalStorage and is not shared between devices or users' separate browsers. Login checks are demo-level only and are not secure production authentication. For real institute-wide use, add a secure backend, database, server-side role permissions, and password hashing. Do not deploy real student/staff personal information with this local-only demo.
