Here's a fun and practical challenge for building an interactive **To-Do List App** this week! This project will boost your JavaScript skills and make use of your creative, unique designs. Let’s turn this simple concept into a personal productivity app with a few extra features to make it challenging and real-world relevant!

---

## 📝 Project Instructions: To-Do List App with Authentication & Task Management

**Main Goal:** Create a fully functional To-Do List App where users can register/login to keep track of their tasks. This means you’ll be building a mini app with user management and task management features!

### 🌟 Requirements

1. **User Registration & Login:**
   - Users must be able to **register** with a username and password, or log in if they already have an account.
   - For an added challenge, consider allowing the user to choose a **display name or theme** they’d like to see when they log in.
   - **Store user credentials** securely (but remember, this is a simple project, so don’t worry about encryption).

2. **Task Management:**
   - **Add New Tasks:** Users should be able to type in a task and add it to their to-do list. Each task should include a title, description, and due date (optional).
   - **Remove Tasks:** Users can delete any task once it’s completed.
   - **Prioritize Tasks:** Let users set **priority levels** for their tasks (like "High," "Medium," or "Low") or even color-code them!
   - **Mark as Completed:** Add a checkbox or toggle so users can mark tasks as complete, and give them the option to hide completed tasks.
   - **Task Categories:** Create simple categories for tasks, such as "Work," "Personal," or "Hobbies" (feel free to get creative with these!).
  
3. **User Session Management:**
   - When users log in, their **tasks should be saved** and ready for them to view. Consider adding a greeting that says “Welcome back, [Username]!”

4. **Data Storage:**
   - **Persist user data** (username, password) and their tasks. Here are some options to consider:
     - **LocalStorage:** Perfect for storing tasks on the same device. Use this to save tasks and user sessions locally.
     - **IndexedDB:** Another option to explore if you want to learn about more structured browser storage.
     - **Firebase Authentication & Firestore:** For those up for an additional challenge, try using Firebase to manage user accounts and tasks. Firebase gives you user auth and database features that will make this feel more like a real app.

---

### 🎨 Design Tips

1. **Build on Your Figma Mockup:**
   - Since you’ve already designed your to-do list in Figma, refer to your design as you build the app. This will help you understand the layout, spacing, and visual hierarchy you want.

2. **Think User-Friendly:**
   - Make sure the layout is intuitive. Consider how you would want to interact with the app daily, from logging in to marking off completed tasks.

3. **Add Fun Animations:**
   - Spice up the experience by adding animations when tasks are added, removed, or marked as complete. (Hint: CSS transitions and animations in JavaScript can make your app feel smoother and more enjoyable.)

---

### 🧰 Resources to Help You

1. **User Authentication:**
   - [Firebase Authentication Docs](https://firebase.google.com/docs/auth)
   - [LocalStorage Guide](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)

2. **Task Storage:**
   - [Using LocalStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
   - [IndexedDB Documentation](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
   - [Firestore for Task Storage](https://firebase.google.com/docs/firestore) (if you’re using Firebase)

3. **JavaScript for Task Management:**
   - [JavaScript Array Methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) (useful for adding/removing tasks)
   - [CSS Animations for Adding Fun Effects](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)

---

### 🎯 Extra Challenges (for those looking for a bit more!)

- **Dark Mode:** Add a button to toggle between light and dark themes.
- **Due Dates & Notifications:** Set up notifications for tasks due today or overdue tasks. 
- **Drag-and-Drop Task Reordering:** Use drag-and-drop functionality to rearrange tasks easily.
- **Search & Filter:** Add a search bar to filter tasks by keywords or by category.

---

### 🚀 Final Steps

1. **Deploy the App**: Once you’re done, make sure you deploy it to GitHub Pages or Vercel to share your work!
   - [How to Deploy on GitHub Pages](https://pages.github.com/)
   - [Deploying on Vercel](https://vercel.com/)

2. **Share with the Team**: Show us your amazing designs and let’s celebrate each other’s progress.

---

Get creative, have fun, and feel free to add your own twist to the app. I can’t wait to see all the unique versions you come up with!
