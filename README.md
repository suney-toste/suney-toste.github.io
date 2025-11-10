# suney-toste.github.io
My official online website and blog. Built with Jekyll and hosted on GitHub Pages.

💎 Setting Up for Jekyll (bundle exec jekyll serve)
This process requires the user to have Ruby (the language Jekyll is built on) and the necessary tools installed on their computer.

📋 1. Prerequisites (Required Installations)
The user must first install the following on their local machine:

Ruby: The programming language that runs Jekyll (version 2.7.0 or higher is recommended).

RubyGems: The package manager for Ruby.

Bundler: A tool to manage Ruby dependencies (Gems) for the project.

You can usually install these via a package manager (like Homebrew on Mac or RubyInstaller on Windows).

⚙️ 2. Project Setup Steps
The user needs to create a Gemfile to define the Jekyll dependency, even for a simple HTML site.

Create a new file named Gemfile in the root of the repository and add this content:

source "https://rubygems.org"
gem "github-pages"

Bash

bundle install

🌐 3. Running the Server Locally
Once the dependencies are installed, the user can use the standard Jekyll command:

Start the Local Server Run the following command in the terminal to build the site and serve it locally:

Bash

bundle exec jekyll serve
View the Site The terminal output will display the server address, usually:

Server address: http://127.0.0.1:4000/
Open your web browser and navigate to that address to view the site.