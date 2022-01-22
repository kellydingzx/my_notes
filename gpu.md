## How to get access to UCL GPU facilities?

### Steps
1. Install VS Code ssh extensions
2. 'Ctrl+Shift+p' -> 'Remote-SSH' add a new host by `ssh -l username -J username@knuckles.cs.ucl.ac.uk username.cs.ucl.ac.uk` -> Linux -> Password
3. First time access:
  - `--user` is there to make sure that it only get installed onto your account
  - **Install/ update stuff**: 
   - Use `pip3` all the time (as the pip version is very old).
   - Upgrade pip3 using `python3.6 -m pip3 install --upgrade pip3` (needs to specify python version to be 3.6).
   - `pip3 install torch torchvision --user`
   - `pip3 install jupyter'
4. Open folder... 