---
layout: default
title: Home
---

<section class="hero">
    <div class="container">
        <img src="{{ site.baseurl }}/assets/images/logo.png" alt="KubeDesk Logo" class="hero-logo" width="100" style="width: 100px; height: auto;">
        <h1>The Desktop Client for Kubernetes Cluster Management</h1>
        <p class="subtitle">Gain complete visibility into your clusters. Browse, inspect, and analyze all Kubernetes objects in real-time. Built with Electron, React, and Go.</p>
        
            <!-- macOS Dropdown -->
            <div class="dropdown">
                <button class="btn-pill btn-mac">
                    <svg class="os-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><path fill="currentColor" d="M318.7 268.7c-.2-36.7 16.4-64.4 50-84.8-18.8-26.9-47.2-41.7-84.7-44.6-35.5-2.8-74.3 20.7-88.5 20.7-15 0-49.4-19.7-76.4-19.7C63.3 141.2 4 184.8 4 273.5q0 39.3 14.4 81.2c12.8 36.7 59 126.7 107.2 125.2 25.2-.6 43-17.9 75.8-17.9 31.8 0 48.3 17.9 76.4 17.9 48.6-.7 90.4-82.5 102.6-119.3-65.2-30.7-61.7-90-61.7-91.9zm-56.6-164.2c27.3-32.4 24.8-61.9 24-72.5-24.1 1.4-52 16.4-67.9 34.9-17.5 19.8-27.8 44.3-25.6 71.9 26.1 2 52.3-11.4 69.5-34.3z"/></svg>
                    <span>Download for macOS</span>
                    <svg class="arrow-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M288 32c0-17.7-14.3-32-32-32s-32 14.3-32 32V274.7l-73.4-73.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l128 128c12.5 12.5 32.8 12.5 45.3 0l128-128c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L288 274.7V32zM64 352c-35.3 0-64 28.7-64 64v32c0 35.3 28.7 64 64 64H448c35.3 0 64-28.7 64-64V416c0-35.3-28.7-64-64-64H346.5l-45.3 45.3c-25 25-65.5 25-90.5 0L165.5 352H64zM432 456c-13.3 0-24-10.7-24-24s10.7-24 24-24s24 10.7 24 24s-10.7 24-24 24z"/></svg>
                </button>
                <div class="dropdown-menu">
                    <a href="https://github.com/akkezi/KubeDesk/releases/latest/download/KubeDesk-mac-arm64.dmg">Apple Silicon (M1/M2/M3)</a>
                    <a href="https://github.com/akkezi/KubeDesk/releases/latest/download/KubeDesk-mac-x64.dmg">Intel Chip</a>
                </div>
            </div>

            <!-- Windows Dropdown -->
            <div class="dropdown">
                <button class="btn-pill btn-win">
                    <svg class="os-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path fill="currentColor" d="M0 93.7l183.6-25.3v177.4H0V93.7zm0 324.6l183.6 25.3V268.4H0v149.9zm203.8 28L448 480V268.4H203.8v177.9zm0-380.6v180.1H448V32L203.8 65.7z"/></svg>
                    <span>Download for Windows</span>
                    <svg class="arrow-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M288 32c0-17.7-14.3-32-32-32s-32 14.3-32 32V274.7l-73.4-73.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l128 128c12.5 12.5 32.8 12.5 45.3 0l128-128c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L288 274.7V32zM64 352c-35.3 0-64 28.7-64 64v32c0 35.3 28.7 64 64 64H448c35.3 0 64-28.7 64-64V416c0-35.3-28.7-64-64-64H346.5l-45.3 45.3c-25 25-65.5 25-90.5 0L165.5 352H64zM432 456c-13.3 0-24-10.7-24-24s10.7-24 24-24s24 10.7 24 24s-10.7 24-24 24z"/></svg>
                </button>
                <div class="dropdown-menu">
                    <a href="https://github.com/akkezi/KubeDesk/releases/latest/download/KubeDesk-Setup.exe">Installer (.exe)</a>
                    <a href="https://github.com/akkezi/KubeDesk/releases/latest/download/KubeDesk-Portable.exe">Portable (.exe)</a>
                </div>
            </div>

            <!-- Linux Dropdown -->
            <div class="dropdown">
                <button class="btn-pill btn-linux">
                    <svg class="os-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path fill="currentColor" d="M512 448c0 35.3-28.7 64-64 64H64c-35.3 0-64-28.7-64-64V64C0 28.7 28.7 0 64 0h384c35.3 0 64 28.7 64 64v384zM153.6 288c-14.1 0-25.6 11.5-25.6 25.6 0 14.1 11.5 25.6 25.6 25.6 14.1 0 25.6-11.5 25.6-25.6 0-14.1-11.5-25.6-25.6-25.6zm204.8 0c-14.1 0-25.6 11.5-25.6 25.6 0 14.1 11.5 25.6 25.6 25.6 14.1 0 25.6-11.5 25.6-25.6 0-14.1-11.5-25.6-25.6-25.6zm-59.5-125.6c-4.2-13.8-21.6-15.6-26.6-2.4-1.9 4.9-2.6 10.3-2.1 15.6l1.3 12.5c.3 3.3 2.1 6.2 5 7.8 2.8 1.6 6.2 1.5 9-.4l11.1-7.2c2.7-1.8 7-2.6 10.1-2.2 4.1 .5 7.7 3.3 8.3 7.5 .4 3-.5 6-2.4 8.3-2.1 2.5-5.2 3.9-8.4 3.7l-15.2-1c-15.3-1-28.8-11.7-32.3-26.7-2.5-10.9 .8-22 8.7-29.6 10.1-9.6 25-11.7 36.6-5.1 8 4.6 13.9 12 16.5 21l2.5 8.7c.3 1.1-.3 2.2-1.4 2.5s-2.2-.3-2.5-1.4l-2.5-8.7c-1.8-6.1-5.7-11.2-11.1-14.4-8.8-5.1-19.8-3.1-26.5 4.3zm67.8 1.8c1.9-4.9 2.6-10.3 2.1-15.6l-1.3-12.5c-.3-3.3-2.1-6.2-5-7.8-2.8-1.6-6.2-1.5-9 .4l-11.1 7.2c-2.7 1.8-7 2.6-10.1 2.2-4.1-.5-7.7-3.3-8.3-7.5-.4-3 .5-6 2.4-8.3 2.1-2.5 5.1-3.9 8.3-3.7l15.2 1c15.3 1 28.8 11.7 32.3 26.7 2.5 10.9-.8 22-8.7 29.6-10.1 9.6-25 11.7-36.6 5.1-8-4.6-13.9-12-16.5-21l-2.5-8.7c-.3-1.1 .3-2.2 1.4-2.5s2.2 .3 2.5 1.4l2.5 8.7c1.8 6.1 5.7 11.2 11.1 14.4 8.8 5.1 19.8 3.1 26.5-4.3 4.2 13.8 21.6 15.6 26.6 2.4zM245.9 378.1c-11.6 0-21.7 6.4-27 16-1.5 2.7-5 3.7-7.8 2.2s-3.7-5-2.2-7.8c7-12.7 20.3-21.2 35.6-21.2s28.6 8.5 35.6 21.2c1.5 2.7 .5 6.1-2.2 7.8s-6.3 .7-7.8-2.2c-5.3-9.6-15.4-16-27-16zM151.7 391.8c.8-1.1 2.4-1.5 3.7-.8 27.6 15.6 63.6 15.6 91.2 0 1.3-.8 2.9-.3 3.7 .8l16.2 21.6c.9 1.2 .8 2.9-.3 4l-42 42c-2.3 2.3-6.1 2.3-8.5 0l-42-42c-1.1-1.1-1.2-2.8-.3-4l16.2-21.6z"/></svg>
                    <span>Download for Linux</span>
                    <svg class="arrow-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M288 32c0-17.7-14.3-32-32-32s-32 14.3-32 32V274.7l-73.4-73.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l128 128c12.5 12.5 32.8 12.5 45.3 0l128-128c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L288 274.7V32zM64 352c-35.3 0-64 28.7-64 64v32c0 35.3 28.7 64 64 64H448c35.3 0 64-28.7 64-64V416c0-35.3-28.7-64-64-64H346.5l-45.3 45.3c-25 25-65.5 25-90.5 0L165.5 352H64zM432 456c-13.3 0-24-10.7-24-24s10.7-24 24-24s24 10.7 24 24s-10.7 24-24 24z"/></svg>
                </button>
                <div class="dropdown-menu">
                    <a href="https://github.com/akkezi/KubeDesk/releases/latest/download/KubeDesk.AppImage">Portable AppImage</a>
                    <a href="https://github.com/akkezi/KubeDesk/releases/latest/download/kubedesk_amd64.deb">Debian / Ubuntu (.deb)</a>
                    <a href="https://github.com/akkezi/KubeDesk/releases/latest/download/kubedesk.x86_64.rpm">RedHat / Fedora (.rpm)</a>
                </div>
            </div>
        
        <div class="hero-image">
            <img src="{{ site.baseurl }}/assets/images/screenshots/001.png" alt="KubeDesk Dashboard" class="app-screenshot">
        </div>
    </div>
</section>

<section class="features">
    <div class="container">
        <h2>Unmatched Observability & Visualization</h2>
        <div class="feature-grid">
            <div class="feature-card">
                <h3>🔄 Multi-Cluster Management</h3>
                <p>Switch between multiple Kubernetes clusters seamlessly from a single interface. Monitor all your environments without context switching.</p>
            </div>
            <div class="feature-card">
                <h3>👀 Ultimate Resource Viewer</h3>
                <p>Browse all your K8s resources with a beautiful and intuitive UI. Designed for administrators to audit and inspect cluster status.</p>
            </div>
            <div class="feature-card">
                <h3>📜 Real-time Logs</h3>
                <p>Stream pod logs instantly in read-only mode. Filter, search, and analyze logs to diagnose issues faster.</p>
            </div>
            <div class="feature-card">
                <h3>📄 Manifest Viewer</h3>
                <p>Inspect the full YAML configuration of any object. syntax highlighting helps you understand exactly how your resources are defined.</p>
            </div>
            <div class="feature-card">
                <h3>⚓ Helm Deployment & Catalog</h3>
                <p>Deploy Helm charts directly to your cluster. Browse and install from a rich catalog of available Helm repositories.</p>
            </div>
             <div class="feature-card">
                <h3>🧩 Custom Resource Inspection</h3>
                <p>Native support for viewing Custom Resource Definitions (CRDs) and their instances. See the full picture of your extensions.</p>
            </div>
        </div>
    </div>
</section>

<section class="gallery">
    <div class="container">
        <div class="gallery-scroll">
            <img src="{{ site.baseurl }}/assets/images/screenshots/002.png" alt="Cluster View">
            <img src="{{ site.baseurl }}/assets/images/screenshots/003.png" alt="Pod Details">
            <img src="{{ site.baseurl }}/assets/images/screenshots/004.png" alt="Terminal">
            <img src="{{ site.baseurl }}/assets/images/screenshots/005.png" alt="Settings">
             <img src="{{ site.baseurl }}/assets/images/screenshots/009.png" alt="Logs">
        </div>
    </div>
</section>

<section class="object-visibility">
    <div class="container">
        <h2>Comprehensive Object Visibility</h2>
        <p class="subtitle">Access detailed information for every Kubernetes object without touching the CLI.</p>
        <div class="object-grid">
            <div class="object-category">
                <h3>Dashboard & Events</h3>
                <ul>
                    <li>Dashboard Overview</li>
                    <li>Cluster Events</li>
                </ul>
            </div>
            <div class="object-category">
                <h3>Infrastructure</h3>
                <ul>
                    <li>Nodes</li>
                    <li>Namespaces</li>
                    <li>Resource Quotas</li>
                    <li>Limit Ranges</li>
                    <li>Leases</li>
                </ul>
            </div>
            <div class="object-category">
                <h3>Workloads</h3>
                <ul>
                    <li>Pods & Templates</li>
                    <li>Deployments</li>
                    <li>StatefulSets</li>
                    <li>DaemonSets</li>
                    <li>ReplicaSets</li>
                    <li>Jobs & CronJobs</li>
                    <li>Replication Controllers</li>
                </ul>
            </div>
             <div class="object-category">
                <h3>Configuration</h3>
                <ul>
                    <li>ConfigMaps</li>
                    <li>Secrets</li>
                    <li>Runtime Classes</li>
                    <li>HPA</li>
                    <li>Pod Disruption Budgets</li>
                    <li>Priority Classes</li>
                </ul>
            </div>
            <div class="object-category">
                <h3>Networking</h3>
                <ul>
                    <li>Services</li>
                    <li>Endpoints & Slices</li>
                    <li>Ingress & Classes</li>
                    <li>Network Policies</li>
                </ul>
            </div>
            <div class="object-category">
                <h3>Storage</h3>
                <ul>
                    <li>Storage Classes</li>
                    <li>Persistent Volumes (PV)</li>
                    <li>Volume Claims (PVC)</li>
                    <li>Volume Attachments</li>
                    <li>CSI Drivers & Nodes</li>
                </ul>
            </div>
            <div class="object-category">
                <h3>Access Control</h3>
                <ul>
                    <li>Service Accounts</li>
                    <li>Roles & Bindings</li>
                    <li>Cluster Roles & Bindings</li>
                    <li>CSR</li>
                </ul>
            </div>
            <div class="object-category">
                <h3>Admission & Dynamic</h3>
                <ul>
                    <li>Mutating/Validating Webhooks</li>
                    <li>Validating Policies</li>
                    <li>Device Classes</li>
                    <li>Resource Claims</li>
                </ul>
            </div>
             <div class="object-category">
                <h3>Applications & CRDs</h3>
                <ul>
                    <li>Helm Charts & Releases</li>
                    <li>Repositories</li>
                    <li>Custom Resource Definitions</li>
                    <li>GitOps (Planned)</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<section class="tech-stack">
    <div class="container">
        <h2>Built on Modern Tech</h2>
        <p class="stack-subtitle">Engineered for performance and reliability.</p>
        <div class="stack-grid">
            <div class="stack-item"><span>⚛️</span> React</div>
            <div class="stack-item"><span>📘</span> TypeScript</div>
            <div class="stack-item"><span>🐹</span> Go (Backend)</div>
            <div class="stack-item"><span>⚡</span> Electron</div>
            <div class="stack-item"><span>🚀</span> Turborepo</div>
        </div>
    </div>
</section>

<section class="installation">
    <div class="container">
        <h2>Installation</h2>
        <p class="install-subtitle">Get started in seconds. Download the latest release related to your OS.</p>
        <div class="install-tabs">
            <div class="code-block">
                <div class="code-header">Windows (Coming to Winget soon)</div>
                <pre><code># Download the installer from Releases
KubeDesk Setup 0.3.4.exe</code></pre>
            </div>
            <div class="code-block">
                <div class="code-header">Portable</div>
                <pre><code># Run without installation
KubeDesk 0.3.4.exe</code></pre>
            </div>
        </div>
        <div class="cta-bottom">
            <a href="https://github.com/akkezi/KubeDesk/releases" class="btn btn-secondary">View all releases on GitHub</a>
        </div>
    </div>
</section>
