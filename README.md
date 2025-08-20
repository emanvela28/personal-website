# Emmanuel Velazquez - Personal Website

A modern, responsive personal portfolio website built with Flask, showcasing my skills, experience, and projects.

## 🚀 Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Works perfectly on all devices
- **Interactive**: Smooth scrolling, hover effects, and animations
- **Professional**: Showcases skills, experience, and projects

## 🛠️ Tech Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Custom CSS with modern design principles
- **Icons**: Font Awesome
- **Fonts**: Inter (Google Fonts)

## 📁 Project Structure

```
personal_site/
├── app.py                 # Flask application
├── requirements.txt       # Python dependencies
├── vercel.json           # Vercel deployment config
├── static/
│   ├── style.css         # Main stylesheet
│   ├── script.js         # JavaScript functionality
│   └── images/           # Images and assets
└── templates/
    └── index.html        # Main HTML template
```

## 🚀 Deployment

### Option 1: Vercel (Recommended)

1. **Push to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/emanvela28/personal-website.git
   git push -u origin main
   ```

2. **Deploy to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Sign up with GitHub
   - Click "New Project"
   - Import your repository
   - Deploy!

### Option 2: Railway

1. **Install Railway CLI**:
   ```bash
   npm install -g @railway/cli
   ```

2. **Deploy**:
   ```bash
   railway login
   railway init
   railway up
   ```

### Option 3: Render

1. **Create account** at [render.com](https://render.com)
2. **Connect GitHub** repository
3. **Create Web Service**
4. **Deploy automatically**

## 🏃‍♂️ Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/emanvela28/personal-website.git
   cd personal-website
   ```

2. **Set up virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run locally**:
   ```bash
   python app.py
   ```

5. **Visit**: http://localhost:5000

## 📝 Customization

- **Profile Photo**: Replace `static/images/profile.jpeg`
- **Content**: Edit `templates/index.html`
- **Styling**: Modify `static/style.css`
- **Functionality**: Update `static/script.js`

## 📧 Contact

- **Email**: emanvelazquez28@gmail.com
- **LinkedIn**: [Emmanuel Velazquez](https://linkedin.com/in/emmanuel-velazquez-39a415250)
- **GitHub**: [emanvela28](https://github.com/emanvela28)

---

Built with ❤️ by Emmanuel Velazquez
