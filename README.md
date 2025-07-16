# Free-IQ-Tester
# 🧠 IQ Test - Comprehensive Cognitive Assessment

A web-based IQ test application that evaluates multiple cognitive domains through scientifically-informed question types. This interactive assessment provides detailed analysis of cognitive abilities across different reasoning domains.

## 🌟 Features

- **Multi-Domain Assessment**: Tests 5 key cognitive areas
  - Logical Reasoning
  - Pattern Recognition
  - Mathematical Ability
  - Verbal Comprehension
  - Spatial Visualization

- **Adaptive Timing**: Variable time limits based on question complexity
- **Speed Bonus Scoring**: Rewards faster correct responses
- **Professional Scoring**: Converts raw scores to standardized IQ scale (mean=100, SD=15)
- **Detailed Analysis**: Domain-specific performance breakdown
- **Modern UI**: Clean, responsive design with smooth animations
- **Progress Tracking**: Real-time progress indicators and timers

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch" → main branch
4. Your test will be available at `https://yourusername.github.io/iq-test`

### Option 2: Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/iq-test.git
   cd iq-test
   ```

2. Open `index.html` in your web browser or serve it locally:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. Navigate to `http://localhost:8000` in your browser

## 📊 Assessment Details

### Question Types
- **Logical Reasoning** (4 questions): Syllogisms, deductive reasoning, logical puzzles
- **Pattern Recognition** (4 questions): Sequence completion, visual patterns
- **Mathematical Ability** (4 questions): Algebra, arithmetic, word problems
- **Verbal Comprehension** (4 questions): Analogies, vocabulary, categorization
- **Spatial Visualization** (4 questions): 3D reasoning, geometric problems

### Scoring System
- **Base Score**: 5 points per correct answer
- **Time Bonus**: Up to 2 additional points based on response speed
- **Final IQ Score**: Normalized to standard scale (μ=100, σ=15)

### Score Interpretation
- **140+**: Highly Gifted (99.9th percentile)
- **130-139**: Gifted (98th percentile)
- **120-129**: Above Average (91st percentile)
- **110-119**: High Average (75th percentile)
- **90-109**: Average (25th-75th percentile)
- **80-89**: Low Average (9th percentile)
- **Below 80**: Below Average

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic markup and accessibility
- **CSS3**: Modern styling with gradients and animations
- **Vanilla JavaScript**: No external dependencies
- **Responsive Design**: Works on desktop and mobile devices

### File Structure
```
iq-test/
├── index.html          # Main application file
├── README.md           # This file
└── LICENSE             # License information
```

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🎯 Usage Instructions

1. **Start Assessment**: Click "Begin Assessment" to start the test
2. **Answer Questions**: Select the best answer for each question
3. **Time Management**: Each question has a specific time limit
4. **Review Results**: View your IQ score and domain breakdown
5. **Retake Test**: Click "Take Test Again" to restart

## 🔬 Scientific Basis

This assessment is based on established cognitive testing principles:

- **Fluid Intelligence**: Pattern recognition and logical reasoning
- **Crystallized Intelligence**: Verbal comprehension and mathematical knowledge
- **Processing Speed**: Timed responses with speed bonuses
- **Working Memory**: Complex problem-solving tasks
- **Spatial Intelligence**: 3D visualization and geometric reasoning

## ⚠️ Important Disclaimers

- This is an **educational tool**, not a clinical assessment
- For official IQ testing, consult a qualified psychologist
- Results may vary based on factors like fatigue, stress, or technical issues
- Practice effects may influence scores on repeated testing
- Cultural and linguistic factors may affect performance

## 🤝 Contributing

Contributions are welcome! Areas for improvement:

- Additional question types
- Enhanced accessibility features
- Mobile optimization
- Multilingual support
- Advanced analytics

### Development Guidelines
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classical IQ test formats (Wechsler, Raven's Progressive Matrices)
- Question types based on established cognitive assessment literature
- UI design principles from modern web applications

## 📈 Future Enhancements

- [ ] Additional question banks
- [ ] User account system with score history
- [ ] Detailed performance analytics
- [ ] Adaptive difficulty adjustment
- [ ] Multi-language support
- [ ] Accessibility improvements
- [ ] Mobile app version

## 📞 Support

If you encounter issues or have suggestions:
- Open an issue on GitHub
- Check existing issues for solutions
- Contribute improvements via pull requests

---

**Note**: This tool is for educational and entertainment purposes. Professional cognitive assessment should always be conducted by qualified practitioners in controlled environments.
