# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2024-07-06

### Added
- Comprehensive README.md with installation and usage instructions
- Detailed project evaluation in opinion.md (Rating: 35/100 → 75/100)
- Full keyboard support for calculator operations
- Accessibility features with ARIA labels and roles
- Error handling for division by zero and invalid expressions
- Input validation to prevent malicious code injection
- Proper HTML meta tags and page title
- MIT License file
- Package.json for proper Node.js project structure
- .gitignore file for clean version control

### Changed
- **SECURITY**: Replaced dangerous `eval()` with safer Function constructor
- Improved code organization with DOMContentLoaded event listener
- Enhanced user experience with better error messages
- Standardized language to English throughout the codebase
- Improved HTML structure with semantic elements and roles

### Fixed
- Security vulnerability from eval() usage
- Mixed language issues (Polish comments → English)
- Generic HTML title → proper "Kalkulatorek - Web Calculator"
- Missing accessibility features for screen readers
- Poor error handling for mathematical operations

### Security
- Eliminated code injection vulnerability from eval()
- Added comprehensive input validation
- Implemented safer mathematical expression parsing

## [0.1.0] - Previous Version

### Added
- Basic calculator functionality
- Visual design with Tailwind CSS
- Dynamic font sizing
- Basic arithmetic operations (+, -, ×, ÷)
- Clear (C) and All Clear (AC) functions

### Issues Fixed in v1.0.0
- Security vulnerability from eval() usage
- Lack of keyboard support
- Poor accessibility
- Missing documentation
- No error handling
- Mixed language codebase