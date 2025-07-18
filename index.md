---
layout: default
title: Software Development ePortfolio
---

# Welcome to My Software Development ePortfolio

<div class="intro-text">
This is my Software Development ePortfolio site. Here you will find the
projects and enhancements I have created while working toward my CS
bachelor's in Software Development.
</div>

<div class="terminal-window" onclick="openCodeReview()">
    <div class="terminal-header">
        <span class="terminal-title">Code Review</span>
        <div class="terminal-buttons">
            <div class="terminal-button minimize"></div>
            <div class="terminal-button maximize"></div>
            <div class="terminal-button close"></div>
        </div>
    </div>
    <div class="terminal-content">
        <code>apursley2012@ePortfolio-PC:~$ cd Software-Dev-ePortfolio
apursley2012@ePortfolio-PC:~/Software-Dev-ePortfolio$ python
Python 3.11.4 (tags/v3.11.4)
>>> # Open and read Code Review page
>>> path = r"Software-Dev-ePortfolio/code-review.md"
>>> file = open(path, "r")
>>> print(file.read())
Opening file: code-review.md ...
<span class="clickable-link">Click here to open Code Review</span></code>
    </div>
    <div class="status-bar">Ready</div>
</div>

<div class="terminal-window" onclick="openProjectArt()">
    <div class="terminal-header">
        <span class="terminal-title">Project Artifacts</span>
        <div class="terminal-buttons">
            <div class="terminal-button minimize"></div>
            <div class="terminal-button maximize"></div>
            <div class="terminal-button close"></div>
        </div>
    </div>
    <div class="terminal-content">
        <code>apursley2012@ePortfolio-PC:~/Software-Dev-ePortfolio$ ls -la projects/
total 48
drwxr-xr-x 2 apursley2012 apursley2012 4096 Jul 16 10:30 .
drwxr-xr-x 5 apursley2012 apursley2012 4096 Jul 16 10:28 ..
-rw-r--r-- 1 apursley2012 apursley2012 8192 Jul 16 10:30 enhancement1.md
-rw-r--r-- 1 apursley2012 apursley2012 8192 Jul 16 10:29 enhancement2.md
-rw-r--r-- 1 apursley2012 apursley2012 8192 Jul 16 10:28 enhancement3.md
>>> # Navigate to project artifacts
<span class="clickable-link">Click here to open Project Artifacts</span></code>
    </div>
    <div class="status-bar">3 artifacts found</div>
</div>

<div class="markdown-content">
## About This Portfolio

This ePortfolio showcases my journey through software development during my Computer Science bachelor's program. Each section demonstrates different aspects of my technical skills and growth as a developer.

### Navigation

- **Code Review:** Analysis and reflection on my development process
- **Project Artifacts:** Three major enhancements showcasing different technical skills
- **Professional Assessment:** Self-evaluation and career objectives

### Technical Skills Demonstrated

- Software engineering and design principles
- Algorithm development and data structures
- Database management and optimization
- Security-focused development practices
- Version control and collaborative development
</div>

<script>
function openCodeReview() {
    // Replace with actual code review page URL
    window.location.href = 'code-review.html';
}

function openProjectArt() {
    // Replace with actual project artifacts page URL
    window.location.href = 'projects.html';
}

// Add hover effects for terminal windows
document.addEventListener('DOMContentLoaded', function() {
    const terminalWindows = document.querySelectorAll('.terminal-window');
    terminalWindows.forEach(window => {
        window.addEventListener('mouseenter', function() {
            this.style.border = '2px outset #d0d0d0';
        });
        window.addEventListener('mouseleave', function() {
            this.style.border = '2px outset #c0c0c0';
        });
    });
});
</script>
