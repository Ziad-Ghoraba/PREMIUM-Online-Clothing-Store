# ZIRA Online Clothing Store

**ZIRA** is a modern e-commerce platform for online clothing shopping, built with scalability, performance, and clean architecture. It combines cutting-edge technologies and agile practices to deliver a seamless user experience.

🔗 **Live Demo:** [ZIRA Online Store](https://zira.runasp.net)

📑 **Presentation**  
For additional details on ZIRA’s development, including the tech stack and design process, refer to the [ZIRA Project Presentation](/ZIRA-Presentation.pdf).  

---

## 🛠️ Technologies

ZIRA leverages a robust tech stack for performance and modularity:

### Backend:
- **ASP.NET MVC**: Drives server-side logic and routing.
- **ASP.NET Core Identity**: Manages authentication with custom password policies and unique email requirements.
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
- **Figma**: Used for wireframing and ERD design.

---

## 📋 User Stories

ZIRA’s development was guided by the following user stories:
[ZIRA User Stories](/ZIRA-User-Stories.pdf).

---

## 🧩 Project Structure

ZIRA is organized for clarity and maintainability:

- **Controllers**: `OrderController`, `ItemController`, `AccountController` for request handling.
- **Models**: `ApplicationUser`, `Item`, `Order` for core data.
- **Views**: Razor-based for dynamic rendering.
- **Repository Layer**: Implements the Generic Repository Pattern.
- **Configuration**: Managed in `Program.cs` for routing, HTTPS, and authentication.
- **Custom Attributes**: Includes `NavModelFilterAttribute` for streamlined controller logic.

---

## 📐 Design & Documentation

- **User Stories**: Aligned features with user needs.
- **Wireframes**: Designed in Figma for intuitive UI flow.
- **ERD**: Created in Figma for database structure planning.
- **Agile Documentation**: Managed in Notion for sprint planning and task tracking.

---

## ⚙️ Development Process

ZIRA was built using an Agile methodology with Notion for sprint and task management.

### Core Features:
- Responsive UI across all pages
- Admin panel for managing users and products
- Product variant selection and customer reviews
- Filtered order history for faster tracking
- Best-seller highlights
- Unit testing for reliability

### Post-Launch Polish:
One week dedicated to UI refinements, bug fixes, and performance optimization.

---

## 🧪 Testing & Deployment

- **Unit Testing**: Ensured key functionality before release.
- **Performance Optimization**: Used `IMemoryCache` for frequently accessed data.
- **Deployment**: Hosted at `zira.runasp.net`.

---

## 🎥 Try It Yourself!

Head over to the [Live Demo](#zira-online-clothing-store) and explore ZIRA — browse products, try out variant selection, manage orders, and more!

---

## 📬 Contact

For feedback or inquiries, please open an [issue](../../issues) in this repository.

---

**Built with 💻 and ☕ by [Ziad Ghoraba](https://www.linkedin.com/in/ziad-ghoraba-developer/)**
