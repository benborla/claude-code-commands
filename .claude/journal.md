DIRECTIVE: Maintain comprehensive work_journal.md for all development activities, make sure to create this file if it doesn't exist.

STRUCTURE:
1. Header
   - Title: "# [Project Name] Work Journal"
   - Table of Contents with anchors to major features
   - Last updated timestamp

2. Feature Entry Format
   - Feature name with date
   - Project and version context
   - Clear feature description

3. Required Sections
   a. Overview
      - Concise summary of implemented changes
   
   b. Background and Motivation
      - Business Need: Why this feature matters to users
      - Initial Problems: Technical issues being addressed
      - Technical Constraints: Environmental limitations
   
   c. Tasks
      - Status: "Done" only for confirmed working solutions
      - Categorized implementation details with bullet points
   
   d. Implementation Details
      - Code snippets for key components
      - Configuration details
      - API usage examples
   
   e. Documentation Updates
      - Mental Model Updates
      - Implementation Details Documentation
      - Gotchas and Edge Cases
   
   f. Files Modified
      - Git-diff style listing of changed files
      - Key changes per file in diff format
   
   g. Reference Resources
      - Official documentation links
      - Stack Overflow solutions
      - GitHub issues/discussions
      - Blog posts and tutorials
      - Version-specific documentation
      - Compatibility notes
   
   h. Things to Consider
      - Compatibility considerations
      - Performance optimizations
      - Potential future enhancements
      - Known limitations

EXECUTION_RULES:
- Only document confirmed working solutions based on user feedback
- Update work_journal.md after each significant change
- Include code snippets for reference
- Follow documentation-first approach
- Maintain git-diff style change tracking
- Document both what was done AND why it was done
- Include business context alongside technical details
- Track all files modified during implementation, use terminal command `git diff` to easily get all the file changes
- Use project-relative paths for file references
- Adapt section depth based on project complexity
- Use technology-appropriate code examples
- Always include specific version numbers for libraries and tools
- Add direct links to relevant documentation and resources
- Archive copies of critical reference materials when possible

VALIDATION:
- Confirm solutions work before adding to work journal
- Review work journal with user periodically
- Update based on user feedback
- Ensure journal remains navigable as it grows
- Verify documentation links are still valid during reviews
