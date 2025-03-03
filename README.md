# Photo Book App - React Developer Exercise

## **Objective**
Build a **Photo Book Web Application** where users can browse, search, and favorite photos. This exercise tests proficiency in **React**, **state management**, **API handling**, and **performance optimization**.

---

## **Requirements**

### **1. Project Setup**
- Use **Vite** or **Create React App** for project initialization.
- Install **Tailwind CSS** for styling.
- Use **React Router** for navigation.

### **2. Features**

#### **Photo Gallery Page**
- Fetch photos from the API:
  ```plaintext
  https://jsonplaceholder.typicode.com/photos?_limit=50
  ```
- Display photos in a **responsive grid**.
- Each photo should include:
  - **Thumbnail** image.
  - **Title**.
  - Clicking a photo navigates to the **Photo Details Page**.
- Implement **search functionality** (filter photos by title).

#### **Photo Details Page**
- Display the **full-sized image**.
- Show the **photo title** and **album ID**.
- Allow users to **mark the photo as favorite** (persist in local state).

#### **Favorites Page**
- Show all photos that users have marked as **favorite**.
- Users can **remove a photo from favorites**.

---

## **Technical Requirements**
- **State Management**: Use **React Context API** or **Redux** for managing favorites.
- **API Calls**: Use **React Query** (or `fetch` with `useEffect`).
- **Performance Optimization**:
  - Use **React.memo()** or **useCallback()**.
  - Implement **debounced search** using `useState` and `useEffect`.
- **Routing**: Use **React Router** for page navigation.

---

## **Evaluation Criteria**
1. **Code Structure & Best Practices**.
2. **Component Composition & Reusability**.
3. **State Management (Local & Global)**.
4. **API Integration & Optimized Fetching**.
5. **Performance Optimization**.
6. **Routing & Navigation**.
7. **Error Handling & Edge Cases**.
8. **Styling & Responsive UI**.

---

## **Bonus Features (Optional)**
- **Infinite Scroll** instead of pagination.
- **Dark Mode** toggle.
- **Drag-and-Drop to reorder favorite photos**.

---

## **Getting Started**

### **1. Clone the Repository**
```sh
git clone https://github.com/your-username/photo-book-app.git
cd photo-book-app
```

### **2. Install Dependencies**
```sh
npm install  # or yarn install
```

### **3. Run the Application**
```sh
npm run dev  # or yarn dev
```

### **4. Open in Browser**
Go to `http://localhost:5173` (if using Vite) or the respective port.

---

## **API Reference**
- Photos API: `https://jsonplaceholder.typicode.com/photos`
- Fetch only 50 photos: `https://jsonplaceholder.typicode.com/photos?_limit=50`

---

## **License**
MIT License

---

Happy Coding! 🚀

