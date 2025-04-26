## Prerequisites

1. **Ruby**: Install Ruby (version 2.5.0 or higher).
    - On macOS: `brew install ruby`
    - On Linux: Use your package manager.
    - On Windows: Install via [RubyInstaller](https://rubyinstaller.org/).

2. **Bundler**: Install Bundler, a Ruby gem for managing dependencies.
    ```bash
    gem install bundler
    ```

3. **Git**: Ensure Git is installed and configured.

4. **GitHub Repository**: Create a new repository on GitHub for your site.

## Steps to Build Your Jekyll Site

### 1. Install Jekyll
Install Jekyll using Bundler:
```bash
gem install jekyll
```

### 2. Create a New Jekyll Site
Run the following command to create a new Jekyll site:
```bash
jekyll new my-site
```
Replace `my-site` with your desired folder name.

### 3. Navigate to Your Site Directory
```bash
cd my-site
```

### 4. Install Dependencies
Run Bundler to install dependencies:
```bash
bundle install
```

### 5. Test Locally
Serve your site locally to preview:
```bash
bundle exec jekyll serve
```
Visit `http://localhost:4000` in your browser.