# GDG-Recruitment
Round 1 Hiring Process


## 5. Development Team


## How It Works

1. **Register**

   * User enters **Name, Email, and Password**.
   * Data is saved into the browser’s **localStorage** as a JSON array of users.

2. **Login**

   * User enters **Email and Password**.
   * The script checks if the credentials match any user in localStorage.
   * If yes → Login successful → Redirects to **hello.html**.
   * If no → Shows “Invalid credentials”.

3. **Forgot Password**

   * User enters registered **Email**.
   * If email exists → New Password + Confirm Password inputs are shown.
   * After validation, the old password is updated in localStorage.
   * If email not found → “User not found” alert.

4. **Hello Page**

   * Displays a greeting using the **user’s name** passed through the URL.


# what i met ?

When iam in the middle of this project, one of the biggest thing was **how to store user data** without using database.

my first idea is to store the data in json file **( records.json )** but java script can't directly store data in json local file

so, i got a insight from web we can store data in current session but, it wont access by other pages.. , but later i got the real ans what it is ? we can store data in local storage , it can access till the browser session.. like **mini database inside the browser**

so i stored user's data in an array while registering and accessed while logging.. and etc...

* the data can store in  **key–value pairs**.
* data **stays saved even after refreshing** the page.
* stored users as a **JSON array of objects**, it could handle multiple accounts.



# live Website

https://arun-r-007.github.io/GDG-Recruitment/5.%20Development%20Team/index.html