# 🛒 QuickCart – Real-Time Grocery Ordering Platform


### **Authentication & Authorization**
- JWT-based Sign Up / Login
- Role-based access:
  - Admin: Manage products
  - Customer: Browse products, manage cart, place orders

### **Products**
- Create, edit, and delete products (Admin)
- View products with filters and search
- Product images and descriptions

### **Cart**
- Add/remove items from cart
- Cart persistence across sessions

### **Orders**
- Create order from cart
- Payment processing with **Stripe**
- Customer can recieve the order in 10 minutes 

### **UI & UX**
- **Dark/Light mode** toggle with `localStorage`
- Responsive design with **TailwindCSS**
- Toast notifications & loading spinners
- Error handling for API requests

### **Deployment**
- **Frontend**: Vercel
- **Backend**: Render 
- **Database**: MongoDB Atlas

---

## 🛠 Tech Stack

**Frontend:**
- React.js
- TailwindCSS
- Redux Toolkit
- Axios


**Backend:**
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT authentication
- Stripe API

