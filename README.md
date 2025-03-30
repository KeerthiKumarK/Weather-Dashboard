# Weather Dashboard Web App

## 🌍 Overview
The **Weather Dashboard Web App** is a responsive and modern web application built using **React.js**. It allows users to search for any city and view real-time weather information using data fetched from the **OpenWeatherMap API**.

## 🚀 Features
### 🏙️ User Interface
- A **search bar** to enter a city name.
- **Search on enter keypress** or click on the search button.
- Displays a **weather information card** with:
  - City Name
  - Current Temperature (**°C**)
  - Weather Condition (**Sunny, Rainy, Snow, etc.**)
  - Humidity (**%**)
  - Wind Speed (**km/h**)
  - Weather Icon (provided by API)
- **Loading state** while fetching data.
- **Error state** for:
  - Invalid city name.
  - API failures.

### 🔥 Bonus Features (Optional but Recommended)
- **Recent Search History**: Displays last 5 searched cities.
- **5-Day Weather Forecast**: Uses OpenWeatherMap's 5-Day API.
- **Dark/Light Mode Toggle**.
- **Refresh Button** to re-fetch data for the current city.
- **Loading animation** while fetching data.
- **Basic animations** using Framer Motion or CSS.

## 🌐 API Integration
This app uses the **OpenWeatherMap Current Weather API**:
```
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={YOUR_API_KEY}&units=metric
```

### 🔑 API Key Setup
1. Register for a free API key: [OpenWeatherMap API](https://openweathermap.org/api)
2. Add your API key to a `.env` file:
   ```
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

## 🛠️ Tech Stack
- **React.js** (Vite)
- **State Management**: React Hooks (useState, useEffect)
- **Styling**: Tailwind CSS 
- **HTTP Requests**: Fetch API / Axios
- **Animations**: Framer Motion / CSS Transitions
- **Error Handling**: User-friendly error messages
- **Mobile + Desktop Responsive Design**

## 📦 Installation & Setup
1. **Clone the repository:**
   ```sh
   git clone https://github.com/KeerthiKumarK/weather-dashboard.git
   ```
2. **Navigate to the project directory:**
   ```sh
   cd weather-dashboard
   ```
3. **Install dependencies:**
   ```sh
   npm install
   ```
4. **Set up environment variables:**
   - Create a `.env` file in the root directory.
   - Add your OpenWeatherMap API key as `REACT_APP_WEATHER_API_KEY`.
5. **Run the development server:**
   ```sh
   npm start
   ```
6. **Build for production:**
   ```sh
   npm run build
   ```

## 📸 Screenshots
 
![image](https://github.com/user-attachments/assets/39031c8d-0525-441a-bdf0-a8a299f0757f)
![image](https://github.com/user-attachments/assets/b105778c-f113-4b29-b807-3c2c65142052)

## Mobile Design
  ![image](https://github.com/user-attachments/assets/6f38b75c-a697-404a-94ca-6534e3116b72)




## 🤝 Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Make your changes and commit (`git commit -m "Added a new feature"`).
4. Push to your fork (`git push origin feature-branch`).
5. Create a Pull Request.

## 📜 License
This project is licensed under the **MIT License**.

## ⭐ Acknowledgments
- [OpenWeatherMap](https://openweathermap.org/) for the weather data.
- React.js community for their amazing support.

---

**Made with ❤️ using React.js & Tailwind CSS**

