<!-- Sync Impact Report -->
<!--
Version change: 0.0.0 -> 0.1.0
Modified principles: All principles updated/defined.
Added sections: Key Standards, Constraints, Success Criteria
Removed sections: None
Templates requiring updates:
- .specify/templates/plan-template.md: ⚠ pending (Constitution Check section needs update)
- .specify/templates/spec-template.md: ✅ updated (Aligned)
- .specify/templates/tasks-template.md: ✅ updated (Aligned)
- .specify/templates/commands/sp.constitution.md: ⚠ pending (File not found, assumed embedded)
Follow-up TODOs: None
-->
# AI/Spec-Driven Book Creation (Physical AI & Humanoid Robotics) Constitution

## Core Principles

### I. Precision in Technical Explanations
All technical explanations related to Physical AI, Robotics, and Simulation Systems MUST be precise, accurate, and scientifically sound. Content must reflect current industry best practices and research.

### II. Consistency Across Modules
All content and code examples MUST maintain consistency across modules by strictly adhering to Spec-Kit Plus specifications. This includes naming conventions, data structures, and architectural patterns.

### III. Clarity for Target Audience
Content MUST be written with clarity suitable for intermediate-to-advanced readers in AI, Robotics, and Computer Science. Complex concepts must be explained accessibly without oversimplification.

### IV. Modularity and Independence
Each topic and module MUST be independently understandable, allowing readers to grasp concepts without requiring exhaustive prior knowledge of other sections. This supports flexible learning paths.

### V. Technical Integrity of Robotics Workflows
All described robotics workflows (ROS 2, Gazebo, Isaac, VLA) MUST follow current industry standards and best practices. Code examples and configurations must be verifiable against official documentation.

## Key Standards

All diagrams, code examples, and explanations MUST be generated through Spec-Kit Plus + Claude Code workflows.
Content structure MUST follow Docusaurus documentation standards for navigation, formatting, and presentation.
All robotics concepts (ROS 2, URDF, Isaac Sim, Nav2, VLA) MUST be validated from official documentation.
Book chapters MUST maintain a logical progression from fundamentals → simulation → perception → humanoid AI.
GitHub Pages deployment MUST include versioned documentation to track changes and updates.

## Constraints

Book length MUST be between 8–12 chapters, with a minimum of 25,000 words.
Each module MUST include: theory, relevant tools, detailed workflows, and at least 1 hands-on lab.
Mandatory inclusion of 1 full capstone walkthrough titled “The Autonomous Humanoid” is required.
Output format MUST be a Docusaurus static website, designed for deployment on GitHub Pages.
Tools used for generation, refinement, and structure MUST exclusively be Spec-Kit Plus + Claude Code.

## Success Criteria

The book MUST fully cover all 4 modules:
1.  The Robotic Nervous System (ROS 2)
2.  The Digital Twin (Gazebo & Unity)
3.  The AI-Robot Brain (NVIDIA Isaac)
4.  Vision-Language-Action (VLA)
All provided code MUST run reproducibly and enable a robot to perform a task encompassing: perceive → navigate → detect → manipulate object (simulation acceptable).
The final GitHub Pages site MUST be error-free, responsive across devices, and adhere to the specified Docusaurus content structure.

## Governance
This Constitution supersedes all other project practices. Amendments require a documented proposal, review, and approval by the project lead, along with a migration plan for any affected artifacts. Compliance with these principles will be verified in all major milestones and code reviews.

**Version**: 0.1.0 | **Ratified**: 2025-12-04 | **Last Amended**: 2025-12-04
