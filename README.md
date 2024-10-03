# :fire: Calorie Calculator
This project is a simple and efficient Calorie Calculator that allows users to track their calorie intake and calories burned. The application provides a smooth user experience by leveraging React's modern hooks for state and side effect management, and optimizes performance with memoization.

## :star2: Features
- **Add Category:** Users can select between "Food" or "Exercise" as a category.
- **Add Activity:** Enter the name of the food or exercise.
- **Add Calories:** Input the number of calories consumed or burned.
- **Calorie Calculation:** The app calculates the total calories consumed and burned.
- **Calorie Difference:** Automatically calculates the difference between calories consumed and calories burned.
- **Persistent Data:** The app uses Local Storage to store and persist your entries, even after refreshing the page.
- **Edit Entries:** You can update any item on your list, whether it’s food or exercise.
- **Delete Entries:** You have the option to remove individual items or clear the entire list.
- **Responsive UI:** Built with Tailwind.css, the app is responsive and user-friendly across devices.

## :gear: Technologies Used
- **React** (with TypeScript for type safety)
- **Vite** (for fast builds and development)
- **Tailwind.css** (for modern and responsive UI design)

## :wrench: Performance Optimization
To enhance performance, I implemented:

- **Use of useReducer:** Ideal for managing complex state, allowing for clear action management and state changes.

- **Optimization with useMemo:** Helps avoid unnecessary calculations by recalculating only when dependencies change, reducing unnecessary re-renders.

- **Persistence with localStorage:** The use of useEffect ensures that activities are saved between sessions, enhancing efficiency and user experience.

- **Efficient Event Handling:** Defined functions are used to handle events, avoiding the creation of new functions on each render.

- **Clear Structure:** Well-organized components facilitate maintainability and performance.

## :globe_with_meridians: Site
**Site:** https://calorietracker-sac.netlify.app

## 🚀 Getting Started

To run this project locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/Calorie-Tracker.git
```
### 2. Navigate to the project folder
```bash
cd calorie-tracker
```
### 3. Install dependencies
```bash
npm install
```
### 4. Start the application
```bash
npm run dev
```
### 5. Build the application
```bash
npm run build
```