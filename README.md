# Run command
This is an extensible runner for command commands to do common things such as run jobs or run flask commands locally

## Installation
### Clone this repository
```bash
git clone git@github.com:adam-alaya/run.git ~/wombats/
```

### Ensure the script is executable
```bash
chmod +x ~/wombats/run
```

### Add the command to your PATH
####  ZSH
```bash
echo 'export PATH="$HOME/wombats/run:$PATH"' >> ~/.zshrc &&
source ~/.zshrc  # Reload the configuration
```

#### bash
```
echo 'export PATH="$HOME/wombats/run:$PATH"' >> ~/.bash_profile
source ~/.bash_profile
```

## Usage
```run <command```

## Available commands
- app
    - open a console in the app container
- accounting
    - open a console in the accounting container
- billing
    - run the billing template creation job
- jobs
    - run php jobs, including invoice creation  
