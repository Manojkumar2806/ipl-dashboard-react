# 🏏 IPL Dashboard

A responsive and dynamic IPL Dashboard web application built using **React JS**, fetching live data from the [CCBP IPL API](https://apis.ccbp.in/ipl). It displays team cards, the latest match highlights, and recent match summaries for each IPL team, with routing and loading states.

---

## 🚀 Live Demo

👉 **[Click here to view the live app](https://manojiplscores.ccbp.tech/)**

---

## 📸 Screenshots

### 🏠 Home Page
![image](https://github.com/user-attachments/assets/125db886-1d29-40be-8d82-476dc462c70b)


### 🧢 Team Matches Page
![image](https://github.com/user-attachments/assets/1a697992-671d-48bd-9516-519e68edb250)
![image](https://github.com/user-attachments/assets/386b5074-fead-4d4e-b03e-63fd30a151c6)


## Preview
<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/ipl-dashboard-output-v2.gif" alt="ipl dashboard output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

---

## 🚀 Features

- ⚡ **Real-time API Integration** – fetches data for all IPL teams and matches.
- 🧭 **Routing with Parameters** – navigates to team-specific pages using React Router.
- 🖼️ **Team Banners** – each team page displays a unique banner.
- 🔄 **Loading Spinners** – clean UX while data is fetched.
- 📋 **Latest Match Summary** – shows detailed match info with venue, result, date, and innings.
- 📊 **Recent Matches List** – dynamic rendering of match cards with win/loss status indicators.
- 🎨 **Team-Specific Theming** – dynamic background colors per team using route IDs.
- 📱 **Fully Responsive** – works smoothly across devices.

---

## 🧩 Tech Stack

- **React JS**
- **JavaScript (ES6+)**
- **React Router**
- **CSS Modules**
- **Loader Spinner (react-loader-spinner)**

---

## 🧠 Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Handling API loading states | Used `isLoading` state with `react-loader-spinner`. |
| Mapping nested JSON data | Formatted API responses using helper methods. |
| Dynamic routing with props | Used `match.params.id` to fetch specific team data. |
| Reusability of UI | Abstracted repeated UI elements into reusable components. |
| Responsive UI | Customized layouts with `index.css` and media queries. |


## Thank you for visting my repo 💖


