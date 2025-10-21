<h1> Blockchain Developer Rootstock Beginner to Expert Course <br>| Edition 2025  |</h1>

# Table of Contents

> All the sections in this repo are for the Rootstock Developer Course.

<details>
<summary> <a href="#welcome-to-the-course-repo">Welcome to the Course Repo!</a></summary>
<ol>
  <li><a href="#welcome-to-the-course">Welcome to the course!</a></li>
  <li><a href="#best-practices">Best Practices</a></li>
  <li><a href="#getting-started">Getting Started</a></li>
  <li><a href="#how-to-submit-your-work">How to Submit Your Work</a></li>
</ol>
</details>
<details>
<summary> <a href="#module-1-solidity-fundamentals">Module 1: Solidity Fundamentals</a></summary>
<ol>
  <li><a href="#module-1-overview">Overview</a></li>
  <li><a href="#exercises">Exercises</a></li>
  <li><a href="#running-tests">Running Tests</a></li>
  <li><a href="#submission-guidelines">Submission Guidelines</a></li>
</ol>
</details>
<details>
<summary> <a href="#module-2-smart-contract-development">Module 2: Smart Contract Development</a></summary>
<ol>
  <li><a href="#coming-soon">Coming Soon</a></li>
</ol>
</details>

---

# Welcome to the Course Repo

## Welcome to the course!

Welcome to the **Rootstock Developer Course**! This hands-on course will guide you through blockchain development fundamentals, from basic Solidity concepts to advanced smart contract patterns.

### What You'll Learn

- ✅ Solidity programming language fundamentals
- ✅ Smart contract development and deployment
- ✅ Best practices for secure contract design
- ✅ Integration with blockchain networks
- ✅ Real-world project development

## Best Practices

### Working with the Repository

- **Fork this repository** to your GitHub account before starting
- **Create a new branch** for each module following the format: `module[número]/[usuario]`
  - Example: `module1/scguaquetam` or `module1/student@email.com`
- **Commit frequently** with descriptive messages
- **Test your code** before submitting
- **Read the instructions carefully** in each exercise

### Code Quality

- Follow Solidity style guidelines
- Write clean, readable code
- Test your contracts thoroughly
- Document complex logic with comments
- Use meaningful variable and function names

### Getting Help

- Review the lesson videos before starting exercises
- Check the exercise descriptions in each module's README
- Test your code frequently using the provided test suites
- Ask questions in the course community forum
- Review the reference documentation when needed

## Getting Started

### Prerequisites

Before starting the course, ensure you have:

- **Node.js** (v18 or higher) - [Download here](https://nodejs.org/)
- **npm** or **yarn** package manager
- **Git** - [Install Git](https://git-scm.com/downloads)
- A code editor (we recommend [VS Code](https://code.visualstudio.com/))
- Basic JavaScript/TypeScript knowledge

### Installation

1. **Fork this repository** to your GitHub account

2. **Clone your fork** to your local machine:
   ```bash
   git clone https://github.com/rsksmart/rootstock-academy-dev-course
   cd rootstock-academy-dev-course
   ```

3. **Navigate to Desired Module Folder** and install dependencies:
   ```bash
   cd module1 #(module1 for example)
   npm install
   ```

4. **Verify your setup** by running the tests:
   ```bash
   npx hardhat test
   ```

You should see tests running (they will fail initially - that's expected!).

## How to Submit Your Work

### Submission Process

1. **Complete the exercises** by filling in the blanks in the contract templates
2. **Run the tests** to verify your solutions
3. **Commit your changes** to your fork
4. **Create a Pull Request** to the main repository
5. **Wait for review** from the RSK Developer Education team

### Creating a Pull Request

**Important**: Your Pull Request must follow this naming convention:

```
module[número]/[usuario-o-correo]
```

**Examples**:
- `module1/your-username` (using course username)
- `module1/student@email.com` (using email)
- `module2/your-username` (for Module 2)

**Steps to create your PR**:

```bash
# Create a branch with the correct naming format
git checkout -b module1/your-username

# Commit your changes
git add .
git commit -m "Complete Module 1 exercises"

# Push your branch to your fork
git push origin module1/your-username

# Create a PR on GitHub from your fork to the parent repository
# Make sure the PR title follows the same format: module1/your-username
```

### What Happens Next?

1. Your PR will be automatically tested
2. The DevX team will review your submission
3. You'll receive feedback if changes are needed
4. Once approved, your grade will be recorded in Thinkific
5. You can proceed to the next module!

<p align="right">(<a href="#table-of-contents">back to top</a>) ⬆️</p>

---

# Module 1: Solidity Fundamentals

💡 **Learning Time**: 4-6 hours  
📹 **Video Lessons**: Available on Thinkific  
🎯 **Goal**: Master core Solidity concepts through hands-on coding

## Module 1 Overview

In Module 1, you'll learn the fundamental building blocks of Solidity smart contracts through 13 progressive exercises. Each exercise builds on the previous one, taking you from basic contract structure to advanced concepts like interfaces and imports.

### What You'll Build

You'll build a **Car Registry Smart Contract** that demonstrates:
- Contract structure and state management
- Data types (primitives, enums, structs)
- Functions with parameters and return values
- Access control with modifiers
- Events for logging
- Contract interaction through interfaces

## Exercises

| # | Exercise | Concepts | Difficulty |
|---|----------|----------|------------|
| 01 | [Contract Structure](./module1/ContractsTemplate/01-contract.sol) | `pragma`, `contract`, `constructor` | ⭐ |
| 02 | [Primitive Variables](./module1/ContractsTemplate/02-primitive-variables.sol) | `bool`, `uint256`, `address`, `public` | ⭐ |
| 03 | [Enumerations](./module1/ContractsTemplate/03-enum.sol) | `enum`, custom types | ⭐ |
| 04 | [Structures](./module1/ContractsTemplate/04-struct.sol) | `struct`, composite types | ⭐⭐ |
| 05 | [Dynamic Variables](./module1/ContractsTemplate/05-dynamic-variables.sol) | `mapping`, key-value storage | ⭐⭐ |
| 06 | [Function Signatures](./module1/ContractsTemplate/06-function-stub.sol) | function declarations, parameters | ⭐⭐ |
| 07 | [Function Implementation](./module1/ContractsTemplate/07-function-impl.sol) | `memory`, `msg.sender`, logic | ⭐⭐ |
| 08 | [Require Statements](./module1/ContractsTemplate/08-require.sol) | `payable`, `require`, validation | ⭐⭐⭐ |
| 09 | [Function Modifiers](./module1/ContractsTemplate/09-function-modifier.sol) | `modifier`, `_`, reusable checks | ⭐⭐⭐ |
| 10 | [Events & Logs](./module1/ContractsTemplate/10-event-logs.sol) | `event`, `emit`, `indexed` | ⭐⭐⭐ |
| 11 | [Interfaces](./module1/ContractsTemplate/11-interface.sol) | `interface`, `external`, `is` | ⭐⭐⭐⭐ |
| 12 | [Interface References](./module1/ContractsTemplate/12-reference-interface.sol) | contract references, casting | ⭐⭐⭐⭐ |
| 13 | [Imports](./module1/ContractsTemplate/13-import.sol) | `import`, modular code | ⭐⭐⭐⭐ |

## Running Tests

### Run All Tests
```bash
cd module1
npx hardhat test
```

### Run a Specific Test
```bash
npx hardhat test test/01-contract.ts
```

### View Detailed Test Output
```bash
npx hardhat test --verbose
```

### Check Gas Usage
```bash
REPORT_GAS=true npx hardhat test
```

## How to Complete Exercises

### Step 1: Open the Template

Navigate to `module1/ContractsTemplate/` and open the exercise file. You'll see code with blanks (`___`):

```solidity
// Example from 01-contract.sol
___ solidity ^0.8.0;

___ Abc {
    ___() {
    }
}
```

### Step 2: Fill in the Blanks

Replace each `___` with the correct Solidity code:

```solidity
pragma solidity ^0.8.0;

contract Abc {
    constructor() {
    }
}
```

### Step 3: Test Your Solution

Run the corresponding test file:

```bash
npx hardhat test test/01-contract.ts
```

### Step 4: Fix Any Errors

If tests fail, read the error messages carefully:
- ❌ **Syntax errors**: Check your Solidity syntax
- ❌ **Test failures**: Verify you used the correct keywords and types
- ❌ **Compilation errors**: Ensure your code compiles

### Step 5: Move to the Next Exercise

Once all tests pass (✅), move to the next exercise!

## Submission Guidelines

### Before Submitting

- ✅ All tests must pass
- ✅ Code must compile without warnings
- ✅ No syntax errors
- ✅ Follow the exercise instructions exactly

### Submission Checklist

```bash
# 1. Create a branch following the naming convention: module1/your-username
git checkout -b module1/your-username

# 2. Run all tests one final time
cd module1
npx hardhat test

# 3. Check for any uncommitted changes
git status

# 4. Commit your work
git add module1/
git commit -m "Complete Module 1: Solidity Fundamentals"

# 5. Push to your fork
git push origin module1/your-username

# 6. Create Pull Request on GitHub to the parent repository
# PR title must be: module1/your-username
```

**Remember**: Replace `your-username` with your course username or email address.

### What We Check

Your submission will be evaluated on:
1. **Correctness**: All tests pass ✅
2. **Completeness**: All exercises completed
3. **Code Quality**: Clean, readable code
4. **Following Instructions**: Used correct keywords and patterns

## Tips for Success

### 📚 Learning Resources

- **Watch the video lessons** before starting exercises
- **Read the exercise descriptions** carefully in each file
- **Review Solidity documentation** when stuck
- **Study the test files** to understand what's expected

### 💡 Common Mistakes to Avoid

- Don't skip exercises - they build on each other
- Don't copy/paste without understanding
- Don't ignore compiler warnings
- Don't submit without running tests

### 🎯 Pro Tips

- Start with easier exercises (01-03) to build confidence
- Use VS Code with Solidity extensions for syntax highlighting
- Read error messages carefully - they often tell you exactly what's wrong
- Test frequently - don't wait until all exercises are done
- Ask for help if you're stuck for more than 30 minutes

## Troubleshooting

### Tests Won't Run

```bash
# Try reinstalling dependencies
rm -rf node_modules package-lock.json
npm install
```

### Compilation Errors

- Check your Solidity version (`pragma solidity ^0.8.0;`)
- Ensure all syntax is correct
- Look for missing semicolons or brackets

### Test Failures

- Read the test output carefully
- Check you're using the exact keywords required
- Verify variable types match expectations
- Ensure function signatures are correct

### Need More Help?

- Check the [Hardhat Documentation](https://hardhat.org/docs)
- Review [Solidity by Example](https://solidity-by-example.org/)
- Ask in the course discussion forum
- Reach out to the DevX team

<p align="right">(<a href="#table-of-contents">back to top</a>) ⬆️</p>

---

# Module 2: Smart Contract Development

## Coming Soon

Module 2 will cover advanced smart contract development topics. Stay tuned!

<p align="right">(<a href="#table-of-contents">back to top</a>) ⬆️</p>

---

## Additional Resources

### Official Documentation

- [Rootstock Developers Portal](https://dev.rootstock.io/)
- [Solidity Documentation](https://docs.soliditylang.org/)
- [Hardhat Documentation](https://hardhat.org/docs)

### Community

- [Rootstock Discord](https://rootstock.io/discord)
- [Twitter/X](https://twitter.com/rootstock_io)

### Tools

- [Remix IDE](https://remix.ethereum.org/) - Browser-based Solidity IDE
- [Hardhat](https://hardhat.org/) - Development environment
- [OpenZeppelin](https://www.openzeppelin.com/) - Secure contract library

---

## Contact & Support

For questions or issues:
- **Technical Support**: DevX (DevRel) Team
- **Course Content**: Thinkific platform messaging
- **Community Help**: Discord #developer-support channel

---

## License

This course material is provided by Rootstock for educational purposes.

© 2025 Rootstock. All rights reserved.

---
