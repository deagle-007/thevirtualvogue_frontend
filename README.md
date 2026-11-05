# 👗 Virtual Vogue – Frontend

**Bringing the Fitting Room to You**

Virtual Vogue is an AI-powered virtual fashion try-on platform designed to transform the online shopping experience. The frontend provides an interactive and responsive interface where users can explore fashion collections, select garments, upload images, and experience virtual outfit visualization.

Built with **Next.js, React, and TypeScript**, the application provides the user-facing experience of Virtual Vogue and connects with the separate backend and AI/ML system responsible for virtual try-on processing.

🌐 **Live Application:** [https://virtualvogue.vercel.app](https://virtualvogue.vercel.app)

---

## ✨ Features

- **Modern User Interface:** Clean, interactive, and visually appealing fashion-oriented design.
- **Fashion Collections:** Browse available clothing collections and categories.
- **Virtual Try-On Interface:** User-facing workflow for AI-powered clothing visualization.
- **Image Upload:** Upload user and garment images for virtual try-on processing.
- **Outfit Selection:** Select garments for the virtual fitting experience.
- **Result Visualization:** View generated virtual try-on results.
- **Responsive Design:** Optimized interface for different screen sizes.
- **API Integration:** Communication with backend services for application functionality.
- **Interactive Components:** Smooth navigation, animations, and reusable UI elements.

## 🛠️ Technology Stack

### Core Technologies

| Technology | Purpose |
|---|---|
| TypeScript 5 | Type-safe development |
| Next.js 15 | React-based frontend framework |
| React 18 | Component-based UI development |
| Tailwind CSS 3 | Utility-first styling |
| Node.js | JavaScript runtime |

### UI & Component Libraries

- **Radix UI:** Accessible and customizable UI primitives.
- **Headless UI:** Accessible interactive components.
- **Lucide React:** Icon library.
- **React Icons:** Additional icon components.
- **AOS:** Animate On Scroll library.
- **Embla Carousel:** Carousel functionality.
- **Keen Slider:** Touch-enabled sliders.

### State Management & API Integration

- **Zustand:** Lightweight state management.
- **Axios:** HTTP requests and API communication.
- **React Hook Form:** Form handling and validation.
- **Zod:** Schema validation.
- **MongoDB:** Database integration library.
- **Cloudinary:** Image and media management integration.
- **Clerk / Auth0:** Authentication integration libraries.

### Additional Libraries

- Recharts – Data visualization.
- React Day Picker – Date selection.
- Next Themes – Theme management.
- Sonner – Toast notifications.
- Class Variance Authority – Component styling variants.
- Tailwind Merge – Utility class merging.

## 🚀 Getting Started

Follow the instructions below to set up the frontend development environment locally.

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- npm
- [Git](https://git-scm.com/)

### 1. Clone the Repository

```bash
git clone https://github.com/deagle-007/thevirtualvogue_frontend.git
```

### 2. Navigate to the Project Directory

```bash
cd thevirtualvogue_frontend
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env.local` file in the root directory.

Add the environment variables required by the application, such as:

- Backend API URL.
- Authentication configuration.
- Database connection settings, if required by the application.
- Cloudinary credentials, if required.

Keep all sensitive credentials private. Never commit `.env.local` to GitHub.

### 5. Run the Development Server

```bash
npm run dev
```

Open your browser and navigate to:

```text
http://localhost:3000
```

### 6. Build for Production

```bash
npm run build
```

### 7. Start the Production Server

```bash
npm run start
```

## 📁 Project Architecture

The frontend is developed using the Next.js application architecture, with React components and TypeScript for application logic.

Its primary responsibilities include:

- Rendering the Virtual Vogue user interface.
- Managing user interactions and application state.
- Handling image uploads and garment selection.
- Communicating with backend services.
- Presenting virtual try-on results.

## 🔗 Related Repository

The AI/ML implementation is maintained in a separate repository.

**[Virtual Vogue – Backend & AI/ML Repository](https://github.com/deagle-007/Virtual_Vogue)**

The separate repository contains the Python-based model development, training scripts, preprocessing pipeline, inference implementation, and computer-vision components.

## 🌐 Deployment

The frontend application is deployed using **Vercel**.

| Detail | Link |
|---|---|
| Live Application | [virtualvogue.vercel.app](https://virtualvogue.vercel.app) |
| Frontend Source Code | [GitHub Repository](https://github.com/deagle-007/thevirtualvogue_frontend) |
| Backend & AI/ML | [GitHub Repository](https://github.com/deagle-007/Virtual_Vogue) |



## 📄 License

Refer to the repository's license information for licensing and usage permissions.

---

<p align="center">
  <strong>Virtual Vogue</strong><br/>
  Bringing the Fitting Room to You.<br/>
  <i>Redefining Digital Fashion Through Artificial Intelligence.</i>
</p>
