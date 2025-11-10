# Weather App: Project Description

## 1. Project Title
**Weather App**

---

## 2. Objective
Build a responsive, user-friendly web application that shows **real-time weather** for any city or the user’s current location. The app will use the **OpenWeatherMap API** to display temperature, humidity, wind speed, and a general condition (e.g., sunny, cloudy).

---

## 3. Requirements

### 3.1 Functional Requirements
- **Search by City:** Users can enter a city name and view current weather.
- **My Location:** Geolocate user to show weather at their current position.
- **API Integration:** Use OpenWeatherMap for live data.
- **Weather Details Display:** Temperature, humidity, wind, and condition icon/label.
- **Error Handling:** Friendly messages on invalid city or network errors.
- **Responsive Layout:** Works smoothly on desktop and mobile.

### 3.2 Non-Functional Requirements
- **Performance:** Aim to load weather results in under 3 seconds.
- **Usability:** Clean, minimal UI with readable typography and clear hierarchy.
- **Security:** Protect API key via environment variables or server proxy.
- **Accessibility:** Good contrast, labeled inputs, keyboard-friendly interactions.

---

## 4. User Stories
- As a **user**, I want to enter a city name to see its current weather so I can plan my day.
- As a **traveler**, I want a **My Location** option so I can instantly check weather where I am.
- As a **mobile user**, I want the interface to be easy to read and navigate on my phone.
- As a **power user**, I want clear error messages if a search fails, so I know what to try next.
- As a **developer**, I want a clean codebase and documentation for easy maintenance.

---

## 5. Implementation Details

### 5.1 Technical Stack (Proposed)
| Component | Technology | Purpose |
|---|---|---|
| **Frontend** | React.js (or Vanilla JS) | Interactive UI, component-based structure |
| **Styling** | CSS / Tailwind CSS | Responsive, modern styling |
| **HTTP** | Fetch API / Axios | API requests and error handling |
| **API** | OpenWeatherMap | Real-time weather data |
| **Deployment** | Netlify / GitHub Pages | Fast static hosting and CI/CD |

### 5.2 API Integration Strategy
- Use endpoints like `/weather?q={city}` and `/weather?lat={lat}&lon={lon}`.
- Handle loading, success, and error states with clear UI feedback.
- Convert temperature units (Kelvin → °C/°F) as needed.
- Cache recent searches (optional) to enhance user experience.

---

## 6. Deliverables
1. **Deployed Web App** meeting all functional and non-functional requirements.
2. **Source Code (GitHub)** with clear README and setup steps.
3. **Documentation**: this project description + API notes.
4. **Wireframes**: at least 3 pages with desktop and mobile versions.

---

## 7. UI/UX: Wireframes (Figma)

> Each page includes **Desktop** and **Mobile** variants. The links below open the frames/pages in Figma. If multiple variants share the same link, both are located within that Figma file’s nodes.

### 7.1 Home Page
- **Desktop:** [Figma Wireframe](https://www.figma.com/design/UGo9uf8xM13XPjyryPq5aP/Draft?node-id=0-1&t=VMNjtUuwMUGD1LjW-1)
- **Mobile:** [Figma Wireframe](https://www.figma.com/design/UGo9uf8xM13XPjyryPq5aP/Draft?node-id=9-6&t=VMNjtUuwMUGD1LjW-1)

### 7.2 Weather Details Page
- **Desktop:** [Figma Wireframe](https://www.figma.com/design/UGo9uf8xM13XPjyryPq5aP/Draft?node-id=2-29&t=VMNjtUuwMUGD1LjW-1)
- **Mobile:** [Figma Wireframe](https://www.figma.com/design/UGo9uf8xM13XPjyryPq5aP/Draft?node-id=9-6&m=dev&t=VMNjtUuwMUGD1LjW-1)

### 7.3 Error / No Results Page
- **Desktop:** [Figma Wireframe](https://www.figma.com/design/UGo9uf8xM13XPjyryPq5aP/Draft?node-id=2-29&t=VMNjtUuwMUGD1LjW-1)
- **Mobile:** [Figma Wireframe](https://www.figma.com/design/UGo9uf8xM13XPjyryPq5aP/Draft?node-id=9-6&t=VMNjtUuwMUGD1LjW-1)

> **Note:** If any link points to a Figma page that contains multiple frames, ensure you select the correct **Desktop** or **Mobile** frame before exporting images for your final report.

---

## 8. Next Steps
- Export PNGs from Figma (one for each desktop + mobile frame).
- Insert the PNGs (or links) into your submission document.
- Build the MVP in React and connect to OpenWeatherMap.
- Prepare a 3–5 minute demo walkthrough.

---

**Prepared by:** Abubakarr Mansaray & Abdulrahman Bah  
**Course:** CIS 332 – Web Programming I
