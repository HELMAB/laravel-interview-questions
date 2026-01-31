# Laravel Interview Prep

An interactive quiz application with 50 carefully curated Laravel interview questions covering fundamentals to advanced topics.

## Features

- **50 Comprehensive Questions** across 7 categories
- **Interactive Quiz Interface** with real-time feedback
- **Progress Tracking** with visual indicators
- **Detailed Explanations** for each answer
- **Category-Based Performance Analysis**
- **Responsive Design** optimized for all devices
- **Beautiful UI** with gradient themes and smooth animations

## Categories Covered

1. **Fundamentals (10 questions)** - Artisan, .env, MVC, Blade, directory structure
2. **Routing & Controllers (8 questions)** - Route model binding, resource controllers, middleware
3. **Eloquent ORM (10 questions)** - Relationships, scopes, eager loading, mass assignment
4. **Migrations & Database (7 questions)** - Migrations, seeders, factories, foreign keys
5. **Middleware & Security (7 questions)** - CSRF, authentication, authorization, policies
6. **Queues & Jobs (4 questions)** - Background processing, queue workers, job handling
7. **Testing & Advanced (4 questions)** - Service container, testing strategies, Horizon

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or dependencies required

### Installation

1. Clone or download this repository:
```bash
git clone <repository-url>
cd laravel-interview-questions
```

2. Open the quiz:
```bash
# Option 1: Open directly in browser
open index.html

# Option 2: Use a local server
python3 -m http.server 8000
# Then visit: http://localhost:8000
```

## Usage

1. **Answer Questions**: Click on your chosen answer for each question
2. **View Explanation**: After answering, see the detailed explanation
3. **Track Progress**: Monitor your score and progress bar at the top
4. **Navigate**: Use Previous/Next buttons or click progress dots to jump to questions
5. **Review**: At the end, view your grade and performance by category
6. **Retry**: Review missed questions or restart the entire quiz

## Quiz Features

### Real-Time Feedback
- ✅ Correct answers highlighted in green
- ❌ Incorrect answers highlighted in red
- 💡 Detailed explanations appear after answering

### Progress Indicators
- Progress bar showing quiz completion
- Current score display
- Category badges for context
- Quick stats (correct, incorrect, remaining)

### Results Dashboard
- Letter grade (A+ to D) based on performance
- Percentage score
- Category-wise breakdown
- Performance charts for each topic
- Options to review missed questions or retry

## Grading Scale

| Grade | Percentage | Interpretation |
|-------|-----------|----------------|
| A+    | 90-100%   | Outstanding! Laravel-ready 🚀 |
| A     | 80-89%    | Excellent work! Very solid knowledge |
| B     | 70-79%    | Good job! Review the missed topics |
| C     | 60-69%    | Decent, but more practice needed |
| D     | 0-59%     | Keep studying! You'll get there |

## Technology Stack

- **HTML5** - Semantic structure
- **Tailwind CSS** (CDN) - Modern, utility-first styling
- **Vanilla JavaScript** - Interactive quiz logic
- **No dependencies** - Single file, works offline

## Question Quality

All questions are:
- Based on **real Laravel interview scenarios**
- Cover **Laravel 10/11** best practices
- Include **practical explanations** with context
- Aligned with **official Laravel documentation**
- Designed to test **practical knowledge**, not just memorization

## Learning Path

### For Beginners
Start with the Fundamentals category to build a strong foundation.

### For Intermediate Developers
Focus on Eloquent ORM, Routing & Controllers, and Migrations.

### For Advanced Developers
Challenge yourself with Middleware & Security, Queues & Jobs, and Testing questions.

## Contributing

Contributions are welcome! To add questions or improve the quiz:

1. Fork the repository
2. Add your questions following the existing format:
```javascript
{
    category: "Category Name",
    question: "Your question here?",
    options: [
        "A) First option",
        "B) Second option",
        "C) Third option",
        "D) Fourth option"
    ],
    correct: 1, // Index of correct answer (0-3)
    explanation: "Detailed explanation of why this is correct..."
}
```
3. Submit a pull request

## Best Practices for Interview Prep

1. **Don't Rush**: Take time to read each question carefully
2. **Understand Why**: Focus on the explanations, not just getting answers right
3. **Multiple Attempts**: Retake the quiz to reinforce learning
4. **Hands-On Practice**: Apply concepts in a real Laravel project
5. **Review Documentation**: Check official Laravel docs for topics you struggle with

## Resources

- [Laravel Documentation](https://laravel.com/docs)
- [Laravel News](https://laravel-news.com)
- [Laracasts](https://laracasts.com)
- [Laravel Daily](https://laraveldaily.com)
- [Spatie Guidelines](https://spatie.be/guidelines/laravel-php)

## License

This project is open source and available for educational purposes.

## Acknowledgments

- Questions curated from real-world Laravel interview experiences
- UI inspired by modern quiz applications
- Built with ❤️ for the Laravel community

## Feedback

Found an error or have suggestions? Please open an issue or submit a pull request!

---

**Happy Learning! 🚀**
