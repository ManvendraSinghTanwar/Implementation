# Made By Manvendra Singh Tanwar

## Question 1: AI Lab Question System - Unique Question Generation & Digital Assessment

An intelligent AI-powered platform for laboratory education with question generation, student management, and automated evaluation.

### ✨ Key Features
- 🎯 **AI Question Generation**: Create 4 unique equivalent lab question variations
- 👥 **Student Management**: Easy registration and progress tracking
- 🤖 **Automated Evaluation**: AI-powered grading with detailed feedback
- 🎨 **Modern UI**: Glass morphism design with dark/light themes

### 🚀 Tech Stack
- **Frontend**: Next.js 15, React 19, TypeScript
- **AI**: Together AI (Llama 3.3 70B Instruct Turbo)
- **Styling**: Tailwind CSS, Radix UI

---
4. **Progress Tracking**: Monitor your submission history and scores

*Streamlined student experience from login to feedback*

### 🛠️ Installation & Setup

#### Prerequisites
- Node.js 18+
- pnpm (recommended) or npm

#### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ManvendraSinghTanwar/AI-Lab-Question-System.git
   cd AI-Lab-Question-System
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   # or
   npm install
   ```

3. **Set up environment variables**
   ```bash
   # Create .env.local file and add your Together AI API key
   echo "TOGETHER_AI_API_KEY=your_api_key_here" > .env.local
   ```

4. **Run the development server**
   ```bash
   pnpm dev
   # or
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000` to see the application

#### Production Build
```bash
pnpm build
pnpm start
```

### 🎯 Use Cases

*Various educational scenarios where the AI Lab Question System excels*

#### Educational Institutions
- **Laboratory Courses**: Generate unique questions for chemistry, physics, biology labs
- **Practical Exams**: Create equivalent but different questions for fair assessment
- **Student Practice**: Provide varied practice questions for better learning

#### Research Labs
- **Training Programs**: Standardized question sets for new researchers
- **Skill Assessment**: Evaluate understanding of lab procedures and concepts
- **Documentation**: Maintain organized question banks for different experiments

#### Online Learning Platforms
- **Course Content**: Generate diverse question sets for online lab simulations
- **Assessment Tools**: Automated evaluation reduces instructor workload
- **Personalized Learning**: Each student gets unique questions for better engagement

*Measurable benefits and return on investment for educational institutions*

### 🔧 Configuration

#### AI Service Configuration
The system uses Together AI's Llama 3.3 70B model. You can modify the AI service in `lib/ai-service.ts`:

```typescript
// Change the model or API endpoint
private model = "meta-llama/Llama-3.3-70B-Instruct-Turbo"
private baseUrl = "https://api.together.xyz/v1"
```

#### Customization Options
- **Question Categories**: Modify categories in the question generator form
- **Difficulty Levels**: Adjust difficulty options (Easy, Medium, Hard)
- **UI Themes**: Customize colors and animations in the CSS files
- **Evaluation Criteria**: Modify AI prompts for different evaluation standards

### 🚀 Future Enhancements
- [ ] Database integration for persistent storage
- [ ] Multi-language question support
- [ ] Advanced analytics and reporting
- [ ] Integration with LMS platforms
- [ ] Question bank import/export functionality
- [ ] Real-time collaboration features

---

## Question 2: Neon Exam System - Digital Paper Reduction System

**Problem Statement**: Academic activities like exams, lab manuals, and projects consume large amounts of paper, causing waste (e.g., one semester exam in a university can use 80+ sheets for question papers alone).

**Task**: Design an AI-powered system to minimize paper usage by securely generating, delivering, and evaluating question papers digitally. Ensure exam integrity, role-based access, and multi-device compatibility.

### 🚀 Solution: Neon Exam System
A futuristic AI-powered examination system with a stunning cyberpunk neon design. Built with Next.js, TypeScript, and powered by Meta's Llama 3.3 70B model via Together AI.

### ✨ Key Features

#### 🎯 Multi-Role Dashboard
- **Admin Dashboard**: Complete exam management and analytics
- **Faculty Dashboard**: Question creation and student monitoring
- **Student Dashboard**: Take exams with real-time tracking
- **Invigilator Dashboard**: Live proctoring and violation detection

#### 🤖 AI-Powered Question Generation
- **Smart Question Creation**: Generate questions using Meta Llama 3.3 70B model
- **Multiple Question Types**: Multiple choice, descriptive, and more
- **Difficulty Levels**: Easy, Medium, Hard, Expert
- **Subject Customization**: Any subject or topic
- **Bulk Generation**: Create multiple questions at once

#### 🎨 Cyberpunk Neon Design
- **Futuristic UI**: Stunning neon glow effects and animations
- **Dark Theme**: Eye-friendly dark mode with neon accents
- **Responsive Design**: Works perfectly on all devices
- **Interactive Elements**: Smooth hover effects and transitions

#### � Advanced Exam Features
- **Real-time Exam Taking**: Live timer and auto-save
- **Instant Results**: Immediate scoring and feedback
- **Analytics Dashboard**: Comprehensive exam statistics
- **Violation Detection**: AI-powered cheating prevention
- **Bulk Student Management**: Easy student assignment and tracking
- **Secure Examination Environment**: Anti-cheating measures and proctoring

### 🚀 Tech Stack
- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS, Radix UI Components
- **AI Integration**: Together AI (Llama-3.3-70B-Instruct-Turbo-Free)
- **Icons**: Lucide React
- **Development**: ESLint, PostCSS

### 🎮 Role-Specific Features

#### 👨‍💼 Admin Dashboard
- System-wide analytics and monitoring
- User management and permissions
- Violation detection and security alerts
- Comprehensive reporting tools

#### 👨‍🏫 Faculty Dashboard
- Question bank management
- Exam creation and scheduling
- Student performance tracking
- Grade management

#### 👨‍� Student Dashboard
- Available examinations
- Exam history and results
- Progress tracking
- Performance analytics

#### 👁️ Invigilator Dashboard
- Live exam monitoring
- Real-time violation alerts
- Student behavior tracking
- Incident reporting

### 🎯 Environmental Impact & Paper Reduction
- **Estimated Savings**: 80+ sheets per exam × number of students
- **Annual Impact**: Thousands of sheets saved per academic year
- **Carbon Footprint**: Significant reduction in paper production
- **Cost Efficiency**: Reduced printing, storage, and distribution costs
- **Digital Archives**: Permanent storage without physical space requirements

---

---

## Question 3: Fighting Against Fake News on Emerging Crisis - Implementation Completed

**Problem Statement**: You have been given a GitHub code link in an Excel sheet, and your task is to download and execute the code. (20 marks)

**GitHub Repository**: [Fighting Against FakeNews on Emerging Crisis - WWW24](https://github.com/DSAIL-SKKU/Fighting_Against_FakeNews_on_Emerging_Crisis-WWW24)

### ✅ Implementation Status: **COMPLETED**

The code from the provided GitHub repository has been successfully downloaded, set up, and executed.

### 📸 Implementation Proof

#### Execution Screenshot 1
![Implementation Screenshot 1](Screenshot%202025-08-14%20163921.png)

*System successfully running - showing model training and data processing*

#### Execution Screenshot 2
![Implementation Screenshot 2](Screenshot%202025-08-14%20164306.png)

*System execution completed - showing results and performance metrics*

### 🎯 Implementation Summary

- ✅ Repository successfully cloned from GitHub
- ✅ Dependencies installed and environment configured
- ✅ Code executed without errors
- ✅ Results generated and validated
- ✅ Screenshots captured as proof of implementation

**Status**: Implementation completed successfully with documented proof of execution.

---

## 🤝 Contributing

We welcome contributions to any of these projects! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙋‍♂️ Support

If you encounter any issues or have questions:
- Open an issue on GitHub
- Contact: [ManvendraSinghTanwar](https://github.com/ManvendraSinghTanwar)

---

**Made with ❤️ for better education through AI**

