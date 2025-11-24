# 🍛 Indian Food Calorie Estimator

A modern, user-friendly web application for tracking nutritional information of popular Indian dishes. Upload a photo of your meal and instantly get detailed calorie and macronutrient data.

![Indian Food Calorie Estimator](https://img.shields.io/badge/React-18.0-blue) ![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC) ![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- 📸 **Image Upload** - Upload photos of your Indian meals
- 🔍 **Smart Search** - Quick search functionality to find your dish
- 📊 **Detailed Nutrition** - Get calories, protein, carbs, and fat content
- 🍽️ **30+ Dishes** - Comprehensive database of popular Indian foods
- 🎨 **Beautiful UI** - Clean, modern interface with gradient design
- 📱 **Responsive** - Works perfectly on desktop, tablet, and mobile
- ⚡ **Fast & Lightweight** - No backend required, runs entirely in browser

## 🍽️ Supported Dishes

### Breads & Staples
- Roti, Naan, Paratha, Puri, Dosa, Idli
- Rice, Jeera Rice, Biryani, Pulao, Khichdi

### Curries & Main Dishes
- Paneer Butter Masala, Paneer Tikka
- Dal, Dal Makhani, Chole, Rajma
- Butter Chicken, Chicken Curry, Tandoori Chicken

### Snacks & Street Food
- Samosa, Pakora, Vada, Medu Vada
- Pav Bhaji, Vada Pav
- Upma, Poha
- Masala Dosa, Aloo Paratha

### Sweets
- Gulab Jamun, Jalebi

### Sides
- Raita

## 🚀 Quick Start

### Option 1: Run HTML File (Easiest)

1. Download `indian-food-calorie.html`
2. Double-click to open in your browser
3. Start using immediately!

### Option 2: React + Vite (For Development)

```bash
# Create new Vite project
npm create vite@latest indian-food-calorie -- --template react

# Navigate to project
cd indian-food-calorie

# Install dependencies
npm install
npm install lucide-react

# Replace src/App.jsx with the project code

# Run development server
npm run dev
```

Visit `http://localhost:5173`

### Option 3: Create React App

```bash
# Create project
npx create-react-app indian-food-calorie

# Navigate and install dependencies
cd indian-food-calorie
npm install lucide-react

# Replace src/App.js with project code

# Start server
npm start
```

Visit `http://localhost:3000`

## 💻 Usage

1. **Upload Image**: Click the upload area and select a photo of your Indian food
2. **Search**: Type the name of your dish in the search box
3. **Select**: Click on your dish from the list
4. **View Results**: Get instant nutritional information!

## 🛠️ Technology Stack

- **React 18** - Frontend framework
- **Tailwind CSS** - Styling
- **Lucide React** - Icons
- **FileReader API** - Image handling

## 📊 Nutritional Data

All nutritional data is sourced from:
- Indian Food Composition Tables (IFCT)
- National Institute of Nutrition (NIN) Database
- USDA Food Database

Data includes:
- Calories (kcal)
- Protein (g)
- Carbohydrates (g)
- Fat (g)
- Serving size

## 🎯 Use Cases

- **Fitness Tracking** - Monitor daily calorie intake
- **Diabetes Management** - Track carb consumption
- **Weight Loss/Gain** - Maintain calorie goals
- **Meal Planning** - Plan balanced Indian meals
- **Health Awareness** - Learn about food nutrition

## 📁 Project Structure

```
indian-food-calorie/
├── src/
│   ├── App.jsx           # Main application component
│   └── index.css         # Global styles
├── public/
│   └── index.html
├── package.json
└── README.md
```

## 🔧 Configuration

### Add More Foods

Edit the `indianFoodDatabase` object in `App.jsx`:

```javascript
const indianFoodDatabase = {
  'your-dish-name': {
    calories: 300,
    protein: 15,
    carbs: 40,
    fat: 10,
    serving: '1 plate (250g)',
    icon: '🍛'
  }
};
```

### Customize Styling

The app uses Tailwind CSS. Modify classes in the JSX or add custom CSS in `index.css`.

## ⚠️ Important Notes

- Calorie estimates are **approximate** and may vary based on:
  - Cooking method (fried vs. baked)
  - Amount of oil/ghee used
  - Regional recipe variations
  - Portion sizes
- Always consult a nutritionist for personalized dietary advice
- The app works offline once loaded (no API calls required)

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-dish`)
3. Commit your changes (`git commit -m 'Add new dish'`)
4. Push to the branch (`git push origin feature/new-dish`)
5. Open a Pull Request

### Areas for Contribution
- Add more Indian dishes
- Improve nutritional accuracy
- Add regional cuisine filters
- Implement meal logging
- Add export functionality
- Create mobile app version

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Created with ❤️ for the Indian food-loving community

## 🙏 Acknowledgments

- Nutritional data from IFCT and NIN
- Icons from Lucide React
- UI inspiration from modern health apps

## 📞 Support

Having issues? Please open an issue on GitHub with:
- Your browser version
- Steps to reproduce
- Screenshot (if applicable)

## 🗺️ Roadmap

- [ ] AI-powered automatic food recognition
- [ ] Daily calorie tracking dashboard
- [ ] Meal planning suggestions
- [ ] Recipe calorie calculator
- [ ] Multi-language support (Hindi, Tamil, etc.)
- [ ] Dark mode
- [ ] PWA (Progressive Web App) support
- [ ] Barcode scanner for packaged foods
- [ ] Integration with fitness apps

## 📈 Stats

- **30+** Indian dishes
- **100%** browser-based (no backend)
- **<1 second** nutrition lookup
- **0** API calls needed

---

### 🌟 Star this repo if you found it helpful!

**Made with React + Tailwind CSS** | **No API Required** | **Works Offline**

ScreenShot:
<img width="1897" height="978" alt="image" src="https://github.com/user-attachments/assets/2527c492-fdd0-456d-babd-aab160bff622" />
