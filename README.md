#### ~/.tmuxinator/your-project-name.yml

# Setup
This initial app contains everything I need to setup a rails app

Live-Reload
Live-Reload-Goard
Zeus
Zeus-Guard
RSpec
Capybara
FactoryGirl
Should Matchers
Letter Opener
Haml
PG
Faker


# Tmuxinator Setup

name: your-project-name
root: ~/Projects/your-project-name/

windows:
  - editor: vim
  - zeus-server: sleep 2 && zeus s
  - zeus-guard:
      layout: main-vertical
      panes:
        - guard
  - rspec:


