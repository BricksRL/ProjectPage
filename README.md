# ProjectPage

## Setting Up Git LFS on Linux

To handle large video files in this repository, follow these steps to set up Git LFS on your Linux machine:

1. **Install Git LFS:**

   For Debian-based systems (e.g., Ubuntu), run:
   ```sh
   sudo apt-get install git-lfs 
   ```
   For other distributions, see the [Git LFS installation guide](https://github.com/git-lfs/git-lfs/wiki/Installation).

2. **Initialize Git LFS:**
In your cloned repository's directory, run:

   ```sh
   git lfs install
   ```

3. **Pull LFS Files:**
Download the large files with:

   ```sh
   git lfs pull
   ```