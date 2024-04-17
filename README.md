## This repository contains examples to test live

**How to Use:**

1. **Clone the repository:**

   ```bash
   git clone git@github.com:username/ruby-calculator.git ```

   (Replace "username" with your GitHub username)
   
2. Open your terminal and navigate to the project directory (ruby-calculator).
    
    Run the calculator using:
    
    ```bash
    ruby calculator.rb ```

3. Run the rspec `--seed 1234` `--bisect` command: Once you're in the correct directory, type this command and press Enter. RSpec will then start the bisection process. It will iteratively divide your test suite into smaller subsets and run them independently. The goal is to isolate the minimal set of tests that consistently reproduce the failure.
