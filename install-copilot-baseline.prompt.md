---
mode: 'agent'
description: 'Install GitHub Copilot Baseline by downloading and installing chatmodes, prompts, and instructions from the AB-Lindex/github-copilot repository for improved AI-assisted development.'
tools: ['changes', 'codebase', 'editFiles', 'fetch', 'findTestFiles', 'githubRepo', 'new', 'openSimpleBrowser', 'problems', 'runCommands', 'runTasks', 'runTests', 'search', 'searchResults', 'terminalLastCommand', 'terminalSelection', 'testFailure', 'usages', 'vscodeAPI', 'github', 'edit']
---

# Install GitHub Copilot Baseline

Download and install chatmodes, prompts, and instructions from the [AB-Lindex/github-copilot repository](https://github.com/AB-Lindex/github-copilot) to enhance your development workflow with standardized AI-assisted tools.

## Process

1. **Fetch Repository Content**: Extract available chatmodes, prompts, and instructions from [AB-Lindex/github-copilot repository](https://github.com/AB-Lindex/github-copilot)
2. **Scan Local Structure**: Discover existing files in `.github/chatmodes/`, `.github/instructions/`, and `.github/prompts/` folders
3. **Extract Metadata**: Read front matter from local files to get descriptions and configurations
4. **Analyze Gaps**: Compare available files with what's already installed in the current repository
5. **Present Options**: Display available files with descriptions, installation status, and benefits
6. **Validate Structure**: Ensure target directories exist or can be created
7. **Download Files**: Download selected files from the source repository
8. **Install Files**: Place files in appropriate directories (`.github/chatmodes/`, `.github/instructions/`, `.github/prompts/`) and use the `edit` tool to create directories and files as needed
9. **Verify Installation**: Confirm files are properly installed and accessible
10. **Summary**: Provide installation report with list of installed files and next steps

## Installation Analysis Criteria

🔍 **Repository Content Types**:
- **Chatmodes**: Specialized AI assistant modes for different development tasks (.chatmode.md files)
- **Instructions**: Coding guidelines and best practices for consistent development (.instructions.md files)
- **Prompts**: Reusable prompt templates for common development scenarios (.prompt.md files)

� **Target Directory Structure**:
- `.github/chatmodes/` - AI assistant chatmode configurations
- `.github/instructions/` - Development guidelines and coding standards
- `.github/prompts/` - Prompt templates for various development tasks

🗨️ **Benefits Analysis**:
- Standardized AI-assisted development workflows
- Consistent coding practices across teams
- Reusable prompt templates for common tasks
- Enhanced development productivity

## Output Format

Display installation analysis results in structured table showing available files from AB-Lindex/github-copilot repository:

| File Type | File Name | Description | Installation Status | Benefits |
|-----------|-----------|-------------|-------------------|----------|
| Chatmode | [critical-thinking.chatmode.md](https://github.com/AB-Lindex/github-copilot/blob/main/.github/chatmodes/critical-thinking.chatmode.md) | Enhanced critical analysis and problem-solving chatmode | ✅ Already Installed | Improves code analysis and decision making |
| Chatmode | [implementation-plan.chatmode.md](https://github.com/AB-Lindex/github-copilot/blob/main/.github/chatmodes/implementation-plan.chatmode.md) | Structured implementation planning assistant | ✅ Already Installed | Helps create detailed development plans |
| Instruction | [markdown.instructions.md](https://github.com/AB-Lindex/github-copilot/blob/main/.github/instructions/markdown.instructions.md) | Markdown formatting and documentation guidelines | ❌ Available for Install | Ensures consistent documentation standards |
| Chatmode | [prd.chatmode.md](https://github.com/AB-Lindex/github-copilot/blob/main/.github/chatmodes/prd.chatmode.md) | Product Requirements Document creation assistant | ✅ Already Installed | Streamlines PRD creation process |

## Content Discovery Process

1. **Scan Source Repository**: List all files in `.github/chatmodes/`, `.github/instructions/`, and `.github/prompts/` directories from AB-Lindex/github-copilot
2. **Read File Metadata**: Extract front matter (YAML) from each file to get descriptions and configurations
3. **Check Local Installation**: Compare with existing files in current repository's `.github/` directory structure
4. **Build Content Inventory**: Create comprehensive list of available vs. installed content
5. **Identify Installation Candidates**: Focus on files not yet installed that would benefit the current repository

## Installation Process

1. **Create Directory Structure**: Ensure `.github/chatmodes/`, `.github/instructions/`, and `.github/prompts/` directories exist
2. **Download Selected Files**: Fetch content from AB-Lindex/github-copilot repository using GitHub API
3. **Install Files**: Write downloaded content to appropriate local directories
4. **Validate Installation**: Verify files are correctly installed and properly formatted
5. **Generate Report**: Provide summary of installed files and their purposes

## Requirements

- Use `githubRepo` tool to get content from AB-Lindex/github-copilot repository
- Scan local file system for existing files in `.github/chatmodes/`, `.github/instructions/`, and `.github/prompts/` directories
- Read YAML front matter from files to extract descriptions and metadata
- Compare available files with installed files to identify installation candidates
- Create directory structure if it doesn't exist
- Download and install selected files maintaining proper formatting and structure
- Provide clear installation status and benefits for each file type
- Include links to source files in the AB-Lindex/github-copilot repository
- Offer automatic installation with user confirmation
- Generate installation summary report

## File Types and Extensions

- **Chatmodes**: `*.chatmode.md` - AI assistant mode configurations
- **Instructions**: `*.instructions.md` - Development guidelines and coding standards  
- **Prompts**: `*.prompt.md` - Reusable prompt templates

## Installation Status Icons

- ✅ Already installed in current repository
- ❌ Available for installation from source repository
- ⚠️ Conflict detected (different version exists locally)
- 🔄 Update available (newer version in source repository)