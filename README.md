# Daily Mood Tracker

A simple and intuitive iOS app to track and document your daily mood patterns.

## Features

- Daily mood logging with customizable emotions
- Visual mood history and trends
- Optional notes for each mood entry
- Private and secure data storage
- Clean, minimalist interface

## Technologies

- React Native
- TypeScript
- iOS 15.0+
- Android 8.0+

## Development Setup

1. Prerequisites:
   - Node.js (v14 or newer)
   - npm or yarn
   - Xcode (for iOS development)
   - Android Studio (for Android development)
   - Ruby (for iOS dependencies)

2. Initial Setup:
   ```bash
   # Clone the repository
   git clone <repository-url>
   cd MyFirstApp

   # Install dependencies
   npm install
   # or
   yarn install

   # Install iOS dependencies
   cd ios
   bundle install
   bundle exec pod install
   cd ..
   ```

3. Running the App:
   ```bash
   # For iOS
   npm run ios
   # or
   yarn ios

   # For Android
   npm run android
   # or
   yarn android
   ```

## Git Workflow

### Initial Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd MyFirstApp
   ```

2. Create and switch to a new branch for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```

### Daily Workflow
1. Before starting work, pull the latest changes:
   ```bash
   git checkout main
   git pull origin main
   git checkout your-branch-name
   ```

2. Make your changes and commit them:
   ```bash
   # Stage changes
   git add .

   # Commit changes with a descriptive message
   git commit -m "Description of your changes"
   ```

3. Push your changes to remote:
   ```bash
   git push origin your-branch-name
   ```

4. Create a Pull Request on GitHub/GitLab when ready to merge

### Best Practices
- Write clear, descriptive commit messages
- Keep commits focused and atomic
- Regularly pull from the main branch to stay up to date
- Never commit sensitive information or large binary files
- Use `.gitignore` to exclude unnecessary files (already configured)

### Common Git Commands
```bash
# Check status of your changes
git status

# View commit history
git log

# Discard changes in a file
git checkout -- <file>

# Create and switch to a new branch
git checkout -b branch-name

# Switch to an existing branch
git checkout branch-name

# Merge main branch into your feature branch
git checkout your-branch
git merge main
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
