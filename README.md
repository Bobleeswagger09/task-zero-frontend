# Responsive Profile Card

A **modern, responsive Profile Card** built with **HTML, CSS, and Vanilla JavaScript**. This card displays essential user details, including a **profile picture, name, job title, bio, location, email, social links, and dynamic UTC time**.

## 🚀 Features
-  **Fully Responsive** – Works on all screen sizes.
-  **Dynamic UTC Time** – Updates on page refresh.
- **Clean UI/UX** – Simple and professional design.
-  **Accessible & Semantic HTML** – Easy to test with `data-testid` attributes.

## 📌 Required Elements
Each element follows the **correct `data-testid`** attribute for easy testing:
| **Element**        | **Description**          | **Attribute** |
|--------------------|--------------------------|--------------|
| Profile Picture   | Displays user image.      | `data-testid="profilePicture"` |
| Full Name        | Displays full name.      | `data-testid="fullName"` |
| Job Title        | Shows job position.      | `data-testid="jobTitle"` |
| Short Bio        | Brief user bio (50-100 words). | `data-testid="shortBio"` |
| Location         | Displays city & country. | `data-testid="currentLocation"` |
| Email Address    | Displays professional email. | `data-testid="emailAddress"` |
| Social Links     | Links to GitHub, LinkedIn, Twitter, etc. | `data-testid="socialLinks"` |
| UTC Time         | Displays live UTC time.  | `data-testid="currentTimeUTC"` |
