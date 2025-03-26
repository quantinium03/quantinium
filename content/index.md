---
id: index
aliases: []
tags: []
---

Teaching computers how to do stuff. Sometimes they listen

<div class="projects-container">
    <h2 class="section-title">/dev/projects</h2>
    <div class="projects-list">
        <div class="project-item">
            <span class="tree-prefix">├─ </span>
            <span class="project-name">/lomes</span>
            <span class="status ongoing">ongoing</span>
            <p class="project-description">A self hosting local media server</p>
            <div class="tech-stack">
                <span class="tech reactjs">reactjs</span>
                <span class="tech expressjs">expressjs</span>
                <span class="tech go">go</span>
            </div>
        </div>
        <div class="project-item">
            <span class="tree-prefix">├─ </span>
            <span class="project-name">/grimoire</span>
            <span class="status ongoing">ongoing</span>
            <p class="project-description">A static site generator for obsidian</p>
            <div class="tech-stack">
                <span class="tech typescript">typescript</span>
                <span class="tech handlebars">handlebars</span>
            </div>
        </div>
        <div class="project-item">
            <span class="tree-prefix">├─ </span>
            <span class="project-name">/webalyze</span>
            <span class="status completed">completed</span>
            <p class="project-description">A tool to automatically summarize, organize or do anything with the data from any website</p>
            <div class="tech-stack">
                <span class="tech python">python</span>
                <span class="tech llama">llama</span>
            </div>
        </div>
        <div class="project-item">
            <span class="tree-prefix">├─ </span>
            <span class="project-name">/personal website</span>
            <span class="status completed">completed</span>
            <p class="project-description">A website to showcase all the things I'm doing that works by sending data from my laptop to a vps</p>
            <div class="tech-stack">
                <span class="tech reactjs">reactjs</span>
                <span class="tech go">go</span>
                <span class="tech rust">rust</span>
            </div>
        </div>
        <div class="project-item">
            <span class="tree-prefix">├─ </span>
            <span class="project-name">/lated</span>
            <span class="status completed">completed</span>
            <p class="project-description">A latex editor</p>
            <div class="tech-stack">
                <span class="tech reactjs">reactjs</span>
                <span class="tech expressjs">expressjs</span>
            </div>
        </div>
    </div>
</div>

<style>
.section-title {
    color: #f0ad4e;
    font-weight: bold;
    margin-bottom: 5px;
    font-size: x-large;
}

.projects-list {
    border-left: 1px solid #555;
    margin-left: 10px;
}

.project-item {
    margin-bottom: 20px;
    position: relative;
}

.tree-prefix {
    color: #555;
    margin-left: -5px;
}

.project-name {
    color: #f0ad4e;
    font-weight: bold;
}

.status {
    border-radius: 15px;
    padding: 2px 10px;
    font-size: 0.9em;
    background-color: #2d2d2d;
    position: absolute;
    right: 0;
}

.status.ongoing {
    border: 1px solid #f0ad4e;
    color: #f0ad4e;
}

.status.completed {
    border: 1px solid #8bc34a;
    color: #8bc34a;
}

.project-description {
    margin-left: 40px;
    margin-bottom: 10px;
}

.tech-stack {
    margin-left: 40px;
    display: flex;
    gap: 10px;
    margin-bottom: 20px;
}

.tech {
    background-color: #2d2d2d;
    border: 1px solid #444;
    border-radius: 15px;
    padding: 2px 10px;
    font-size: 0.9em;
}

.tech.reactjs {
    color: #61dafb;
}

.tech.expressjs {
    color: #8bc34a;
}

.tech.go {
    color: #29beb0;
}

.tech.typescript {
    color: #3178c6;
}

.tech.handlebars {
    color: #f0772b;
}

.tech.python {
    color: #3572a5;
}

.tech.llama {
    color: #a855f7;
}

.tech.rust {
    color: #dea584;
}
</style>
