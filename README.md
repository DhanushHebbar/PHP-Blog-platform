Simple Blog Platform
Project Title: Simple Blog Platform
Tech Stack: PHP (Core), MySQL, Tailwind CSS, HTML5
Deployment: Live via InfinityFree (Custom database routing)

Overview:
Designed and developed a custom, lightweight Content Management System (CMS) from the ground up without relying on heavy frameworks. This project demonstrates strong foundational backend engineering, secure session management, and responsive frontend design.

Key Features & Technical Implementations:

Custom Authentication System: Built secure user registration and login flows utilizing password_hash() and password_verify() with role-based access control (Admin vs. Author).

Dynamic Content Management: Engineered a relational database architecture (MySQL) to handle articles, dynamic category generation, and user associations, enforcing referential integrity with cascading deletes.

Integrated Moderation Queue: Developed a comment system with an admin approval workflow, preventing spam and ensuring content quality control.

Responsive UI/UX: Implemented a modern, mobile-first interface using Tailwind CSS, featuring a flexbox sticky footer and CSS grid layouts for optimal content display across all devices.

Security Best Practices: Secured the application against common vulnerabilities by sanitizing all inputs with htmlspecialchars(), utilizing prepared statements for all database transactions to prevent SQL injection, and managing secure state via strictly controlled PHP sessions.
