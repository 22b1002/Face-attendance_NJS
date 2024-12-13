# Face Attendance System (Next.js)
This project implements a facial recognition-based attendance system using TensorFlow.js and Next.js. The system allows users to log attendance by detecting their faces through the mobile device camera. The user can stay logged in via the Progressive Web App (PWA) features on their phone.

Inside your Next.js project directory, organize your files as follows:  
project-root/

├── components/            <-- Custom components go here  
│   ├── Camera.js  
│   ├── AttendanceLogger.js  
├── pages/                 <-- Next.js handles routes via this directory  
│   ├── index.js  
│   ├── _app.js  
├── styles/                <-- Custom styles go here  
│   ├── globals.css  
├── public/                <-- Static files like images go here  
├── node_modules/          <-- Installed dependencies (auto-generated)  
├── package.json           <-- Project configuration  
├── tailwind.config.js     <-- TailwindCSS configuration  
├── postcss.config.js      <-- PostCSS configuration  
