
# Nested Web Application

## Overview
The Nested Web Application is a full-stack solution designed for a modern and intuitive home interior shopping experience. It features a clean UI, responsive layout, and core features like product search, cart, wishlist, and user authentication. Built with HTML, CSS, JavaScript on the frontend, and Node.js/Express on the backend, this project also includes Docker support and can be deployed via cloud platforms like Netlify and Render.

---

## Project Structure

```
NestedWebApp/
├── frontend/
│   ├── index.html
│   ├── products.html
│   ├── wishlist.html
│   ├── cart.html
│   ├── login.html
│   ├── register.html
├── backend/
│   ├── server.js
│   ├── users.json
│   ├── package.json
│   └── package-lock.json
├── docker/
│   ├── Dockerfile
│   └── docker-compose.yml
├── documentation/
│   ├── UC-11839 phase 2 report.docx
│   ├── Nested_Web_App_Detailed_Presentation.pptx
│   ├── Abstract.txt
│   └── SpeakerNotes.txt
├── README.md
```

---

## Installation & Usage Guide

### Manual Setup:
1. Navigate to the `/backend` directory.
2. Run `npm install`.
3. Start server: `node server.js` (runs on port 3000).
4. Open `index.html` in browser to launch frontend.

### Docker Setup:
1. Ensure Docker and Docker Compose are installed.
2. Run: `docker-compose up --build`.
3. Access frontend at: `http://localhost:8080`.
4. Backend runs at: `http://localhost:3000`.

---

## Sample Login Credentials
```
Username: aaaaa
Password: aaaaa
```

---

## Cloud Hosting (Optional)
- Frontend can be deployed on Netlify or Vercel.
- Backend can be hosted via Render or Railway.

---

## Technical Notes
- Uses localStorage to manage cart/wishlist.
- Session-based page restriction for unauthenticated users.
- Development uses JSON for storage; MongoDB recommended for production.

---

## License
This project is academic and developed under university course guidelines.
