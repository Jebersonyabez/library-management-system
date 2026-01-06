# 📚 Library Book Management System

A full-stack library book management system built with **React** (frontend), **Express.js** (backend), **HTML5**, **CSS3**, and **JavaScript**. Features complete CRUD operations, beautiful gradient UI, and real-time updates.

## 🚀 Features

✅ **Add Books** - Create new books with title, author, and year  
✅ **View All Books** - Display books in an organized table  
✅ **Toggle Availability** - Change book status (Available/Borrowed)  
✅ **Delete Books** - Remove books with confirmation dialog  
✅ **Real-time Updates** - Instant UI refresh on changes  
✅ **Form Validation** - Required field validation  
✅ **Beautiful UI** - Purple gradient background with professional styling  
✅ **Responsive Design** - Works on all screen sizes  

## 🛠️ Tech Stack

- **Frontend**: React.js, HTML5, CSS3
- **Backend**: Node.js, Express.js
- **JavaScript**: ES6+
- **Styling**: CSS3 with gradient backgrounds
- **Deployment**: Render (backend), Netlify (frontend)

## 📁 Project Structure

```
library-management-system/
├── index.html          # Complete HTML with embedded CSS and JS
├── README.md          # This file
└── library-backend/   # Backend folder (optional for local setup)
    ├── index.js       # Express server
    ├── package.json   # Dependencies
    └── .env          # Configuration
```

## 🎯 Quick Start

### Option 1: Use index.html (Fastest)
1. Download or clone this repository
2. Open `index.html` in your web browser
3. Start managing books!

### Option 2: Full-Stack Setup

#### Backend Setup
```bash
cd library-backend
npm install
echo "PORT=5000" > .env
node index.js
```

#### Frontend Setup
```bash
cd library-frontend
npm install
npm start
```

## 📝 Sample Data

The application comes pre-loaded with 3 sample books:
- The Hobbit by J.R.R. Tolkien (1937) - Available
- 1984 by George Orwell (1949) - Borrowed
- To Kill a Mockingbird by Harper Lee (1960) - Available

## API Endpoints

```
GET    /api/books              - Get all books
POST   /api/books              - Add new book
DELETE /api/books/:id          - Delete book
PATCH  /api/books/:id/toggle   - Toggle availability
```

## 🎨 Features Showcase

### Add Book Form
- Title input field
- Author input field
- Year input field
- Add button with hover effect

### Books Table
- ID, Title, Author, Year columns
- Availability status (Available/Borrowed)
- Toggle button (green)
- Delete button (red)

### UI Design
- Purple gradient background (#667eea → #764ba2)
- White card-style sections
- Professional typography
- Smooth hover effects
- Responsive grid layout

## 🔧 Installation

### Requirements
- Node.js (v14+)
- npm or yarn

### Steps
1. Clone the repository
   ```bash
   git clone https://github.com/Jebersonyabez/library-management-system.git
   cd library-management-system
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the application
   ```bash
   npm start
   ```

## 📊 Usage Example

1. **Add a Book**:
   - Enter book title and author
   - Set publication year
   - Click "Add Book"

2. **Toggle Availability**:
   - Click "Toggle" button next to any book
   - Status changes between Available and Borrowed

3. **Delete a Book**:
   - Click "Delete" button
   - Confirm deletion in dialog

## 🌐 Deployment

### Deploy Backend (Render.com)
1. Push code to GitHub
2. Go to render.com
3. Create Web Service
4. Connect GitHub repo
5. Build: `npm install`
6. Start: `npm start`

### Deploy Frontend (Netlify)
1. Build React app: `npm run build`
2. Go to netlify.com
3. Drag and drop `build` folder
4. Set ENV variable: `REACT_APP_API_URL`

## 📚 Learning Resources

- [React Documentation](https://react.dev)
- [Express.js Guide](https://expressjs.com)
- [CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [REST API Best Practices](https://restfulapi.net)

## 🐛 Troubleshooting

**Issue**: Books not loading
- Check backend is running on port 5000
- Verify API_BASE URL in code

**Issue**: Styles not applying
- Clear browser cache
- Check CSS is properly loaded

**Issue**: Cannot add books
- Fill in all required fields
- Check browser console for errors

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

Created by **Jebersonyabez**

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests.

## ⭐ Support

If you found this helpful, please give it a star! ⭐

---

**Made with ❤️ using React, Express.js, and JavaScript**
