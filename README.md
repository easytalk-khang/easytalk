# EasyTalk - English Learning Platform

Welcome to EasyTalk, a free English learning website for sharing class information, lesson materials, and student updates.

## 🌟 Features

### Current Phase (Live Now)
- ✅ **Class Schedules** - Display your courses with times and levels
- ✅ **Course Information** - Organized course details and enrollment info
- ✅ **Lesson Materials** - Grammar, listening, writing, vocabulary, tests, and videos
- ✅ **Announcements** - Share updates and important news with students
- ✅ **Contact Form** - Students can reach out with questions
- ✅ **Mobile Responsive** - Works perfectly on all devices
- ✅ **Professional Design** - Modern, clean, and user-friendly interface

### Future Phase (Coming Soon)
- 🔄 **Student Login** - Secure authentication system
- 📊 **Grade Tracking** - View student progress and grades
- 📤 **Assignment Submission** - Students submit work directly
- 📈 **Progress Dashboards** - Visualize learning progress

## 🚀 Quick Start

### View Your Live Site
Your website is now live at: **`https://khangth-english.github.io/easytalk`**

### Update Your Information

Edit these sections easily:

#### Update Class Information
Open `index.html` and find the "Class Schedule" section. Modify:
```html
<h3>Your Course Name</h3>
<p><strong>Level:</strong> A1-A2</p>
<p><strong>Time:</strong> Your schedule here</p>
<p><strong>Duration:</strong> Course length</p>
```

#### Add Announcements
Find the "Announcements" section and add new announcement items:
```html
<div class="announcement-item">
    <div class="announcement-date">Today's Date</div>
    <h3>Your Announcement Title</h3>
    <p>Your announcement content</p>
</div>
```

#### Add Learning Materials
Add new resource cards in the "Materials" section:
```html
<div class="material-card">
    <div class="material-icon">📚</div>
    <h3>Your Resource Title</h3>
    <p>Description</p>
    <a href="your-link" class="btn-secondary">Learn More</a>
</div>
```

#### Update Contact Information
Find the contact section and update:
- Email address
- Phone number
- Office hours

## 📁 File Structure

```
easytalk/
├── index.html          # Main website page
├── styles.css          # All styling and layout
├── script.js           # Interactive features and animations
├── _config.yml         # GitHub Pages configuration
└── README.md           # This file
```

## 🎨 Customization

### Colors
Edit colors in `styles.css` - find the `:root` section:
```css
:root {
    --primary-color: #2563eb;      /* Main blue */
    --secondary-color: #1e40af;    /* Darker blue */
    --accent-color: #f59e0b;       /* Orange highlights */
}
```

### Fonts
Change the font family in `styles.css`:
```css
body {
    font-family: 'Your Font Name', sans-serif;
}
```

## 📱 Responsive Design

The website works perfectly on:
- Desktop computers (1920px and up)
- Tablets (768px - 1024px)
- Mobile phones (320px - 767px)

## ✨ Features Explained

### Smooth Scrolling
Click any navigation link and smoothly scroll to that section.

### Scroll-to-Top Button
A button appears when you scroll down - click to return to top instantly.

### Hover Effects
Cards and buttons have interactive hover effects for better user experience.

### Animations
Elements fade in as you scroll down the page for a polished look.

### Form Validation
Contact form validates email and required fields before submission.

## 📝 Next Steps for Advanced Features

When you're ready to add:
- **Student Login**: We can integrate GitHub OAuth or a simple authentication
- **Grade Tracking**: We'll add a dashboard with student progress
- **Assignments**: Create a submission system
- **Student Dashboard**: Personalized progress tracking

## 🔗 Useful Links

- **GitHub Repository**: https://github.com/khangth-english/easytalk
- **Live Website**: https://khangth-english.github.io/easytalk
- **GitHub Pages Docs**: https://pages.github.com/

## 💡 Tips for Success

1. **Keep Content Updated** - Regularly update announcements and schedule
2. **Use Clear Language** - Make course descriptions easy to understand
3. **Add Media** - Include images and videos in learning materials
4. **Engage Students** - Respond promptly to contact form submissions
5. **Mobile First** - Always test on mobile before publishing changes

## 🆘 Need Help?

To update your website:
1. Edit the HTML/CSS/JS files directly in GitHub
2. Changes publish automatically within seconds
3. Or ask for help implementing new features

## 📄 License

This project is open source and free to use for educational purposes.

---

**Happy Teaching! 🎓**

For questions or feature requests, feel free to reach out!
