# 🎯 Quiz Score App

A modern and responsive web application for tracking multi-player quiz scores in real-time. This application is designed to help quiz hosts easily manage and display participant scores interactively.

## ✨ Features

- **Multi-Player Support**: Add and remove players dynamically
- **Real-time Score Tracking**: Update scores instantly with smooth animations
- **Customizable Scoring**: Set score values for correct and wrong answers
- **History Tracking**: View complete history of all score activities
- **Statistics**: Display statistics of correct and wrong answers per player
- **Multiple Themes**: Choose from 5 different themes (Light, Dark, Blue, Green, Purple)
- **Responsive Design**: Optimal display on desktop, tablet, and mobile
- **Undo Function**: Easily undo the last action
- **Reset & Clear**: Reset all scores or clear history

## 🚀 How to Use

1. **Open HTML File**

   - Open the `quiz_score_app.html` file in a modern web browser (Chrome, Firefox, Safari, Edge)

2. **Set Player Names**

   - Click on the player name input to change it
   - Default: Player 1 and Player 2

3. **Set Score Values** (Optional)

   - In the "Score Settings" section, set values for:
     - Correct Answer Score (default: +100)
     - Wrong Answer Score (default: -50)

4. **Add Players** (Optional)

   - Click the "Add Player" button to add a new player
   - Click the "×" button in the top right corner of the player card to remove

5. **Update Scores**

   - Click the "✓ Correct" button to add score for correct answer
   - Click the "✗ Wrong" button to subtract score for wrong answer
   - Scores will update in real-time with animations

6. **Change Theme**

   - Click the 🎨 icon in the top right corner
   - Select the desired theme (Light, Dark, Blue, Green, Purple)
   - Theme will be saved in your browser

7. **Host Controls**
   - **Reset Scores**: Reset all scores to 0
   - **Undo Last**: Undo the last action
   - **Clear History**: Clear all history (scores remain)

## 📱 Responsive Design

This application is designed responsively and works well on:

- Desktop (1920px+)
- Laptop (1024px - 1920px)
- Tablet (768px - 1024px)
- Mobile (320px - 768px)

## 🎨 Available Themes

1. **Light** - Default light theme
2. **Dark** - Dark theme for nighttime use
3. **Blue** - Calming blue theme
4. **Green** - Fresh green theme
5. **Purple** - Elegant purple theme

## 🛠️ Technology

- **HTML5** - Application structure
- **CSS3** - Styling and animations
- **Vanilla JavaScript** - Application logic
- **LocalStorage** - Theme preference storage

## 📋 Detailed Features

### Score Tracking

- Scores displayed with large and clear font
- Animation when score changes
- Temporary score change indicator (+/-)
- Red color for negative scores

### History

- Per-player history (last 6 items)
- Complete history of all activities (last 15 items)
- Timestamp for each activity
- Different colors for correct (green) and wrong (red) answers

### Statistics

- Number of correct answers per player
- Number of wrong answers per player
- Real-time updates

## 💡 Usage Tips

- Use Dark theme for presentations in dark rooms
- Set score values before starting the quiz
- Use Undo feature if input errors occur
- History will automatically be limited for optimal performance

## 🔧 Customization

You can easily customize this application by editing the HTML file:

- Change theme colors in the CSS section
- Change default score values in input fields
- Modify animations in the `@keyframes` section
- Add new features in the JavaScript section

## 📝 License

This application is free to use for personal or commercial purposes.

## 🤝 Contributing

Contributions are welcome! If you have ideas to improve this application, please create an issue or pull request.

## 📧 Support

If you find bugs or have suggestions, please create an issue in this repository.

---

**Made with ❤️ to make quiz score management easier**
