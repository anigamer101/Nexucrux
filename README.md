<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Nexucrux Framework OS</title>
  <style>
    body { font-family: Arial, sans-serif; line-height: 1.6; margin: 40px; }
    h1, h2, h3 { color: #2c3e50; }
    code { background: #f4f4f4; padding: 2px 4px; border-radius: 4px; }
    pre { background: #f4f4f4; padding: 10px; border-radius: 6px; }
    ul { margin-left: 20px; }
    .tagline { font-style: italic; color: #555; }
  </style>
</head>
<body>

<h1>Nexucrux Framework OS</h1>
<p class="tagline">The crux of connected frameworks.</p>

<p>
Nexucrux Framework OS is a developer-centric operating system built on Arch Linux.  
It provides a pipeline where a <strong>library</strong> supports development, a <strong>Python script</strong> is wrapped with <strong>argparse</strong>,  
and the result is packaged into a <strong>bootable ISO</strong>.
</p>

<hr>

<h2>📖 Overview</h2>
<p>
Nexucrux bridges terminals, sockets, and HTML interfaces into a unified environment.  
The Framework OS makes this workflow reproducible and distributable as a standalone system image.
</p>

<hr>

<h2>🚀 Features</h2>
<ul>
  <li>Arch Linux base with minimal kernel</li>
  <li>Preinstalled Python + Nexucrux library</li>
  <li>Argparse wrapper that generates program + source folders</li>
  <li>ISO packaging for bootable distribution</li>
  <li>Open source under GNU GPL v3.0</li>
</ul>

<hr>

<h2>📦 Installation</h2>
<p>To build the ISO:</p>
<pre><code>git clone https://github.com/yourusername/nexucrux-os.git
cd nexucrux-os
mkarchiso -v path/to/profile
</code></pre>

<hr>

<h2>⚡ Quick Start</h2>
<p>Inside the OS, run the wrapper:</p>
<pre><code>nexucrux --output my_build</code></pre>
<p>This creates <code>my_build/</code> containing both the runnable program and its source code.</p>

<hr>

<h2>🏗 Architecture</h2>
<ul>
  <li><strong>Library Layer</strong>: Nexucrux framework utilities</li>
  <li><strong>Script Layer</strong>: User-created Python file</li>
  <li><strong>Wrapper Layer</strong>: Argparse CLI that generates folders</li>
  <li><strong>ISO Layer</strong>: ArchISO packaging for bootable distribution</li>
</ul>

<hr>

<h2>🌐 Use Cases</h2>
<ul>
  <li>Distribute Python programs as bootable environments</li>
  <li>Create reproducible developer toolchains</li>
  <li>Teach OS concepts with live ISO builds</li>
  <li>Prototype system-level frameworks</li>
</ul>

<hr>

<h2>🛠 Roadmap</h2>
<ul>
  <li>Plugin system for custom wrappers</li>
  <li>Prebuilt ISO releases</li>
  <li>Documentation website with tutorials</li>
  <li>Community-driven package registry</li>
</ul>

<hr>

<h2>🤝 Contributing</h2>
<p>
Contributions are welcome! Fork the repo, create a branch, and submit a pull request.  
Please follow coding standards and document changes clearly.
</p>

<hr>

<h2>👥 Community</h2>
<ul>
  <li><strong>Discussions</strong>: GitHub Discussions tab</li>
  <li><strong>Issues</strong>: Report bugs or request features via GitHub Issues</li>
  <li><strong>Chat</strong>: Community Discord/Matrix (coming soon)</li>
</ul>

<hr>

<h2>📜 License</h2>
<p>
Nexucrux Framework OS is licensed under the <strong>GNU General Public License v3.0 (GPL-3.0)</strong>.  
You are free to use, modify, and distribute this software under the terms of the GPL.  
See the <code>LICENSE</code> file for full details.
</p>

<hr>

<h2>✨ Acknowledgements</h2>
<p>
Inspired by the need to unify <strong>terminal power</strong> with <strong>web accessibility</strong>.  
Built with love by open-source contributors.
</p>

</body>
</html>
