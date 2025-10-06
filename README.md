# Blue - Developer Community Platform

# Phase 1: Initial Developement

## overview

### what is blue?

Blue is a developer community platform designed to facilitate collaboration, knowledge sharing, and networking among developers. It provides a space for developers to connect, share ideas, and work together on projects, ultimately fostering a vibrant and supportive community.

### key features

- **User Profiles**: Each user has a customizable profile showcasing their skills, projects, and contributions.
- **Project Showcase**: Developers can create and manage project profiles to highlight their work and receive feedback from the community.
- **Discussion Forums**: Engage in discussions on various topics related to development, technology, and best practices.
- **Networking Tools**: Connect with other developers, collaborate on projects, and exchange knowledge through events, meetups, and virtual gatherings.
- **Community Moderation**: Blue includes a robust moderation system to ensure a respectful and inclusive environment for all users.
- **Career Opportunities**: Blue provides a platform for developers to showcase their skills, attract job opportunities, and network with potential employers.
- **Event Hosting**: Blue allows community members to host events, meetups, and hackathons, fostering a sense of belonging and collaboration.
- **User Projects**: Developers can create and manage project profiles to highlight their work and receive feedback from the community.
- **Skill Sharing**: Developers can share their skills, techniques, and best practices with the community, helping others learn and grow.
- **Skill Exams**: Blue offers a platform for developers to take and share skill exams, helping them evaluate their knowledge and progress.

### target audience

Blue is designed for developers of all skill levels, from beginners to experienced professionals. It caters to individuals looking to learn, share knowledge, and collaborate on projects within a supportive community.

### benefits

- **Collaboration**: Blue fosters collaboration among developers, enabling them to work together on projects and share ideas.
- **Learning**: The platform provides opportunities for developers to learn from each other through discussions, feedback, and shared resources.
- **Networking**: Blue helps developers build their professional network, connect with like-minded individuals, and explore new opportunities.
- **Visibility**: By showcasing their projects and contributions, developers can gain visibility within the community and potentially attract job offers or collaborations.

### conclusion

Blue is a developer community platform that aims to create a vibrant and inclusive environment for developers to connect, collaborate, and learn. With its user-friendly interface, robust features, and supportive community, Blue has the potential to become a valuable resource for the developer community worldwide.

## Developement Plan

### Folder Structure

```folder
developer-community-platform/
|-- backend/
|-- frontend/
|-- ChangeLog.md
|-- WorkResult.md
|-- README.md
```

### Teams 

- **Team1**
- **Team2**
- **Team3**
- **Team4**
- **Team5**
- **Team6**

### Frontend
 
- **Vite & ReactJS + Javascript + Swc**: Frontend framework for building the user interface.
- **Manual Styling**: Utilize manual styling techniques to ensure a consistent and visually appealing design.
- **Color Scheme**: Implement a color scheme that aligns with the overall design of the platform and is easy to maintain.

---

### 🎨 **Color Scheme**

| Element                  | Light Theme | Dark Theme | Description                                 |
| ------------------------ | ----------- | ---------- | ------------------------------------------- |
| **Primary Blue**         | `#2563EB`   | `#3B82F6`  | Vibrant modern blue — tech and trust driven |
| **Accent Blue (Hover)**  | `#1E40AF`   | `#60A5FA`  | Used for hover states, highlights           |
| **Background**           | `#F9FAFB`   | `#0F172A`  | Neutral base; clean and minimal             |
| **Card / Surface**       | `#FFFFFF`   | `#1E293B`  | For posts, threads, and panels              |
| **Secondary Background** | `#F3F4F6`   | `#111827`  | For sidebars, code panels                   |
| **Border / Divider**     | `#E5E7EB`   | `#374151`  | Subtle, non-distracting separation          |
| **Text Primary**         | `#0F172A`   | `#F9FAFB`  | High contrast readability                   |
| **Text Secondary**       | `#334155`   | `#CBD5E1`  | Softer secondary text for meta info         |
| **Success (Green)**      | `#16A34A`   | `#22C55E`  | For verified users or status indicators     |
| **Error (Red)**          | `#DC2626`   | `#F87171`  | For errors, warnings                        |
| **Highlight / Link**     | `#1D4ED8`   | `#60A5FA`  | Clickable elements, underlines              |

---

### ✍️ **Typography**

| Element             | Font                               | Style              | Notes                                     |
| ------------------- | ---------------------------------- | ------------------ | ----------------------------------------- |
| **Heading (H1–H3)** | **Poppins** / **Inter**            | Semi-bold / Bold   | Modern, geometric feel — great for titles |
| **Body Text**       | **Inter** / **Roboto**             | Regular / Medium   | Clean, dev-friendly readability           |
| **Code / Syntax**   | **JetBrains Mono** / **Fira Code** | Regular            | Monospaced for code snippets              |
| **Button Text**     | **Poppins**                        | Medium / Uppercase | Clear call-to-action                      |

---

### 🌗 **Theme Behavior**

**Light Mode:**
– Developer dashboard / documentation view.
– Focus on content clarity and whitespace.
– Highlight code panels in subtle gray boxes.

**Dark Mode:**
– Ideal for community threads, coding sessions, and late-night reading.
– Blue glow effects on buttons and links (slight neon aesthetic).
– Background gradients can use subtle blue-to-navy transitions.

Example Dark Gradient:

```css
background: linear-gradient(135deg, #0F172A 0%, #1E293B 50%, #1E40AF 100%);
```

---

### 💡 **Text Color Logic**

| Mode  | Text                 | Background | Use Case             |
| ----- | -------------------- | ---------- | -------------------- |
| Light | `#0F172A` (Blackish) | `#FFFFFF`  | Normal text on white |
| Dark  | `#F9FAFB` (White)    | `#0F172A`  | Text on dark         |

---

### Backend - Python
- **Flask**
- **SQLite**: Database for developement
- **PostgreSQL**: Database for production
- **RestAPI**: For frontend to backend communication
- **JWT**: For user authentication
- **SMTP**: For email notifications, password reset, and account verification.

# Flow

- **Login** : Email/username and password. Forget password(Email verification -> New password -> Login). Don't have account? SignUp
- **SignUp** : Email, username(Unique, allowed special characters: _, - , instant check availability), password(Minimum 10 characters, at least 1 letter, 1 number, and 1 special character), confirm password(Should match the password) -> Account verification email -> Login.
- **Account Verification** : Email verification link in the signup email. Click the link to verify your account.

- **Feeds** : Combination of posts, events, queries, community posts, projects, and skill exams. Feeds Algorithms will Shared Later
- **Create**:
    - **Posts** : Users can create posts to share their knowledge, experiences, or ask questions.
    - **Events** : Users can create events to meet other developers, attend meetups, or hackathons.
    - **Queries** : Users can ask questions and get answers from the community.
    - **Community Posts** : Users can create posts to share their projects, collaborate on ideas, or seek help.
    - **Skill Exams** : Users can take skill exams to evaluate their knowledge and progress.
    - **Projects** : Users can create project profiles to highlight their work and receive feedback from the community.
    - **Dev Conference** : Users can create and attend developer conferences, meetups, or hackathons.
- **Search** : Users can search for posts, events, queries, community posts, projects, and skill exams. Users can search by keywords, hashtags, or specific users, and filter results by date, popularity, or relevance.
- **Notifications** : Users can receive notifications for new posts, comments, events, queries, community posts, skill exam results, and project updates.
- **Profile** : Users can create and update their profiles, including their bio, skills, and projects. if(profile is not complete) show a warning message to complete their profile in every page to say "Complete your profile to get full access".
- **Premium** : Users can upgrade to a premium account to access additional features, such as priority support, ad-free experience, who viewed your profile, and boost your profile posts.
    - **Plan 1** : $9.99/month
    - **Plan 2** : $26.99/3 months
    - **Plan 3** : $99.99/6 months
    - **Plan 4** : $199.99/year
- **Cancel** : Users can cancel their premium subscription at any time. Cancellation will be effective at the end of the current billing period.
- **Payment** : Users can pay for their premium subscription using credit/debit cards, PayPal, stripe, or other supported payment methods.
- **Skill Exam Payment** : Users can pay for their skill exam using credit/debit cards, PayPal, stripe, or other supported payment methods. Every attempt will require a payment. payment will based on the Skill Exam Price. For example, Java Basic Skill exam price is $6.19 per attempt. Java Intermediate exam price is $15.49 per attempt, etc. If user passed(85/100) the exam Then automatically add the Skill badge in the user profile.


⚠️ COPYRIGHT / USAGE NOTICE

This repository is public for visibility, but it is NOT licensed for reuse.  
All rights reserved. You do NOT have permission to copy, modify, redistribute, or use this code without express written permission from the author. Contact <support@nocorps.org>.
