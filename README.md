# Harsh - Professional Portfolio Website

A modern, customizable portfolio website built with Next.js, React, and Tailwind CSS. Features a clean, Google-like aesthetic with smooth animations and responsive design.

## 🎨 Features

✨ **Modern Design** - Clean, minimalist Google-like aesthetics  
🎭 **Smooth Animations** - Framer Motion powered animations  
📱 **Fully Responsive** - Works perfectly on all devices  
⚡ **Fast Performance** - Optimized with Next.js  
🎯 **Easy to Customize** - Simple component structure  
🔗 **Project Showcase** - Display your work with links and screenshots  
📞 **Contact Section** - Easy way for people to reach you  
🌓 **Modern UX** - Scroll animations and interactive elements  

## 📋 Sections

- **Hero** - Eye-catching introduction
- **About** - Personal bio and skills
- **Projects** - Showcase your work with images, descriptions, and links
- **Contact** - Social media links and contact information
- **Footer** - Copyright and quick navigation

## 🚀 Getting Started

### Prerequisites
- Node.js 16+ installed
- npm or yarn package manager

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/pathakharshh/Harsh.git
cd Harsh
```

2. **Install dependencies**
```bash
npm install
```

3. **Run the development server**
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the site.

## 🎨 Customization Guide

### Edit Your Information

#### 1. **Update Hero Section** (`app/components/Hero.js`)
```javascript
<h1 className="text-4xl sm:text-5xl lg:text-6xl font-bold text-gray-900 mb-6">
  Hi, I'm <span className="text-blue-600">Harsh</span>
</h1>
```

#### 2. **Update About Section** (`app/components/About.js`)
- Change the bio text
- Update the skills array:
```javascript
const skills = [
  'JavaScript',
  'React',
  'Next.js',
  // Add your skills here
]
```

#### 3. **Add Your Projects** (`app/components/Projects.js`)
```javascript
const projects = [
  {
    id: 1,
    title: 'Your Project Title',
    description: 'Project description',
    tags: ['React', 'Node.js', 'MongoDB'],
    image: 'https://your-image-url.com/image.jpg',
    links: {
      github: 'https://github.com/your-repo',
      live: 'https://your-live-site.com',
      screenshots: 'https://drive.google.com/drive/folders/your-folder-id',
    },
  },
]
```

#### 4. **Update Contact Links** (`app/components/Contact.js` & `app/components/Footer.js`)
- Update email address
- Add your GitHub profile
- Add your LinkedIn profile
- Add your Twitter/X handle

### 📸 Adding Project Screenshots from Google Drive

1. Create a folder in Google Drive with your project screenshots
2. Right-click the folder → Share
3. Copy the folder ID from the URL: `https://drive.google.com/drive/folders/FOLDER_ID`
4. Replace `your-folder-id` in the project links
5. Users can click to view all screenshots

### 🎨 Change Colors

Edit `tailwind.config.js` to customize the color scheme:

```javascript
colors: {
  primary: '#1f2937',
  secondary: '#6b7280',
  accent: '#3b82f6',
  light: '#f9fafb',
}
```

Or use Tailwind classes directly: `bg-blue-600`, `text-gray-900`, etc.

## 📁 Project Structure

```
Harsh/
├── app/
│   ├── components/
│   │   ├── Navbar.js
│   │   ├── Hero.js
│   │   ├── About.js
│   │   ├── Projects.js
│   │   ├── Contact.js
│   │   └── Footer.js
│   ├── layout.js
│   ├── page.js
│   └── globals.css
├── public/
├── package.json
├── tailwind.config.js
├── next.config.js
└── README.md
```

## 🛠️ Built With

- **[Next.js](https://nextjs.org/)** - React framework
- **[React](https://react.dev/)** - UI library
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS
- **[Framer Motion](https://www.framer.com/motion/)** - Animation library
- **[React Icons](https://react-icons.github.io/react-icons/)** - Icon library

## 🚀 Deployment

### Deploy to Vercel (Recommended)
1. Push to GitHub
2. Go to [Vercel](https://vercel.com)
3. Select your repository
4. Click "Deploy"

### Deploy to Netlify
1. Connect GitHub repository
2. Build command: `npm run build`
3. Publish directory: `.next`

## 📝 Customization Tips

✅ Use high-quality project images  
✅ Write clear project descriptions  
✅ Keep skills list concise  
✅ Add real contact links  
✅ Test on mobile devices  
✅ Add professional profile picture  

---

**Happy building! 🚀**
