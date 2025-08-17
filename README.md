# PREMIUM Online Clothing Store

**PREMIUM** is a modern, responsive e-commerce platform for online clothing shopping, built with ASP.NET MVC and Clean Architecture. It combines scalability, performance, and agile practices to deliver a seamless shopping experience.

🔗 **Live Demo:** [PREMIUM Online Store](https://premiumegy.com)

📑 **Presentation**  
For additional details on PREMIUM’s development, including the tech stack and design process, refer to the [PREMIUM Project Presentation](/PREMIUM-Presentation.pdf).  

---

## 🛠️ Technologies

PREMIUM leverages a robust tech stack for performance and modularity:

### Backend:
- **ASP.NET MVC**: Drives server-side logic and routing.
- **ASP.NET Core Identity**: Manages authentication with custom password policies and unique email requirements.
- **Google Sign-In Integration**: Enables quick and secure authentication via Google accounts.
- **Dependency Injection**: Built-in for modular, testable code.
- **Generic Repository Pattern**: Enables reusable data access.
- **SendGrid API**: Powers transactional emails via a custom `EmailServiceRepository`.
- **IMemoryCache**: Optimizes performance for frequently accessed data.

### Frontend:
- **Razor Views**: Renders dynamic, responsive UI.
- **Static File Serving**: Delivers CSS, JavaScript, and image assets.
- **AJAX**: Supports dynamic partial updates for a smooth user experience.

### Development Tools:
- **Notion**: Manages agile sprints, tasks, and documentation.
- **Figma**: Used for wireframing, UI design, and ERD creation.

---

## 📋 User Stories

PREMIUM’s development was guided by the following user stories:  
[PREMIUM User Stories](/PREMIUM-User-Stories.pdf).

---

## 🧩 Project Structure

PREMIUM is organized for clarity and maintainability:

- **Controllers**: `OrderController`, `ItemController`, `AccountController` for request handling.
- **Models**: `ApplicationUser`, `Item`, `Order` for core data.
- **Views**: Razor-based for dynamic rendering.
- **Repository Layer**: Implements the Generic Repository Pattern.
- **Configuration**: Managed in `Program.cs` for routing, HTTPS, and authentication.
- **Custom Attributes**: Includes `NavModelFilterAttribute` for streamlined controller logic.

---

## 📐 Design & Documentation

- **User Stories**: Aligned features with user needs.
- **Wireframes & UI Design**: Created in Figma for intuitive user experience.
- **ERD**: Designed in Figma for database structure planning.
- **Agile Documentation**: Managed in Notion for sprint planning and task tracking.

---

## ⚙️ Core Features

- Modern, responsive UI across all pages.
- Google Sign-In for quick, secure authentication.
- Guest cart allowing users to shop without creating an account.
- Smart shipping system for faster and optimized delivery options.
- Discounts on categories, subcategories, and individual items for flexible promotions.
- Review filtering to help customers make informed decisions.
- Admin dashboard for managing users, products, and orders.
- Product variant selection and customer reviews.
- Filtered order history for faster tracking.
- Best-seller highlights.
- Unit testing for reliability.

---

## 🧪 Testing & Deployment
- **Performance Optimization**: Achieved up to **20% faster performance** through WebP image compression, query optimization, and `AsNoTracking`.
- **Caching**: Used `IMemoryCache` for frequently accessed data.
- **Deployment**: Hosted at `premiumegy.com`.

---

## 🎥 Try It Yourself!

Head over to the [Live Demo](https://premiumegy.com) and explore PREMIUM — browse products, try Google Sign-In, use the guest cart, explore category discounts, and more!

---

## 📬 Contact

For feedback or inquiries, please open an [issue](../../issues) in this repository.

---

**Built with 💻 and ☕ by [Ziad Ghoraba](https://www.linkedin.com/in/ziad-ghoraba-developer/) & [Sara Elghazaly](https://www.linkedin.com/in/sarahesham/)**
