# GitHub Copilot Baseline Configuration

This repository serves as the organizational baseline for GitHub Copilot instructions, prompts, and chat modes specifically adopted for **AB-Lindex**. It provides standardized configurations, best practices, and custom prompts to ensure consistent and effective use of GitHub Copilot across our development teams.

## 📥 Installation Instructions

To use the **Install Copilot Baseline** prompt in your VS Code environment:

1. **Create the prompts directory** (if it doesn't exist):
   - **Windows with VS Code**: `%AppData%\Code\User\prompts\`  
     Open a terminal or the `Run` dialog and run the following command:
      ```powershell
      cmd /c "mkdir %AppData%\Code\User\prompts"
      ```

2. **Download the prompt file**: 
   - Navigate to [`install-copilot-baseline.prompt.md`](https://github.com/AB-Lindex/github-copilot/blob/main/install-copilot-baseline.prompt.md) (right-click and "Open in new tab" recommended)
   - Click the **Download** button ( **⤓** ) in the top right of the file view
   - Save the file to your desired prompts directory (see step 1)

3. **Use the prompt**: Type `/install-copilot-baseline` in GitHub Copilot Chat to use the install-prompt.

   > 💡 **Tip**: You can re-run `/install-copilot-baseline` anytime to get the latest updates from this repository and ensure you have the most current chat modes, instructions, and prompts.

## 🎯 Purpose

This repository contains:
- **Chat Modes**: Specialized AI assistants for specific development scenarios
- **Instructions**: Guidelines for code formatting and development practices  
- **Prompts**: Meta-prompts that help discover and suggest additional GitHub Copilot resources

## � Acknowledgments

Most of the chat modes and prompts in this repository are adapted from [github.com/github/awesome-copilot](https://github.com/github/awesome-copilot) with modifications to better align with our organization's specific needs and workflows. We extend our gratitude to the GitHub Copilot community for their excellent contributions to the ecosystem.

## �💡 Chat Modes (.github/chatmodes)

- **Critical Thinking**: Challenge assumptions and encourage critical thinking to ensure the best possible solution and outcomes
- **Implementation Plan**: Generate an implementation plan for new features or refactoring existing code
- **PRD Generator**: Generate a comprehensive Product Requirements Document (PRD) in Markdown, detailing user stories, acceptance criteria, technical considerations, and metrics

## 💡 Instructions (.github/instructions)

- **Markdown Guidelines**: Instructions for creating clean and professional markdown files with appropriate formatting standards

## 💡 Prompts (.github/prompts)

- **Suggest Chatmodes**: Analyze repository context and suggest relevant chatmode files from the awesome-copilot repository
- **Suggest Prompts**: Analyze repository context and suggest relevant prompt files from the awesome-copilot repository

## 🚀 Happy Coding !

* Review the baseline instructions in `.github/instructions/`
* Use the provided chat modes from `.github/chatmodes/`
* Follow our organization's coding standards and best practices

## 📚 Best Practices

### Code Generation
- **Always** review generated code for security vulnerabilities
- Ensure compliance with your organization's coding standards
- Test generated code thoroughly before committing
- Document any modifications made to generated code

### Prompt Engineering
- Be specific about requirements and constraints
- Include context about existing codebase and patterns
- Reference relevant baseline instructions
- Iterate and refine prompts for better results

## 🤝 Contributing

1. Fork this repository
2. Create a feature branch
3. Add your improvements
4. Submit a Pull Request

Follow existing structure and include examples for new instructions.
